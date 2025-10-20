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
