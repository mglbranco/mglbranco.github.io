---
layout: post
title: Reproducibilidade en ciencia con R
date: 2016-11-11 20:20
blog: true
---

O pasado 20 de novembro, hai pouco, os _R-galegos_ tivemos unha nova quedada, e xa é a terceira!. Antes de seguir, doulle as grazas por se animar repetir e os meus parabéns pola organización a [Melisa](http://webmelisa.es/) e ás/aos axudantes!.

Convidáronme a participar cun obradoiro e (despois de ver posibilidades e argallar un pouco) decidimos repetir a temática do ano [anterior](https://github.com/mglbranco/researcheRs/). Falei da _«Reproducibilidade en ciencia con R: da obtención de datos á publicación»_. Moitos de nós, que investigamos na biomedicina, na xenómica, na ecología poboacional e macroecoloxía..., temos que afrontar os retos da obtención dunha gran cantidade de datos e/ou de diversas fontes, o seu tratamento, a súa análise e a publicación dos seus resultados. Pero un aspecto fundamental hoxe por hoxe nos debates destes campos científicos, é a capacidade de repetición tanto dos estudos coma das análises que nos levaron ás nosas conclusións científicas. Xa non abonda cunha publicación descriptiva nunha revista de "gran impacto". Agora é __«give me the code!» (and the data too!)__.

Así que o primeiro que introducín no obradoiro son as posibilidades que agora mesmo nos ofrece __R__ para isto, no que se está a chamar _[«Reproducible research»](https://cran.r-project.org/web/views/ReproducibleResearch.html)_. Hai varias liñas de investigación que actualmente están a xerar inxentes cantidades de datos, _p.ex._ a xenómica e a secuenciación masiva de comunidades microbianas. Mais, [seica son tantos datos que xa case non sabemos que facer con eles!](https://www.washingtonpost.com/news/speaking-of-science/wp/2015/07/07/sequencing-the-genome-creates-so-much-data-we-dont-know-what-to-do-with-it/). Arestora xa R cobre todos os aspectos que supón obter e re-analizar datos. R tamén che nolos permite compartir analizados como publicacións dinámicas. Tamén depositar en [repositorios públicos](http://journals.plos.org/plosone/s/data-availability#loc-recommended-repositories), como [NCBI](https://www.ncbi.nlm.nih.gov/gquery/) ou [Dryad](http://datadryad.org/), os datos cos que temos traballado, i.e. que foron recolleitos no campo ou tratados no laboratorio por nós. Por iso digo con moita facilidade que R é a linguaxe franca das ciencias ([sen dúbidalo](http://stackoverflow.com/questions/1738087/what-can-matlab-do-that-r-cannot-do)).

O __obradoiro__ estivo pensado para facer unha introdución das posibiliades de R neste campo e xerar un breve resumo dunha análise de datos. Ambas partes están dispoñibles aquí:
1. A [Introdución do curso](https://github.com/mglbranco/researcheRs2/blob/master/introducion.md)
2. O [material da tarefa e as "solucións"](https://github.com/mglbranco/researcheRs2/tree/master/markdown_ex)

Tamén se pode descargar o __material completo do curso__ desde o seu repositorio: [ResearcheRs2](https://github.com/mglbranco/researcheRs2). Sobre da tarefa, a idea é que se colla o ficheiro "margalef53-ex.Rmd" se solucionen os erros e fagan as tarefas que ten indicadas. Podedes empregar unha IDE como [RStudio](https://www.rstudio.com/) para iso ou facelo en liña de comandos como indico na sección de _«Procesado dos ficheiros R Markdow»_.  

Se tedes dúbidas, [deixádemas bo buzón](mbranco@protonmail.com). Mais, o bo de que o tivese publicado nun repositorio _git_ público é que o podedes _clonar_, modificar e facer tantas _pull requests_ como erros haxa para solventar ou cafés/cañas que lle queirades adicar :D
