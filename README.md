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
    \small \faPhone\ +91-9876XXXXXX ~ 
    \href{mailto:vinaykumar.data@gmail.com}{\faEnvelope\ \underline{vinaykumar.data@gmail.com}} ~ 
    \href{https://www.linkedin.com/in/vinay-kumar}{\faLinkedin\ \underline{linkedin.com/in/vinay-kumar}} 
\end{center}

%-----------SUMMARY-----------
\section{Summary}
Data Analyst with a strong command over SQL, Python, and Power BI. Passionate about transforming data into actionable insights and developing dashboards to support strategic decisions. Adept at solving business problems through analytical reasoning and visualization.

%-----------SKILLS-----------
\section{Skills}
\textbf{Programming \& Querying:} Python, SQL \\ 
\textbf{Visualization Tools:} Power BI, Tableau, Advanced Excel \\ 
\textbf{Core Competencies:} Data Cleaning, EDA, KPI Reporting, Business Intelligence

%-----------EXPERIENCE-----------
\section{Experience}
\resumeSubHeadingListStart
  \resumeSubheading
    {Data Analyst Intern}{Nov 2024 -- Present}
    {Inoglle (ADV Indian Coder)}{Remote — Bengaluru, India}
    \resumeItemListStart
      \resumeItem{Analyzing datasets for digital initiatives under ADV Indian Coder’s ecosystem to identify audience patterns and engagement KPIs.}
      \resumeItem{Designed Power BI dashboards to visualize project performance, student analytics, and training outcomes.}
      \resumeItem{Automated weekly Excel reports using formulas and lookups, improving reporting efficiency by 35\%.}
      \resumeItem{Collaborated with tech and marketing teams to define metrics that align data insights with organizational goals.}
    \resumeItemListEnd
\resumeSubHeadingListEnd

%-----------PROJECTS-----------
\section{Projects}
\resumeSubHeadingListStart
  \resumeProjectHeading
      {\textbf{E-Commerce Sales Analysis Dashboard} $|$ \emph{Power BI, SQL}}{July 2024 -- Aug 2024}
      \resumeItemListStart
        \resumeItem{Developed a Power BI dashboard using sales data from multiple sources (CSV and SQL) to track daily, monthly, and product-wise revenue.}
        \resumeItem{Identified top 10 performing products and regions contributing to 70\% of total sales.}
        \resumeItem{Provided actionable insights that helped forecast upcoming quarter demand with 85\% accuracy.}
      \resumeItemListEnd

  \resumeProjectHeading
      {\textbf{Netflix Data Insights Project} $|$ \emph{Python, Pandas, Matplotlib}}{May 2024 -- June 2024}
      \resumeItemListStart
        \resumeItem{Performed exploratory data analysis on the Netflix dataset to uncover patterns in genres, ratings, and content production countries.}
        \resumeItem{Visualized relationships between content type, release year, and viewer trends using Matplotlib and Seaborn.}
        \resumeItem{Suggested data-driven strategies for enhancing recommendation models and improving user retention.}
      \resumeItemListEnd
\resumeSubHeadingListEnd

%-----------AWARDS & CERTIFICATIONS-----------
\section{Awards \& Certifications}
\resumeItemListStart
  \resumeItem{\textbf{Google Data Analytics Certificate – Coursera (2024):} Completed end-to-end projects using SQL, Excel, and Power BI.}
  \resumeItem{\textbf{Excel for Business – Macquarie University (2023):} Specialized in Excel-based business analytics and reporting automation.}
  \resumeItem{\textbf{Power BI Data Visualization Challenge – 2024:} Ranked in top 10 among 200+ participants.}
\resumeItemListEnd

%-----------EDUCATION-----------
\section{Education}
\resumeSubHeadingListStart
  \resumeSubheading
    {B.Tech in Information Technology}{Expected Graduation: 2026}
    {Dhanalakshmi Srinivasan College of Engineering and Technology (DSCET)}{Kallakurichi, Tamil Nadu}
\resumeSubHeadingListEnd

\end{document}

````

-----

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
