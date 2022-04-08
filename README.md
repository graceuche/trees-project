# This is my practice exercise on using Plotly

```sql
SELECT
  COUNT(*) AS number_trees,
  health
FROM
  `bigquery-public-data.new_york_trees.tree_census_2015`
GROUP BY
  health
ORDER BY
  number_trees DESC;
```

