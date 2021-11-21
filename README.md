# Image-Classification-using-PyTorch
This repository presents the Image Classification project. For learning I used Dataset containing of about 25 000 images sized 150x150 distributed under 6 categories:
- Buildings
- Forest
- Glacier
- Mountain
- Sea
- Street

Train data contains 14 000 images, test data - 3 000 images, prediction data - 7 000 images.

## How to run
### Downloading the dataset
Since we are using opendatasets library, which uses the Kaggle Official API to download the dataset from Kaggle, in order to run the code you will need to use your own API credentials. Follow these steps to find your API credentials:
1. Sign in to https://kaggle.com/, then click on your profile picture on the top right and select "My Account" from the menu.
2. Scroll down to the "API" section and click "Create New API Token". This will download a file kaggle.json with the following contents:
```{"username" : "YOUR_KAGGLE_USERNAME", "key" : "YOUR_KAGGLE_KEY"}```
3. When you run opendatsets.download, you will be asked to enter your username & Kaggle API, which you can get from the file downloaded in step 2.
> Note that you need to download the kaggle.json file only once. On Google Colab, you can also upload the kaggle.json file using the files tab, and the credentials will be read automatically.

### Running the code
To run the code in reasonable amount of time I used Google Colab. To make the learning process more efficient, I highly recommend using the GPU.

