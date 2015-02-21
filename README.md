d3_tree_resume
=========

This is an animated d3.js tree visualization.

Required Resources
------------------
External Libraries
```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>
<script src="http://d3js.org/d3.v3.min.js"></script>
```

Project Files
```
<script src="http://rawgithub.com/cbm360/d3_tree_resume/master/d3resume.js"></script>
```

Creating the data
-----------------
You need a hierarchical JSON data file like the following.  Additional child tiers can be added as desired.

Format:
```
{
  "name": "skill",
  "children": [
    {
      "name": "data visualization",
      "children": [
        {
          "name": "d3",
          "children": [
            {"name": "job or project where used"},
            {"name": "job or project where used"},
            {"name": "job or project where used"}
          ]
        },
        {
          "name": "HighCharts",
          "children": [
            {"name": "job or project where used"},
            {"name": "job or project where used"},
            {"name": "job or project where used"}
          ]
        }
      ]
    },
    {
      "name": "JavaScript",
      "children": [
        {
          "name": "d3",
          "children": [
            {"name": "job or project where used"},
            {"name": "job or project where used"},
            {"name": "job or project where used"}
          ]
        },
        {
          "name": "jQuery",
          "children": [
            {"name": "job or project where used"},
            {"name": "job or project where used"},
            {"name": "job or project where used"}
          ]
        }
      ]
    }
  ]
}
```

Helpful Resources
-----------------
https://github.com/mbostock/d3/wiki/Gallery


http://mbostock.github.io/d3/talk/20111018/tree.html

