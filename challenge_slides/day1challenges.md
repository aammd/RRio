day1challenges
========================================================
author: 
date: 28 Sept 2015

Challenge
========================================================

Run the code below, and write a command to
compare mass to age. Is mass larger than age?

```r
mass <- 47.5
age <- 122
mass <- mass * 2.3
age <- age - 20
```

Challenge
========================================================

We're going to create a new project in RStudio:

1. Click the "File" menu button, then "New Project".
2. Click "New Directory".
3. Click "Empty Project".
4. Type in the name of the directory to store your project, e.g. "my_project".
5. Make sure that the checkbox for "Create a git repository" is selected.
6. Click the "Create Project" button.

Challenge
========================================================

Use your knowledge of how to assign a value to
a variable, to create examples of data with the
following characteristics:

1. Variable name: 'answer', Type: logical
2. Variable name: 'height', Type: numeric
3. Variable name: 'dog_name', Type: character

For each variable you've created, test that it
has the data type you intended. Do you find
anything unexpected?

Challenge
========================================================

```r
x <- matrix(rnorm(18), ncol=6, nrow=3)
```

What do you think will be the result of
`length(x)`?
Try it.
Were you right? Why / why not?

Challenge
========================================================

* Make another matrix, this time containing the numbers 1:50,
with 5 columns and 10 rows.
* Did the `matrix` function fill your matrix by column, or by
row, as its default behaviour?
* See if you can figure out how to change this.
(hint: read the documentation for `matrix`!)


Challenge
========================================================

```r
df <- data.frame(id = c('a', 'b', 'c', 'd', 'e', 'f'), x = 1:6, y = c(214:219))
df
```
Try using the `length` function to query
your data frame `df`. Does it give the result
you expect?

Challenge
========================================================

Create a data frame that holds the following information for yourself:

* First name
* Last name
* Age

Then use rbind to add the same information for the people sitting near you.

Challenge
========================================================

```r
x <- c(5.4, 6.2, 7.1, 4.8, 7.5)
names(x) <- c('a', 'b', 'c', 'd', 'e')
x
```

```
  a   b   c   d   e 
5.4 6.2 7.1 4.8 7.5 
```

1. Come up with at least 3 different commands that will produce the following output:


```
  b   c   d 
6.2 7.1 4.8 
```

2. Compare notes with your neighbour. Did you have different strategies?

Challenge
========================================================


```r
m <- matrix(1:18, nrow=3, ncol=6)
print(m)
```

```
     [,1] [,2] [,3] [,4] [,5] [,6]
[1,]    1    4    7   10   13   16
[2,]    2    5    8   11   14   17
[3,]    3    6    9   12   15   18
```

Which of the following commands will extract the values 11 and 14?

1. `m[2,4,2,5]`
1. `m[2:5]`
1. `m[4:5,2]`
1. `m[2,c(4,5)]`

Get gapminder
========================================================

[`http://bit.ly/gminder`](http://bit.ly/gminder)
