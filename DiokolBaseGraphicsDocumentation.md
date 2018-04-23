# Diokol Data Visualization Library
___

## New function
Function used to create an instance of the DklBaseGraphics class. Most use the lua *require* utility to include the DiokolBaseGraphics library before creating an instance.
### Syntax
``` R
DklBaseGraphics:new(w,h)
```
### Arguments
- **w**: Width of the drawing area.
- **h**: Height of the drawing area.

___
## Par function
Used to set or query graphical parameters. 
### Syntax
``` R
par({...})
```
### Arguments
Arguments must be in **tag = value** form.
- **{...}**: The arguments to be passed to the methods.
___

## Plot function
Function used to plot in DklBaseGraphics.
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

## Axis function
Function to add an axis to the current plot.
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

## Title function
This function can be used to add labels to a plot.
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

## Box function
This function draws a box around the current plot.
### Syntax
``` R
box({...})
```
### Arguments
- **{...}**: The arguments to be passed to the methods.
    - **which:** String, one of "plot", "figure". Default is "plot"
    - **bty:** A string which determines the type of box to be drawn. Default is "o". "n" suppresses the box.
___

## Text function
Draws the strings given in a *lua table* at the coordinates given by *x* and *y*.
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

## Indentify function
Reads the position of the graphic's pointer when the mouse button is pressed. 
### Syntax
``` R
indentify(x,y,{...})
```
### Arguments
- **x,y:** Corrdinates in the plot.
- **{...}:** The arguments to be passed to the methods.
    - **tolerance:** Max distance for the pointer to be around a point and be detected.
    - **offset:** Distance between labels and points.
    - **labels:** Optional label names for the points.
___

## Resize function
### Syntax
``` R
resize()
```
___

## Resize Window function
Resizes the window.
### Syntax
``` R
resize()
```
___

## Plot Window function
___

## Resume function
___

## Extent function
___

## Plot New function
___ 

## Make Symbols function


