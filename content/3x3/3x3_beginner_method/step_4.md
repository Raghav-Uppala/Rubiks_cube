+++
type="page"
title="Step 4: Permutation of Yellow Corners"
weight = 4
+++

This step involves swawping corners until the corners are in the right place. However they may not be in the right orientation. This algorithm is used to cycle the position of the corners.

The algorithm(A) is: U R U' L' U R' U' L U


After applying the algorithm, the U face may look like this:
![](/images/bgm/bgm_corner_cycle_ex.png)

Basicly, this algorithm cycles the postions of three of the corners.

![](/images/bgm/bgm_corner_cycle.png)

After you finished the yellow cross, find the corner that is in the correct postion(it may not be in the correct orientation but if the corner is turned, then it should be in the right place). Rotate the U layer such that, that corner is in  right corner closest to you. Now apply the algorithm. If the other corners are in the correct postion then you move on to the next step. If not, then apply the algorithm again.

If there are no corners in the right postion, then apply the algorithm once randomly. Then follow the above.