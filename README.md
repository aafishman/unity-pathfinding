# Pathfinding
Find paths in Unity Tilemaps with A* Search based off Amit Patel's implementation.

Download and Import the Pathfinding [package](https://github.com/antonpantev/pathfinding/raw/master/Pathfinding.unitypackage) then use `AStar.FindPath()` like so:

```c#
List<Vector3> path = AStar.FindPath(tilemap, startPos, endPos);
```

<img src="https://raw.githubusercontent.com/antonpantev/pathfinding/master/PreviewImages/ScreenShot.png">

test this out...