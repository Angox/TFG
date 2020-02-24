---
documentclass: book
#version imprimir a dos caras
classoption: a4paper
#####
#version para libro digital
# classoption: a4paper,oneside
# urlcolor: blue #black
# linkcolor: blue #black
#####
#bibliography: bib/library.bib
bibliography: ["bib/library.bib", "bib/paquetes.bib"]
#csl: methods-in-ecology-and-evolution.csl
csl: acm-sig-proceedings-long-author-list.csl
link-citations: yes
fontsize: 12pt # 10pt,11pt
geometry: margin = 2.5cm 
output: 
  pdf_document: 
    keep_tex: no
    number_sections: yes
#    toc: yes
    fig_caption: yes
    includes:
      in_header: latex/latex_preambulo.tex
      before_body: portadas/latex_paginatitulo_modTFE.tex
#      before_body: portadas/latex_paginatitulo_modTFGE.tex
#      before_body: portadas/latex_paginatitulo_modTFGM.tex
#      before_body: portadas/latex_paginatitulo_modTFDGME.tex
#      before_body: portadas/latex_paginatitulo_modTFMDS.tex
#      before_body: portadas/latex_paginatitulo_mod_OV01.tex
      after_body: latex/latex_antes_enddoc.tex
---

---
nocite: | 
  @Luque2017,@RStudio,@R-base,
  @R-knitr,@R-rmarkdown,@R-dplyr,@R-ggplot2, @R-xtable,
  @R-stringr,@Techopedia
...





<!-- Indentar el texto al inicio de cada nuevo párrafo -->
\setlength{\parindent}{1em}

\pagestyle{fancy}
\fancyhead[LE,RO]{}
\fancyhead[LO,RE]{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}
\pagenumbering{roman}

\setcounter{tocdepth}{4}
\subpdfbookmark{Índice General}{indice}
\tableofcontents


\cleardoublepage   
<!--  \clearpage -->
\section*{Prólogo}
\addcontentsline{toc}{section}{Prólogo}




Escrito colocado al comienzo de una obra en el que se hacen comentarios sobre la obra o su autor, o se introduce en su lectura; a menudo está realizado por una persona distinta del autor.

También se podrían incluir aquí los agradecimientos.


\cleardoublepage   
<!--  \clearpage -->
\section*{Resumen}
\addcontentsline{toc}{section}{Resumen}



Resumen...


\clearpage
\section*{Abstract}
\addcontentsline{toc}{section}{Abstract}



Abstract...


\cleardoublepage   
\listoffigures
\addcontentsline{toc}{section}{Índice de Figuras}

\cleardoublepage   

\listoftables
\addcontentsline{toc}{section}{Índice de Cuadros}


\cleardoublepage   

\pagenumbering{arabic}

\fancyhead[LE,RO]{\scriptsize\rightmark}
\fancyfoot[LO,RE]{\scriptsize\slshape \leftmark}
\fancyfoot[C]{}
\fancyfoot[LE,RO]{\footnotesize\thepage}
\renewcommand{\headrulewidth}{0.4pt}
\renewcommand{\footrulewidth}{0.4pt}









<!-- \setcounter{chapter}{2} -->
<!-- \setcounter{chapter}{2} escribir 2 para capítulo 3  -->
<!-- \pagenumbering{arabic} -->

\fancyhead[LE,RO]{\scriptsize\rightmark}
\fancyfoot[LO,RE]{\scriptsize\slshape \leftmark}
\fancyfoot[C]{}
\fancyfoot[LE,RO]{\footnotesize\thepage}
\renewcommand{\headrulewidth}{0.4pt}
\renewcommand{\footrulewidth}{0.4pt}


# Título del Capítulo

## Primera sección

\FloatBarrier








<!-- \setcounter{chapter}{2} -->
<!-- \setcounter{chapter}{2} escribir 2 para capítulo 3  -->
<!-- \pagenumbering{arabic} -->

\fancyhead[LE,RO]{\scriptsize\rightmark}
\fancyfoot[LO,RE]{\scriptsize\slshape \leftmark}
\fancyfoot[C]{}
\fancyfoot[LE,RO]{\footnotesize\thepage}
\renewcommand{\headrulewidth}{0.4pt}
\renewcommand{\footrulewidth}{0.4pt}


# Título del Capítulo

## Primera sección

\FloatBarrier








<!-- \setcounter{chapter}{2} -->
<!-- \setcounter{chapter}{2} escribir 2 para capítulo 3  -->
<!-- \pagenumbering{arabic} -->

\fancyhead[LE,RO]{\scriptsize\rightmark}
\fancyfoot[LO,RE]{\scriptsize\slshape \leftmark}
\fancyfoot[C]{}
\fancyfoot[LE,RO]{\footnotesize\thepage}
\renewcommand{\headrulewidth}{0.4pt}
\renewcommand{\footrulewidth}{0.4pt}


# Título del Capítulo

## Primera sección

\FloatBarrier








<!-- \setcounter{chapter}{2} -->
<!-- \setcounter{chapter}{2} escribir 2 para capítulo 3  -->
<!-- \pagenumbering{arabic} -->

\fancyhead[LE,RO]{\scriptsize\rightmark}
\fancyfoot[LO,RE]{\scriptsize\slshape \leftmark}
\fancyfoot[C]{}
\fancyfoot[LE,RO]{\footnotesize\thepage}
\renewcommand{\headrulewidth}{0.4pt}
\renewcommand{\footrulewidth}{0.4pt}


# Título del Capítulo

## Primera sección

\FloatBarrier

\appendix







<!-- \appendix -->
<!-- \setcounter{chapter}{0} -->
<!-- \setcounter{chapter}{0} escribir 0 para apéndice A  -->

<!-- \pagenumbering{arabic} -->

\fancyhead[LE,RO]{\scriptsize\rightmark}
\fancyfoot[LO,RE]{\scriptsize\slshape \leftmark}
\fancyfoot[C]{}
\fancyfoot[LE,RO]{\footnotesize\thepage}
\renewcommand{\headrulewidth}{0.4pt}
\renewcommand{\footrulewidth}{0.4pt}


# Apéndice: Título del Apéndice


## Primera sección











<!-- \appendix -->
<!-- \setcounter{chapter}{0} -->
<!-- \setcounter{chapter}{0} escribir 0 para apéndice A  -->

<!-- \pagenumbering{arabic} -->

\fancyhead[LE,RO]{\scriptsize\rightmark}
\fancyfoot[LO,RE]{\scriptsize\slshape \leftmark}
\fancyfoot[C]{}
\fancyfoot[LE,RO]{\footnotesize\thepage}
\renewcommand{\headrulewidth}{0.4pt}
\renewcommand{\footrulewidth}{0.4pt}


# Apéndice: Título del Apéndice


## Primera sección




\FloatBarrier
\cleardoublepage   


\fancyhead[CO,CE]{Bibliografía}

# Bibliografía
