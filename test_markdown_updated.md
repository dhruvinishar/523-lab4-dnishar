test
================
Dhruvi Nishar - dnishar
2022-10-01

## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax
for authoring HTML, PDF, and MS Word documents. For more details on
using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that
includes both content as well as the output of any embedded R code
chunks within the document. You can embed an R code chunk like this:

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

## Including Plots

You can also embed plots, for example:

![](test_markdown_updated_files/figure-gfm/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.

|                                                                      |
|----------------------------------------------------------------------|
| This is a separation for the text sections in this markdown document |

# Header 1

Lets talk about the penguins dataset - The goal of palmerpenguins is to
provide a great dataset for data exploration & visualization, as an
alternative to iris.

# Header 2

There is another dataset - gapminder, where he main object in this
package is the gapminder data frame or “tibble”. There are other
goodies, such as the data in tab delimited form, a larger unfiltered
dataset, premade color schemes for the countries and continents, and ISO
3166-1 country codes.

``` r
print("Let's calculate the sum of two numbers")
```

    ## [1] "Let's calculate the sum of two numbers"

``` r
a <- 643
b <- -834

paste("The sum of ", a, " and ", b, " is ",a+b)
```

    ## [1] "The sum of  643  and  -834  is  -191"

``` r
print("Let's calculate the difference of two numbers")
```

    ## [1] "Let's calculate the difference of two numbers"

``` r
a <- 643
b <- 814

paste("The sum of ", a, " and ", b, " is ",b-a)
```

    ## [1] "The sum of  643  and  814  is  171"
