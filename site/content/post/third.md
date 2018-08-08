---
date: 2018-08-07T10:24:16-04:00
title: Probando Hugo
---

Lo mismo que [aquí](https://test-hugo-01.netlify.com/post/crear-sitios-webs-con-hugo-y-rstudio/), utilizando otro tema ([Casper](https://github.com/vjeantet/hugo-theme-casper)), y publicando directamente desde [Netlify](https://app.netlify.com/start) conectando automáticamente con el correspondiente [repositorio de GitHub](https://github.com/joanh/casper-cms-template)), lo cual permite editar la web y ver los resultados tan pronto como hagas `git commit` y `git push`.

El [siguiente ejemplo](https://test-hugo-03.netlify.com/) es una mezcla de las dos anteriores:

![image](https://raw.githubusercontent.com/joanh/casper-cms-template/master/site/static/images/RblogwdownGitHubHugoNetifly.png)

que incidentalmente es la [recomendada por *Yihui*](https://bookdown.org/yihui/blogdown/workflow.html):

>It can be much easier to publish a website if you are familiar with GIT and GitHub. We recommend that you create a new site on Netlify from your GitHub repository that contains the source files of your website, so that you can enjoy the benefits of continuous deployment instead of manually uploading the public/ folder every time. With this approach, you do not need to run blogdown::hugo_build() locally, because the website can be built on Netlify via Hugo. See [Chapter 3](https://bookdown.org/yihui/blogdown/deployment.html#deployment) for more information.

---

La imagen está sacada de éste interesante artículo: [Migrating blog to Blogdown](https://mikeyharper.uk/migrating-to-blogdown/).
