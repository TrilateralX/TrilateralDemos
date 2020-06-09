# TrilateralDemos  
  
## What is trilateral?  
   
Trilateral takes draw commands like quadTo and draws them using Haxe technologies, essentially it's just a tool to convert lines and curves into triangles for rendering with a shader, being Haxe language based it can obviously be used as c++ on mobile and on the web as WebGL.  
  
<img src="https://user-images.githubusercontent.com/20134338/84164310-4b038a80-aa6a-11ea-8cdd-c1c119b3c81b.png" width="500">
  
  
### JustTriangles  
  
justTriangles was the first iteration.  

<img src="https://cloud.githubusercontent.com/assets/20134338/22331662/91c39c82-e3c4-11e6-8bc6-ee5ad0197ad4.png" width="400">  
  
I first tested the concept of drawing with triangles using Haxe flash swf. Then implemented in haxe WebGL, cross platform OpenFL/NME and Kha, creating code to parse SVG string path data or drawing with lineTo, moveTo, quadTo, curveTo, quadThru.
  
Created specific commands for drawing basic shapes  
  
<img src="https://user-images.githubusercontent.com/20134338/84167307-f235f100-aa6d-11ea-9b6b-974f539aff84.png" width="200"> 

Simple 2D Kha demo. 
  
<img src="https://user-images.githubusercontent.com/20134338/84165830-0b3da280-aa6c-11ea-95b9-e147bfd9f1cf.png" width="300">  
  
[Demo > ](https://nanjizal.github.io/justTrianglesKhaG2/build/)  

### Trilateral

Restructuring, Trilateral was born. ( heaps toolkit render ).
  
<img src="https://user-images.githubusercontent.com/20134338/84169469-91f47e80-aa70-11ea-9d85-41615799d67a.png" width="200">
  
Using TrilateraXtra to for toolkit specific code and TrilateralBazzar for examples.

I improved the svg data path support adding Ellipses.

<img src="https://user-images.githubusercontent.com/20134338/84167836-9ddf4100-aa6e-11ea-9cc5-27cf7eaf2ade.png" width="300">
  
Adding images support so I could create my canvas jigsaw in WebGL or c++ Kha.  
  
<img src="https://user-images.githubusercontent.com/20134338/84168241-147c3e80-aa6f-11ea-9f6d-36c7cd6d7cb8.png" width="300">
  
Experimented with some FXG support  
  
<img src="https://user-images.githubusercontent.com/20134338/84168855-d29fc800-aa6f-11ea-9b0a-3e0865c21e9b.png" width="400">   
   
Supported an approach to gradients similar to the image approach of uv, where shape is plotted and then UV's applied.
  
<img src="https://user-images.githubusercontent.com/20134338/84169173-375b2280-aa70-11ea-9331-8dbafdba49fb.png" width="300">    
  
 
