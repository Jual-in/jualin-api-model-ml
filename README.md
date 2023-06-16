<div align="center">

<img src="image/product_logo.png" alt='Jualin logo' width=500/>

# API Model Machine Learning Jual.In

<div align="left">

This API runs a Machine Learning Image Recognition model using Flask Python. It is built with a focus on simplicity, responsiveness, and reliability. With a simple interface, this API facilitates the management of HTTP requests and provides predictions from the image recognition model. The flexibility of this API allows users to easily integrate it into their applications. It is a robust and reliable solution for developing Machine Learning Image Recognition applications.

## 👨‍🏭 Contributors
- Ari Mulyanto
- Satriadi Putra Santika

## 📋 Endpoint

- POST: `/predict` - To make image predictions

## 📚 Technologies Used

- [Python](https://www.python.org/)
- [Cloud Run](https://cloud.google.com/)

## 💻 Test API
- Testing API on Local Server

1. Clone this repository.
2. Enter CMD and navigate to the API directory.
3. Run the "python main.py" command
4. Use the url from the command response to predict in Postman, like so:: http://192.168.26.14:8080/predict

- Testing the API directly on Postman without a repository clone

 Use this url address : https://jualin-ml-umkm-service-yx5zrdv2ka-et.a.run.app/predict

 ## 📌 Note
 - For machine learning models, you can download the model in the Jualin-Machine-Learning repository. And create a model folder in the API directory to store the downloaded model files
