## Analisis de Supervivencia y Machine Learning

Instala las depencencias de Bioconductor con el siguiente script:

```console
if (!require("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install("RTCGAToolbox")

if (!require("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install("limma")
```