\documentclass[11pt, a4paper]{article}
\usepackage[a4paper, top=1.8cm, bottom=1.8cm, left=1.5cm, right=1.5cm]{geometry}
\usepackage[utf8]{inputenc}
\usepackage[english]{babel}
\usepackage{helvet}
\renewcommand{\familydefault}{\sfdefault}

\usepackage{xcolor}
\usepackage{tcolorbox}
\tcbuselibrary{skins}
\usepackage{multicol}
\usepackage{array}
\usepackage{amssymb} % For cool arrow and box symbols

% Custom Color Palette
\definecolor{navyBlue}{HTML}{1E3A8A}    % Primary Titles
\definecolor{softBlue}{HTML}{EFF6FF}    % Intro Background
\definecolor{customaryRed}{HTML}{991B1B} % Pre-1976 Customary Law
\definecolor{customaryBg}{HTML}{FEF2F2}  % Pre-1976 Box Bg
\definecolor{statuteGreen}{HTML}{065F46} % Post-1976 LRA
\definecolor{statuteBg}{HTML}{ECFDF5}   % Post-1976 Box Bg
\definecolor{amberGold}{HTML}{D97706}   % Important notes / cases
\definecolor{amberBg}{HTML}{FEF3C7}     % Case box background

% Custom Box Styles
\newtcolorbox{headerbox}{
    colback=navyBlue,
    colframe=navyBlue,
    fontupper=\color{white},
    halign=center,
    arc=5mm,
    boxrule=0.5mm,
    top=4mm, bottom=4mm
}

\newtcolorbox{introbox}[1]{
    colback=softBlue,
    colframe=navyBlue!50,
    title=\textbf{#1},
    coltitle=navyBlue,
    fonttitle=\bfseries,
    arc=3mm,
    boxrule=0.8mm
}

\newtcolorbox{prebox}[1]{
    colback=customaryBg,
    colframe=customaryRed!70,
    title=\textbf{#1},
    coltitle=customaryRed,
    fonttitle=\bfseries,
    arc=3mm,
    boxrule=0.8mm
}

\newtcolorbox{postbox}[1]{
    colback=statuteBg,
    colframe=statuteGreen!70,
    title=\textbf{#1},
    coltitle=statuteGreen,
    fonttitle=\bfseries,
    arc=3mm,
    boxrule=0.8mm
}

\newtcolorbox{casebox}[1]{
    colback=amberBg,
    colframe=amberGold!80,
    title=\textbf{#1},
    coltitle=black,
    fonttitle=\bfseries\small,
    arc=2mm,
    boxrule=0.5mm,
    top=2mm, bottom=2mm
}

\begin{document}

% =========================================================================
% HEADER SECTION
% =========================================================================
\begin{headerbox}
    {\LARGE \textbf{LAW434: MALAYSIAN LEGAL SYSTEM}} \\
    \vspace{1.5mm}
    {\large \textbf{VISUAL STUDY DASHBOARD: THE TRANSFORMATION OF CUSTOMARY LAW}} \\
    \vspace{1mm}
    \textit{Comparative Analysis: Pre-1976 Customary Law vs. Law Reform (Marriage \& Divorce) Act 1976}
\end{headerbox}

\vspace{0.4cm}

% =========================================================================
% ROADMAP & STRATEGY (Timeline & Methodology)
% =========================================================================
\begin{introbox}{1. ROADMAP \& STRATEGY: HOW TO TACKLE THE QUESTION}
    \textbf{Selected Structure: IBC (Introduction, Body, Conclusion)} $\Longrightarrow$ Best for Comparative/Historical Essays.\\
    \textit{Why? No hypothetical problem scenario is presented; requires a systematic, theme-based legal comparison.}
    
    \vspace{0.25cm}
    \textbf{\textsf{EVOLUTION TIMELINE:}}
    \vspace{0.15cm}
    \begin{center}
        \sffamily\bfseries\small
        \begin{tabular}{ccccc}
            \color{customaryRed}Pre-1976 Era & & \color{amberGold}1976 (Enactment) & & \color{statuteGreen}1st March 1982 onwards \\
            \framebox{\parbox{4.2cm}{\centering Uncodified Customary Law\\(Polygamy \& Informal Divorces)}} 
            & $\Longrightarrow$ & 
            \framebox{\parbox{3.8cm}{\centering Law Reform Act passed\\(The Uniform Code Initiative)}} 
            & $\Longrightarrow$ & 
            \framebox{\parbox{4.5cm}{\centering Strict Monogamy Enforced\\(Compulsory Registration)}}
        \end{tabular}
    \end{center}
\end{introbox}

\vspace{0.3cm}

% =========================================================================
% THEME 1: POLYGAMY VS MONOGAMY
% =========================================================================
\noindent
\begin{minipage}[t]{0.48\textwidth}
    \begin{prebox}{THEME 1: PRE-1976 CUSTOMARY LAW}
        \textbf{Legality of Polygamous Unions:}
        \begin{itemize}
            \item Polygamy was fully recognized for non-Muslims if validated by customary practices.
            \item Chinese men could take multiple principal wives (\textit{tian}) and secondary wives (\textit{tsip}).
            \item Hindu customary unions tolerated polygamy based on caste laws and regional traditions.
        \end{itemize}
        
        \begin{casebox}{Landmark Precedent (The Six Widows Case)}
            \textit{\textbf{In the Estate of Choo Eng Choon (1908)}} \\
            The court recognized polygamy among the Chinese, granting equal status and inheritance rights to both primary and secondary wives.
        \end{casebox}
    \end{prebox}
\end{minipage}
\hfill
\begin{minipage}[t]{0.48\textwidth}
    \begin{postbox}{THEME 1: POST-1976 STATUTORY LAW}
        \textbf{Strict Enforceability of Monogamy:}
        \begin{itemize}
            \item Complete abolition of polygamy for all non-Muslims in Malaysia.
            \item \textbf{Section 5 of the LRA 1976:} Every marriage solemnized after the commencement of the Act is strictly monogamous.
            \item Any subsequent marriage entered into during the subsistence of a prior marriage is \textbf{void ab initio} (invalid from the start).
            \item \textbf{Bigamy Penalty:} Offenders are liable to criminal prosecution under the Penal Code.
        \end{itemize}
    \end{postbox}
\end{minipage}

\newpage

% =========================================================================
% THEME 2: REGISTRATION REQUIREMENTS
% =========================================================================
\noindent
\begin{minipage}[t]{0.48\textwidth}
    \begin{prebox}{THEME 2: PRE-1976 CUSTOMARY LAW}
        \textbf{Validity via Ritual Performance:}
        \begin{itemize}
            \item No statutory requirements existed for uniform marriage registration.
            \item Marriages were deemed valid as long as customary rites were successfully observed.
            \item \textbf{Chinese:} Tea ceremony, parental consent, and public feast.
            \item \textbf{Indian:} Tying of the \textit{thali} (sacred thread) witnessed by the community.
            \item \textbf{Systemic Issue:} Created massive judicial difficulty in proving the legal existence of a marriage.
        \end{itemize}
    \end{prebox}
\end{minipage}
\hfill
\begin{minipage}[t]{0.48\textwidth}
    \begin{postbox}{THEME 2: POST-1976 STATUTORY LAW}
        \textbf{Compulsory Statutory Registration:}
        \begin{itemize}
            \item Performance of traditional customary or religious rites alone no longer confers legal status.
            \item \textbf{Section 22 of the LRA 1976:} Registration with the Registrar of Marriages is strictly \textbf{compulsory}.
            \item Couples may still practice traditional rites, but the marriage is only legally binding upon official JPN registration.
            \item Guarantees absolute legal certainty and safeguards the status of wives.
        \end{itemize}
    \end{postbox}
\end{minipage}

\vspace{0.3cm}

% =========================================================================
% THEME 3: DIVORCE MECHANISMS
% =========================================================================
\noindent
\begin{minipage}[t]{0.48\textwidth}
    \begin{prebox}{THEME 3: PRE-1976 CUSTOMARY LAW}
        \textbf{Extra-Judicial Customary Divorces:}
        \begin{itemize}
            \item Divorces could be executed outside a formal court of law.
            \item \textbf{Chinese Custom:} Dissolution through mutual consent via public notices or signing a private separation agreement.
            \item \textbf{Indian Custom:} Marital disputes and divorces were settled outside the state apparatus by the \textit{Panchayat} (traditional caste councils).
        \end{itemize}
    \end{prebox}
\end{minipage}
\hfill
\begin{minipage}[t]{0.48\textwidth}
    \begin{postbox}{THEME 3: POST-1976 STATUTORY LAW}
        \textbf{Exclusive High Court Jurisdiction:}
        \begin{itemize}
            \item Complete elimination of extra-judicial customary divorces.
            \item Divorce can only be granted via a judicial decree issued by the civil High Court.
            \item \textbf{Section 53 of the LRA 1976:} Primary ground for divorce is the \textbf{irretrievable breakdown of marriage}.
            \item \textbf{Vectors of Proof:} Adultery, unreasonable behavior, 2 years of desertion, or 2 years of separation.
            \item Mandatory referral to a marriage conciliatory body prior to petition filing.
        \end{itemize}
    \end{postbox}
\end{minipage}

\vspace{0.4cm}

% =========================================================================
% ESSAY WRITING CHECKLIST & SUMMARY
% =========================================================================
\begin{introbox}{3. ESSAY WRITING CHECKLIST FOR HIGH MARKS (20 MARKS)}
    \begin{multicols}{2}
        \textbf{\textsf{Structural Essentials:}}
        \begin{itemize}
            \item[\checkmark] \textbf{Issue:} Clearly state the transition from customary legal pluralism to statutory uniformity.
            \item[\checkmark] \textbf{Theme 1:} Polygamy vs. Strict Monogamy (\textbf{S.5 LRA} \& \textit{\textbf{Six Widows Case}}).
            \item[\checkmark] \textbf{Theme 2:} Ritual Validity vs. Compulsory Registration (\textbf{S.22 LRA}).
            \item[\checkmark] \textbf{Theme 3:} Extra-judicial Custom vs. High Court Decrees (\textbf{S.53 LRA}).
        \end{itemize}
        \vfill\null
        \columnbreak
        \textbf{\textsf{Analytical Takeaway:}}
        \begin{itemize}
            \item[\checkmark] Emphasize that the LRA 1976 is a \textbf{progressive statutory intervention} that prioritized gender equality and legal certainty.
            \item[\checkmark] Explain that it eradicated vulnerabilities faced by women under unchecked, uncodified customs.
            \item[\checkmark] Conclude by highlighting how it permanently redefined the family law landscape.
        \end{itemize}
    \end{multicols}
\end{introbox}

\end{document}
