# OCR

How to use the saved the model?
1. Unzip the folder and save it on your google drive.
2. Open the file and Mount your google drive.
3.  In the file top inference file change the paths to saved model as per your saved model path in the below line.
   `loaded_model = keras.models.load_model("/content/drive/MyDrive/Handwritting OCR 10 epochs")`
4. Give the path to the image you wish to test in `new_image_path = "/content/Screenshot 2023-12-03 142945.png"`
   this line. You will see the result.
