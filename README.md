d3_tree_resume
=========

This is an animated d3.js tree visualization.

Required Resources
------------------
CSS
```
<link href="//maxcdn.bootstrapcdn.com/bootstrap/3.3.2/css/bootstrap.min.css" rel="stylesheet">
```

JavaScript
```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>
<script src="//maxcdn.bootstrapcdn.com/bootstrap/3.3.2/js/bootstrap.min.js"></script>
<script src="http://d3js.org/d3.v3.min.js"></script>
```

Project Files
```
<script src="http://rawgithub.com/cbm360/d3_tree_resume/master/d3resume.js"></script>
```

Creating the data
-----------------
You need a hierarchical JSON data file.

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
            {"name": "job or project where used", "size": 3938},
            {"name": "job or project where used", "size": 3812},
            {"name": "job or project where used", "size": 743}
          ]
        },
        {
          "name": "HighCharts",
          "children": [
            {"name": "job or project where used", "size": 3938},
            {"name": "job or project where used", "size": 3812},
            {"name": "job or project where used", "size": 743}
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
            {"name": "job or project where used", "size": 3938},
            {"name": "job or project where used", "size": 3812},
            {"name": "job or project where used", "size": 743}
          ]
        },
        {
          "name": "jQuery",
          "children": [
            {"name": "job or project where used", "size": 3938},
            {"name": "job or project where used", "size": 3812},
            {"name": "job or project where used", "size": 743}
          ]
        }
      ]
    }
  ]
}
```
