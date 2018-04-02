details of CVI-datasets:

1£©'imagedata' folder contains images of lower limb CVI. 
    subfolder '1' -- normal skin (C0)
    subfolder '2' -- reticular vein or telangiectasia (C1)
    subfolder '3' -- varicose veins (C2, C3)
    subfolder '4' -- pigmentation or edema (C4)
    subfolder '5' -- venous ulcers (C5, C6)

   note: these images have been resized to 250(width)*700(height), and the background has been removed.

2£©local image labels
   'imagePatch-labels15' folder contains the labels of image patch divided by 15*15 grids;
   'imagePatch-labels25' folder contains the labels of image patch divided by 25*25 grids; 
   'imagePatch-labels50' folder contains the labels of image patch divided by 50*50 grids;

   note: the numbers in these files denote the divided patch order. The divided order is from left to right and from top to bottom. 


3) global image labels
   a) gentle class -- means that non-symptom or reticular vein or telangiectasia, including  images in the subfolder '1' and '2' in floder 'imagedata';

   b) moderate class -- denotes varicose vein, including images in the subfolder '3' in floder 'imagedata';

   c) severe class -- contains edema, eczema and venous ulcer, including images in the subfolder '4' and '5' in floder 'imagedata';

   
    
 