# Starfall Postcard Tracer
*inspired by https://github.com/Vurv78/expression2-public-e2s/tree/master/Raytracers/PostcardRaytracers*

Starfall ray tracer with Lambertian diffuse and Blinn-Phong using only 613 characters.  
Multiple shortcuts and character saving techniques have been taken so don't expect any decent renders from it, but I tried to fit as much as possible into approximately 600 chars.  

The render resolution is hard coded at 256x256, while this can be made smaller, increasing it would cause the chip to quota, as it just yields from the render coroutine every column, rather than on a perf check.  

## Example Render (256 x 256) 
![Example Render](https://github.com/100PXSquared/public-starfalls/blob/master/postcard-tracer/render.png)
