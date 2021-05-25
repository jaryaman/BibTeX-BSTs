Add the following to your LaTeX preamble 

```tex
\usepackage[super]{natbib}
\setcitestyle{citesep={,}}
\makeatletter  
\renewcommand\@biblabel[1]{#1.}  
\makeatother
```
