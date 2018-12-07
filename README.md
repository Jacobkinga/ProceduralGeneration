This script when put into unity will generate a terrain using vertices, triangles and will allow you to place textures using UVS

When you load unity in order for this script to function you must create and empty object in the Scene and name it Mesh Generator

Then add a component
  New script
    Name it MeshGenerator
Then add another component
  New script
    Name it MeshRenderer
    
Add another component called TerrainMaterial
  Adjusting the Tiling on the X and Y axis (2D texture) will allow you to adjust how many times the texture repeats over the Terrain
    
Unless I missed something this should then allow you to hit play and see the Generator work it's magic.

Inside the Mesh Generator script in the inspector tab you can adjust the X Size and Y size to whatever you like.
