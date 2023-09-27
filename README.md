Self Driving Cars is an interesting complex problem which uses Deep Learning extensively. Here I aim to solve a sub-problem of detecting traffic signs using Object Detection.
Developed a Yolov3 Model using Tensorflow and Keras that detects traffic signs and classify them into 4 classes.

Dataset: https://benchmark.ini.rub.de/gtsdb_news.html

Detailed Blog :  https://medium.com/@anirudhsr97/german-traffic-signs-detection-using-yolov3-ab7b974fca4e

There are 43 traffic signs in total.Let’s see their names along with their images below.

<img width="692" alt="image" src="https://github.com/anirudh-s97/German-Traffic-Sign-Detection/assets/43056822/71558b6f-cbfa-46b6-a231-90249a23a574">


All the above 43 traffic signs are segregated into 4 different classes and our problem is to detect, localize and classify these traffic signs using Object Detection.
As information given along with the data-set,the traffic signs which are circular,white ground with red color belong to the Prohibitory class.Traffic Signs which are
circular and blue ground belong to the Mandatory class.The Triangular traffic signs with Red Ground belong to the Danger class and the remaining belong to Other Class.





Sample Predictions:

Prohibitory Class:

<img width="880" alt="image" src="https://github.com/anirudh-s97/German-Traffic-Sign-Detection/assets/43056822/883caa08-3c1b-4687-96ec-61cfd0d318f2">


Mandatory Class:

<img width="512" alt="image" src="https://github.com/anirudh-s97/German-Traffic-Sign-Detection/assets/43056822/0f92b51e-b53c-4983-8c93-b9d4baf77f22">


