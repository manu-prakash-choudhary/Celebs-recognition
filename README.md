<h1 align="center">Facial Image Classification</h1>
<p align="center">
<img align="center" src="./banner.jpg" width="100%"/>

</p>

<p align="center">
  In this project, one or more human faces are detected through images and name predictions are made for those faces detected by AI models trained in the background.
<p>

---

<h2> Working Demonstration </h2>

<img src="./demo.gif" />

<p>
  I have used Haar Cascade Classifier and Wavelet Transform to detect faces in the images.  Then after preprocessing the datasets, I tested my model on various classifiers(SVM, Logistic Regression,Random Forest). Then I have used the best performing model to predict the names of the faces detected in the images.
</p>

---

<h2> Usage </h2>

<p>
  To run this project, you need to have Python 3.6 or above installed on your system. Then you can clone this repository and install the required libraries using the following command [/Model directory]:

```bash
pip install -r requirements.txt
```

Then you can activate the flask server using the following command [/Server directory]:

```bash
python server.py
```

Then you can run the application by opening the index.html file in the browser [/UI directory].

</p>

---

<h2>Features</h2>

- [x] Detect faces in images
- [x] User friendly UI
- [x] Predict names of the faces detected
- [ ] Deploy the model on the web

---

<h4>License</h4>

This project is licensed under the Apache License - see the [LICENSE](LICENSE) file for details.
HyperWrite Logo
