# Bess-Detection-Using-AWS-object-detection-and-Yolov5

Bess Detection using two different techniques (AWS SageMaker Ground Truth and Object Detection) and (YOLOv5)


## Introduction
Machine Learning is now an important approach used in many aspects of our life. Particularly now a days it is heading to computer vision applications. Computer Vision is one of the important fields in Artificial intelligence. That allows the computer-based systems to interpret and understand the images. It plays a significant role in solving challenges related to object detection problems. The main purpose of object detection is to locate and identify the needed targets. In this paper we will display the object detection techniques and experiments applied to help in detecting bees.

## Dataset
Using a suitable data set is the key to solving this problem. Bees’ detection is very sensitive problem, as there are many challenges, as the bees’ sizes and the places we can find them that may be overlapped in color with the bees. So, we use a huge amount of data, so we collect our dataset from the **inaturalist.org**. This dataset has 700 images of bees that have been uploaded by Inaturalist users for the purposes of recording the observation and identification. We only used images that their users have licensed under CC0 license. The data is composed of multiple images with single and multiple bees. We have a lot of diversity of bees with different sides, rotations, and sizes. Which is an important aspect to consider. As if the model is trained only on a big bee's sizes in the image it will not be robust enough to solve the main problem. Then we used **IBM cloud annotation** to annotate images by adding a bounding box around the target object in the image to use it in our model so each image has a “.txt” file with the border dimensions. Then split our dataset into 600 images as a training set and 100 images as a validation set before sending our dataset to our model. After the first usage of the data, we saw that the data is not enough and missed a lot of details of the images. Using dataset of 700 image considered to be small dataset in such detailed problems. So, we had to implement **data augmentation** approach of Vertical flips, Horizontal flips, Vertical-Horizontal flips and 90º Rotation. So, we managed to increase the data to 2500 annotated images. Ready to be used in the retraining process.

## Feedback

If you have any feedback, please reach out me at mhuss073@uottawa.ca

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://www.credential.net/profile/mohamedaboalarbe/wallet)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohammed-elaraby/)


