# SnailVision
Vision like a snail! For 2018 and beyond

![Design](schema1.jpg)

## Design Specs
Users first create a target, which is an object that users wish to identify and track. (For example, a boiler vision target or a gear vision target). Users then set the target's name, number of outlines, aspect ratio, and camera view mode. The number of outlines represents the number of contours per target that the app will identify and track. (For example, a boiler vision target has two outlines and a gear vision target has two outlines because they are each made of two pieces of reflective tape. Also if more than the specified number of contours is found then only the biggest ones will be tracked and reported on.) The aspect ratio is the ratio between height and width of the contours to make sure that the shapes are generally reasonable. The camera view mode will control whether or not the camera will be mounted in landscape or portrait on the robot. 
