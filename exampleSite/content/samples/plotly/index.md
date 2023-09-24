---
title: Plotly Plot Test
date: "2023-9-23"
plotly: true
---

## Plot Rendering Test

A plot should be showing below.

Fix this by change line 110 of `congo/layouts/head.html`

from:
```
    {{ partial "extend-head.html" .Site }}
```

to:
```
    {{ partial "extend-head.html" . }}
```

{{< plotly json=test-plotly.json height=200 >}}
