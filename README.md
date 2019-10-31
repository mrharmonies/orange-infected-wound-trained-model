# introduction

orange-infected-wound-trained-model is a supervised trained Neural Network model, trained to classify images of wound as **infected wound** or **clean wound**. This trained model is to be use within **Orange Data Mining program**. 

# requirements

1. Orange Data Mining
2. Image Analytics Addon for Orange Data Mining

# usage

Open Orange Data Mining program, then drag **"Import Images", "Image Embedding", "Load Model", "Predictions" and "Image Viewer"** elements into canvas and **connect the elements in these particular order**

![](https://drive.google.com/uc?id=1uzCtVDHhOGA3aZ4BvBuQkKY3tHPdpMjW)

Then double click **"Import Images"** and select the folder containing the wound images you want to classify.

![](https://drive.google.com/uc?id=1QuinXbpG_Vv9m1w2SzSKPgXZ5dK2xUlb)

Double click **"Image Embedding"** and select **"SqueezeNet (local)"** for the **Embedder**

![](https://drive.google.com/uc?id=1M4lN5TI6WF0O_pDjjQI9NvJief6Y4D4I)

Now its time to load the trained model. Download **"wound nn.pkcls"** from this repository then double click **"Load Model"**. Browse for the file that you've just downloaded

![](https://drive.google.com/uc?id=11_eLgmZ01FOu-UodVqaheUBYI3w3x0_A)

Orange Data Mining program will now evaluate the embedded wound images that you've selected. Double click on **"Predictions"**. Predictions will show you the neural network prediction **confidence**. In this case, the value for infected and clean wound is 1 (means full confidence)

![](https://drive.google.com/uc?id=1KiPK_vCbUYAIYztQ8jJmBwfkbDV4Dfs2)

Double click on **Image Viewer** to view the images. Select **"Neural Network"** from **"Title Attribute"** to view the Neural Network result. Notice the Neural Network result is **displayed under the images**.

![](https://drive.google.com/uc?id=1KyJ579p29zOeE0X3QZ89j7216c2muzUY)

# license
Copyright (C) 2019 Mohd Kholid Yaacob (http://mrharmonies.blogspot.com)

This source is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 2 of the License, or (at your option) any later version.

This code is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

A copy of the GNU General Public License is available on the World Wide Web at http://www.gnu.org/copyleft/gpl.html. You can also obtain it by writing to the Free Software Foundation, Inc., 51 Franklin Street - Fifth Floor, Boston, MA 02110-1335, USA.
