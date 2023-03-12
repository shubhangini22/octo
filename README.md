# Octo
> Deep learning model for recognising pets :)


### I have explained my project by breaking down it into simpler parts. 

- [Description](#description)
- [Technologies used](#technologies)
- [Contact-info](#author-info)

---

## Description 

Step-1:Initially I imported the following libraries:<br>
1.Tensorflow<br>
2.ImageDataGenerator from Keras<br>

Then the data to be utilized was pre-processed in data preprocessing step<br><br><br>
<img width="899" alt="1" src="https://user-images.githubusercontent.com/88343647/224542854-37a5672a-eb4e-4f2e-89f4-0b66c099fa54.png">

       <br><br>
Step-2:Preprocessing the test set and training set respectively by creating respective objects and instance from imagedatagenerator.<br><br><br>

           <img width="888" alt="2" src="https://user-images.githubusercontent.com/88343647/224542986-12ad2f6b-bcdc-41d2-8542-4957a303fd2b.png">
<br><br>
Step-3:After performing the above steps it's time to build our CNN model.<br>
This itself inovolves diving deepinto mathematics by breaking down inti following steps:<br>
1.Convolution<br>
2.Pooling<br>
3.Adding a second convolutional layer<br>
4.Flatterning<br>
5.Full connection<br>
6.Output layer
<img width="857" alt="3" src="https://user-images.githubusercontent.com/88343647/224543177-606ae7fa-f2c0-4e7f-99a4-86100202d952.png">

<br><br><br>
<img width="833" alt="4" src="https://user-images.githubusercontent.com/88343647/224543189-2675a4b3-b46e-4d92-93c3-68cc658be04d.png">

<br><br>
Step-4:After specifying the test set and training set, building of CNN model was done as per the below mentioned steps:<br><br>
<img width="894" alt="5" src="https://user-images.githubusercontent.com/88343647/224543209-0a9857bc-1c00-419a-a8fd-169028c28050.png">

<br><br><br><br>
Step-5:Now, prediction was done by giving a weird image of cat were the model satisfactorily gave accepted result<br><br><br>
###Test image



![cat 4069](https://user-images.githubusercontent.com/88343647/224543329-48ed81c1-e647-4cd5-b409-ad041bb7715e.jpg)
<br><br><br>
###Predicted Result:


<img width="894" alt="5" src="https://user-images.githubusercontent.com/88343647/224543387-e107a2ab-a506-462d-8f8a-972af76e178d.png">
<br><br><br>

#### Technologies


- Tensorflow
- Keras
- Jupyter Notebook


## Author Info

- E-mail - [shubhangini2203@gmail.com]
- Website - [Shubhangini](https://62988a84130dd177a6a2332b--stately-crostata-24e520.netlify.app/)

[Back To The Top](#read-me-template)
