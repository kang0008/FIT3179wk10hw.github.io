<!DOCTYPE html>
<html>
<head>
  <title>Week 10 Homework</title>
  <!-- Import Vega & Vega-Lite (does not have to be from CDN) -->
  <script src="https://cdn.jsdelivr.net/npm/vega@5.20.2"></script>
  <script src="https://cdn.jsdelivr.net/npm/vega-lite@5.1.0"></script>
  <script src="https://cdn.jsdelivr.net/npm/vega-embed@6.17.0"></script>
  
 <!-- Import pure.css -->
 <link rel="stylesheet" href="https://unpkg.com/purecss@2.0.3/build/pure-min.css" integrity="sha384-cg6SkqEOCV1NbJoCu11+bm0NvBRc8IYLRGXkmNrqUBfTjmMYwNKPWBTIKyw9mHNJ" crossorigin="anonymous">
 <meta name="viewport" content="width=device-width, initial-scale=1">

 <!-- Google font -->
 <link href="https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@400;700;900&display=swap" rel="stylesheet">

 <!-- CSS file -->
 <link rel="stylesheet" type="text/css" href="css/style.css" media="all">


</head>

<body>
  
<div class="page">
  <h2>Choropleth_map</h2>
  <!-- pure grid group -->
  <div class="pure-g">
    <div class = "pure-u-1-1">
      <div id = "vis1" class = "vis-container"></div>
    </div>
  </div>
 
  <br>

<hr class="hr3">

  <h2>Interactive Line Chart</h2>
  <!-- pure grid group -->
  <div class="pure-g">
    <div class="pure-u-1-1">
      <div id="vis2" class="vis-container"></div>
    </div>
  </div>
  <!-- end pure grid group -->
  <br>

  <hr class="hr3">
  </div>

<script type="text/javascript">
  var specVis1 = "js_hw/choropleth_map.vg.json";
  vegaEmbed('#vis1', specVis1);

  var specVis2 = "js_hw/carsales_interactive2.vg.json";
  vegaEmbed('#vis2', specVis2);
</script>

</body>
</html>
