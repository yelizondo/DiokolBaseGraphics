# Diokol Data Visualization Library
___
## Par function
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
        - "c": for the lines part alone of "b". ???
        - "o": for both"**o**verplotted" ???
        - "h": for a **h**istogram.
        - "s": for a **s**tepline plot.
        - "n": for **n**o plotting.
___
## Axis
### Description
### Syntax
``` R
axis(side,{...})
```
### Arguments
- **side**: Indicates wich side of the plot is the axis going to be drawn. It's an integer. 1 = RIGHT, 2 = LEFT, 3 = TOP and  4 = RIGHT.
- **{...}**:
    - **at:** The points at which the tick-marks are going to be drawn.
    - **labels:** Labels to be placed in the tick points.
___
## Box

___




