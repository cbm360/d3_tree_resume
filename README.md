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
<script src="http://rawgithub.com/glena/d3-resume/master/d3resume.min.js"></script>
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
            {"name": "tree", "size": 3938},
            {"name": "box plot", "size": 3812},
            {"name": "chord diagram", "size": 743}
          ]
        },
        {
          "name": "JavaScript",
          "children": [
            {"name": "jQuery", "size": 3534},
            {"name": "D3", "size": 5731}
          ]
        }
      ]
    }
  ]
}
```
