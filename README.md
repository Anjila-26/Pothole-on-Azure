# PotHole Detection
This is code after you train your model on the pothole and want to deploy that on the streamlit. This same process can be followed for many other object detection in the azure.

Following Images are Step by Step guide on how to use the Azure Custom Vision for Object Detection:
1. Go to the https://www.customvision.ai/ and sign in, Ounce you signin you will be directed to a page with New Project on it.
   ![1](https://github.com/Anjila-26/Pothole-on-Azure/assets/54539708/b0945055-5c08-48d9-9fda-ee94cbd83990)
2. Create a Name Project with the options shown on the image.
   ![2](https://github.com/Anjila-26/Pothole-on-Azure/assets/54539708/be1632ff-6938-4c4f-b986-92d53a1dbc4d)
3. If you don't have any resourcecs , Click on Create new and create a new resource and resource group
   ![3](https://github.com/Anjila-26/Pothole-on-Azure/assets/54539708/4b0952d8-2015-4147-9763-c613439bbfb8)
4. As seen in Image, below add the images to the system, and it will first be seen on the untagged part
   ![4](https://github.com/Anjila-26/Pothole-on-Azure/assets/54539708/de8f7278-e039-4716-ac07-692078ca8573)
5. Now, annotate any region of your choice and lable the image, ounce you label it will show on Tagged one.
   ![5](https://github.com/Anjila-26/Pothole-on-Azure/assets/54539708/9f22ed4c-acaa-4891-9547-547ba2bc2eec)
6. Now, train as much time as you want which will require additional resources
   ![6](https://github.com/Anjila-26/Pothole-on-Azure/assets/54539708/c3118bd3-6f07-47c8-a4f4-78c96690c4d1)
7. Now you can see the evaluation of your model
   ![7](https://github.com/Anjila-26/Pothole-on-Azure/assets/54539708/f5f7ec49-4837-405a-a057-cea178356537)
8. Now, Ounce you publish your model you can see the prediction key and url for the images from folder and url
   ![8](https://github.com/Anjila-26/Pothole-on-Azure/assets/54539708/ce32f693-5fb5-4e4d-8409-e33f3bd2a3bd)
Now, Create `.env` for your predictionKey on the same folder and get your azure prediction key and headers.






