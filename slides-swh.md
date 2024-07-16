---
title: "Wait! Are you not using Software Heritage yet?!"
subtitle: "DMI-HPC Group Retreat"
author: "Quentin \\textsc{Guilloteau}"
date: "17/07/2024"
---

## {.plain}

\begin{center}
  \includegraphics[height=\textheight]{./figs/meme_rock.jpg}
\end{center}


## {.plain}

\begin{columns}
\begin{column}{0.5\textwidth}
  \includegraphics[height=\textheight]{./figs/meme_harold.jpg}
\end{column}
\hfill
\begin{column}{0.5\textwidth}
  \includegraphics[height=\textheight]{./figs/meme_community.jpg}
\end{column}
\end{columns}



## How to share source code?

\begin{itemize}
\item<1-> google drive? mega(upload)? \only<2->{$\rightsquigarrow$ \textbf{please do not}}
\item<3-> zip on personal webpage?    \only<4->{$\rightsquigarrow$ What if you change institution? Webpage changes? }
\item<5-> github/gitlab link?         \only<6->{$\rightsquigarrow$ What if they close? (Google Code, Forge Inria)}
\item<7-> zenodo? figshare?           \only<8->{$\rightsquigarrow$ Partial exploration?}
\end{itemize}

\only<9>{
    \begin{center}
	    The key word is \textbf{Longevity}
    \end{center}
}

## Software Heritage -- Presentation

\begin{columns}
    \begin{column}{0.5\textwidth}
	\begin{itemize}
	    \item \url{www.softwareheritage.org}
	    \item Archival of \emph{Source Code}
	    \begin{itemize}
		\item GitHub, GitLab, BitBucket, ...
		\item PyPI, NPM, Guix, Nix, ...
	    \end{itemize}
	    \item since 2015/2016 (INRIA)
	    \item Supported by UNESCO
	    \item Jul. 24:
	    \begin{itemize}
		\item 301 Millions of projects
		\item 4 Billions of commits
		\item 19 Billions of files
	    \end{itemize}
	\end{itemize}
    \end{column}
    \hfill
    \begin{column}{0.5\textwidth}
	\begin{center}
	    \includegraphics[width=\textwidth]{./figs/swh.jpg}
	\end{center}
    \end{column}
\end{columns}

## {.standout}

Demo Time!

## Software Heritage -- Biblatex\footnote{https://www.softwareheritage.org/2020/05/26/citing-software-with-style/} (1/2)


:::::::::::::: {.columns}
::: {.column width="25%"}

```latex
\usepackage[
  datamodel=software,
]{biblatex}
\usepackage{
  software-biblatex
}
% ...
LB4OMP \cite{lb4omp}
```

:::
::: {.column width="75%"}

```biblatex
@softwarerevision{lb4omp,
  title = {{LB4OMP}},
  author = {{DMI-HPC Group}},
  year = {2021},
  url = {https://github.com/unibas-dmi-hpc/LB4OMP},
  version = {0.1},
  swhid = {
  swh:1:rev:60e73ee93dccee745603fdc65825cbfa5130f4e9
  },
}
```

:::
::::::::::::::

## Software Heritage -- Biblatex (2/2)

\begin{center}
\includegraphics[width=0.9\textwidth]{./figs/lb4omp.png}
\end{center}

## Conclusion

:::::::::::::: {.columns}
::: {.column width="50%"}
- Software Heritage

  - Long term archival of \emph{Source Code}

  - supported by UNESCO

- Most adapted solution (as of today)

- Can easily and precisely cite software

- (sustainability?)
:::
::: {.column width="50%"}
\begin{center}
    \includegraphics[width=\textwidth]{./figs/meme_future.jpg}
\end{center}
:::
::::::::::::::

