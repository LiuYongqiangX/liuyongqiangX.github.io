%-------------------------
% Resume in Latex
% Author
% License : MIT
%------------------------

%---- Required Packages and Functions ----

\documentclass[a4paper,11pt]{article}
\usepackage[UTF8]{ctex}
\usepackage{latexsym}
\usepackage{xcolor}
\usepackage{float}
\usepackage{ragged2e}
\usepackage[empty]{fullpage}
\usepackage{wrapfig}
\usepackage{lipsum}
\usepackage{tabularx}
\usepackage{titlesec}
\usepackage{geometry}
\usepackage{marvosym}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage{fontawesome5}
\usepackage{multicol}
\usepackage{graphicx}
\usepackage{cfr-lm}
\usepackage[T1]{fontenc}
\setlength{\multicolsep}{0pt} 
\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}
\geometry{left=1.4cm, top=0.8cm, right=1.2cm, bottom=1cm}
% Adjust margins
%\addtolength{\oddsidemargin}{-0.5in}
%\addtolength{\evensidemargin}{-0.5in}
%\addtolength{\textwidth}{1in}
\usepackage[most]{tcolorbox}
\tcbset{
	frame code={}
	center title,
	left=0pt,
	right=0pt,
	top=0pt,
	bottom=0pt,
	colback=gray!20,
	colframe=white,
	width=\dimexpr\textwidth\relax,
	enlarge left by=-2mm,
	boxsep=4pt,
	arc=0pt,outer arc=0pt,
}

\urlstyle{same}

\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-7pt}]

%-------------------------
% Custom commands
\newcommand{\resumeItem}[2]{
  \item{
    \textbf{#1}{\hspace{0.5mm}#2 \vspace{-0.5mm}}
  }
}

\newcommand{\resumePOR}[3]{
\vspace{0.5mm}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
        \textbf{#1}\hspace{0.3mm}#2 & \textit{\small{#3}} 
    \end{tabular*}
    \vspace{-2mm}
}

\newcommand{\resumeSubheading}[4]{
\vspace{0.5mm}\item
    \begin{tabular*}{0.98\textwidth}[t]{l@{\extracolsep{\fill}}r}
        \textbf{#1} & \textit{\footnotesize{#4}} \\
        \textit{\footnotesize{#3}} &  \footnotesize{#2}\\
    \end{tabular*}
    \vspace{-3.4mm}
}

\newcommand{\resumeProject}[4]{
\vspace{0.5mm}\item
    \begin{tabular*}{0.98\textwidth}[t]{l@{\extracolsep{\fill}}r}
        \textbf{#1} & \textit{\footnotesize{#3}} \\
        \footnotesize{\textit{#2}} & \footnotesize{#4}
    \end{tabular*}
    \vspace{-3.4mm}
}

\newcommand{\resumeSubItem}[2]{\resumeItem{#1}{#2}\vspace{-4pt}}

% \renewcommand{\labelitemii}{$\circ$}
\renewcommand{\labelitemi}{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=*,labelsep=0mm]}
\newcommand{\resumeHeadingSkillStart}{\begin{itemize}[leftmargin=*,itemsep=1.7mm, rightmargin=2ex]}
\newcommand{\resumeItemListStart}{\begin{justify}\begin{itemize}[leftmargin=3ex, rightmargin=2ex, noitemsep,labelsep=1.2mm,itemsep=0mm]\small}

\newcommand{\resumeSubHeadingListEnd}{\end{itemize}\vspace{1mm}}
\newcommand{\resumeHeadingSkillEnd}{\end{itemize}\vspace{-1mm}}
\newcommand{\resumeItemListEnd}{\end{itemize}\end{justify}\vspace{-1mm}}
\newcommand{\cvsection}[1]{%
\vspace{1mm}
\begin{tcolorbox}
    \textbf{\large #1}
\end{tcolorbox}
    \vspace{-4mm}
}

\newcolumntype{L}{>{\raggedright\arraybackslash}X}%
\newcolumntype{R}{>{\raggedleft\arraybackslash}X}%
\newcolumntype{C}{>{\centering\arraybackslash}X}%
%---- End of Packages and Functions ------

%-------------------------------------------
%%%%%%  CV STARTS HERE  %%%%%%%%%%%
%%%%%% DEFINE ELEMENTS HERE %%%%%%%
\newcommand{\name}{刘永强} % Your Name
\newcommand{\birthdate}{1995.01.09} % Your Birth Date
\newcommand{\ethnicity}{汉族} % Ethnicity
\newcommand{\politicalStatus}{中共党员} % Political Status
\newcommand{\origin}{甘肃庆阳} % Place of Origin
\newcommand{\englishLevel}{六级} % English Level
\newcommand{\phone}{15652993185} % Your Phone Number
\newcommand{\email}{yongqiangliu@bjtu.edu.cn} % Your Email
\newcommand{\photo}{lyq.jpg} % Path to your photo
\newcommand{\address}{北京交通大学，自动化与智能学院} % Address
\newcommand{\research}{列车定位、组合导航方向} % Address



\begin{document}
\fontfamily{cmr}\selectfont
%----------HEADING-----------------
% \section{\textbf{基本信息}}
\parbox{2.35cm}{%
\includegraphics[width=2.1cm,clip]{lyq.JPG}
}
\parbox{\dimexpr\linewidth-2.8cm\relax}{
\begin{tabularx}{\linewidth}{L r} 
 \textbf{\Large \name} \\
  \origin  & \birthdate \\
  \ethnicity  & {\footnotesize \faPhone}\ +86-\phone \\
  \politicalStatus & \href{mailto:\email}{\raisebox{0.0\height}{\footnotesize \faEnvelope}\ \email} \\
  \address & \research \\
\end{tabularx}
}
\vspace{-1em}

%-----------EDUCATION-----------
\section{\textbf{教育背景}}
  \resumeSubHeadingListStart
    \resumeSubheading
      { 北京交通大学，交通信息工程及控制(导师: 王剑 教授、姜维 教授） }{博士在读}
      {研究课题：视觉位置识别增强的列车无缝定位方法研究}{2022.09-至今}
    \resumeSubheading
      {北京交通大学，控制工程(导师: 姜维教授)}{硕士}
      {研究课题：基于移动基线的列车完整性监测方法研究}{2018.09-2020.07}
    \resumeSubheading
      {北京交通大学}{本科}
      {轨道交通信号与控制}{2014.09-2018.07}
  \resumeSubHeadingListEnd

%
\vspace{-7.0mm}
%-----------EXPERIENCE-----------------
\section{\textbf{工作经历}}
  \resumeSubHeadingListStart
    \resumeSubheading
      {中 国 电 子 科 技 集 团 第 二 十 研 究 所}{西安}
      {软 件 产 品 部， 助 理 工 程 师}{2020.08-2022.08}
      \resumeItemListStart
    \item {基于 QT 的上位机软件设计，实现无人导校设备、DME设备、微波着陆设备测试软件开发；}
    \item {参与塔康机载模拟设备的科研项目，作为两个配置项的软件设计师，负责该配置项的软件设计以及代码实现工作。}
    \resumeItemListEnd
  \resumeSubHeadingListEnd

\vspace{-10.0mm}
%-----------PROJECTS-----------------
\section{\textbf{科研经历}}
\resumeSubHeadingListStart

      \resumeProject
      {基于GNSS/INS/视觉信息融合的列车定位方法} %Project Name
      {主要工作：作为负责人，负责申请书撰写、特征提取方法框架与多源融合算法研究、神经网络模型设计。}%Project Name, Location Name
      {2023.05-2025.06} %Event Dates

      \resumeItemListStart
        \item {项目概述：研究基于全球导航卫星系统、惯性导航系统、视觉轨道地图的多源信息组合定位技术为定位基础，实现卫星信号受限场景下的列车可靠连续无缝定位。}
    \resumeItemListEnd
    \vspace{-5.0mm}

        \resumeProject
      {超长隧道内多模态环境适配的列车自主安全定位技术（国家重点研发计划-任务）} %Project Name
      {主要工作：作为项目骨干成员，负责隧道定位方案和模型构建、平台开发与任务书材料撰写。} %Project Name, Location Name
      {2023.12-2026.12} %Event Dates

      \resumeItemListStart
        \item {项目概述：针对川藏铁路少轨旁少维护需求，探索基于多感知源数据的定位感知融合策略和方法，研究基于卫星导航、速传、应答器、无线定位等多模态感知的列车定位技术研究，实现面向超长隧道的列车自主定位。}
    \resumeItemListEnd
    \vspace{-5.0mm}

        \resumeProject
      {高速列车多源信息融合定位与测姿技术研究} %Project Name
      {作为项目骨干成员，负责研究多天线测姿算法研究设计、结题材料撰写等。} %Project Name, Location Name
      {2020.12-2023.12} %Event Dates

      \resumeItemListStart
        \item {项目概述：本项目以多传感器信息融合为基本途径，深入研究高精度、高可靠列车定位与测姿技术，研究多源融合列车定位的安全风险分析方法，构建基于高精度测姿的轨道不平顺检测方案。}
    \resumeItemListEnd 
  \resumeSubHeadingListEnd
\vspace{-10.0mm}
%-----------出版物-----------------


\vfill
\section{\textbf{论文成果}}

\nocite{ref1}[1] Yongqiang Liu, Wei Jiang, Xiao Hu, Jian Wang, Baigen Cai. A seamless train positioning method based on visual place recognition[C]. 2024 IEEE Intelligent Transportation Systems Conference (ITSC). \\
\nocite{ref1}[2]刘永强, 王剑, 姜维. 基于单天线航向测量的股道占用判别方法研究[J]. 铁道科学与工程学报，2023年.\\
\nocite{ref2}[3]Wei Jiang, Yongqiang Liu, Baigen Cai, Chris Rizos and Jian Wang. Robust train length calculation method using GNSS multi-constellation moving-baseline positioning resolution [J]. GPS Solution，2023年.\\
\nocite{ref3}[4]Wei Jiang, Yongqiang Liu, Baigen Cai, Chris Rizos, Jian Wang and Yiping Jiang. A New Train Integrity Resolution Method Based on Online Carrier Phase Relative Positioning[J]. IEEE Transactions on Vehicular Technology, 2020, 69(10): 10519-1053.\\
\nocite{ref4}[5]姜维, 刘永强, 王剑, 张文彪. 基于GNSS移动基线的列车完整性监测[J]. 交通运输系统工程与信息, 2020, 20(4): 90-96. 
\vspace{-5mm} %5mm vertical space


%-----------Technical skills-----------------
\section{\textbf{技能与评价}}
 \begin{itemize}[leftmargin=0.05in, label={}]
    \small{\item{
     \textbf{语言}{:通过英语六级，具备基本的外语沟通能力；} \\
     \textbf{软件技能}{:熟练使用C++、Python、Matlab、C等编程语言；} \\
     \textbf{自我评价}{: 具有良好的沟通能力，善于执行并具备团队合作精神，自我驱动力强。} \\
    }}
 \end{itemize}
 \vspace{-16pt}

%-------------------------------------------
\end{document}
