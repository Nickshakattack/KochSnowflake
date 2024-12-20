# KochSnowflake

  A recursive procedure is used to create the Koch Snowflake. A single line segment is split into three equal parts at each recursive step, resulting in four smaller segments. 
The middle third of the line is replaced with two sides of an equilateral triangle, pointing outward from the original segment. 
In particular, this includes identifying the apex of the equilateral triangle that the middle third forms and determining the two division points that trisect the segment.
Translating the middle third and then rotating it by ±60° with respect to the direction of the segment yields the apex.
Recursion's base case occurs when the line segment's length falls below a predetermined minimum (such as epsilon) or after a predetermined number of recursive steps. 

  The segment is drawn without any additional subdivision at this point, and the recursion ends.
The vertices of the triangle can be positioned in relation to the original line segment's endpoints using translation to make the implementation simpler. 
The triangular peak can then be created by rotating the middle third to change its direction. 
The fractal pattern is gradually revealed by recursively applying this procedure to each of the four resulting segments. 
This method guarantees that the Koch Snowflake increases in complexity as intended and stops when the required level of detail is reached.
