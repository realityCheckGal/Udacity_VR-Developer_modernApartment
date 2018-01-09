## Udacity VR Developer Modern Apartment Nano-degree Project #2
Modern apartment is designed to demonstrate a basic understanding of working with objects, materials, camera, lighting and simple use of user input to control an animation by creating a simple scene using prefabs.


## Versions
- Unity 2017.1.0p4
- GVR Unity SDK v1.70.0
- Android 7.0

## Lighting Test Notes
as texels per unit increase the sharpness and contrast improve, but so does the baking time
at 2 texels / unit no shadows are visible and the light is very dim
at 80 texels / unit shadows are crisp and the light is bright -  for such a simple scene the baking time is still only a minute or two
by compressing the lighting map, artifacts appear in large flat areas with sublte gradients such as the walls and ceilings

This project is part of [Udacity](https://www.udacity.com "Udacity - Be in demand")'s [VR Developer Nanodegree](https://www.udacity.com/course/vr-developer-nanodegree--nd017).