 # Good Graph

This is a smart Graph Rig for After Effects.

![BSP_Whatevs_1](https://github.com/simonipiponi/ae-graph/assets/20266941/6da7703f-7dd5-46bb-87b5-039034b3bd94)
![BSP_Yes 3](https://github.com/simonipiponi/ae-graph/assets/20266941/3a0216fe-08e4-4cbd-b567-2b2da727cb7e)
![BSP_Multiple Grids_1](https://github.com/simonipiponi/ae-graph/assets/20266941/4dacb118-98fb-4f7c-a83b-e9daf950e890)

# How it works

### Setup
Bars and Text Layers are parented to the `GRID`-Layer, which controls the Graph.
For every new entry, duplicate the last `BAR` and `TXT`-Layers. Then change the displayed value in the `BAR`-Layer.
![GOODGRAPH_Comp 1_2023-06-28_14 15 42](https://github.com/simonipiponi/ae-goodgraph/assets/20266941/c88e74c8-fa0e-481e-a807-a119d6d39c4b)

### Styling

The Bars, Points, Line and Grid can be styled directly from the `GRID`-Layer.
Text Formatting and Styling is done on the text layers themselves.

![EXAMPLE 5_1](https://github.com/simonipiponi/ae-goodgraph/assets/20266941/ecccbb4a-ea8b-40b4-ac7b-334fc9c64a87)

### Logic  
Change the Segments and their Value to modify the graph to your needs. The Bar Charts will always stick to the correct value.

![EXAMPLE 4_1](https://github.com/simonipiponi/ae-goodgraph/assets/20266941/0465f7e4-7cc5-49b8-897d-98b42b28b5b2)



The Grid is a coordinate system, starting from the bottom left at `[1,1]`. The `_x1` or `_y1` in the Layer name determines the position of the Layer.
Changing the `_x1` to `_y1` in a Layer's name will reposition the Layer to the other axis.
The Text Layers can be called anything, as long as `_x1` is at the end of the layer. Change `BAR_x1` and `GRID` to `BAR2_x1` and `GRID2` if you want to have multiple grids in one Comp.

![GOODGRAPH_Comp 2_2023-06-28_14 15 23](https://github.com/simonipiponi/ae-goodgraph/assets/20266941/a5d0889c-5524-4efe-a3b4-b3067eecfd6f)



### Download


Download file in the repo Files.
