# Questions

Please provide your R code in the `todo` spaces beneath each question. Be sure to remove the `todo` tags after providing your solution.

## Add Your Name Here

### 1

Create a `summary` of the diamonds data set. Calculate the mean and standard deviation of each column in the dataset.

``` {R}
TODO
```

### 2

Use `filter()` to create a new dataset called with only the white diamonds (Note: in the diamonds data, the _color_ Variable will be set to "D"). Use the `select()` function to extract the _carat_, _cut_, _color_, _clarity_, and _price_ columns from the dataset.

``` {R}
TODO
```

### 3

Arrange the data set by ascending order of price. Use the `mutate()` function to create a new column called _price_per_carat_ that is equal to the _price_ divided by the _carat_ column.

Hint: Modify the following expression to complete the challenge.

``` {R}
diamonds %>% mutate(TODO) %>% arrange(price))
```

### 4

Use `summarize()` to calculate the _average_, _maximum_, and _minimum_ prices for each cut type. Calculate the standard deviation of the prices for each cut type.

Hint: Modify the following expression to complete the challenge.

``` {R}
diamonds %>% 
   group_by(TODO) %>% 
   summarize(
    mean_price = mean(TODO), 
    max_price = max(TODO), 
    min_price = min(TODO), 
    sd_price = sd(TODO)
    )
```

### 5

Create a plot using `ggplot()`. Create a bar chart showing the _price_ of diamonds for each _cut_ type.

Hint: Modify the following expression to complete the challenge.

``` {R}
diamonds %>% ggplot(TODO) + geom_bar(stat = "identity")
```

### 6

Select only _price_ and _cut_ data from the _Diamonds_ dataset to create a table of statistical summaries.

``` {R}
# Load the diamond dataset
diamonds %>%  TODO %>% summary()
```

### 7

Use `summarize()` to calculate the _average_, _maximum_, and _minimum_ prices for each _color_ type. Calculate the standard deviation of the prices for each _color_ type.

Hint: Modify the following expression to complete the challenge.

``` {R}
diamonds %>% group_by(TODO) %>% summarize(mean_price = TODO(price), max_price = TODO(price), min_price = TODO(price), sd_price = TODO(price))
```

### 8

Create a plot using `ggplot()`. Create a line chart using `geom_line()` that indicates ranges of _prices_ for types of _cuts_.

``` {R}
TODO
```

### 9

Arrange the data set by ascending order of carat _size_. Use the `filter()` function to create a new dataset with only the diamonds that are less than 1 carat. Use `select()` to extract the _carat_, _cut_, _color_, _clarity_, and _price_ columns from the dataset.

``` {R}
TODO
```

### 10

Use `summarize()` to calculate the average, maximum, and minimum prices for each _color_ type in the diamonds that are less than 1 _carat_. Calculate the standard deviation of the _prices_ for each _color_ type.

``` {R}
TODO
```

### 11

Create a plot using `ggplot()`. Create a bar chart using `geom_bar()` showing the number of diamonds for each cut type in the diamonds that are less than 1 _carat_.

``` {R}
TODO
```

### 12

Use `mutate()` to create a new column called "price_per_carat" in the original dataset, which is equal to the _price_ divided by the _carat_ column.

``` {R}
TODO
```

### 13

Create a plot using `ggplot()`. Create a line chart showing the evolution of the average price of diamonds over time in the original dataset.

``` {R}
TODO
```

### 14

Use `filter()` to create a new dataset with only the diamonds that are less than 1 carat and have a cut type of “Ideal”. Use select() to extract the carat, cut, color, clarity, and price columns from the dataset.

``` {R}
TODO
```

### 15

Use `summarize()` to calculate the _average_, _maximum_, and _minimum_ prices for each _color_ type in the diamonds that are less than 1 carat and have a cut type of "Ideal". Calculate the standard deviation of the prices for each color type.

Hint: Modify the following expression to complete the challenge.

``` {R}
diamonds %>% group_by(TODO) %>% filter(TODO) %>% summarize(mean_price = TODO(price), max_price = TODO(price), min_price = TODO(price), sd_price = TODO(price))

```

(Did you remember to add your name to the top of this document?)