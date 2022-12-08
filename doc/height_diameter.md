# What were their heights and diameters?

As we can see by the graph for height, the majority of trees planted are within the 10'-40' range. However, the bulk of the trees being maple extend out to 80'. This could be based on when the trees were planted. Older ones would have a longer period to grow compared to newly planted trees.

As for the diameter of the trees, there seems to be 3 distinct lines of tree groupings. They seem to be primarily cherry and maple trees with a few plum indicators added in. There does seem to be a crowding between the 10" and 30" diameters, but remember that these are indicators only and not full counts. Each mark could consist of 1 or more trees in the count. Like the height of the trees, the diameter of the trees could be due to a longer growth period since being planted compared to newly planted trees.

The average height of trees is 2.6 ft tall and the average diameter is 11.6 ft!

```python
street_trees_df.loc[:,('HEIGHT_RANGE_ID', 'DIAMETER')].describe()
```

I used the following equation to determine the average height and diameter of the planted trees.

$$
\bar{x}=\frac{x_1 + x_2 ... + x_n}{n}=\frac{1}{n}\Bigg( \sum_{i=1}^{n} x_i \Bigg)
$$

```{figure} https://github.com/klew-pdot/fptrees/blob/main/images/height.png?raw=true
---

width: 578px
name: height_and_diameter
---
The height of planted trees.
```

```{figure} https://github.com/klew-pdot/fptrees/blob/main/images/diameter.png?raw=true
---

width: 1578px
name: height_and_diameter
---
The diameter of planted trees.
```