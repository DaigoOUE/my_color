Here, we develop colorschemes for Mathematica:)


## How to use
In order to apply a color scheme,
you need to import a library file, where the scheme is defined.  
On your `.nb` file,
execute

```wl
Import["colorschemes.wl"];
```

and you are ready to go

```wl
DensityPlot[Sin[x*y],{x,-2,2},{y,-2,2},ColorFunction->RubySapphire]
```


## The color schemes
### RubySapphire
- This is useful, for example, when you visualise temperature.
- The default `TemperatureMap` contains yellow spoiling the visibility near zero.
- This is my first colorscheme which resolves this problem, 
  clarifying your negative, zero and positive points. 
![RubySapphire](https://raw.githubusercontent.com/DaigoOUE/my_color/images/rubysapphire.jpg)
