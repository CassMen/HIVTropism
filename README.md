# HIV Tropism
Predicts HIV-1 subtype C tropism using emsemble learning with genotypic algorithms.
Made using R version 3.6.0.

# Required packages 
```r
install.packages("caret")
```
Observation: R may require you to install additional packages, such as the ones needed for the machine learning models.

# Tutorial
- Fill in template.csv with results fom genotypic tests.
- Choose desired stacking model and download the corresponding file:
  * SIMCA: mSIMCA.rds
  * k-Nearest Neighbors: mKnn.rds
  * Rotation Forest: mRotationForest.rds
  * CART: mCART.rds
  * Multi-Layer Perceptron: mMultiPerceptron.rds
- Run script below.

```r
library(caret)

# Write the path to downloaded .RDS file. 
# Example: "C:/Downloads/model.rds"
HIV_ML <- readRDS("model.rds")

# Data should be like template file. Fill in the path to .CSV file.
data <- read.table("template.csv", header = TRUE, sep = ";", na.strings = "NA", dec = ".", strip.white = TRUE)

# Predictions are on vector 'pred'.
pred <- predict(HIV_ML, newdata = data)
```

---

# Tropismo do HIV
Prevê o tropismo do HIV-1 subtipo C com stacking de testes genotípicos.
Feito com R, versão 3.6.0.

# Pacotes necessários
```r
install.packages("caret")
```
Observação: Pode ser necessário instalar pacotes adicionais para os modelos de aprendizado de máquina.

# Tutorial
- Preencha template.csv com os resultados dos testes genotípicos.
- Escolha o modelo de stacking desejado e faça download do arquivo correspondente:
  * SIMCA: mSIMCA.rds
  * k-Nearest Neighbors: mKnn.rds
  * Rotation Forest: mRotationForest.rds
  * CART: mCART.rds
  * Multi-Layer Perceptron: mMultiPerceptron.rds
- Rode o script abaixo.

```r
library(caret)

# Escreva o caminho para o arquivo .RDS baixado. 
# Exemplo: "C:/Downloads/model.rds"
HIV_ML <- readRDS("models.rds")

# Dados devem estar como no arquivo template. Preencha o caminho para o arquivo .CSV.
data <- read.table("template.csv", header = TRUE, sep = ";", na.strings = "NA", dec = ".", strip.white = TRUE)

# Predições estão no vetor 'pred'.
pred <- predict(HIV_ML, newdata = data)
```



