# Iris
<<<<<<< HEAD
branch test 
branch test now
library(datasets)
summary(iris)
names(iris)
library(dplyr)
tolower(names(iris))
head(virginica)
tail(virginica)
sepalLength6 <- filter(iris, species == "virginica", sepal.length > 6)
tail(sepalLength6)
plot(iris$Sepal.Length, iris$Sepal.Width)
install.packages("tidyverse")
library(tidyverse)
ggplot(data = iris, aes(x = Sepal.Length, y = Sepal.Width)) + 
  geom_point(size = 3) + 
  geom_smooth(size = 1, se = FALSE) + 
  facet_grid(rows = vars(Species))
  
  
<<<<<<< HEAD
adding in a box plot 
boop boop bee bop 
it looks good
=======
>>>>>>> 1526aa863846ee1e9e458a99aa7bf48c8dbc1bd8

