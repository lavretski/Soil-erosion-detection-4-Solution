# Soil-erosion-detection-4-Solution
Random Image crop
![image](https://user-images.githubusercontent.com/36608117/224563583-5267fd5e-9a6f-463a-865e-e56233920ef9.png)
Mask for that crop
![image](https://user-images.githubusercontent.com/36608117/224563637-4410a549-c8c4-4286-adce-4581293c9602.png)

Or for example 
roterio.mask.mask, as you can see there are very brown pictures
![image](https://user-images.githubusercontent.com/36608117/224563663-da329afb-4431-4d7c-b800-f2cc12266b72.png)

So it is clearly visible that the masks are bad

In order to correctly attach the masks to the photo, I tried

-play with all train_df.crs = {'init' :'epsg:4326'} changed epsg:4326
-changed and experimented with the poly_from_utm function
-changed parameters in rasterio.mask.mask
-played with transposing the mask in various places in the code
-read other files from the masks folder, which for some reason weigh more and some less, but contain the same masks in the same places on the map

But I write code with modeling
If you can give me a hint on how to fix the masks, I'm ready to continue working, thanks
