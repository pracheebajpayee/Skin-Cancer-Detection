# Skin-Cancer-Detection

Skin cancer is the out-of-control growth of abnormal cells in the epidermis, the outermost skin layer, caused by unrepaired DNA damage that triggers mutations. These mutations lead the skin cells to multiply rapidly and form malignant tumors.
Though skin cancer is a deadly disease but if detected early,survival is rate is 97% !!

Our motivation is to analyse and fine-tune a supervised model fed by data of some already diagnosed lesion images, which would predict whether the image of a suspected lesion is benign or malignant, to a certain level of accuracy which would be considered a standard for an initial diagnosis. This would assist medical professionals to get a quick and accurate initial diagnosis which they can further confirm using more specialised methods.

:We have used a comprehensive dataset which contains 3297 images of dermal skin lesions which would train our model to have a thorough understanding of the observable and underlying patterns in the said images, for a better classification accuracy.

Benign cells :

![benign](https://user-images.githubusercontent.com/82201510/128613197-ee8fae63-dc7d-4782-8190-dbe35578b403.png)

Malignant cells :

![malignant](https://user-images.githubusercontent.com/82201510/128613203-1a775d57-2e86-4ee7-a0e0-9edd9c7dd3b7.png)


# Extracting Features

1. Local Binary Pattern:
   Local binary pattern (LBP) is one of the useful methods for feature extraction. This method is used in many topics of image processing: face detection, breast cancer, X- Ray      images, and LBP in comparison of the gray level between one pixel, called the central pixel, with its pixel neighborhood.
   
   
2. Color Moment Statistics:
    Using Image Matrix, all R, G, and B components in an image are extracted and separated into three different array forms. Using the feature vectors, each image color wise means     are computed. In this method row and overall image mean are computed and stored into the database. Based on all these features, different computing methods are formulated.
    
# Working Flowchart

![Working Flowchart](https://user-images.githubusercontent.com/82201510/128613382-a048ef71-5c31-4421-9504-5f199e2f1e4f.png)


