![image](https://user-images.githubusercontent.com/82112471/175300046-5835dcc8-475f-46b5-bc2b-2b1fdc6fd760.png)
### Project Sloth UI
A single resource made up of several smaller, UI-related scripts for use in your server, accessible via client-side exports. Documentation and previews of each are provided below. We will continue to add to this collection in the future.

![image](https://user-images.githubusercontent.com/82112471/175300175-6d6f926f-b3e2-42d3-b564-2e52e737d6c2.png)

## Notification
![image](https://i.imgur.com/BKmeBlB.png)

## Circle Minigame

```
exports['ps-ui']:Circle(function(success)
    if success then
        print("success")
	else
		print("fail")
	end
end, 2, 20) -- NumberOfCircles, MS
```
![image](https://i.imgur.com/STW3xgo.png)
![image](https://i.imgur.com/EmWQO36.png)

## Number Maze
```
exports['ps-ui']:Maze(function(success)
    if success then
        print("success")
	else
		print("fail")
	end
end, 20) -- Hack Time Limit
```
![image](https://user-images.githubusercontent.com/7463741/170586240-fa92a1fc-aac0-48bb-938f-f6f03a63511f.png)

## VAR
```
exports['ps-ui']:VarHack(function(success)
    if success then
        print("success")
	else
		print("fail")
	end
 end, 2, 3) -- Number of Blocks, Time (seconds)
 ```
 ![image](https://user-images.githubusercontent.com/7463741/170586620-51c8648d-1f2c-4ff5-a8d0-755c82b34d58.png)

 ## Thermite
 ```
exports['ps-ui']:Thermite(function(success)
    if success then
        print("success")
	else
		print("fail")
	end
end, 10, 5, 3) -- Time, Gridsize (5, 6, 7, 8, 9, 10), IncorrectBlocks
 ```
 ![image](https://user-images.githubusercontent.com/7463741/170587067-4c27bf6e-8f5b-4bff-a739-d688be3450fe.png)

## Scrambler
```
eexports['ps-ui']:Scrambler(function(success)
    if success then
        print("success")
	else
		print("fail")
	end
end, "numeric", 30, 0) -- Type (alphabet, numeric, alphanumeric, greek, braille, runes), Time (Seconds), Mirrored (0: Normal, 1: Normal + Mirrored 2: Mirrored only )
```
![image](https://user-images.githubusercontent.com/7463741/170587319-2109661a-8baf-48ff-b4bb-cd18fc10ec73.png)

## Display Text
```
exports['ps-ui']:DisplayText("Example Text", "primary") -- Colors: primary, error, success, warning, info, mint
exports['ps-ui']:HideText()
```
![image](https://user-images.githubusercontent.com/7463741/170587380-0629b5fc-80d6-4c2a-85c1-4e5426167197.png)

## Status UI
```
exports['ps-ui']:StatusShow("Area Dominance", {
  "Gang: Ballas",
  "Influence: %100",
})
exports['ps-ui']:StatusUpdate("Area Dominance", {
  "Gang: Ballas",
  "Influence: %99",
})
exports['ps-ui']:StatusHide()
```
![image](https://user-images.githubusercontent.com/7463741/170587637-57217095-29ab-460e-9933-123fb0500e12.png)

## Menus
![image](https://i.imgur.com/bQIirwJ.png)

## Input
![image](https://i.imgur.com/u9CLuw9.png)

## Show Image

```
exports['ps-ui']:ShowImage("https://user-images.githubusercontent.com/91661118/168956591-43462c40-e7c2-41af-8282-b2d9b6716771.png")
```
![image](https://user-images.githubusercontent.com/70592880/173483722-53c40c11-faf0-42d8-98b2-ec97d99c3a39.png)


CREDITS:
- https://github.com/sharkiller/nopixel_minigame
- https://github.com/iLLeniumStudios/is-statushud
