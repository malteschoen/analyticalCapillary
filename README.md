## Cylindrical capillary

#### Shear rate

For the apparent shear rate in a cylindrical capillary we have:

$\dot{\gamma}=\frac{4\dot{V}}{\pi r^{3}}$

Now if we set the radius to 1.085 mm (1.085 mm = 43 thou = 43 milli-inches) we achieve:

$\dot{\gamma}=10^{9}\frac{\dot{V}}{ m^{3}}$

Now it follows that if $\dot{V}$ is input in m³/s, determination of shear rate only requires moving the decimal point.

Even more practical is the assumption that the fluid density is 1250 kg/m³ - in that case, the conversion from lbs/hr to m³/s again is just movement of the decimal dot because at this density 1 lb/hour corresponds to 1e-7 m³/s.

From this we can then get (by multiplying 1e9 and 1e-7) that you can make the reasonable guess that the shear rate (in 1/s) is 100 times the throughput in pounds/hour, assuming a 1.085 mm capillary and fluid density of 1250 kg/m³.

#### Pressure drop

For the pressure drop in a cylindrical capillary we have:

$\Delta p = 8 \frac{\dot{V}}{\pi r^{4}} \eta L = 2 \dot{\gamma} \frac {1}{r} \eta L$

Now if we set the radius to 1.085 mm and the length to 54 mm (54 mm = 2 inches) for an L/D of 25 we achieve:

$\Delta p =  \dot{V} \eta  L=  \dot{\gamma} \eta L$
