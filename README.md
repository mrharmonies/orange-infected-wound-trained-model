## Welcome to orange-infected-wound-trained-model GitHub Pages

# introduction

orange-infected-wound-trained-model is a supervised trained Neural Network model, trained to categorize images of wound as **infected wound** or **clean wound**. This trained model is to be use within **Orange Data Mining program**. Simply load 

# usage

Open Orange Data Mining program, then drag **"Import Images", "Image Embedding", "Load Model", "Predictions" and "Image Viewer"** elements into canvas and **connect the elements in these particular order**

![](https://drive.google.com/uc?id=1uzCtVDHhOGA3aZ4BvBuQkKY3tHPdpMjW)

Then double click **"Import Images"** and select the folder containing the wound images you want to categorize.

![](https://drive.google.com/uc?id=1QuinXbpG_Vv9m1w2SzSKPgXZ5dK2xUlb)

Double click **"Image Embedding"** and select **"SqueezeNet (local)"** for the **Embedder**

![](https://drive.google.com/uc?id=1M4lN5TI6WF0O_pDjjQI9NvJief6Y4D4I)

Now its time to load the trained model. Download "wound nn.pkcls" from this repository then double click "Load Model". Browse for the file that you've just downloaded

![](https://drive.google.com/uc?id=11_eLgmZ01FOu-UodVqaheUBYI3w3x0_A)

Orange Data Mining program will now evaluate the embedded wound images that you've selected. Double click on Predictions. Predictions will show you the neural network confidence. In this case, the value for infected and clean wound is 1 (means full confidence)

![](https://drive.google.com/uc?id=1KiPK_vCbUYAIYztQ8jJmBwfkbDV4Dfs2)

Double click on Image Viewer to view the images. Select "Neural Network" from "Title Attribute" to view the Neural Network result. Notice the Neural Network result is displayed under the images.

![](https://drive.google.com/uc?id=1KyJ579p29zOeE0X3QZ89j7216c2muzUY)

