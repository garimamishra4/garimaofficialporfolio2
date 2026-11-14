```latex
\documentclass[a4paper,8pt]{article}

%----------PACKAGES----------
\usepackage[margin=0.38in]{geometry}
\usepackage{titlesec}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage{microtype}
\usepackage{tabularx}

%----------PAGE SETTINGS----------
\pagestyle{empty}
\raggedright
\setlength{\parindent}{0pt}
\setlength{\parskip}{0pt}
\setlength{\tabcolsep}{0pt}
\setlength{\emergencystretch}{2em}

%----------SECTION FORMATTING----------
\titleformat{\section}
{\normalsize\bfseries}
{}{0em}{}[\titlerule]

\titlespacing*{\section}{0pt}{3pt}{2pt}

%----------LIST FORMATTING----------
\setlist[itemize]{
    leftmargin=11pt,
    itemsep=0pt,
    topsep=0pt,
    parsep=0pt,
    partopsep=0pt
}

%----------PROJECT LINKS: EDIT HERE----------
\newcommand{\samadhangithub}{}
\newcommand{\portfoliogithub}{https://github.com/garimamishra4/garimaofficialporfolio2}
\newcommand{\portfoliodemo}{https://garimamishrap.netlify.app/}
\newcommand{\arogyagithub}{}
\newcommand{\arogyademo}{}

%----------CONDITIONAL LINKS----------
\newcommand{\projectlink}[2]{%
\if\relax\detokenize{#1}\relax
\else
\href{#1}{#2}%
\fi
}

\begin{document}

%----------HEADER----------
\begin{center}
{\Large\textbf{Garima Mishra}}\\[2pt]
\small
+91-9699724575 \quad | \quad
\href{mailto:garimamishra4official@gmail.com}{garimamishra4official@gmail.com}\\
\href{https://www.linkedin.com/in/garimamishra4}{LinkedIn}
\quad | \quad
\href{https://github.com/garimamishra4}{GitHub}
\end{center}

\vspace{-9pt}

%----------EDUCATION----------
\section{Education}

\textbf{B.Tech in Computer Science and Engineering}
\hfill \textit{2023 -- 2027}\\
GL Bajaj Group of Institutions, Dr. A.P.J. Abdul Kalam Technical University
\hfill CGPA: 7.73/10

\textbf{CBSE Class XII} \hfill 2023
\quad Kendriya Vidyalaya Chero Salempur, Deoria
\hfill 79.8\%

\textbf{CBSE Class X} \hfill 2021
\quad Kendriya Vidyalaya RHE Kirkee, Pune
\hfill 90.8\%

%----------SKILLS----------
\section{Technical Skills}

\textbf{Programming:} Java, Python, C, JavaScript, SQL \\
\textbf{Core CS:} Data Structures and Algorithms, OOP, DBMS, Operating Systems, SDLC\\
\textbf{Web:} React.js, HTML5, CSS3, Tailwind CSS\\
\textbf{AI:} Generative AI, IBM Watsonx, Machine Learning\\
\textbf{Tools:} Git, GitHub, VS Code, IntelliJ IDEA, Jupyter Notebook

%----------EXPERIENCE----------
\section{Internship Experience}

\textbf{Software Development Executive Intern | NextGen Global Services Pvt. Ltd.}
\hfill \textit{Jun 2026 -- Sep 2026}
\begin{itemize}
\item Developed and implemented software solutions by translating technical requirements into application functionalities and supporting feature development.
\item Utilized programming concepts, analytical thinking, and debugging techniques to identify technical issues, troubleshoot errors, and improve application functionality.
\item Collaborated with development teams across the Software Development Life Cycle (SDLC), including requirement analysis, implementation, testing, debugging, and adherence to coding standards.
\end{itemize}

\textbf{Web Developer and UI/UX Design Intern | VisiARise}
\hfill \textit{Nov 2024 -- May 2025}
\begin{itemize}
\item Developed 10+ responsive web pages using React.js, JavaScript, HTML, CSS, and Tailwind CSS.
\item Collaborated through Git-based workflows and contributed to 3 feature releases.
\item Improved user engagement by 20\% and user satisfaction by 35\% through UI/UX enhancements.
\end{itemize}

%----------PROJECTS----------
\section{Projects}

\textbf{Samadhan AI | Generative AI Grievance Redressal System}
\hfill \textit{MMM YYYY -- MMM YYYY}\\
\textit{IBM Watsonx, Generative AI, React.js}
\quad | \quad
\projectlink{\samadhangithub}{GitHub}
\quad | \quad
\href{https://samadhan-ai.netlify.app/}{Live Demo}
\begin{itemize}
\item Developed a Generative AI-based citizen grievance support system using IBM Watsonx, processing 500+ simulated complaint queries.
\item Implemented complaint classification, sentiment analysis, and priority-based routing across 3 deployment workflows.
\item Built a responsive frontend, reducing average user interaction time by 15\%.
\end{itemize}

\textbf{Personal Portfolio Website | Web Development}
\hfill \textit{MMM YYYY -- MMM YYYY}\\
\textit{React.js, JavaScript, HTML, CSS}
\quad | \quad
\projectlink{\portfoliogithub}{GitHub}
\quad | \quad
\projectlink{\portfoliodemo}{Live Demo}
\begin{itemize}
\item Developed a responsive portfolio website showcasing technical skills, projects, and professional achievements.
\item Implemented interactive UI components and responsive layouts to improve accessibility and user experience.
\end{itemize}

\textbf{ArogyaPulse | AI-Based Health Monitoring Application}
\hfill \textit{MMM YYYY -- MMM YYYY}\\
\textit{AI Tools, Web Development}
\quad | \quad
\projectlink{\arogyagithub}{GitHub}
\quad | \quad
\projectlink{\arogyademo}{Live Demo}
\begin{itemize}
\item Designed an AI-based health monitoring application concept integrating food and physical activity inputs for personalized health insights.
\item Planned camera-based stress monitoring and doctor-report features for health tracking.
\end{itemize}

%----------ACHIEVEMENTS----------
\section{Achievements}

\begin{itemize}
\item Winner, IBM Prarambh Hackathon 2025, in collaboration with Uttar Pradesh Government.
\item Winner, CT Solution Hackathon 2025.
\item Regional Qualifier, Yukti Innovation Challenge, Ministry of Education, 2025.
\item Pre-Finalist, Adobe India Hackathon 2025.
\item Top 25\%, Summer Analytics 2024, IIT Guwahati (Machine Learning and Data Analysis).
\end{itemize}

%----------POSITIONS----------
\section{Positions of Responsibility}

\textbf{Frontend Reviewer, Fest Competition} \hfill Apr 2024\\
\textbf{Coordinator, Cultural Committee} \hfill May 2024 -- Nov 2024

%----------CERTIFICATIONS----------
\section{Certifications}

AWS Technical Essentials -- AWS, Oct 2026
\quad | \quad
AI Agents for Beginners -- Simplilearn, Jul 2026
\quad | \quad
Java Programming -- Udemy, May 2025

\end{document}
```
