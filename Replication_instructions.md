Replication Instructions
============

```{r}
library("MissingDataGUI")
```

Figure 1
------------

```{r}
MissingDataGUI(tao)
```

- select the 4th-6th rows in region 1.
- check "year" in region 2.
- click "Missing Any Variables" in region 3.
- click "Simple" in region 4.
- click "Pairwise Plots" in region 5.
- click "Plot" in region 6.


Figure 2
------------

```{r}
MissingDataGUI(tao)
```

- select all the variables in region 1 of the GUI created in Figure 1.
- (left) click "Numeric summary" in region 6 of Figure 1.
- (right) check "year" in region 2, then click "Numeric summary" in region 6.


Figure 3
------------

```{r}
MissingDataGUI(brfss)
```

- (Not necessary: select all the variables in region 1.)
- choose "Missingness Map" in region 5.
- click "Plot" in region 6 (will give all the three graphs).


Figure 4
------------

```{r}
MissingDataGUI(tao)
```

- select the 5th and 6th rows (air.temp and humidity) in region 1 of Figure 1.
- uncheck all the checkboxes in region 2.
- click "Missing on Selected Variables" in region 3.
- click "Pairwise Plots" in region 5.
- To create the four graphs in Figure 3, only need to change the selection of region 4 as follows:
 - (a) Below 10%
 - (bcd) Simple
- click "Plot" in region 6.


Figure 5
------------

```{r}
MissingDataGUI(tao)
```

- select the 5th and 6th rows (air.temp and humidity) in region 1.
- uncheck all the checkboxes in region 2.
- click "Missing on Selected Variables" in region 3.
- click "Neighbor" in region 4.
- click "Pairwise Plots" in region 5.
- click "Plot" in region 6 (will give both plots).


Figure 7
------------

```{r}
MissingDataGUI(tao)
```

- select the 5th and 6th rows (air.temp and humidity) in region 1.
- check "year" in region 2.
- click "Missing on Selected Variables" in region 3.
- click "Pairwise Plots" in region 5.
- To create the four graphs, need to change the selection of region 4 as follows:
 - (a) MI: areg
 - (b) MI: norm
 - (c) MI: mice
 - (d) MI: mi
- click "Plot" in region 6. The four graphs are all from the first chain.


Figure 8
------------

```{r}
MissingDataGUI(tao)
```

- go to the "Settings" tab, edit "Number of imputed sets" in the frame "Multiple imputation" to 4.
- back to the "Summary" tab, select the 5th and 6th rows (air.temp and humidity) in region 1.
- check "year" in region 2.
- click "Missing on Selected Variables" in region 3.
- click "MI: mice" in region 4.
- click "Pairwise Plots" in region 5.
- click "Plot" in region 6 (will give all the four graphs).


Figure 9
------------

```{r}
MissingDataGUI(tao)
```

- select the 4th-6th rows (sea.surface.temp, air.temp and humidity) in region 1 of Figure 1.
- click "Missing on Selected Variables" in region 3.
- click "Simple" in region 4.
- click "Pairwise Plots" in region 5.
- (left panel) uncheck all the checkboxes in region 2.
- (right panel) check "year" in region 2.
- click "Plot" in region 6.


Figure 10
------------

```{r}
MissingDataGUI(tao)
```

The first row from left to right:

(1)
- select the 2nd variable (latitude) in region 1 of Figure 1.
- uncheck all the checkboxes in region 2.
- choose "humidity" in region 3.
- choose "Below 10%" in region 4.
- choose "Histogram/Barchart" in region 5.
- click "Plot" in region 6.

(2)
- select the 4th variable (sea.surface.temp) in region 1 of Figure 1.
- uncheck all the checkboxes in region 2.
- choose "humidity" in region 3.
- choose "Below 10%" in region 4.
- choose "Histogram/Barchart" in region 5.
- click "Plot" in region 6.

(3)
- select the 2nd variable (latitude) in region 1 of Figure 1.
- uncheck all the checkboxes in region 2.
- choose "humidity" in region 3.
- choose "Below 10%" in region 4.
- choose "Spinogram/Spineplot" in region 5.
- click "Plot" in region 6.

(4)
- select the 7th variable (uwind) in region 1 of Figure 1.
- uncheck all the checkboxes in region 2.
- choose "humidity" in region 3.
- choose "Below 10%" in region 4.
- choose "Spinogram/Spineplot" in region 5.
- click "Plot" in region 6.

The second row

(left graph)
- select the 1st, 2nd, 4th-6th rows in region 1 of Figure 1.
- uncheck all the checkboxes in region 2.
- choose "humidity" in region 3.
- choose "Below 10%" in region 4.
- choose "Pairwise Plots" in region 5.
- click "Plot" in region 6.

(right graphs)
- select all the 8 variables in region 1 of Figure 1.
- uncheck all the checkboxes in region 2.
- choose "humidity" in region 3.
- choose "Below 10%" in region 4.
- choose "Parallel Coordinates" in region 5.
- click "Plot" in region 6.


Figure 11
------------

```{r}
MissingDataGUI(tao)
```

- (left) in the GUI of Figure 1, click "Help" on the top left, and then click "Histogram/Barchart" in "Graph Type" to see the help document.
- (right) click "Settings" on the top left of the GUI, double-click the 4th row (sea.surface.temp) in the "MI:mice" table, then click the combo box and select "norm".


Figure 12
------------

```{r}
MissingDataGUI()
```

- click "Open" to choose a csv file.


Figure 13
------------

```{r}
MissingDataGUI(tao)
```

- click "Export data" in region 6 of Figure 1.


Figure 14
------------

```{r}
MissingDataGUI(tao)
```

- In the GUI of Figure 1, double-click the 2nd row ("latitude") in region 1.


Figure 15
------------

```{r}
MissingDataGUI(tao)
```

- select the 4th-6th rows in region 1 of Figure 1.
- uncheck all the checkboxes in region 2.
- click "Missing on Selected Variables" in region 3.
- click "Pairwise Plots" in region 5.
- (left) click "Below 10%" in region 4.
- (right) click "Simple" in region 4.
- click "Plot" in region 6.


Figure 16
------------

```{r}
MissingDataGUI(tao)
```

- select the 4th-6th rows in region 1.
- check "year" in region 2.
- click "Missing on Selected Variables" in region 3.
- click "Pairwise Plots" in region 5.
- (left panel) click "Simple" in region 4.
- (right panel) click "MI: areg" in region 4.
- click "Plot" in region 6.


Figure 17
------------

```{r}
MissingDataGUI(tao)
```

- (left) select all the variables but "air.temp" in region 1, and click "air.temp" in region 3.
- (right) select all the variables but "humidity" in region 1, and click "humidity" in region 3.
- uncheck all the checkboxes in region 2.
- choose "Below 10%" in region 4.
- choose "Parallel Coordinates" in region 5.
- click "Plot" in region 6.


Figure 18
------------

```{r}
MissingDataGUI(tao)
```

- select the 1th, 7th, and 8th rows (year, uwind, vwind) in region 1.
- uncheck all the checkboxes in region 2.
- (left) click "air.temp" in region 3.
- (right) click "humidity" in region 3.
- choose "Neighbor" in region 4.
- choose "Pairwise Plots" in region 5.
- click "Plot" in region 6.
- The plots are at the (2,3) and (3,2) position of the plot matrix. The contour plots are transposed.
