# Beat-Saber-custom-trails

This github contails the .blend (Blender program found at https://Blender.org/download/ for Windows, Mac, Linux, and steam) file used to make these trails for Beat Saber custom sabers.

How to use the .blend file:

When first opening the .blend file, you'll be greeted to the shading workspace, you're going to go see the 3D viewport on the top and the bottom you're going to see the shader editor.

If you see nodes that are hidden or closed, they are closed because it does'nt need to be edited or changed. You can use the RGB Curves to change/manipulate the shape of the trail. The Scale node is to change the scale of the trail. Know if you raise the scale using the node you're going to change the trail a bit more to not make it overlap the plane itself. The Displacement is used to animate the trail if it has a noise texture. (explained later on) The Texture coordenate thats connected to the Mapping node does'nt need to be changed unless you want a different end result. The Mapping node is to change the the X, Y, Z coordenates for scale, rotation, and location if youre going to have a noise/ displacement texture. there's a gap between the Mapping node and the Math node(the node that is named Multiply Add) because thats where you would put in a noise/ displacement texture. You can use the blenders default texture nodes and mix it with others to have a different result, you can mix to texture nodes by adding the node and dragging it to the line connecting the Mapping node to the Math node. If youre adding two default texture nodes the one on the Left is the affected and the one on the Right is the affecting. You can use images as the texture, if it has color you select non-color for the color space. I havent seen what happens if you put non-color to a image that has no color but I think it'll one lower the image strength. The math node more known as the multiply add node is to change the brightness strength of the texture. the multiply is to change the strenght of the texture, the add is to change the brightness of all the trail. The Mix shader is to combine the trail shape and the texture IN the trail, if you mess with that node it could possibly mess the whole trail. And the texture output is to put the nodes as an image and put it to the plane in the 3d workspace. And thats all you need to know that I know. If you have any questions/conserns you can add me in discord Swift#7578 and dm me, I dont take long too respond so dont be afraid to ask questions.