---
layout: default
---

## Status (last 5 commits)
```
{% include_relative data/repo.txt %}
```

## Matrix operation performance
(last 5 commits)

{% include_relative data/matrix.html %}

### ISL rowops with vector types performance

{% include_relative data/vector_bench.html %}

## ISL rowops performance

{% include_relative data/checked_rowops.html %}

## Paper plots

### Rowops hot

{% include_relative data/rowops_hot_gmp.html %}

### Rowops cold

{% include_relative data/rowops_cold_gmp.html %}

### Rowops checked vs unchecked (cold)

{% include_relative data/rowops_checked_unchecked_cold.html %}

### Rowops checked vs unchecked (hot)

{% include_relative data/rowops_checked_unchecked_hot.html %}
