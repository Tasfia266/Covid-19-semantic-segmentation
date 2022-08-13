# Covid-19-semantic-segmentation
1. Semantic segmentation of the infected tissue regions of the lung ct-scan images. 
2. The dataset can be downloaded from kaggle. 
3. U-net semantic segmentation model was used to automatically segment infected regions of lungs. Both the images and masks were augmented using ImageDataGenerator from keras library. 
4. The U-net model was trained in Google Colab using approximately 500 epochs. The validation focal-loss score was 0.0076. 
![covid-19](https://user-images.githubusercontent.com/76652458/184506685-89fea39f-9650-43b1-92bf-ddb27597cb05.png)
