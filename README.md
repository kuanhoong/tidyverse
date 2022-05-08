# Introduction to Tidyverse

[tidyverse](https://www.tidyverse.org) in R, one of the Important packages in R, there are a lot of new techniques available maybe users are not aware of.

## Description

In this live code-along session, you'll learn the basic principles of analyzing your data using R and the tidyverse. You'll code along to explore the `nycflights13` dataset and discover how you can use packages (i.e. sets of tools for doing stuff with data) in the tidyverse to get from data to insight as intuitively and efficiently as possible. But seriously: if you want to filter your data, you use the verb (or function) `filter`; if you wish to arrange it in a particular order, you use `arrange`. The tidyverse set of tools is a revolution that consists of computational tools that intuitively mirror how we all think about data.

In this session, we will use Kaggle Notebook and Tidyverse to explore the [`NYC Flights 2013`](https://cran.r-project.org/web/packages/nycflights13/) dataset, which consists of observations of all flights that departed NYC in 2013. The data frame contains all 336,776 flights and the data comes from the US Bureau of Transportation Statistics, and is documented in `?flight`

## dplyr package
There are five key dplyr functions that allow you to solve the vast majority of your data manipulation challenges:

- Pick observations by their values (`filter()`).
- Reorder the rows (`arrange()`).
- Pick variables by their names (`select()`).
- Create new variables with functions of existing variables (`mutate()`).
- Collapse many values down to a single summary (`summarise()`).


These can all be used in conjunction with group_by() which changes the scope of each function from operating on the entire dataset to operating on it group-by-group. These six functions provide the verbs for a language of data manipulation.


# Tidy Data

There’s a popular saying in Data Science that goes like this — *“Data Scientists spend up to 80% of the time on data cleaning and 20 percent of their time on actual data analysis.*

## tidyr package

`tidyr` — set of functions to help you get tidy data. It’s the successor to reshape2(which uses melt and cast). It has 5 main categories

- Pivoting → `pivot_longer()` & `pivot_wider()`
- Rectangling → `unnest_longer()`, `unnest_wider()`, `hoist()`
- Nesting → `nest()` & `unnest()`
- Splitting and combining columns → `separate()`,`extract()`, `unite()`
- Missing Values → `complete()`, `drop_na()`, `fill()`, `replace_na()`

## Clone the repository

To get set up for this live coding session, clone this repository. You can do so by executing the following in your terminal:

```
git clone https://github.com/kuanhoong/tidyverse
```

Alternatively, you can download the zip file of the repository at the top of the main page of the repository. If you prefer not to use git or don't have experience with it, this a good option.
