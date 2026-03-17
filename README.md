\documentclass{article}
\usepackage[utf8]{inputenc}
\usepackage{geometry}
\usepackage{titlesec}
\usepackage{hyperref}
\usepackage{enumitem}

\geometry{margin=1in}
\titleformat{\section}{\large\bfseries}{}{0em}{}[\titlerule]

\begin{titlepage}
    \centering
    \vspace*{2cm}
    \Huge \textbf{Employee Attrition Data Analysis} \\
    \vspace{0.5cm}
    \Large \textit{Workforce \& Attrition Intelligence} \\
    \vspace{1cm}
    \normalsize Tool: \textbf{Power BI Desktop}
\end{titlepage}

\section{📌 Project Overview}
This project delivers a deep-dive analysis of organizational human resources data. By transforming raw employee records into an interactive Power BI dashboard, this study provides HR leadership with the tools to monitor workforce stability, track diversity goals, and identify attrition triggers before they impact the bottom line.

\section{🛠️ Technical Toolbelt}
\begin{itemize}
    \item \textbf{Analytics Tool:} Power BI Desktop
    \item \textbf{Data Engineering:} Power Query (ETL processes for cleaning nulls and normalizing departmental hierarchies).
    \item \textbf{Advanced Analytics (DAX):} Created specialized measures for $Attrition\_Rate\%$, $Headcount\_Velocity$, and $Performance\_to\_Salary\_Ratios$.
    \item \textbf{Data Modeling:} Optimized \textbf{Star Schema} architecture for high-speed reporting.
\end{itemize}

\section{🔍 Key Features \& Insights}
\begin{itemize}
    \item \textbf{Executive Summary:} Instant visibility into Total Headcount and Organizational Attrition Rate.
    \item \textbf{Demographics \& Diversity:} Granular breakdown by Age, Gender, and Ethnicity.
    \item \textbf{Performance vs. Compensation:} Correlation analysis between Performance Ratings and Salary Packages.
\end{itemize}

\section{📈 Data Architecture}
The project utilizes a \textbf{Star Schema} to ensure maximum performance:
\begin{itemize}
    \item \textbf{Fact Table:} Centralized employee records (Salary, Tenure, Performance).
    \item \textbf{Dimension Tables:} Dedicated tables for Calendar, Departmental Metadata, Job Roles, and Geographic Locations.
\end{itemize}

\section{💡 Strategic Business Insights}
\begin{itemize}
    \item \textbf{Retention Alert:} Sales Department experiences a 15\% higher attrition rate in employees with $<2$ years tenure.
    \item \textbf{Pay Equity:} Discovered a 10\% gap in performance-to-pay alignment in middle-management.
\end{itemize}

\end{document}
