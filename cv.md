%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% Deedy - One Page Two Column Resume
% LaTeX Template
% Version 1.2 (16/9/2014)
%
% Original author:
% Debarghya Das (http://debarghyadas.com)
%
% Original repository:
% https://github.com/deedydas/Deedy-Resume
%
% IMPORTANT: THIS TEMPLATE NEEDS TO BE COMPILED WITH XeLaTeX
%
% This template uses several fonts not included with Windows/Linux by
% default. If you get compilation errors saying a font is missing, find the line
% on which the font is used and either change it to a font included with your
% operating system or comment the line out to use the default font.
% 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% 
% TODO:
% 1. Integrate biber/bibtex for article citation under publications.
% 2. Figure out a smoother way for the document to flow onto the next page.
% 3. Add styling information for a "Projects/Hacks" section.
% 4. Add location/address information
% 5. Merge OpenFont and MacFonts as a single sty with options.
% 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
% CHANGELOG:
% v1.1:
% 1. Fixed several compilation bugs with \renewcommand
% 2. Got Open-source fonts (Windows/Linux support)
% 3. Added Last Updated
% 4. Move Title styling into .sty
% 5. Commented .sty file.
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
% Known Issues:
% 1. Overflows onto second page if any column's contents are more than the
% vertical limit
% 2. Hacky space on the first bullet point on the second column.
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


\documentclass[]{deedy-resume-openfont}
\usepackage{fancyhdr}
 
\pagestyle{fancy}
\fancyhf{}
 
\begin{document}


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     TITLE NAME
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\namesection{Gabriel}{Lima}{ 
\href{mailto:gabriel.nachtigal@gmail.com}{gabriel.nachtigal@gmail.com} | \href{tel:+5551995846027}{+55 51 99584-6027}\\ 
\href{https://github.com/gnachtigal}{github.com/gnachtigal} |
\href{https://www.linkedin.com/in/gabrielnachtigal/}{linkedin.com/in/gabrielnachtigal}
}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     COLUMN ONE
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\begin{minipage}[t]{0.33\textwidth} 

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     EDUCATION
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{EDUCATION} 

\subsection{UNISINOS}
\descript{Bachelor of Science\\Computer Science}
\location{Jun 2022 | Porto Alegre, Brazil}
\sectionsep

\subsection{IFRS}
\descript{Information Technology}
\location{Dec 2018 | Porto Alegre, Brazil}
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     SKILLS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{SKILLS}
\subsection{TECHNICAL}
\location{Proeficient with:}

% CV Default %
C\# \textbullet{} .NET \textbullet{} PHP \textbullet{} Laravel\\
SQL \textbullet{} HTML \textbullet{} CSS \textbullet{} Javascript \\

% CV para vaga .NET %
%C\# \textbullet{} .NET \textbullet{} SQL \\
%HTML \textbullet{} Javascript \textbullet{} CSS \\

% CV para vaga PHP %
%PHP \textbullet{} Laravel \textbullet{}  SQL\\
%HTML \textbullet{} CSS \textbullet{} Javascript \\

Git \textbullet{} Agile \textbullet{} CI/CD \\
MVC \textbullet{} API REST \textbullet{} Microservices \\
\location{Familiar with:}
Angular \textbullet{} Mulesoft \textbullet{} Java \textbullet{} Python \\ 
Automated Tests \textbullet{} Cloud 
\sectionsep

\subsection{Soft Skills}
Leadership \textbullet{} Adaptability \textbullet{} Creativity
\sectionsep

\subsection{Languages}
Portuguese (Native) \\ English (C2) \\ Spanish (B1)
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     INTERESSES
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{INTERESTS} 

\subsection{PROFESSIONAL}
Software Architecture \textbullet{} Microservices \\
Machine Learning \textbullet{} IOT \textbullet{} Open Source
\sectionsep

\subsection{PERSONAL}
Cooking \textbullet{} Gardening \textbullet{} Podcasts \\
Online Games \textbullet{} Sports
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     COLUMN TWO
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\end{minipage} 
\hfill
\begin{minipage}[t]{0.66\textwidth} 

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     EXPERIENCE
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{WORK EXPERIENCE}
\runsubsection{Zallpy Digital}
\descript{| Senior Software Engineer (C\#) }
\location{Feb 2023 - Present | BMW Partner | Porto Alegre, Brazil }
\vspace{\topsep} % Hacky fix for awkward extra vertical space
\begin{tightemize}
\item Assumed a leadership role by providing guidance and training to team members in development techniques, fostering a culture of continuous learning, and enhancing the quality of code produced.
\item Contributed significantly to the establishment of a microservices architecture, segmenting functionalities into autonomous and scalable components. This facilitated more efficient maintenance and improved system scalability.
\item Collaborated closely with the front-end team to embrace a micro front-end approach leveraging Angular. This approach empowered different teams to work autonomously on reusable and easily maintainable front-end components.
\item Developed system integration through Mulesoft APIs, optimizing communication among diverse software components and thereby enhancing operational efficiency.
\item Played a key role in restructuring payment infrastructure, seamlessly integrating a third-party method, resulting in a new payment feature for customers with minimal bugs, ensuring reliable transactions and a seamless user experience.
\end{tightemize}
\location{Feb 2019 - Feb 2023 | Outsourcing Team  | Porto Alegre, Brazil }
\begin{tightemize}
\item Conceptualized and built complex systems with queues, databases integration, RESTful APIs and Microservices.
\item Managed relational and non-relational databases (Redis) using indexes, procedures, functions and triggers.
\item Launched new products using continuous integration and delivery (CI/CD) with Docker and Kubernetes in the Azure DevOps and Google Cloud platforms.
\item Conceptualized, built and launched a product which increased the lead capture in at least 20\% in the system. 
\item Led the restructuring of a legacy project to new technologies which improved the data update timing from 7 days to 24 hours.
\end{tightemize}
\sectionsep

\runsubsection{Plugar Data \& Intelligence}
\descript{| Software Developer (C\#) }
\location{Feb 2018 – Feb 2019 | Porto Alegre, Brazil}
\begin{tightemize}
\item Designed and developed C\# .NET MVC applications using the best practices.
\item Built complex applications using RESTful APIs, queue systems and WebScraping (ETL).
\item Managed 2 developers and 1 QA Analyst; Led the development and achieved outstanding feedbacks in the CS indicators in a long-term project.
\item Responsible for the client interface, negotiating the priorities and development of new features.
\item Participation in the design and development of a machine learning product which considerably improved the key processes of the client. 
\end{tightemize}
\sectionsep

\runsubsection{LongView}
\descript{| Software Development Intern (C\#, PHP)}
\location{Oct 2015 – Feb 2018 | Porto Alegre, RS}
\begin{tightemize}
\item Web Development using C\# .Net (Web Pages \& MVC) and PHP with Laravel framework.
\item Front-end development with HTML, CSS and Javascript technologies.
\item Built and maintained multiple relational databases.
\item Led a CRM application project with another 2 developers.
\item Designed web applications with RESTful APIs, MVC and DDD architectures.
\end{tightemize}
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     RESEARCH
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

% \section{Research}
% \runsubsection{Cornell Robot Learning Lab}
% \descript{| Researcher}
% \location{Jan 2014 – Jan 2015 | Ithaca, NY}
% Worked with \textbf{\href{http://www.cs.cornell.edu/~ashesh/}{Ashesh Jain}} and \textbf{\href{http://www.cs.cornell.edu/~asaxena/}{Prof Ashutosh Saxena}} to create \textbf{PlanIt}, a tool which  learns from large scale user preference feedback to plan robot trajectories in human environments.  
% \sectionsep


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     PUBLICATIONS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

% \section{Publications} 
% \renewcommand\refname{\vskip -1.5em} % Couldn't get this working from the .cls file
% \bibliographystyle{abbrv}
% \nocite{*}

\end{minipage} 
\end{document}  \documentclass[]{article}
