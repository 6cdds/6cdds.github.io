---
layout: page
title: Test
plotly: true
---

# Test notebook


```python
import plotly.graph_objs as go
from plotly.offline import init_notebook_mode, iplot

init_notebook_mode(connected = True)
```


<script src="plotly.js" charset="utf-8"></script>



```python
iplot([go.Histogram(x = [1,5,2,7,8,3,3,4,6,5,4,2,5,4,2])])
```


<div id="0b2b3a9e-df32-4189-b627-e709336e1ebf" style="height: 525px; width: 100%;" class="plotly-graph-div"></div><script type="text/javascript">require(["plotly"], function(Plotly) { window.PLOTLYENV=window.PLOTLYENV || {};window.PLOTLYENV.BASE_URL="https://plot.ly";Plotly.newPlot("0b2b3a9e-df32-4189-b627-e709336e1ebf", [{"x": [1, 5, 2, 7, 8, 3, 3, 4, 6, 5, 4, 2, 5, 4, 2], "type": "histogram"}], {}, {"linkText": "Export to plot.ly", "showLink": true})});</script>
