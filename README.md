# Notebooks
Miscellaneous collection of analysis, simulation and investigation notebooks. List and details following, in no particular order.


## Common Ancestor Analysis/Simulation
**notebook**: ancestry.ipynb

- Population setup - have been keeping this static, but can be variable;
- Creation of networkx digraph for all generations that randomly assigns parents to child nodes in the family tree (present to past);
- Determination of Most Common Recent Ancestor (MCRA), implied common ancestors, no descendent nodes and indentical ancestors generation;
- Graph plot of ancestor generation map containing above information, split out by generations.

![Ancestry Generational Map Plot][ancestry_plot]


## Arboretum Game Model/Analysis
**notebook**: arboretum.ipynb

- Model setup for card game Arboretum: https://boardgamegeek.com/boardgame/140934/arboretum;
- **Very much work in progress** - still has a lot of early working;
- Randomly generate card layouts and identify associated allowed paths;
- Plot card layout using networkx with above information incorporated.


[ancestry_plot]: https://github.com/rokkuran/notebooks/blob/master/output/ancestry_generational_map_plot.png


