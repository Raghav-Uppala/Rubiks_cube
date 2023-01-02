+++
type="page"
title="Step 3: 2 Look OLL"
weight = 4
+++

OLL is the step where you orient the top pieces. You make sure that the top is all the same color.

![](/images/bgm/bgm_OLL_dia_1.png)

For 2-Look OLL there are 2 steps.

1. Cross
2. Corners
## Cross
The algorithm(it will be used later): F (R U R’ U’) F'

The following are 3 cases that the yellow side could look like in the first stage of OLL.

|Case 1|Case 2|Case 3|
|:-|:-|:-|
|![](/images/bcfop/bcfop_OLL_stage_1_case_1.png)|![](/images/bcfop/bcfop_OLL_stage_1_case_2.png)|![](/images/bcfop/bcfop_OLL_stage_1_case_3.png)|
|Apply the algorithm to get Case 2.|Rotate to the above orientation. Apply the algorithm but instead of F and F' do f and f'.|You're done! Move on to stage 2.|

## Corners
There are 7 algorithms to memorize for 2-look OLL.  Orient the top layer(using U moves) and then apply the relevant algorithm. After that, the top layer will be all the same color, and you can move on to the next and final stage.

|Case Name|Case|Algorithm|
|:-:|:-:|:-:|
|Antisune|![](/images/bcfop/bcfop_OLL_stage_2_antisune.png)|R U2 R' U' R U' R'|
|H|![](/images/bcfop/bcfop_OLL_stage_2_H.png)|R U R' U R U' R' U R U2 R'|
|L|![](/images/bcfop/bcfop_OLL_stage_2_L.png)|F R' F' r U R U' r'|
|Pi|![](/images/bcfop/bcfop_OLL_stage_2_Pi.png)|R U2 R2 U' R2 U' R2 U2 R|
|Sune|![](/images/bcfop/bcfop_OLL_stage_2_sune.png)|R U R' U R U2 R'|
|T|![](/images/bcfop/bcfop_OLL_stage_2_T.png)|r U R' U' r' F R F'|
|U|![](/images/bcfop/bcfop_OLL_stage_2_U.png)|R2 D R' U2 R D' R' U2 R'|