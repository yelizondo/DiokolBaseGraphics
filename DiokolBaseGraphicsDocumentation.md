# Diokol Data Visualization Library
___
## Par function
### Description
### Syntax
``` R
par({...})
```
### Arguments
Me parece que la mayoria de cosas estan hardcodeadas, preguntar al profe
___
## Plot function
### Description
### Syntax
``` R
plot(x,y,{...})
```
### Arguments
- **x**: The _x_ coordinates of points in the plot.
- **y**: The _y_ coordinates of points in the plot.
- **{...}**: The arguments to be passed to the methods.
    - **main**: An overall title for the plot.
    - **sub**: Subtitle for the plot.
    - **xlab**: Subtitle for the _x_ axis.
    - **ylab**: Subtitle for the _y_ axis.
    - **asp**: The _x/y_ aspect ratio.
    - **type**: Type of plot to draw.
        - "p": for a **p**oint plot.
        - "l": for a **l**ine plot.
        - "b": for a **b**oth, point and line plot.
        - "o": for both"**o**verplotted" 
___
## Axis
### Description
### Syntax
``` R
axis(side,{...})
```
### Arguments
- **side**: Indicates wich side of the plot is the axis going to be drawn. It's an integer. 1 = RIGHT, 2 = LEFT, 3 = TOP and  4 = RIGHT.
- **{...}**: The arguments to be passed to the methods.
    - **at:** The points at which the tick-marks are going to be drawn.
    - **labels:** Labels to be placed in the tick points.
___
## Title
### Description
### Syntax
``` R
title({...})
```
### Arguments
- **{...}**: The arguments to be passed to the methods.
    - **main:** The main title (top) 
    - **sub:** Sub-title (bottom)
    - **xlab:** Label for the X axis
    - **ylab:** Label for the Y axis
___
## Box

___
## Text
### Description
### Syntax
``` R
text(x,y,labels,{...})
```
### Arguments
- **x,y:** Coordinates where the text labels should be written.
- **labels:** Text to be written    
- **{...}:** The arguments to be passed to the methods.
    - **col:** The color to be used.
    - **cex:** **ESTA VALIDADO COMO PARAMETRO, MAS NO TIENE NINGUNA FUNCION**
    - **pos:** Indicates position for the text. It's an integer. 1 = BOTTOM, 2 = LEFT, 3 = TOP and  4 = RIGHT. The default value is 1.
    - **offset:** Indicates the offset of the label from the specified *pos* coordinate or it's default value. The default value is 1.
___
## Indetify

___




