+++
type="page"
title="Step 4: 2 Look PLL"
weight = 5
+++

2-Look PLL is the final stage of the beginner CFOP method. Its goal is to move the edges and corners into the correct position. For example:
![](/images/bcfop/bcfop_PLL_example.png)

There are two stages too 2-Look PLL:
1. Corners
2. Edges

## Corners

There are two algorithms for solving the corners of the top layer.

|Case Name|Case|Algorithm|
|:-|:-|:-|
|Diagonal(Y perm)|If none of the sides have matching corners|F R U' R' U' R U R' F' R U R' U' R' F R F'|
|Headlights(T perm)|If one of the sides has matching corners(headlights). Orient them to the left.|R U R' U' R' F R2 U' R' U' R U R' F'|

## Edges

After solving the corners, you now have to solve the edges(unless you get lucky and the cube is already solved).

|Case Name|Case|Algorithm|
|:-|:-|:-|
|H perm|If the edge piece belongs on the opposite side of the cube.|M2 U M2 U2 M2 U M2|
|Z perm|If the edge piece belongs to the the side on the left of the cube(if it belongs on the right, do U).|M' U M2 U M2 U M' U2 M2|
|Ua perm|if one side is fully solved and(when the solved side is on the opposite side) the edge pieces need to go to the right.|R U' R U R U R U' R' U' R2|
|Ub perm|Similar to the Ua perm but the pieces need to go to the left.|R2 U R U R' U' R' U' R' U R'|