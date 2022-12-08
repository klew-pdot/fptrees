# Which trees were the most popular to plant?

After exploring the data, I have been able to determine the total number of trees planted and by type.

```python
x = sum(trees_df.groupby(['TREE_TYPE'])['TREE_TYPE'].count())
print(x)
```

```{margin} Did you know?
There have been 66,770 trees planted!
```

```{note}
This value may change as the data source is updated.
```


The code above may be confusing, but it is essentially counting how many trees in each tree type and then summing those counts.  Below is a simple mathematical formula to display to mechanics of it.

$$
\sum_{i=1}^n x_i = x_{maple} + x_{cherry} + x_{plum} + x_{other}
$$

Below is the breakdown of the trees in graphical format.


```{figure} https://github.com/klew-pdot/fptrees/blob/main/images/number_of_trees_planted_by_type.png?raw=true
---
height: 139px
width: 735px
name: number_of_trees_planted_by_type
---
Number of trees plant by type.
```