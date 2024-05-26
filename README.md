# UnalR <a href='https://estadisticaun.github.io/UnalR/'><img src='man/figures/Logo.png' align="right" height="134" /></a>

<!-- badges: start -->
[![R-CMD-check](https://github.com/estadisticaun/UnalR/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/estadisticaun/UnalR/actions/workflows/R-CMD-check.yaml)
[![test-coverage](https://github.com/estadisticaun/UnalR/actions/workflows/test-coverage.yaml/badge.svg)](https://github.com/estadisticaun/UnalR/actions/workflows/test-coverage.yaml)
[![Codecov test coverage](https://codecov.io/gh/estadisticaun/UnalR/branch/master/graph/badge.svg)](https://app.codecov.io/gh/estadisticaun/UnalR?branch=master)
<!-- badges: end -->

El paquete `UnalR` proporciona métodos y herramientas para la gestión y disposición de estadísticas institucionales. Su objetivo principal es disponer, facilitar y optimizar la disposición de microdatos y la visualización de las cifras y estadísticas oficiales de la [Universidad Nacional de Colombia](https://unal.edu.co) las cuales se encuentran disponibles, dentro del [sistema de planeación](https://planeacion.unal.edu.co/home/) institucional, en el componente de [estadísticas oficiales](https://estadisticas.unal.edu.co/home/). Contiene una biblioteca de funciones gráficas, tanto estáticas como interactivas, que ofrece numerosos tipos de gráficos con una sintaxis altamente configurable y simple. Entre estos, encontramos la visualización de tablas `HTML`, series, gráficos de barras y circulares, mapas, boxplots, radar charts, treemaps, drilldown, etc. Todo lo anterior apoyado en bibliotecas de `JavaScript`.

El paquete `UnalR` permanecerá en su estado actual y se mantendrá solo con correcciones de errores.

## Instalación

Puede instalar la versión publicada de `UnalR` (*versión menor*) desde [GitHub](https://github.com/) con:

``` r
# install.packages("devtools")
devtools::install_github("estadisticaun/UnalR")

# install.packages("remotes")
remotes::install_github("estadisticaun/UnalR")
```

## Uso

Es difícil describir de manera sucinta cómo funciona `UnalR` porque encarna una profunda filosofía de visualización que abarca las principales librerías para representar de forma dinámica e interactiva datos usando `JavaScript` (**htmlwidgets**).

## Ejemplo

``` r
library(UnalR)
example(topic = Tabla, package = "UnalR")
```
![](man/figures/PlotExample1.png)

``` r
example(topic = Plot.Series, package = "UnalR")
```
![](man/figures/PlotExample2.png)

``` r
example(topic = Plot.Barras, package = "UnalR")
```
![](man/figures/PlotExample3.png)

``` r
example(topic = Plot.Mapa, package = "UnalR")
```
![](man/figures/PlotExample4.png)
![](man/figures/PlotExample5.png)

``` r
example(topic = Plot.Boxplot, package = "UnalR")
```
![](man/figures/PlotExample6.PNG)

``` r
example(topic = Plot.Treemap, package = "UnalR")
```
![](man/figures/PlotExample7.PNG)
![](man/figures/PlotExample8.PNG)
![](man/figures/PlotExample9.PNG)
![](man/figures/PlotExample10.PNG)

## Licencia

Este paquete es un software gratuito y de código abierto, con licencia GPL-3.

## Ayuda

Si requiere ayuda para usar `UnalR`:

  * Para problemas de instalación, comuníquese a los correos electrónicos proporcionados en la documentación del paquete, normalmente respondemos con prontitud y usted también ayudará a futuros usuarios.

Si cree que ha encontrado un error:

  * Instale la versión de desarrollo de `UnalR` usando `devtools` (*ver arriba*) y vea si eso ayuda.
  * Consulte los [problemas de github](https://github.com/estadisticaun).

¡Gracias por tu interés en `UnalR`!
