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

## Paper plots

### Rowops hot

{% include_relative data/rowops_hot_gmp.html %}

{% include_relative data/rowops_hot_gmp_perf.html %}

### Rowops cold

{% include_relative data/rowops_cold_gmp.html %}

{% include_relative data/rowops_cold_gmp_perf.html %}

### Rowops checked vs unchecked (cold)

{% include_relative data/rowops_checked_unchecked_cold.html %}

### Rowops checked vs unchecked (hot)

{% include_relative data/rowops_checked_unchecked_hot.html %}

### Rowops scalar vs vectorized (cold)

{% include_relative data/rowops_cold_vector_speedup.html %}

{% include_relative data/rowops_cold_vector_perf.html %}

### Rowops scalar vs vectorized (hot)

{% include_relative data/rowops_hot_vector_speedup.html %}

{% include_relative data/rowops_hot_vector_perf.html %}
