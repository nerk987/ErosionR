# ErosionR
Blender Addon for simulated erosion

For anyone wanting to try the ErosionR version, I suggest the following steps..

- Clone ErosionR.zip and save to your computer
- Install and enable the add-on in the usual way
-       (File/User Preferences
         Addons Tab
         Install from File
         Select ErosionR.zip)
- Ensure ANT Landscapes are also enabled
- Add a new ANT Landscape
- Change to weight paint mode
- Select 'ErodeR' from the 'weight' menu
- Have a look at the vertex groups that have been added
- Select a water related group like 'water' or 'capacity'
- Increase the 'River Iterations' in the 'Eroder' panel in the tools panel and watch the vertex group
- To make the rivers flow to the edge might take 100-200 iterations (more for large meshes) but it's a speed tradeoff
- Fiddle with the 'River Erosion' settings until you get the water patterns you like
- If you set the main iterations to a number that's greater than 1, it's the same as pressing refresh many times, so it's most useful when you have the settings you want, and you want to erode a large mesh gradually for best quality.
