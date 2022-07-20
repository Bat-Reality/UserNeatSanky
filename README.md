# UserNeatSanky
<h1>Abstract</h1>
Sankey diagrams are widely used to visualize event sequence data. However, when the data volume is large, its readability is affected by edge crossing and wiggling, while obtaining an optimal layout takes lots of time. In this paper, we propose NeatSankey, a balanced method that generates Sankey diagrams smoothly. It can be laid out quickly with good readability when Sankey diagrams are very complex.  To comprehensively evaluate the readability of Sankey diagrams, we propose new evaluation metrics: swing amplitude and layout coverage. Firstly, we use a barycentric heuristic layout algorithm and a force-oriented algorithm to adjust the spacing of the same layer to minimize the lines' swing amplitude and layout coverage. Secondly, to better reduce the dense confusion caused by edge crossings, we introduce an ambiguity-free edge bundling algorithm based on attribute similarity. We present three evaluations: a comprehensive comparison of our results with state-of-the-art techniques, user studies with 30 volunteers, and a case study of five datasets. Our evaluations demonstrate the effectiveness and practicability of the NeatSankey. 
