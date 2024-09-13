# Lecture 1, task 2
___
## Transition from Cartesian to Polar coordinate system

$ \rho = \sqrt{x^2 + y^2} $

$ \theta = atan2(y, x) $
> atan2() is an arctangent function 
> that takes into account the quadrants of the points 
> so as not to lose information about the signs.
> It returns the value in radians
> 
> To convert radians to degrees, you need to use the formula
> $ degrees = \frac{radians \cdot 180}{\pi} $

## Transition from Polar to Cartesian coordinate system

> To convert degrees to radians, you need to use the formula
> $ radians = \frac{degrees \cdot \pi}{180} $

$ x = \rho \cos{\theta} $

$ x = \rho \sin{\theta} $

___

## Transition from Cartesian to Spherical coordinate system

$ \rho = \sqrt{x^2 + y^2 + z^2} $

$ \theta = \arccos{\frac{z}{\rho}} $ (in radians)

$ \phi = atan2(y, x) $ (in radians)

## Transition from Spherical to Cartesian coordinate system

$ x = \rho \sin{\theta} \cos{\phi}$

$ y = \rho \sin{\theta} \sin{\phi}$

$ z = \rho \cos{\theta} $

___

## Transition from Cartesian to Cylindrical coordinate system

$ \rho = \sqrt{x^2 + y^2} $

$ \theta = atan2(y, x) $  (in radians)

$ z = z $

## Transition from Cylindrical to Cartesian coordinate system

$ x = \rho \cos{\theta} $

$ y = \rho \sin{\theta} $

$ z = z $


