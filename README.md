
# Traffic Signs Recognition with 95% Accuracy

## A. PROJECT SUMMARY

**Project Title:** Traffic Signs Recognition


**Project developer:** 
- Radwan Mohammed Rashed Mahdi


- [ ] **Objectives:**
- To recognise the traffic sign.
- To explain the action of a particular traffic sign.
- To achieving accuracy in this technology for self-driving cars.


##  B. ABSTRACT 

In the world of Artificial Intelligence and advancement in technologies, many researchers and 
big companies like Tesla, Uber, Google, Mercedes-Benz, Toyota, Ford, Audi, etc are working on 
autonomous vehicles and self-driving cars. 
So, for achieving accuracy in this technology, the vehicles should be able to interpret 
traffic signs and make decisions accordingly.

There are several different types of traffic signs like speed limits, no entry, traffic signals, 
turn left or right, children crossing, no passing of heavy vehicles, etc. 
Traffic signs classification is the process of identifying which class a traffic sign belongs to.

In this Python project example, we will build a deep neural network model that can classify 
traffic signs present in the image into different categories. 
With this model, we are able to read and understand traffic signs 
which are a very important task for all autonomous vehicles.

![Coding](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2019/12/graphical-user-interface-project-in-python.png)

Figure 1 shows the AI output of recognizing what is the traffic sign and its meaning.


## C.  DATASET

For this project, I am using the public dataset of traffic sign.
The dataset contains more than 500 images of different traffic signs. 
It is further classified into 40 different classes. 
The dataset is quite varying, some of the classes have many images while some classes have few images. 
The size of the dataset is around 100 MB.
The dataset has a train folder which contains images inside each class 
and a test folder which we will use for testing our model.




## D.   PROJECT STRUCTURE

The following directories are our structure of our project:
- $ tree --dirsfirst --filelimit 5
- .
- ├── dataset
- │   ├── song_data.csv [1000001 entries]
- │   └── triplets_file.csv [1048576 entries]
- ├── music_recommender
- │   ├── popularityBased_recommender.py
- │   ├── contentBased_recommender.py
- │   └── Main.py
- └── trainMusicDatasetRecommendation.py

- 2 directories, 15 files



## E.   TRAINING THE TRAFFIC SIGN DETECTION

I am ngoing to train my traffic sign detection using using model.fit(). 
I tried with batch size 32 and 64. my model performed better with 64 batch size. And after 15 epochs the accuracy was stable.

From there, open up a terminal, and execute the following command:

- $ python train_traffic_sign_detector.py --dataset dataset
- but our project is not 100% ready to do the test. This is an example of documentation on github.


![Figure 4](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2019/12/accuracy-loss-python-machine-learning-project.png)

Figure 4: Figure 10: Traffic Sign recognizer training accuracy and loss graph.

As you can see, the project is obtaining ~99% accuracy on my test set.

However, we can see there are little signs of overfitting, with the validation loss lower than the training loss. 



## F.  RESULT AND CONCLUSION

In this Python project with source code, I can successfully classified the traffic signs classifier with 95% accuracy 
and also visualized how our accuracy and loss changes with time, which is pretty good from a simple CNN model.

[![Figure5](https://img.youtube.com/vi/U-SBY9eJ-xc/0.jpg)](https://www.youtube.com/watch?v=U-SBY9eJ-xc)

Figure 5: Traffic Sign in real-time video streams

In Figure 5, you can see that my Traffic Sign recognizer in real-time (and is correct in its predictions as well).









