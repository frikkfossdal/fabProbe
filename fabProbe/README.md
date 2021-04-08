# Fab Touchprobe 

Documenting sparsely. Main goal of this project is to make a fabricatable touch probe that I can use to probe stuff on my [Scribler platfrom)(https://github.com/frikkfossdal/scribler). The philosophy driving the design lies in it's circuitry. I have a circular pattern of steel balls serving as contact points for 3 dowels. The circuit breaks if one of the dowels looses contact with the steel-ball-circuit. Rough sketch below. 

![](img/sketch.jpeg)

For the kinematic coupling, I will make an attempt to follow the design pattern that I use in my toolchanger on the scribler. This means ball screws, m5 dowels and magnets to hold things together. For the probe itself I'm using a 4mm precision shaft mounted on a [Polulu mounting hub](https://www.pololu.com/product/1997).


Here is a gif of the kinematic coupling priciple. The top-side is held in place by the magnets. If the probe touches something, the kinematic coupling will loose contact with one of the ball-couplings and break the circuit. 

![](img/principle.gif)