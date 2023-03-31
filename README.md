
## Pie chart

```mermaid
pie 
  title Pet ownership
  "Dogs" : 386
  "Cats" : 97
  "Fish" : 15
```


```mermaid
gantt
    title Test
    todayMarker off
    dateFormat  X
    axisFormat %s

    section Baseline
    70111   : 0, 6170460

    section Automatic
    This PR (3781) (4.134M)   : 0, 4134494

    section Manual
    This PR (3781) (5.199M)   : 0, 5199286
    master (5.335M)   : 0, 5335475
    benchmarks/2.23.0 (5.464M)   : 0, 5464474

    section Manual + Automatic
    This PR (3781) (3.922M)   : 0, 3921636
    master (4.023M)   : 0, 4023108
    benchmarks/2.23.0 (4.095M)   : 0, 4094835
```
