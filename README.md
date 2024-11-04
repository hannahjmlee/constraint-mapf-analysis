# An Analysis of Constraint-Based Multi-Agent Pathfinding Algorithms - Data and Results
This repository holds all of the data and plots presented in the "An Analysis of Constraint-Based Multi_Agent Pathfinding Algorithms" paper. Raw and compiled data can be found in the Data repository. Grouped and Individual map plots are shown in the Figures directory. All figures are also present within this README.

If you are looking to reproduce our results, please see our [MANA-Core](https://github.com/hannahjmlee/MANA-Core/tree/constraint_analysis) repository. For our representation topological analysis code, please see our [TopologyAnalysis](https://github.com/hannahjmlee/TopologyAnalysis) repository.

If you would like to run the data scraper and plot generator, please run the Plot jupyter notebook to generate all grouped and individual plots.

If you have any questions, please contact me at [hannah9@illinois.edu](hannah9@illinois.edu).

<br>
<br>

## Grouped Map Plots
| Group | Average Runtime | Success Rate | Flowtime Ratios |
|--|--|--|--|
|  Empty | ![plot-Empty](./Figures/GroupedFigures/AverageTime_empty.png) | ![plot-Empty](./Figures/GroupedFigures/SuccessRate_empty.png) | ![plot-Empty](./Figures/GroupedFigures/CostRatios_empty.png) |
|  Random | ![plot-Random](./Figures/GroupedFigures/AverageTime_random.png) | ![plot-Random](./Figures/GroupedFigures/SuccessRate_random.png) | ![plot-Random](./Figures/GroupedFigures/CostRatios_random.png) |
|  Narrow | ![plot-Narrow](./Figures/GroupedFigures/AverageTime_Narrow.png) | ![plot-Narrow](./Figures/GroupedFigures/SuccessRate_Narrow.png) | ![plot-Narrow](./Figures/GroupedFigures/CostRatios_Narrow.png) |
|  Cities | ![plot-Cities](./Figures/GroupedFigures/AverageTime_cities.png) | ![plot-Cities](./Figures/GroupedFigures/SuccessRate_cities.png) | ![plot-Cities](./Figures/GroupedFigures/CostRatios_cities.png) |
|  Games | ![plot-Games](./Figures/GroupedFigures/AverageTime_games.png) | ![plot-Games](./Figures/GroupedFigures/SuccessRate_games.png) | ![plot-Games](./Figures/GroupedFigures/CostRatios_games.png) |

<br>
<br>

## Individual Map Plots
| Map | Average Runtime | Success Rate | Flowtime Ratios |
|--|--|--|--|
|  empty-8-8 | ![plot-empty-8-8](./Figures/IndividualFigures/AverageTime_empty-8-8.png) | ![plot-empty-8-8](./Figures/IndividualFigures/SuccessRate_empty-8-8.png) | ![plot-empty-8-8](./Figures/IndividualFigures/CostRatios_empty-8-8.png) |
|  empty-16-16 | ![plot-empty-16-16](./Figures/IndividualFigures/AverageTime_empty-16-16.png) | ![plot-empty-16-16](./Figures/IndividualFigures/SuccessRate_empty-16-16.png) | ![plot-empty-16-16](./Figures/IndividualFigures/CostRatios_empty-16-16.png) |
|  empty-32-32 | ![plot-empty-32-32](./Figures/IndividualFigures/AverageTime_empty-32-32.png) | ![plot-empty-32-32](./Figures/IndividualFigures/SuccessRate_empty-32-32.png) | ![plot-empty-32-32](./Figures/IndividualFigures/CostRatios_empty-32-32.png) |
|  empty-48-48 | ![plot-empty-48-48](./Figures/IndividualFigures/AverageTime_empty-48-48.png) | ![plot-empty-48-48](./Figures/IndividualFigures/SuccessRate_empty-48-48.png) | ![plot-empty-48-48](./Figures/IndividualFigures/CostRatios_empty-48-48.png) |
|  random-32-32-10 | ![plot-random-32-32-10](./Figures/IndividualFigures/AverageTime_random-32-32-10.png) | ![plot-random-32-32-10](./Figures/IndividualFigures/SuccessRate_random-32-32-10.png) | ![plot-random-32-32-10](./Figures/IndividualFigures/CostRatios_random-32-32-10.png) |
|  random-32-32-20 | ![plot-random-32-32-20](./Figures/IndividualFigures/AverageTime_random-32-32-20.png) | ![plot-random-32-32-20](./Figures/IndividualFigures/SuccessRate_random-32-32-20.png) | ![plot-random-32-32-20](./Figures/IndividualFigures/CostRatios_random-32-32-20.png) |
|  random-64-64-10 | ![plot-random-64-64-10](./Figures/IndividualFigures/AverageTime_random-64-64-10.png) | ![plot-random-64-64-10](./Figures/IndividualFigures/SuccessRate_random-64-64-10.png) | ![plot-random-64-64-10](./Figures/IndividualFigures/CostRatios_random-64-64-10.png) |
|  random-64-64-20 | ![plot-random-64-64-20](./Figures/IndividualFigures/AverageTime_random-64-64-20.png) | ![plot-random-64-64-20](./Figures/IndividualFigures/SuccessRate_random-64-64-20.png) | ![plot-random-64-64-20](./Figures/IndividualFigures/CostRatios_random-64-64-20.png) |
|  room-32-32-4 | ![plot-room-32-32-4](./Figures/IndividualFigures/AverageTime_room-32-32-4.png) | ![plot-room-32-32-4](./Figures/IndividualFigures/SuccessRate_room-32-32-4.png) | ![plot-room-32-32-4](./Figures/IndividualFigures/CostRatios_room-32-32-4.png) |
|  room-64-64-8 | ![plot-room-64-64-8](./Figures/IndividualFigures/AverageTime_room-64-64-8.png) | ![plot-room-64-64-8](./Figures/IndividualFigures/SuccessRate_room-64-64-8.png) | ![plot-room-64-64-8](./Figures/IndividualFigures/CostRatios_room-64-64-8.png) |
|  room-64-64-16 | ![plot-room-64-64-16](./Figures/IndividualFigures/AverageTime_room-64-64-16.png) | ![plot-room-64-64-16](./Figures/IndividualFigures/SuccessRate_room-64-64-16.png) | ![plot-room-64-64-16](./Figures/IndividualFigures/CostRatios_room-64-64-16.png) |
|  maze-32-32-2 | ![plot-maze-32-32-2](./Figures/IndividualFigures/AverageTime_maze-32-32-2.png) | ![plot-maze-32-32-2](./Figures/IndividualFigures/SuccessRate_maze-32-32-2.png) | ![plot-maze-32-32-2](./Figures/IndividualFigures/CostRatios_maze-32-32-2.png) |
|  maze-32-32-4 | ![plot-maze-32-32-4](./Figures/IndividualFigures/AverageTime_maze-32-32-4.png) | ![plot-maze-32-32-4](./Figures/IndividualFigures/SuccessRate_maze-32-32-4.png) | ![plot-maze-32-32-4](./Figures/IndividualFigures/CostRatios_maze-32-32-4.png) |
|  maze-128-128-10 | ![plot-maze-128-128-10](./Figures/IndividualFigures/AverageTime_maze-128-128-10.png) | ![plot-maze-128-128-10](./Figures/IndividualFigures/SuccessRate_maze-128-128-10.png) | ![plot-maze-128-128-10](./Figures/IndividualFigures/CostRatios_maze-128-128-10.png) |
|  maze-128-128-2 | ![plot-maze-128-128-2](./Figures/IndividualFigures/AverageTime_maze-128-128-2.png) | ![plot-maze-128-128-2](./Figures/IndividualFigures/SuccessRate_maze-128-128-2.png) | ![plot-maze-128-128-2](./Figures/IndividualFigures/CostRatios_maze-128-128-2.png) |
|  Berlin_1_256 | ![plot-Berlin_1_256](./Figures/IndividualFigures/AverageTime_Berlin_1_256.png) | ![plot-Berlin_1_256](./Figures/IndividualFigures/SuccessRate_Berlin_1_256.png) | ![plot-Berlin_1_256](./Figures/IndividualFigures/CostRatios_Berlin_1_256.png) |
|  Boston_0_256 | ![plot-Boston_0_256](./Figures/IndividualFigures/AverageTime_Boston_0_256.png) | ![plot-Boston_0_256](./Figures/IndividualFigures/SuccessRate_Boston_0_256.png) | ![plot-Boston_0_256](./Figures/IndividualFigures/CostRatios_Boston_0_256.png) |
|  Paris_1_256 | ![plot-Paris_1_256](./Figures/IndividualFigures/AverageTime_Paris_1_256.png) | ![plot-Paris_1_256](./Figures/IndividualFigures/SuccessRate_Paris_1_256.png) | ![plot-Paris_1_256](./Figures/IndividualFigures/CostRatios_Paris_1_256.png) |
|  ht_chantry | ![plot-ht_chantry](./Figures/IndividualFigures/AverageTime_ht_chantry.png) | ![plot-ht_chantry](./Figures/IndividualFigures/SuccessRate_ht_chantry.png) | ![plot-ht_chantry](./Figures/IndividualFigures/CostRatios_ht_chantry.png) |
|  ht_mansion_n | ![plot-ht_mansion_n](./Figures/IndividualFigures/AverageTime_ht_mansion_n.png) | ![plot-ht_mansion_n](./Figures/IndividualFigures/SuccessRate_ht_mansion_n.png) | ![plot-ht_mansion_n](./Figures/IndividualFigures/CostRatios_ht_mansion_n.png) |
|  lak303d | ![plot-lak303d](./Figures/IndividualFigures/AverageTime_lak303d.png) | ![plot-lak303d](./Figures/IndividualFigures/SuccessRate_lak303d.png) | ![plot-lak303d](./Figures/IndividualFigures/CostRatios_lak303d.png) |
|  lt_gallowstemplar_n | ![plot-lt_gallowstemplar_n](./Figures/IndividualFigures/AverageTime_lt_gallowstemplar_n.png) | ![plot-lt_gallowstemplar_n](./Figures/IndividualFigures/SuccessRate_lt_gallowstemplar_n.png) | ![plot-lt_gallowstemplar_n](./Figures/IndividualFigures/CostRatios_lt_gallowstemplar_n.png) |
|  den312d | ![plot-den312d](./Figures/IndividualFigures/AverageTime_den312d.png) | ![plot-den312d](./Figures/IndividualFigures/SuccessRate_den312d.png) | ![plot-den312d](./Figures/IndividualFigures/CostRatios_den312d.png) |
|  ost003d | ![plot-ost003d](./Figures/IndividualFigures/AverageTime_ost003d.png) | ![plot-ost003d](./Figures/IndividualFigures/SuccessRate_ost003d.png) | ![plot-ost003d](./Figures/IndividualFigures/CostRatios_ost003d.png) |
|  brc202d | ![plot-brc202d](./Figures/IndividualFigures/AverageTime_brc202d.png) | ![plot-brc202d](./Figures/IndividualFigures/SuccessRate_brc202d.png) | ![plot-brc202d](./Figures/IndividualFigures/CostRatios_brc202d.png) |
|  den520d | ![plot-den520d](./Figures/IndividualFigures/AverageTime_den520d.png) | ![plot-den520d](./Figures/IndividualFigures/SuccessRate_den520d.png) | ![plot-den520d](./Figures/IndividualFigures/CostRatios_den520d.png) |
|  w_woundedcoast | ![plot-w_woundedcoast](./Figures/IndividualFigures/AverageTime_w_woundedcoast.png) | ![plot-w_woundedcoast](./Figures/IndividualFigures/SuccessRate_w_woundedcoast.png) | ![plot-w_woundedcoast](./Figures/IndividualFigures/CostRatios_w_woundedcoast.png) |

<br>
<br>

## Graph Statistics and Map Groupings
|  Type  	|         Map         	|    Size   	| Res 	| States 	| CBS Min 	| CBS Max 	| PBS Min 	| PBS Max 	|
|:------:	|:-------------------:	|:---------:	|:---:	|:------:	|:-------:	|:-------:	|:-------:	|:-------:	|
|  Empty 	| empty-8-8           	|   8 x 8   	|  1  	|     64 	|      12 	|      24 	|      12 	|      28 	|
|        	|                     	|           	|  2  	|    225 	|      12 	|      28 	|      24 	|      32 	|
|        	|                     	|           	|  4  	|    841 	|       4 	|      24 	|      20 	|      32 	|
|        	| empty-16-16         	|  16 x 16  	|  1  	|    256 	|      12 	|      36 	|      20 	|      40 	|
|        	|                     	|           	|  2  	|    961 	|       0 	|      40 	|      32 	|      56 	|
|        	|                     	|           	|  4  	|   3721 	|       0 	|      36 	|      24 	|      56 	|
|        	| empty-32-32         	|  32 x 32  	|  1  	|   1024 	|      12 	|      68 	|      32 	|      80 	|
|        	|                     	|           	|  2  	|   3969 	|       8 	|      68 	|      32 	|      80 	|
|        	|                     	|           	|  4  	|  15625 	|       8 	|      40 	|      28 	|      76 	|
|        	| empty-48-48         	|  48 x 48  	|  1  	|   2304 	|      16 	|      84 	|      48 	|      84 	|
|        	|                     	|           	|  2  	|   9025 	|      16 	|      76 	|      44 	|     100 	|
|        	|                     	|           	|  4  	|  35721 	|      12 	|      40 	|      16 	|      60 	|
| Random 	| random-32-32-10     	|  32 x 32  	|  1  	|    922 	|      12 	|      44 	|      32 	|      60 	|
|        	|                     	|           	|  2  	|   3185 	|       4 	|      44 	|      28 	|      60 	|
|        	|                     	|           	|  4  	|  11575 	|       4 	|      40 	|      28 	|      60 	|
|        	| random-32-32-20     	|  32 x 32  	|  1  	|    819 	|      12 	|      40 	|      24 	|      44 	|
|        	|                     	|           	|  2  	|   2468 	|       8 	|      40 	|      24 	|      44 	|
|        	|                     	|           	|  4  	|   8040 	|       4 	|      28 	|      20 	|      40 	|
|        	| random-64-64-10     	|  64 x 64  	|  1  	|   3687 	|      20 	|      84 	|      44 	|      88 	|
|        	|                     	|           	|  2  	|  12830 	|       8 	|      68 	|      28 	|      88 	|
|        	|                     	|           	|  4  	|  46764 	|       4 	|      56 	|      12 	|      60 	|
|        	| random-64-64-20     	|  64 x 64  	|  1  	|   3270 	|       8 	|      52 	|      20 	|      76 	|
|        	|                     	|           	|  2  	|  10031 	|       8 	|      48 	|      20 	|      48 	|
|        	|                     	|           	|  4  	|  33225 	|       8 	|      36 	|      20 	|      48 	|
| Narrow 	| room-32-32-4        	|  32 x 32  	|  1  	|    682 	|       8 	|      24 	|       4 	|      28 	|
|        	|                     	|           	|  2  	|   1902 	|       4 	|      20 	|       4 	|      28 	|
|        	|                     	|           	|  4  	|   5878 	|       0 	|      20 	|       4 	|      24 	|
|        	| room-64-64-8        	|  64 x 64  	|  1  	|   3232 	|       8 	|      24 	|       8 	|      28 	|
|        	|                     	|           	|  2  	|  11090 	|       0 	|      20 	|       8 	|      24 	|
|        	|                     	|           	|  4  	|  40630 	|       0 	|      16 	|       0 	|      20 	|
|        	| room-64-64-16       	|  64 x 64  	|  1  	|   3646 	|       4 	|      36 	|       8 	|      32 	|
|        	|                     	|           	|  2  	|  13585 	|       4 	|      24 	|       8 	|      24 	|
|        	|                     	|           	|  4  	|  52297 	|       0 	|      16 	|       0 	|      16 	|
|        	| maze-32-32-2        	|  32 x 32  	|  1  	|    666 	|       4 	|      16 	|       8 	|      20 	|
|        	|                     	|           	|  2  	|   1951 	|       0 	|      16 	|       4 	|      16 	|
|        	|                     	|           	|  4  	|   6381 	|       0 	|      12 	|       0 	|      12 	|
|        	| maze-32-32-4        	|  32 x 32  	|  1  	|    790 	|       4 	|      16 	|       4 	|      16 	|
|        	|                     	|           	|  2  	|   2695 	|       0 	|      16 	|       5 	|      16 	|
|        	|                     	|           	|  4  	|   9853 	|       0 	|      12 	|       4 	|      12 	|
|        	| maze-128-128-2      	| 128 x 128 	|  1  	|  10858 	|       0 	|      12 	|       0 	|      12 	|
|        	|                     	|           	|  2  	|  32383 	|       0 	|       4 	|       0 	|       4 	|
|        	|                     	|           	|  4  	| 107437 	|       0 	|       0 	|       0 	|       0 	|
|        	| maze-128-128-10     	| 128 x 128 	|  1  	|  14818 	|       0 	|      20 	|       0 	|      20 	|
|        	|                     	|           	|  2  	|  56143 	|       0 	|      16 	|       0 	|      16 	|
|        	|                     	|           	|  4  	| 218317 	|       0 	|       4 	|       0 	|       4 	|
| Cities 	| Berlin-1-256        	| 256 x 256 	|  1  	|  47536 	|       4 	|      88 	|      24 	|      92 	|
|        	|                     	|           	|  2  	| 182171 	|       4 	|      60 	|       8 	|      48 	|
|        	|                     	|           	|  4  	| 712615 	|       0 	|      36 	|       0 	|      36 	|
|        	| Boston-0-256        	| 256 x 256 	|  1  	|  47747 	|      12 	|      64 	|       8 	|      52 	|
|        	|                     	|           	|  2  	| 181232 	|       4 	|      40 	|       4 	|      32 	|
|        	|                     	|           	|  4  	| 705218 	|       0 	|      12 	|       0 	|      12 	|
|        	| Paris-1-256         	| 256 x 256 	|  1  	|  47216 	|       0 	|      68 	|      24 	|      64 	|
|        	|                     	|           	|  2  	| 179271 	|       0 	|      44 	|       4 	|      44 	|
|        	|                     	|           	|  4  	| 697685 	|       0 	|      24 	|       0 	|      24 	|
|  Games 	| ht-chantry          	| 141 x 162 	|  1  	|   7461 	|      12 	|      28 	|      12 	|      28 	|
|        	|                     	|           	|  2  	|  27912 	|       4 	|      20 	|       4 	|      20 	|
|        	|                     	|           	|  4  	| 107742 	|       0 	|      16 	|       0 	|      16 	|
|        	| ht-mansion-n        	| 270 x 133 	|  1  	|   8959 	|       4 	|      40 	|      12 	|      40 	|
|        	|                     	|           	|  2  	|  33376 	|       4 	|      32 	|       0 	|      24 	|
|        	|                     	|           	|  4  	| 128554 	|       0 	|      20 	|       0 	|      16 	|
|        	| lak303d             	| 194 x 194 	|  1  	|  14784 	|       4 	|      24 	|       4 	|      24 	|
|        	|                     	|           	|  2  	|  54938 	|       0 	|      16 	|       0 	|      16 	|
|        	|                     	|           	|  4  	| 211230 	|       0 	|       8 	|       0 	|       8 	|
|        	| lt-gallowstemplar-n 	| 180 x 251 	|  1  	|  10021 	|       8 	|      36 	|      12 	|      36 	|
|        	|                     	|           	|  2  	|  54938 	|       0 	|      16 	|       0 	|      16 	|
|        	|                     	|           	|  4  	| 211230 	|       0 	|       8 	|       0 	|       8 	|
|        	| den312d             	|  81 x 65  	|  1  	|   2445 	|       4 	|      28 	|      16 	|      32 	|
|        	|                     	|           	|  2  	|   8779 	|       4 	|      28 	|       8 	|      28 	|
|        	|                     	|           	|  4  	|  33105 	|       0 	|      20 	|       4 	|      24 	|
|        	| ost003d             	| 194 x 194 	|  1  	|  13214 	|       4 	|      32 	|       4 	|      32 	|
|        	|                     	|           	|  2  	|  49986 	|       0 	|      20 	|       0 	|      20 	|
|        	|                     	|           	|  4  	| 194168 	|       0 	|      12 	|       0 	|      12 	|
|        	| brc202d             	| 481 x 530 	|  1  	|  43151 	|       0 	|      16 	|       0 	|      16 	|
|        	|                     	|           	|  2  	| 162968 	|       0 	|       8 	|       0 	|       8 	|
|        	|                     	|           	|  4  	| 632432 	|       0 	|       4 	|       0 	|       4 	|
|        	| den520d             	| 257 x 256 	|  1  	|  28178 	|       0 	|      48 	|       4 	|      28 	|
|        	|                     	|           	|  2  	| 108918 	|       0 	|      24 	|       0 	|      24 	|
|        	|                     	|           	|  4  	| 427970 	|       0 	|      16 	|       0 	|      16 	|
|        	| w-woundedcoast      	| 578 x 642 	|  1  	|  34002 	|       4 	|      20 	|       4 	|      16 	|
|        	|                     	|           	|  2  	| 127838 	|       0 	|       8 	|       0 	|       8 	|
|        	|                     	|           	|  4  	| 495024 	|       0 	|       0 	|       0 	|       0 	|
