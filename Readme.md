G440: a 5-chromatic unit-distance graph with 440 vertices

By Erik deNeve

GitHub: numbersandcode

G440 is a set of 440 points in the plane, with an edge between every two points at distance exactly 1 (2,099 edges), that cannot be colored with four colors so that the ends of every edge differ. A proper five-coloring is included in G440.k21 and graph440.json. I found it on 23 November 2026 and certified it the same day with standard tools (kissat, drat-trim, cake_lpr). I found an earlier 440-vertex graph with 2,106 edges on 21 November 2026, and the sevenfold rotationally symmetric 442-vertex graph on 19 November 2026.

It stands at the end of a line of constructions inspired by Haugland’s heptagon framework: Haugland (2,131 vertices), Wong (1,501), Sergi Galán (852) and Chandan Shukla (557), whose graph was the starting point for G440. 
Aubrey de Grey's first 5-chromatic unit-distance graph (2018) and Marijn Heule's computer-checked reductions opened the way for all of them.

Heule and Przybocki’s 449-vertex graph, posted on 21 November 2026, has its complex vertex positions in the same cyclotomic field, ℚ(ζ₂₁), as G440. Their construction grew outward from a symmetric core before being reduced to 449 vertices.

I reached this 440-vertex graph the other way: by walking down from Shukla's graph in small exchanges of points, and by taking the union of seven rotational copies to work with fully symmetric graphs along the way. Its fully sevenfold-symmetric relative, G442 (442 vertices, 2,100 edges, 430 vertex locations in common with G440), is included.

