
# 🧠 [Brain Tumor Test](https://brain-tumor-test.herokuapp.com/)

Brain Tumor Test is a **Deep Learning Web Application** based on a **CNN Architecture** which uses MRI Scanned *clear* images to find out whether a patient is suffering from a brain tumor or not.

It also helps us to distinguish between the *types* of Brain Tumors which could be present. 

![Home Page](https://raw.githubusercontent.com/jaykumar1607/Brain-Tumor-Web-App/main/docs/images/homepage.png)
![What is brain tumor1](https://raw.githubusercontent.com/jaykumar1607/Brain-Tumor-Web-App/main/docs/images/whatis.png)

## 🎥 Demo
This demo shows how you will input the data and based on that, the predicted result is provided to you along with some knowledge about the type of tumor you're suffering from.

<div>
    <center><img src="https://raw.githubusercontent.com/jaykumar1607/Brain-Tumor-Web-App/main/demo/demo.gif"></center>
</div>



## 🤖 Under the hood

Brain Tumor Test uses the concept of **Transfer Learning** which enables us to use the *weights and biases* of some of the famous CNN architectures which ***decreases the amount of computational time significantly.***

I've used the **EfficientNetB0** architecture for this task.
To understand how the model was made more clearly, I would recommend you to visit my Kaggle Notebook [here](https://www.kaggle.com/jaykumar1607/brain-tumor-mri-classification-tensorflow-cnn)

## 📊 Dataset

The dataset contains a total of **10000** images of MRI Scanned clear images of patients with and without brain tumors.
There are 3 major types of tumors which we're dealing with in this dataset:
- Meningioma Tumor
- Glioma Tumor
- Pituitary Tumor
Along with this, we also train the model on MRI Scanned images of patients who do ***not*** have a brain tumor.

The dataset is present on **Kaggle** and you can check it out by clicking on this link [here](https://www.kaggle.com/sartajbhuvaji/brain-tumor-classification-mri)


  
## ⚙️ Tech Stack

- **Programming Language:** Python
- **Scripting Languages:** HTML, CSS
- **Packages**: Tensorflow, Scikit-learn, OpenCV, Gunicorn, WTForms, Numpy, Pandas, Joblib, Flask Bootstrap
- **Backend Framework:** Flask
- **Cloud Platform**: Heroku

## 🌐 Deployment

I've used **Heroku** as the preferred platform to deploy my web application.

  
## 👨‍💻 Contributors

- [Jay Kumar](https://github.com/jaykumar1607)
  
