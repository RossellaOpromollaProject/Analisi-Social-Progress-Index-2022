# Analisi del Social Progress Index 2022

## Autore
Rossella Opromolla

## Descrizione del progetto
Questo progetto analizza il Social Progress Index 2022 (SPI), un indicatore composito che misura il livello di progresso sociale dei Paesi andando oltre le tradizionali metriche economiche come il PIL.

L’analisi è sviluppata in R Markdown e si concentra su:

- Analisi esplorativa dei dati
- Analisi delle componenti principali 
- Clustering
- Regressione lineare semplice e multipla

## Struttura del Social Progress Index
L’indice è articolato in tre dimensioni fondamentali:

- Basic Human Needs
- Foundations of Wellbeing
- Opportunity

Ciascuna dimensione contribuisce al punteggio complessivo attraverso specifici indicatori.

## Struttura del repository
- Analisi-Social-Progress-Index-2022/
- ReportRossellaOpromolla.Rmd
- Social Progress Index 2022.csv
- README.md

## Dataset
Il dataset utilizzato è:

Social Progress Index 2022.csv

Contiene:

- Punteggio complessivo SPI
- Ranking dei Paesi
- Punteggi per dimensione

## Tecnologie utilizzate
- R
- R Markdown
- tidyverse
- psych
- car
- corrplot
- factoextra
- knitr
- cluster
- ggplot2
- MASS
- dplyr
- sandwich
- lmtest
- tidyr
- mclust


## Come eseguire il progetto
1. Clonare il repository
2. Aprire `ReportRossellaOpromolla.Rmd` in RStudio
3. Installare le librerie necessarie
4. Eseguire:

rmarkdown::render("ReportRossellaOpromolla.Rmd")

## Finalità
Progetto realizzato a fini accademici per l’analisi e l’interpretazione di indicatori compositi di sviluppo sociale.
