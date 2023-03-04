[![IMAGE ALT TEXT HERE](https://youtu.be/eRrKFU3xS5U/0.jpg)](https://youtu.be/eRrKFU3xS5U)  
↑ Click image to watch Youtube instruction  
or or from link below
https://youtu.be/eRrKFU3xS5U

日本語での動画(https://youtu.be/BieNlr3j0O8)

日本語でのQiita記事↓　(Japanese document ↓)
https://qiita.com/nakamurata/items/b27d5b15e92f685e43a9

## prerequisite
Windows10  
Unreal Engine 5  
VR HMDs like Meta Quest Series, HTC VIVE Series or Stuff supporting OpenXR may work.  

### Recommended system
Intel i7 gen 9th - 11th / Intel i9 gen 9th - 11th / AMD ryzen 7 / AMD ryzen 9  
+16 GB RAM memory  
NVIDIA RTX 3080 or Higher  
Unreal Engine 5.0  
Meta Quest Pro / Meta Quest 2  

## commentary
I know you all think this.
Noise removal in point clouds is hard.

If you want clearer point clouds, you can de-noisb with CloudCompare, PCL, or Open3D using algorithms such as ROR or SOR.
However, most point clouds cannot be automatically removed as you wish, and I know many people who want a cleaner point clouds use Cloud Compare or other paid GUI software to manually remove noise.

I understand the difficulty of those who clean up large point clouds.
You know it's hard to manually edit a point clouds on a 2D display.
Poor perceptibility makes it time consuming and difficult to have confidence in accuracy.

This project is for that kind of people.

Please refer to the youtube video for operating instructions.
https://youtu.be/eRrKFU3xS5U


# Manuals

### Input (Quest2)
![image](https://user-images.githubusercontent.com/57085424/222885209-bec6b589-0727-44db-9f93-98d988232c13.png)
| Input | action |
|---|---|
| HandTrigger | Show/Hide Sphere |
|HandTrigger & IndexTrigger	| [ ] OK<br> [ ] NG|
Overlay Sphere and point cloud, delete point cloud with HandTrigger & IndexTrigger

### Export
Right-click on the edited point cloud file (.uasset) and select Asset Action → Export
![image](https://user-images.githubusercontent.com/57085424/222884999-60af7f16-6e50-4573-8eb5-c3a18559e6bf.png)




## Appendix
If the low FPS is caused by insufficient computer power, try setting the "MAX Bucket Size" to a smaller value.
![image](https://user-images.githubusercontent.com/57085424/219933468-c61dd4b7-948a-4b96-b61f-90fe2151c420.png)

