% README.txt
% Last reviewed: 9 Oct 2024 by Sina Abdipoor

DISCLAIMER
This is not an official UPM template. Before using this for your thesis, check, double-check, and triple-check with your supervisor, your faculty, and SGS that they accept this.

COPYRIGHT
This project is licensed under the MIT license. You can use or modify this for your thesis as needed, but please credit the source: (https://sites.google.com/view/sina-abdipoor)

INTRODUCTION
This is a LaTeX thesis template I created to replicate the Universiti Putra Malaysia (UPM) official Word template (20240812102832Thesis_A4_Format_(Template)_(17.05.2024).docx)(included in this project) for the year 2025. I have tried to keep it as close to the official template as I could. I have already confirmed with my supervisor and SGS that I could use this. I'm using this exact template for my own Ph.D. thesis, but as mentioned in the disclaimer, make sure your supervisor, your committee, your faculty, SGS, and UPM all accept this before you start using this.

This template was a lot of work. I think I have done my part. I hope you find it useful. If you end up fixing something, or updating it, please open a request on GitHub (https://github.com/SinaAbdipoor/2025-upm-latex-thesis-template). Let's try to keep this template alive for the next students.

HOW TO USE
If you are a UPM postgraduate student and want to use this for your thesis, simply follow these steps:

Step 0: Play around with the template a bit. Make sure everything works and that it still follows the official template.

Step 1: Show this template to your supervisor, your committee members, your faculty, SGS, and everyone else concerned to make sure they all agree that you can use this. Otherwise, just use UPM's official template.

Step 2: Go to "info.tex" and insert all your information in the second brackets "{}". For example:
\newcommand{\infothesistitle}{Write your title of thesis here}

Step 3: Put all your figures in the "figures" folder.

Step 4: Go to "acronym.tex" and define all your abbreviations.

Step 5: Go to "publications.bib" and add all your publications in the .bib format.

Step 6: Go to "references.bib" and add all your references in the .bib format.

Step 7: Go to "thesis.tex" and start writing your thesis.

Step 8: Go to "appendix.tex" to write your appendices.

Step 9: Done! Recompile, check everything is correct, and submit it. Wish you the best of luck. You can stop reading here.

But, if you need more explanation or something in the template is wrong, continue reading.

SAMPLES
Sectioning
You can section your thesis and appendix using these commands:

\chapter{}, \section{}, \subsection{}, \subsubsection{}, and \paragraph{}

Abbreviations
This is an example of how to define an abbreviation in the "acronym.tex":

\DeclareAcronym{upm}{
  short=UPM,
  long=Universiti Putra Malaysia,
}

This is an example of how to use these acronyms within your thesis:

I studied at \ac{upm}.

Figures
An example of a figure is shown in Figure~\ref{fig:enter-label}.

\begin{figure}
    \centering
    \includegraphics[width=0.75\linewidth]{onion.png}
    \caption{Enter Caption}
    \label{fig:enter-label}
\end{figure}

Tables
An example of a table is shown in Table~\ref{tab:my_label}.

\begin{table}
    \centering
    \caption{Caption}
    \begin{tabular}{ccc}
         &  & \\
         &  & \\
         &  & \\
    \end{tabular}
    \label{tab:my_label}
\end{table}

Bullet List
An example of a bullet list:

\begin{itemize}
    \item 
\end{itemize}

Numbered List
An example of a numbered list:

\begin{enumerate}
    \item 
\end{enumerate}

Referencing
Use \textcite{} command to cite a paper from your "references.bib" as a text and use \parencite{} to cite in a parenthesis. Example: \textcite{abdipoor2023meta} claimed that their paper is super good \parencite{abdipoor2023meta}.

HOW TO MODIFY
By the time you read this, I'll have hopefully graduated (knock on wood). So, as Cantonese say "Ji Gaau Dim" or you are on your own. But just a few things to help you:

If you want to change the general formatting of the paper, like the font, the margins, etc., go to "main.tex"

Everything is pretty modular. So, if 1 of the pages of the template is outdated, or if there's an error, just go to the corresponding .tex file of that page and try to fix it.

If the official UPM template has changed a lot (and this template is not kept updated by volunteers after me), or if you are trying to use this template to adapt it to another university, don't do it. Trust me, it isn't worth it. Just use the official template.

Wow, you really read the entire README. You are either not a programmer or belong to a very niche 1% of the population. Regardless, give yourself a pat on the shoulder, you deserve it!