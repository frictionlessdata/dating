# Most popular topics

```json chart
{
  "data": {"url": "../data/topics.csv"},
  "mark": "bar",
  "encoding": {
    "x": {"field": "topic", "type": "nominal"},
    "y": {"field": "topic", "aggregate": "count"}
  },
  "height": "400",
  "width": "600"
}
```

