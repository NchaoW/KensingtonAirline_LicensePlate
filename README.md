# KensingtonAirline_LicensePlate

## WEEK 2
- Using Sarun's_ThangLuang.ttf font to generate character to predict license plate
- Use keras ImageDataGenerator to do data augmentation
- Train character prediction model using CNN 
- Use OpenCV to detect license plate and create bounding box for each character
- Use model to predict character in bounding box


## How to run
- Open .ipynb file in Google Colab
- Upload .ttf file to session storage
- Upload image file to session storage (Default is image9.jpg)
- to change image file, change the original_image filename in the last cell
- Run all cells
- In case you want to run the file in your local machine, you need to change google colab's cv2_imshow to cv2.imshow and change the path to the image file