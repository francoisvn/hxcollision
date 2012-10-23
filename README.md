#hxcollision : SAT for haxenme*


##Test / demo

- http://dev.underscorediscovery.com/hxcollision

## Facts

- This is a port of Separating Axis Theorem, for collision detection between shapes.
- Supports polygons and circles, currently.
- A work in progress, see tests for an nme project testing the code.
- A haxelib will be added to the global repo when a test is done
- The name is tentative, maybe hxSAT or hxcollision.SAT only, so other implementations may be added?
- COLLISION ONLY. No physics here. By design :)
- Contributions welcome

## Notes

- [Original code posted on rocketmandevelopment blog](http://rocketmandevelopment.com/2010/05/19/separation-of-axis-theorem-for-collision-detection/)
- [Usage from the original author](http://rocketmandevelopment.com/2010/11/22/using-sat/)
- [More usage from the original author](http://rocketmandevelopment.com/2010/11/28/detecting-collisions-with-sat/)
- [TODO : Add the raycast from author](http://rocketmandevelopment.com/2011/02/15/using-ray-casting-with-shapes/)


## Getting Started

For now, git clone the repo or use 

`haxelib git hxcollision https://github.com/FuzzYspo0N/hxcollision.git hxcollision`

If you have trouble getting it working, check that the .dev file inside :

`..haxelibs../hxcollision/git/` 

is pointing at the root git folder, not the child hxcollision path. It seems haxelib points it one too deep.

#Recent changes

**1.0.1**
 - Added an option for Polygon.rectangle() to be non-centered
 - More to come 
 
**1.0.0** 
 - Initial project pull and compile/port, functional
