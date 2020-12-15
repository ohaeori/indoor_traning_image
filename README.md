# indoor_traning_image

1. Download project

2. Open with unity

3. Open scene in Assets folder

4. Put your model in model folder

5. Load your model in unity

6. Set your model's position (0,0,0)

7. Set Navigation Static and click "yes"

![image](https://user-images.githubusercontent.com/50140277/102225410-89eb2f00-3f2a-11eb-9217-bb20a1611a35.png)
![image](https://user-images.githubusercontent.com/50140277/102225421-8ce61f80-3f2a-11eb-957e-b1c609100bfc.png)

8. Set Navigation

![image](https://user-images.githubusercontent.com/50140277/102225428-8f487980-3f2a-11eb-9fae-b09b719132c1.png)

9. Adjust parameter to your model then Bake

![image](https://user-images.githubusercontent.com/50140277/102225440-91123d00-3f2a-11eb-9851-739f14eaca8c.png)

10. Create a folder with the same name as your model in ScreenShot folder

11. Change NAME object's name to your model (transparent one)

12. Move object REAL in your model and adjust it's y position for good photo

13. Change REAL's "far" enough cover your model

14. Click your model in Hierachy Tap

15. Click on the same sub object and select children

16. Set appropriate tag for object (Refer to ApplySegmentation.cs)

17. Click play button

18. Check screenshot folder ("real", "depth" and "segmentation" will be end of file name)

Script "ApplySegmentation" : for Segmentation camera. put it in the "Segmentation" object

Script "DepthCam" : for Depth camera. put it in the "Depth" object

Script "TrackingCam" : tracking Real's position (put it in "Depth" and "Segmentation" object)

Script "HiResScreenShots" : screenshot with Camera name(put it in "Real", "Depth" and "Segmentation" object. Screenshot image will save with camera's name)

