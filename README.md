# An Analysis of Constraint-Based Multi-Agent Pathfinding Algorithms - Data and Results
This repository holds all of the data and plots presented in the "An Analysis of Constraint-Based Multi_Agent Pathfinding Algorithms" paper. Raw and compiled data can be found in the Data repository. Grouped and Individual map plots are shown in the Figures directory. All figures are also present within this README.

If you would like to run the data scraper and plot generator, please unzip the stat_files.zip and then use the ExportData jupyter notebook to compile the raw data into csvs. Then, run the Plot jupyter notebook to generate all grouped and individual plots.

If you have any questions, please contact me at [hannah9@illinois.edu](hannah9@illinois.edu).

<br>
<br>

## Grouped Map Plots
| Group | Average Runtime | Success Rate | Flowtime Ratios |
|--|--|--|--|
|  Empty | ![plot-Empty](./Figures/GroupedFigures/AverageTime_Empty.png) | ![plot-Empty](./Figures/GroupedFigures/SuccessRate_Empty.png) | ![plot-Empty](./Figures/GroupedFigures/CostRatios_Empty.png) |
|  Random | ![plot-Random](./Figures/GroupedFigures/AverageTime_Random.png) | ![plot-Random](./Figures/GroupedFigures/SuccessRate_Random.png) | ![plot-Random](./Figures/GroupedFigures/CostRatios_Random.png) |
|  Narrow | ![plot-Narrow](./Figures/GroupedFigures/AverageTime_Narrow.png) | ![plot-Narrow](./Figures/GroupedFigures/SuccessRate_Narrow.png) | ![plot-Narrow](./Figures/GroupedFigures/CostRatios_Narrow.png) |
|  Cities | ![plot-Cities](./Figures/GroupedFigures/AverageTime_Cities.png) | ![plot-Cities](./Figures/GroupedFigures/SuccessRate_Cities.png) | ![plot-Cities](./Figures/GroupedFigures/CostRatios_Cities.png) |
|  Games | ![plot-Games](./Figures/GroupedFigures/AverageTime_Games.png) | ![plot-Games](./Figures/GroupedFigures/SuccessRate_Games.png) | ![plot-Games](./Figures/GroupedFigures/CostRatios_Games.png) |

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
| Type          | Map                 | Size      | Res | States | CBS Min | CBS Max | PBS Min | PBS Max |
|---------------|---------------------|-----------|-----|--------|---------|---------|---------|---------|
| Empty         | empty-8-8           | 8 x 8     | 1   | 64     | 14      | 24      | 14      | 30      |
|               |                     |           | 2   | 225    | 16      | 30      | 22      | 30      |
|               |                     |           | 4   | 841    | 8       | 30      | 20      | 30      |
|               | empty-16-16         | 16 x 16   | 1   | 256    | 14      | 38      | 20      | 44      |
|               |                     |           | 2   | 961    | 14      | 40      | 24      | 56      |
|               |                     |           | 4   | 3721   | 2       | 38      | 20      | 50      |
|               | empty-32-32         | 32 x 32   | 1   | 1024   | 10      | 60      | 32      | 60      |
|               |                     |           | 2   | 3969   | 10      | 60      | 32      | 60      |
|               |                     |           | 4   | 15625  | 10      | 42      | 26      | 56      |
|               | empty-48-48         | 48 x 48   | 1   | 2304   | 22      | 60      | 32      | 60      |
|               |                     |           | 2   | 9025   | 16      | 54      | 22      | 60      |
|               |                     |           | 4   | 35721  | 8       | 48      | 10      | 60      |
| Random        | random-32-32-10     | 32 x 32   | 1   | 922    | 8       | 48      | 28      | 58      |
|               |                     |           | 2   | 3185   | 6       | 46      | 26      | 58      |
|               |                     |           | 4   | 11575  | 6       | 44      | 16      | 46      |
|               | random-32-32-20     | 32 x 32   | 1   | 819    | 14      | 40      | 22      | 44      |
|               |                     |           | 2   | 2468   | 8       | 40      | 22      | 40      |
|               |                     |           | 4   | 8040   | 8       | 36      | 18      | 40      |
|               | random-64-64-10     | 64 x 64   | 1   | 3687   | 4       | 60      | 36      | 60      |
|               |                     |           | 2   | 12830  | 4       | 60      | 12      | 60      |
|               |                     |           | 4   | 46764  | 4       | 44      | 4       | 52      |
|               | random-64-64-20     | 64 x 64   | 1   | 3270   | 16      | 54      | 26      | 58      |
|               |                     |           | 2   | 10031  | 8       | 46      | 22      | 48      |
|               |                     |           | 4   | 33225  | 8       | 36      | 14      | 46      |
| Narrow        | room-32-32-4        | 32 x 32   | 1   | 682    | 10      | 24      | 4       | 28      |
|               |                     |           | 2   | 1902   | 4       | 22      | 4       | 26      |
|               |                     |           | 4   | 5878   | 4       | 20      | 4       | 26      |
|               | room-64-64-8        | 64 x 64   | 1   | 3232   | 6       | 20      | 10      | 26      |
|               |                     |           | 2   | 11090  | 4       | 18      | 6       | 20      |
|               |                     |           | 4   | 40630  | 2       | 16      | 4       | 18      |
|               | room-64-64-16       | 64 x 64   | 1   | 3646   | 6       | 30      | 10      | 28      |
|               |                     |           | 2   | 13585  | 6       | 20      | 10      | 22      |
|               |                     |           | 4   | 52297  | 2       | 18      | 2       | 18      |
|               | maze-32-32-2        | 32 x 32   | 1   | 666    | 6       | 18      | 6       | 20      |
|               |                     |           | 2   | 1951   | 6       | 16      | 6       | 16      |
|               |                     |           | 4   | 6381   | 2       | 12      | 2       | 16      |
|               | maze-32-32-4        | 32 x 32   | 1   | 790    | 2       | 16      | 4       | 20      |
|               |                     |           | 2   | 2695   | 2       | 16      | 4       | 18      |
|               |                     |           | 4   | 9853   | 2       | 16      | 2       | 18      |
|               | maze-128-128-2      | 128 x 128 | 1   | 10858  | 2       | 12      | 2       | 10      |
|               |                     |           | 2   | 32383  | 2       | 4       | 2       | 4       |
|               |                     |           | 4   | 107437 | 2       | 4       | 2       | 4       |
|               | maze-128-128-10     | 128 x 128 | 1   | 14818  | 2       | 20      | 4       | 20      |
|               |                     |           | 2   | 56143  | 2       | 10      | 2       | 10      |
|               |                     |           | 4   | 218317 | 2       | 4       | 2       | 4       |
| Cities        | Berlin-1-256        | 256 x 256 | 1   | 47536  | 8       | 60      | 8       | 60      |
|               |                     |           | 2   | 182171 | 8       | 28      | 8       | 28      |
|               |                     |           | 4   | 712615 | 2       | 14      | 2       | 14      |
|               | Boston-0-256        | 256 x 256 | 1   | 47747  | 8       | 52      | 8       | 52      |
|               |                     |           | 2   | 181232 | 2       | 26      | 2       | 26      |
|               |                     |           | 4   | 705218 | 2       | 10      | 2       | 10      |
|               | Paris-1-256         | 256 x 256 | 1   | 47216  | 2       | 46      | 12      | 54      |
|               |                     |           | 2   | 179271 | 2       | 34      | 4       | 34      |
|               |                     |           | 4   | 697685 | 2       | 16      | 2       | 16      |
| Games         | ht-chantry          | 141 x 162 | 1   | 7461   | 6       | 26      | 10      | 30      |
|               |                     |           | 2   | 27912  | 4       | 22      | 4       | 22      |
|               |                     |           | 4   | 107742 | 2       | 16      | 2       | 16      |
|               | ht-mansion-n        | 270 x 133 | 1   | 8959   | 6       | 40      | 18      | 50      |
|               |                     |           | 2   | 33376  | 4       | 34      | 8       | 34      |
|               |                     |           | 4   | 128554 | 2       | 28      | 2       | 28      |
|               | lak303d             | 194 x 194 | 1   | 14784  | 2       | 22      | 2       | 18      |
|               |                     |           | 2   | 54938  | 2       | 16      | 2       | 16      |
|               |                     |           | 4   | 211230 | 2       | 8       | 2       | 8       |
|               | lt-gallowstemplar-n | 180 x 251 | 1   | 10021  | 4       | 32      | 6       | 38      |
|               |                     |           | 2   | 37637  | 4       | 28      | 4       | 28      |
|               |                     |           | 4   | 145549 | 4       | 20      | 4       | 20      |
|               | den312d             | 81 x 65   | 1   | 2445   | 6       | 28      | 20      | 36      |
|               |                     |           | 2   | 8779   | 6       | 28      | 12      | 30      |
|               |                     |           | 4   | 33105  | 2       | 18      | 2       | 24      |
|               | ost003d             | 194 x 194 | 1   | 13214  | 4       | 22      | 4       | 20      |
|               |                     |           | 2   | 49986  | 2       | 18      | 2       | 16      |
|               |                     |           | 4   | 194168 | 2       | 10      | 2       | 12      |
|               | brc202d             | 481 x 530 | 1   | 43151  | 2       | 12      | 2       | 12      |
|               |                     |           | 2   | 162968 | 2       | 10      | 2       | 8       |
|               |                     |           | 4   | 632432 | 2       | 4       | 2       | 4       |
|               | den520d             | 257 x 256 | 1   | 28178  | 8       | 42      | 8       | 40      |
|               |                     |           | 2   | 108918 | 2       | 26      | 2       | 26      |
|               |                     |           | 4   | 427970 | 2       | 14      | 2       | 14      |
|               | w-woundedcoast      | 578 x 642 | 1   | 34002  | 2       | 14      | 2       | 14      |
|               |                     |           | 2   | 127838 | 2       | 10      | 2       | 10      |
|               |                     |           | 4   | 495024 | 0       | 0       | 0       | 0       |
