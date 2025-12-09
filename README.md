# CG Final Exam


!!!!!!!!!!!!!NOTE!!!!!!!!!!!! : Build issue I went to build it and noticed most of the shaders are purple in the game build exe, I worked super hard on the scene only to realise this right at the end, please review the actual project version as that is how the game is supposed to actually look. If I had known these wouldn't work in a build ahead of time I would have been able to fix it but this surprised me, I put a lot of effort into building up the scene to look really good to please make sure to look at the actual unity project or the video I submitted in the git showing how the game looks. 


The first step was setting up the scene and space, for this final I wanted to try something out there and enhance packman by putting him a world or location and trying to create a cool environment around that, I went with a futuristic city sorta vibe since I was tasked with using scrolling and hologram textures and thought these would really well with that atheistic.



Scrolling Texture

* Figured out I wanted to create a scrolling city background
* Created the 2D sprite assets and separated them from clouds and buildings in order to create depth. 
* I than used and a plan and applied the scrolling water shader and implemented by 2 drawn assets, adjusting the X and Y displacement so it scrolls the city in a certain direction. 
* Using this texture/fragment shader I am able to get the desired effect I was looking for, the idea behind this was that the main game is taking place on another building or perhaps some sort of hovercraft and the buildings are passing by in the distance which I think sorta enhances packman's display a lot from being rather simple to sorta making a more interesting environment with our current knowledge on shaders. 

Hologram Shader

* My plan was I wanted to bring 3D more into the mix of packman and so I created these energy pillars protruding out of the scene, I think it has a pretty cool effect and draws the eye to the play area, specially when there is more moving in the background it really helps keep you focused. By adjusting the opacity of this shader I am able to still see packman behind the pillars which is important for gameplay.
* This shader was repeated in a couple other areas, most out there being the peaches to create a blinking effect for them and make them stand out a bit more as power ups.

Rim light

* By calculating the view direction of the camera and projecting the light on the darker points of the model I was able to use rim lighting to enhance the walls in my scene, I sorta liked this cartoony but also neon colour scheme to further add to this more futuristic atheistic I was going for. By adjusting the strength of the rim lighting it is better use for high lighting the 3D aspects of the walls. 

Vertex Displacement

* I wanted to make packman's main powerups and items stand out a lot more but also keep there simplicity of fruits, in order to do that I wanted to give them animations and So i choose to use vertex displacement. By using one of the water shaders and adjusting some of its values to be more subtle and applying to a 3D sphere I was able to get this cartoony subtle bouncing effect which I think really makes them pop out more and feel more fun. 

Post Processing

* Colour Correction was added using a LUT and unity's built in post processing system, I wanted to sorta stylize the whole project at the end and bring it all together.
* Lighting enhancements 



Textures and Models

* All textures and models where made with photoshop and blender ad I wanted to ensure those classic shapes of packman stood out and he wasn't just a simple cube. 
