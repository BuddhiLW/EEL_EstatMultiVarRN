# Redes Neurais - R
Este repositório contém os notebooks apresentados no trabalho sobre Redes Neurais, da disciplina de Estatística Multivariável. Os notebooks são escritos em R, e rodam em cima de Jupyter.

## Setup
Este repositório pode ser clonado através do comando `git clone git@github.com:igor-yamamoto/EEL_EstatMultiVarRN.git` ou baixado diretamente como aquivo zip.

Os pacotes utilizados são gerenciados através do pacote de ambiente virtual [`renv`](https://github.com/rstudio/renv). A sua instalação pode ser feita através dos comandos em um prompt R:
``` r 
install.packages("remotes")
library("remotes")
remotes::install_github("rstudio/renv")
```

Após instalar este pacote, um ambiente virtual pode ser inicializado através através do comando `renv::init()`, e as dependências instaladas com `renv::restore()`.