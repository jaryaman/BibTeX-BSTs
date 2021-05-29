Add the following to your LaTeX preamble 

```
\usepackage[super]{natbib}
\setcitestyle{citesep={,}}
\makeatletter  
\renewcommand\@biblabel[1]{#1.}  
\makeatother
```
An additional useful command is to be able to locally disable superscript citations:
```
\newcommand*{\citen}{}% generate error, if `\citen` is already in use
\DeclareRobustCommand*{\citen}[1]{%
  \begingroup
    \romannumeral-`\x % remove space at the beginning of \setcitestyle
    \setcitestyle{numbers}%
    \cite{#1}%
  \endgroup
}
```
