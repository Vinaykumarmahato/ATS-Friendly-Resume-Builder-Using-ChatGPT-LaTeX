<p align="center">
  <img src="https://github.com/Vinaykumarmahato/ATS-Friendly-Resume-Builder-Using-ChatGPT-LaTeX/blob/main/Build%20Your%20ATS-Friendly%20Resume%20Tumbnail.png" alt="Build Your ATS-Friendly Resume Thumbnail" width="600">
</p>

# Video Guide: Build a Job-Winning ATS-Friendly Resume in 5 Minutes!

Bhai, mera script simple hai! This repository contains all the instructions and code you need to follow along with my YouTube video.

In this guide, I'll show you **3 simple methods** to create a professional, one-page, ATS-friendly resume using ChatGPT and LaTeX (Overleaf).

**[➡️ Click Here to Watch the Full Video Tutorial on YouTube ⬅️](https://www.youtube.com/YOUR_VIDEO_LINK_HERE)**

---

## 🚀 The 4-Step Process

Here is the simple workflow we will follow to get your resume ready.

### Step 1: Choose Your Method (Prepare Your Data)

In the video, I cover three ways to get started. Pick the one that suits you best:

* **1. You Have an Existing Resume (PDF/DOCX)** 📄
    * Find your most recent resume (even if it's not ATS-friendly).
    * We will upload this file directly to ChatGPT and ask it to reformat it.

* **2. You Have an Updated LinkedIn Profile** 🌐
    * Go to your LinkedIn Profile.
    * Click the **"More"** button (below your name).
    * Click **"Save to PDF"**.
    * We will upload this PDF to ChatGPT.

* **3. You Are a Fresher (Starting from Scratch)** ✍️
    * Open a simple text file (like Notepad) and write down all your details.
    * **Important:** Follow this structure (as I mention in the video):
        * **Profile Summary:** A short, powerful summary of who you are.
        * **Technical Skills:** (e.g., Programming, Tools, Databases).
        * **Projects:** Your most important projects with 2-3 bullet points each.
        * **Education:** Your degree, university, and graduation year.
        * **Achievements & Certifications:** (e.g., Hackathons, Google Certificates).
        * **Languages:** (e.g., English, Hindi).

---

### Step 2: Generate the LaTeX Code with ChatGPT

This is the most important step. We will ask ChatGPT to write the code for our resume.

1.  Go to **ChatGPT** (GPT-4 with file upload is recommended).
2.  **Upload your file** (from Method 1 or 2) OR **paste your text** (from Method 3).
3.  Use a prompt exactly like this. Just change `[Your Job Role]`!

    **Prompt to use:**
    > "Analyze this resume (file/text). I am applying for a **[Your Job Role]** role. Please rewrite this as a strong, one-page, ATS-friendly resume.
    >
    > You **MUST** use the exact LaTeX template I am providing below. Generate the complete, ready-to-use LaTeX code for me. Make sure all my information is filled in."

4.  **CRITICAL:** Immediately after your prompt, paste the *entire* template code below into the same message.

#### The One-Page LaTeX Template (Copy all of this)
## For Data Analytics

```latex
%-------------------------
% Resume in Latex
% Author: Vinay Kumar
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}

\pagestyle{fancy}
\fancyhf{}
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}

\urlstyle{same}
\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

\titleformat{\section}{
  \vspace{-6pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

\pdfgentounicode=1

\newcommand{\resumeItem}[1]{\item\small{{#1 \vspace{-2pt}}}}
\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & \textbf{\small #2} \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-6pt}
}
\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-6pt}
}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}
\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}

\begin{document}

%----------HEADING----------
\begin{center}
    {\Huge \scshape Vinay Kumar} \\ \vspace{4pt}
    \textbf{\Large \scshape Data Analyst} \\ \vspace{4pt}
    \small \faPhone\ +91-9919XXXXXX ~ 
    \href{mailto:advindiancoder@gmail.com}{\faEnvelope\ \underline{advindiancoder@gmail.com}} ~ 
    \href{https://www.linkedin.com/in/vinay-kumar860964/}{\faLinkedin\ \underline{linkedin.com/in/vinay-kumar860964}} 
\end{center}

%-----------SUMMARY-----------
\section{Summary}
Data Analyst with a strong foundation in SQL, Python, Excel, and Power BI. Skilled in cleaning, analyzing, and visualizing data to generate insights and support data-driven decision-making. Interested in collaborating on meaningful analytical work in fast-paced environments.

%-----------SKILLS-----------
\section{Skills}
\textbf{Programming \& Querying:} SQL, Python  \\
\textbf{Data Visualization Tools:} Advanced MS Excel, Power BI, Tableau \\
\textbf{Analytical Abilities:} Data Cleaning, Exploratory Data Analysis (EDA), Insight Generation, Descriptive Statistics

%-----------INTERNSHIP-----------
\section{Experience}
\resumeSubHeadingListStart
  \resumeSubheading
    {Data Analyst Intern}{April 2025 -- June 2025}
    {Dataview Analytics (Remote)}{Tools Used: Excel, SQL, Power BI}
    \resumeItemListStart
      \resumeItem{\textbf{Processed and standardized a dataset of over 1,00,000 rows} from multiple regions to support weekly analytics—enabled business teams to track KPIs across geography and time.}
      \resumeItem{Designed smart Excel templates embedded with lookup functions and pivot logic, \textbf{saving 40\% reporting time across 4 departments.}}
      \resumeItem{Developed and maintained Power BI dashboards to visualize revenue trends, customer mix, and monthly performance—regularly used by managers and analysts across business units.}
      \resumeItem{Collaborated with 4 analysts and 2 senior managers to define and validate 6 KPIs, improving report reliability and strategic alignment.}
    \resumeItemListEnd
\resumeSubHeadingListEnd

%-----------PROJECTS-----------
\section{Projects}
\resumeSubHeadingListStart
  \resumeProjectHeading
      {\textbf{Customer Churn Analysis} $|$ \emph{Python }}{March 2025 -- April 2025}
      \resumeItemListStart
        \resumeItem{\textbf{Analyzed behavior of 7,043 telecom customers} to identify churn patterns based on tenure, contract type, and monthly charges.}
        \resumeItem{Engineered new features including contract type buckets and tenure bands to improve segmentation and insights.}
        \resumeItem{Generated 11 visualizations (histograms, box plots, heatmaps) to highlight churn-prone segments.}
        \resumeItem{Revealed that 38\% of churned users were on monthly contracts with less than 3-month tenure—suggested early engagement strategies.}
      \resumeItemListEnd
  \resumeProjectHeading
      {\textbf{Sales Dashboard for Regional Performance} $|$ \emph{SQL, Power BI}}{February 2025 -- March 2025}
      \resumeItemListStart
        \resumeItem{Queried and joined 3 sales-related tables covering over 25,000 rows across 12 months and 5 regions using optimized SQL joins to create consistent, analysis-ready datasets.}
        \resumeItem{Built 10 dynamic measures and KPIs in Power BI to track regional sales, return trends, and product performance.}
        \resumeItem{Designed multipage dashboards with slicers and filters, helping stakeholders drill down by region, product category, and time.}
        \resumeItem{Detected a 14\% sales drop post-festival in the South region. Later, the insight was used for a marketing recovery plan.}
      \resumeItemListEnd
\resumeSubHeadingListEnd

%-----------AWARDS-----------
\section{Awards \& Certifications}
\resumeItemListStart
  \resumeItem{\textbf{Google Data Analytics Certificate – Coursera (2024):} Completed 8 practical case studies involving SQL, data cleaning, dashboards, and presentations.}
  \resumeItem{\textbf{Top 5\% in SQL Hackerrank Challenge – 2024:} Ranked among top 150 out of more than 3,000 participants for advanced SQL problem-solving.}
  \resumeItem{\textbf{Best Final Year Project – 2025, Marwari College:} Built a Power BI dashboard analyzing academic performance across 6 departments over 3 years.}
\resumeItemListEnd

%-----------EDUCATION-----------
\section{Education}
\resumeSubHeadingListStart
  \resumeSubheading
    {B.Sc. Information Technology}{Graduated: 2025}
    {Marwari College, Ranchi}{CGPA: 8.2 / 10}
\resumeSubHeadingListEnd

\end{document}

````


### Full Stack Developer (ATS-Friendly Resume using LaTeX)

```latex
%-------------------------
% Resume in Latex
% Author: Vinay Kumar
%------------------------

\documentclass[letterpaper,11pt]{article}
\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}

\pagestyle{fancy}
\fancyhf{}
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}

\urlstyle{same}
\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

\titleformat{\section}{
  \vspace{-6pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

\pdfgentounicode=1

\newcommand{\resumeItem}[1]{\item\small{{#1 \vspace{-2pt}}}}
\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & \textbf{\small #2} \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-6pt}
}
\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-6pt}
}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}
\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}

\begin{document}

%----------HEADING----------
\begin{center}
    {\Huge \scshape Vinay Kumar} \\ \vspace{4pt}
    \textbf{\Large \scshape Full Stack Developer} \\ \vspace{4pt}
    \small \faPhone\ +91-9919XXXXXX ~ 
    \href{mailto:advindiancoder@gmail.com}{\faEnvelope\ \underline{advindiancoder@gmail.com}} ~ 
    \href{https://www.linkedin.com/in/vinay-kumar860964/}{\faLinkedin\ \underline{linkedin.com/in/vinay-kumar860964}} 
\end{center}

%-----------SUMMARY-----------
\section{Summary}
Versatile and detail-oriented \textbf{Full Stack Developer} skilled in designing and deploying end-to-end web applications using Java, Spring Boot, React.js, and MySQL. Demonstrated expertise in RESTful API development, performance tuning, and scalable architecture. Passionate about clean code, open-source collaboration, and mentoring budding developers through technical content creation.

%-----------SKILLS-----------
\section{Skills}
\resumeItemListStart
  \resumeItem{\textbf{Frontend:} HTML5, CSS3, JavaScript (ES6+), React.js, Bootstrap, Tailwind CSS}
  \resumeItem{\textbf{Backend:} Java, Spring Boot, Hibernate, J2EE, JDBC, Servlets, REST API}
  \resumeItem{\textbf{Database:} MySQL, MongoDB}
  \resumeItem{\textbf{Tools \& Platforms:} Git, GitHub, Maven, Postman, Docker, IntelliJ IDEA, VS Code}
  \resumeItem{\textbf{Concepts:} OOP, MVC, Microservices, API Integration, Agile Development}
\resumeItemListEnd

%-----------EXPERIENCE-----------
\section{Experience}
\resumeSubHeadingListStart
  \resumeSubheading
    {Founder \& CEO — ADV SparkTech}{Aug 2023 -- Apr 2025}
    {Bengaluru, India}{}
    \resumeItemListStart
      \resumeItem{Developed and deployed multiple full-stack applications integrating REST APIs with MySQL databases.}
      \resumeItem{Led a 4-member developer team to deliver enterprise-grade projects with 35\% improved delivery speed.}
      \resumeItem{Mentored interns in Java and Spring Boot; improved project quality through peer code reviews.}
    \resumeItemListEnd

  \resumeSubheading
    {Full Stack Developer Intern — Inoglle (Part-Time)}{Jan 2024 -- Jul 2024}
    {Remote}{}
    \resumeItemListStart
      \resumeItem{Designed and implemented REST APIs in Spring Boot with JWT authentication and role-based access.}
      \resumeItem{Integrated React.js frontend with backend services, achieving 97\% uptime and responsive UX.}
      \resumeItem{Optimized MySQL schema resulting in 20\% faster query performance.}
    \resumeItemListEnd
\resumeSubHeadingListEnd

%-----------PROJECTS-----------
\section{Projects}
\resumeSubHeadingListStart
  \resumeProjectHeading
    {\textbf{E-Commerce Platform (Spring Boot + React.js + MySQL)}}{2024}
    \resumeItemListStart
      \resumeItem{Developed a full-stack online shopping system supporting user authentication, cart management, and secure payments.}
      \resumeItem{Optimized REST APIs for scalability, reducing latency by 25\%.}
    \resumeItemListEnd

  \resumeProjectHeading
    {\textbf{Student Management System (Java + JDBC + MySQL)}}{2023}
    \resumeItemListStart
      \resumeItem{Built CRUD-based application managing student data and grades with secure authentication.}
      \resumeItem{Applied normalization and indexing for faster query retrieval.}
    \resumeItemListEnd
\resumeSubHeadingListEnd

%-----------AWARDS & CERTIFICATIONS-----------
\section{Awards \& Certifications}
\resumeItemListStart
  \resumeItem{Microsoft Office 365 Productivity Suite (Advanced Level) — Naan Mudhalvan, 2022}
  \resumeItem{Top 5\% Global Designer on Canva — 2024}
  \resumeItem{Mock Technical Interview Score: 8.89/10 — 2024}
\resumeItemListEnd

%-----------EDUCATION-----------
\section{Education}
\resumeSubHeadingListStart
  \resumeSubheading
    {B.Tech in Information Technology}{Expected: 2025}
    {Dhaanish Ahmed College of Engineering (Anna University)}{CGPA: 8.2 / 10}
\resumeSubHeadingListEnd

\end{document}


````
### Data Scientist – LaTeX Resume
```latex
%-------------------------
% Resume in Latex
% Author: Vinay Kumar
%------------------------

\documentclass[letterpaper,11pt]{article}
\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}

\pagestyle{fancy}
\fancyhf{}
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}

\urlstyle{same}
\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

\titleformat{\section}{
  \vspace{-6pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

\pdfgentounicode=1

\newcommand{\resumeItem}[1]{\item\small{{#1 \vspace{-2pt}}}}
\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & \textbf{\small #2} \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-6pt}
}
\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-6pt}
}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}
\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}

\begin{document}

%----------HEADING----------
\begin{center}
    {\Huge \scshape Vinay Kumar} \\ \vspace{4pt}
    \textbf{\Large \scshape Data Scientist} \\ \vspace{4pt}
    \small \faPhone\ +91-9919XXXXXX ~ 
    \href{mailto:advindiancoder@gmail.com}{\faEnvelope\ \underline{advindiancoder@gmail.com}} ~ 
    \href{https://www.linkedin.com/in/vinay-kumar860964/}{\faLinkedin\ \underline{linkedin.com/in/vinay-kumar860964}} 
\end{center}

%-----------SUMMARY-----------
\section{Summary}
Analytical and solution-driven \textbf{Data Scientist} with strong proficiency in Python, Machine Learning, and Data Visualization. Experienced in building predictive models, performing statistical analysis, and deriving actionable business insights from large datasets. Passionate about leveraging AI and data-driven decision-making to solve complex real-world challenges.

%-----------SKILLS-----------
\section{Skills}
\resumeItemListStart
  \resumeItem{\textbf{Programming:} Python, SQL, R, Java (Basics)}
  \resumeItem{\textbf{Libraries \& Tools:} NumPy, Pandas, Scikit-learn, TensorFlow, Matplotlib, Seaborn, Power BI, Tableau}
  \resumeItem{\textbf{Machine Learning:} Regression, Classification, Clustering, Feature Engineering, Model Evaluation}
  \resumeItem{\textbf{Data Handling:} Data Cleaning, EDA, Data Wrangling, Visualization, Predictive Analytics}
  \resumeItem{\textbf{Concepts:} Statistics, Probability, Linear Algebra, Hypothesis Testing, Time Series Analysis}
\resumeItemListEnd

%-----------EXPERIENCE-----------
\section{Experience}
\resumeSubHeadingListStart
  \resumeSubheading
    {Data Science Intern — Inoglle (Part-Time)}{Jan 2024 -- Jul 2024}
    {Remote}{}
    \resumeItemListStart
      \resumeItem{Developed machine learning models using Scikit-learn to predict customer churn with 88\% accuracy.}
      \resumeItem{Automated data cleaning pipelines using Python and Pandas, reducing preprocessing time by 40\%.}
      \resumeItem{Created interactive dashboards in Power BI to visualize sales trends and business KPIs.}
    \resumeItemListEnd

  \resumeSubheading
    {Founder \& CEO — ADV SparkTech}{Aug 2023 -- Apr 2025}
    {Bengaluru, India}{}
    \resumeItemListStart
      \resumeItem{Led multiple data-centric projects integrating AI solutions into web platforms.}
      \resumeItem{Analyzed customer engagement data to drive product optimization and feature prioritization.}
      \resumeItem{Trained and mentored interns in Python, Data Analysis, and ML concepts.}
    \resumeItemListEnd
\resumeSubHeadingListEnd

%-----------PROJECTS-----------
\section{Projects}
\resumeSubHeadingListStart
  \resumeProjectHeading
    {\textbf{Customer Churn Prediction (Python, Scikit-learn, Power BI)}}{2024}
    \resumeItemListStart
      \resumeItem{Implemented classification models (Logistic Regression, Random Forest) to identify churn patterns.}
      \resumeItem{Deployed dashboards visualizing churn risk factors and actionable insights.}
    \resumeItemListEnd

  \resumeProjectHeading
    {\textbf{Sales Forecasting Using Time Series (Python, ARIMA, Tableau)}}{2023}
    \resumeItemListStart
      \resumeItem{Built time-series forecasting model achieving 92\% prediction accuracy on historical data.}
      \resumeItem{Presented visual insights to support inventory and business planning decisions.}
    \resumeItemListEnd
\resumeSubHeadingListEnd

%-----------AWARDS & CERTIFICATIONS-----------
\section{Awards \& Certifications}
\resumeItemListStart
  \resumeItem{Microsoft Certified: Data Fundamentals — 2023}
  \resumeItem{Google Data Analytics Professional Certificate — Coursera, 2023}
  \resumeItem{Top 5\% Performer in Mock Technical Assessment (Score: 8.89/10) — 2024}
\resumeItemListEnd

%-----------EDUCATION-----------
\section{Education}
\resumeSubHeadingListStart
  \resumeSubheading
    {B.Tech in Information Technology}{Expected: 2025}
    {Dhaanish Ahmed College of Engineering (Anna University)}{CGPA: 8.2 / 10}
\resumeSubHeadingListEnd

\end{document}


````
### Resume for AI Engineer
```latex

%-------------------------
% Resume in Latex
% Author: Vinay Kumar
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}

\pagestyle{fancy}
\fancyhf{}
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}

\urlstyle{same}
\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

\titleformat{\section}{
  \vspace{-6pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

\pdfgentounicode=1

\newcommand{\resumeItem}[1]{\item\small{{#1 \vspace{-2pt}}}}
\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & \textbf{\small #2} \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-6pt}
}
\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-6pt}
}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}
\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}

\begin{document}

%----------HEADING----------
\begin{center}
    {\Huge \scshape Vinay Kumar} \\ \vspace{4pt}
    \textbf{\Large \scshape AI Engineer} \\ \vspace{4pt}
    \small \faPhone\ +91-9919XXXXXX ~ 
    \href{mailto:advindiancoder@gmail.com}{\faEnvelope\ \underline{advindiancoder@gmail.com}} ~ 
    \href{https://www.linkedin.com/in/vinay-kumar860964/}{\faLinkedin\ \underline{linkedin.com/in/vinay-kumar860964}} 
\end{center}

%-----------SUMMARY-----------
\section{Summary}
AI Engineer with expertise in Machine Learning, Deep Learning, and Natural Language Processing. Skilled in developing and deploying AI models using Python, TensorFlow, PyTorch, and Hugging Face. Experienced in building computer vision, NLP, and recommendation systems to solve real-world business problems. Passionate about creating AI solutions that improve automation and decision-making.

%-----------SKILLS-----------
\section{Skills}
\textbf{Programming:} Python, SQL, R \\
\textbf{AI \& ML Frameworks:} TensorFlow, PyTorch, Keras, Scikit-learn \\
\textbf{Deep Learning:} CNN, RNN, LSTM, Transformers, GANs \\
\textbf{NLP Tools:} Hugging Face, spaCy, NLTK \\
\textbf{Visualization \& Tools:} Matplotlib, Seaborn, Power BI, Tableau

%-----------EXPERIENCE-----------
\section{Experience}
\resumeSubHeadingListStart
  \resumeSubheading
    {AI Intern}{April 2025 -- June 2025}
    {Inoglle (Remote)}{Tools Used: Python, TensorFlow, PyTorch, Hugging Face}
    \resumeItemListStart
      \resumeItem{Developed and deployed NLP models using Hugging Face to automate resume analysis with 92\% accuracy.}
      \resumeItem{Built CNN-based computer vision models for image classification and object detection projects achieving 95\%+ accuracy.}
      \resumeItem{Implemented automated data preprocessing pipelines using Python and Pandas, reducing training data preparation time by 40\%.}
    \resumeItemListEnd
  \resumeSubheading
    {Founder \& CEO}{Aug 2023 -- Apr 2025}
    {ADV SparkTech (Bengaluru, India)}{}
    \resumeItemListStart
      \resumeItem{Led AI-driven projects including recommendation systems, predictive modeling, and chatbots using deep learning frameworks.}
      \resumeItem{Trained and mentored a team of 4 interns on AI/ML concepts and Python-based model development.}
    \resumeItemListEnd
\resumeSubHeadingListEnd

%-----------PROJECTS-----------
\section{Projects}
\resumeSubHeadingListStart
  \resumeProjectHeading
      {\textbf{AI Resume Analyzer} $|$ \emph{Python, Hugging Face, Streamlit}}{March 2025 -- April 2025}
      \resumeItemListStart
        \resumeItem{Built an AI tool to automatically evaluate and optimize resumes using NLP models and GPT APIs.}
        \resumeItem{Improved resume scoring accuracy and provided actionable insights for better job matching.}
      \resumeItemListEnd
  \resumeProjectHeading
      {\textbf{Face Mask Detection System} $|$ \emph{TensorFlow, OpenCV, CNN}}{February 2025 -- March 2025}
      \resumeItemListStart
        \resumeItem{Developed a CNN model for real-time face mask detection achieving 97\% classification accuracy.}
        \resumeItem{Integrated model with webcam feed for real-time monitoring and alerts.}
      \resumeItemListEnd
\resumeSubHeadingListEnd

%-----------AWARDS-----------
\section{Awards \& Certifications}
\resumeItemListStart
  \resumeItem{\textbf{Microsoft AI Fundamentals (AI-900) – 2024:} Completed AI foundational certification covering ML, DL, and AI concepts.}
  \resumeItem{\textbf{Deep Learning Specialization – Coursera 2024:} Completed practical projects on CNNs, RNNs, and Transformers.}
  \resumeItem{\textbf{Top 5\% in Mock Technical Assessment – 2024:} Scored 8.89/10 outperforming 92\% of participants.}
\resumeItemListEnd

%-----------EDUCATION-----------
\section{Education}
\resumeSubHeadingListStart
  \resumeSubheading
    {B.Sc. Information Technology}{Graduated: 2025}
    {Marwari College, Ranchi}{CGPA: 8.2 / 10}
\resumeSubHeadingListEnd

\end{document}

````


### Step 3: Compile Your Resume on Overleaf

Now we turn that code into a beautiful PDF.

1.  🟢 Go to [**https://www.overleaf.com/**](https://www.overleaf.com/).
2.  🔵 Click **"Register"** and sign in with your Google account (it's free).
3.  🟡 On your dashboard, click **New Project** \> **Blank Project**.
4.  🟣 Name your project (e.g., "My Resume").
5.  🔴 You'll see a file named `main.tex`. **Delete all the text** inside it.
6.  📋 **Paste the full LaTeX code** you got from ChatGPT into this empty `main.tex` file.
7.  ❇️ Click the green **"Recompile"** button (or press `Ctrl+S`).

-----

### Step 4: Download Your Finished Resume\!

  * 🎉 On the right side of the screen, you will see your perfectly formatted, one-page resume.
  * ⬇️ Click the **"Download PDF"** button (it looks like a down-arrow).

**That's it\!** You now have a professional, ATS-friendly resume ready to send to recruiters.

-----

## 👍 Found this helpful?

If this video and guide helped you, please:

  * **Star** this repository ⭐️
  * **Subscribe** to [ADV Indian Coder on YouTube](https://www.youtube.com/@ADVIndianCoder-i9y) 📺
  * **Share** the video with your friends\!

<!-- end list -->

```
```
