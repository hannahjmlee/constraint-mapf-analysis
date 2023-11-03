# An Analysis of Constraint-Based Multi-Agent Pathfinding Algorithms - Data and Results
This repository holds all of the data and plots presented in the "An Analysis of Constraint-Based Multi_Agent Pathfinding Algorithms" paper. Raw and compiled data can be found in the Data repository. Grouped and Individual map plots are shown in the Figures directory. All figures are also present within this README. 

If you would like to run the data scraper and plot generator, please use the ExportData jupyter notebook to compile the raw data into csvs. Then, run the Plot jupyter notebook to generate all grouped and individual plots. 

If you have any questions, please contact me at [hannah9@illinois.edu](hannah9@illinois.edu). 

## Graph Statistics and Map Groupings

## Grouped Map Plots
| Group | Average Runtime | Success Rate | Flowtime Ratios | 
|--|--|--|--|
|  Empty | ![plot-Empty](./Figures/GroupedFigures/AverageTime_Empty.png) | ![plot-Empty](./Figures/GroupedFigures/SuccessRate_Empty.png) | ![plot-Empty](./Figures/GroupedFigures/CostRatios_Empty.png) | 
|  Random | ![plot-Random](./Figures/GroupedFigures/AverageTime_Random.png) | ![plot-Random](./Figures/GroupedFigures/SuccessRate_Random.png) | ![plot-Random](./Figures/GroupedFigures/CostRatios_Random.png) | 
|  Rooms | ![plot-Rooms](./Figures/GroupedFigures/AverageTime_Rooms.png) | ![plot-Rooms](./Figures/GroupedFigures/SuccessRate_Rooms.png) | ![plot-Rooms](./Figures/GroupedFigures/CostRatios_Rooms.png) | 
|  Maze | ![plot-Maze](./Figures/GroupedFigures/AverageTime_Maze.png) | ![plot-Maze](./Figures/GroupedFigures/SuccessRate_Maze.png) | ![plot-Maze](./Figures/GroupedFigures/CostRatios_Maze.png) | 
|  Cities | ![plot-Cities](./Figures/GroupedFigures/AverageTime_Cities.png) | ![plot-Cities](./Figures/GroupedFigures/SuccessRate_Cities.png) | ![plot-Cities](./Figures/GroupedFigures/CostRatios_Cities.png) | 
|  Games-Small | ![plot-Games-Small](./Figures/GroupedFigures/AverageTime_Games-Small.png) | ![plot-Games-Small](./Figures/GroupedFigures/SuccessRate_Games-Small.png) | ![plot-Games-Small](./Figures/GroupedFigures/CostRatios_Games-Small.png) | 
|  Games-Large | ![plot-Games-Large](./Figures/GroupedFigures/AverageTime_Games-Large.png) | ![plot-Games-Large](./Figures/GroupedFigures/SuccessRate_Games-Large.png) | ![plot-Games-Large](./Figures/GroupedFigures/CostRatios_Games-Large.png) |

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


