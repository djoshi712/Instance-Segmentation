# Instance-Segmentation

--Notebooks--
1) Preprocessing 
2) Crack detection
3) Wrist Fracture detection


Use Surface crack dataset and --
1. Change image size to 800*600
2. use labelme and start annotating the dataset by creating the segmentation mask
3. convert to coco format using labelme2coco.py file
4. split the dataset into train and test set randomly (80:20)
5. Train the surface crack dataset using maskRCNN architecture trained on COCO dataset and save it as "surface_crack_detection.pth"
Use wrist frcature dataset and --
6. Change image size to 800*600
7. use labelme and start annotating the dataset by creating the segmentation mask
8. convert to coco format using labelme2coco.py file
9. split the dataset into train and test set randomly (80:20)
10. Train the wrist frcature dataset using maskRCNN architecture trained on surfacr crack dataset and save it as "final_model.pth"
