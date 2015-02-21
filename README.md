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
  "name": "flare",
  "children": [
    {
      "name": "analytics",
      "children": [
        {
          "name": "cluster",
          "children": [
            {"name": "AgglomerativeCluster", "size": 3938},
            {"name": "CommunityStructure", "size": 3812},
            {"name": "MergeEdge", "size": 743}
          ]
        },
        {
          "name": "graph",
          "children": [
            {"name": "BetweennessCentrality", "size": 3534},
            {"name": "LinkDistance", "size": 5731}
          ]
        }
      ]
    }
  ]
}
```
