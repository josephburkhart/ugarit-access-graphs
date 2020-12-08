# Introduction

This repository contains justified access graphs for the following buildings at Late Bronze Age Ugarit: the Royal Palace, the House of Yabninu, and the House of Rapanu. All graphs were created in Gephi [1] and published to a github page using the Oxford Internet Institute's SigmaExporter Plugin For Gephi [2]. The URL for the github page is https://botdoubt.github.io/ugarit-access-graphs/.

The Justified Access Graph for the Royal Palace is at [https://botdoubt.github.io/ugarit-access-graphs/RoyalPalace](https://botdoubt.github.io/ugarit-access-graphs/RoyalPalace).
The Justified Access Graph for the House of Yabninu is at [https://botdoubt.github.io/ugarit-access-graphs/YabninuHouse](https://botdoubt.github.io/ugarit-access-graphs/YabninuHouse).  

The _config.json_ file for each graph was modified as follows:  
```
    "labelThreshold": 5,
    "defaultEdgeType": "line"
``` 

[1] https://gephi.org/  
[2] https://github.com/oxfordinternetinstitute/gephi-plugins/tree/sigmaexporter-plugin/modules/sigmaExporter

# Method
Access graphs represent the configurations of spaces in buildings and other built environments using networks of nodes and edges. By showing how spaces (represented by circular nodes) are joined together by doorways and other thresholds (represented by linear edges), access graphs can highlight patterns of movement, access, and control within a structure. When an access graph is "justified," it is arranged so that each space is aligned with all other spaces at the same "depth" (that is, the same number of edges) away from the outside. The outside is conventionally called the "carrier," and is represented by `+`.

# Data
All graphs were created using floorplans presented in Marguerite Yon's (2006) _The City of Ugarit at Tell Ras Shamra_.

# Additional Resources
Volodymyr Miz has written a very clear and useful tutorial on publishing to the web using the SigmaExporter Plugin [3]. 

Ostwald 2011 gives a recent overview of justified access graphs [4]. A broader, more recent discussion of Space Syntax in general can be found in Dawes and Ostwald 2018 [5].

[3] https://blog.miz.space/tutorial/2020/01/05/gephi-tutorial-sigma-js-plugin-publishing-interactive-graph-online/  
[4] https://doi.org/10.1007/s00004-011-0075-3  
[5] https://doi.org/10.1007/978-3-319-70658-0_6-1
