# knowledgeGraph
This repository includes knowledge graphs mined from Stack Overflow by our methods. It contains one file and two subfolders:

1. knowledgeGraph: There are 110 (10x11) knolwedge graphs with combinations of two parameters, minimal support (0.0001 to 0.001 by 0.0001) and minimal confidence (0 to 0.5 by 0.05). Each graph is named in style like "support_confidence.pdf";

2. evolution: There are 69 knolwedge graphs in this folder. Each graph represents one month of Stack Overflow from 2008-08 to 2014-04. Each graph is named in style like "year_month.pdf"

There is also one html file named 'knowledgeGraph.html'. We incorporate our knowledge graph in the interactive webpage with minimal support as 0.0007 and minimal confidence as 0.15. It is written in javascript with D3 lib. You can download it and open it in your web server and then better observe our knowledge graph.
Have fun.
