# Excersise 1B

---
title: "1B"
author: "Ylva Carlen"
format: html
editor: visual
---
```{r}
?qnbinom()
```

#### Define the variables

the Mean:

```{r}
mean<-mu
mu=10
mean
```

the Variance:

```{r}
variance=mu+mu^2*2
variance

```

#### Variable in line

The variance and the mean can be calculated with the formula variance= mean+mean\^2\*dispersion. By using the Formula with a mean of `r mean` and a dispersion of 2 we obtein for the variance `r variance`.

#### Define the negative binomial distribution to x1

```{r}
x1 <- rnbinom(100, mu = 10, size = 2)
```

#### Create a histogram

```{r}
?hist
h1<-hist(x1, main= paste("Histogramm of negative binomia-distribution, with mean=10 and sd=210"), col="lightblue")
```



