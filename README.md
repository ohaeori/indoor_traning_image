# indoor_traning_image

1. download project

2. open with unity

3. open scene in Assets folder

4. put your model in model folder

5. load your model in unity

6. set your model's position (0,0,0)

7. set Navigation Static and click "yes"
  
8. set Navigation

9. adjust parameter to your model then Bake

10. Create a folder with the same name as your model in ScreenShot folder

11. Change NAME object's name to your model (transparent one)

12. move object REAL in your model and adjust it's y position for good photo

13. change REAL's "far" enough cover your model

14. click play button

15. check screenshot folder ("real", "depth" and "segmentation" will be end of file name)

script "ApplySegmentation" : for Segmentation camera. put it in the "Segmentation" object

script "DepthCam" : for Depth camera. put it in the "Depth" object

script "TrackingCam" : tracking Real's position (put it in "Depth" and "Segmentation" object)

script "HiResScreenShots" : screenshot with Camera name(put it in "Real", "Depth" and "Segmentation" object. Screenshot image will save with camera's name)

