
### This is a ongoing blog about personal product we are building targeting business owners. 

I and my colleague ShekharPatel  are developing a hardware product for detecting fires if they happen on timber  yard.

## July 2019

So on somewhere around July 2019 , shekhar has discussed with me about fire accident happened at his home while working on a project in the company.

## August 2019

Cut to the August 2019 we are discussing holiday plans for Independence day and I was scrolling thorugh twitter feed . I noticed somthing in  my feed regarding fire 

detection [FireNet on Twitter](https://twitter.com/OlafenwaMoses/status/1163776222993801217?s=20) and I immedeiately showed it to shekhar and we agreed  we would do it when in our free 

time. 


## January 2020 

But project did not materialize due to personal emergency of mine  and we got allocated to different teams in the company. And it was january 

2020 i am adjusting to the new team and once again out of boredom i wanted to test some pretrained fire detection models. In free time i had converstaions with 

shekhar regarding product. He suggested to make a ppt about features we can add. Later we  decided product was not worth the cost the features we are providing etc.

It was bit long time back my memory was vague.

## June 2020

I got switched back to old team in march 2020 and reunited with **Shekhar,Sreeram,Aditya** and all. But CORONA happened  we went to lockdown and i came to my 

hometown. While i was doing evening walking i menitioned it to my dad about the project. He encouraged me try solo.

He had doubts that there were existing  cameras to do this , I tried to convince him otherwise.Again  anyway i was testing  again pretrained classification 

models for fire.But  with no success but one saturday morining  i tried Firenet from twitter on candle fire it was able to draw a box correctly on it from 8 feet 

distance.

![Firenet detection on candle](https://github.com/papasanimohansrinivas/papasanimohansrinivas.github.io/raw/master/images/08_08_2020_2.jpg). 

I was happy and started testing for fire detection from long distances and also for false positives like what will happen when you run object detection on a scene 

when  no fire is there. It failed in case of bedsheets when there are yellow or something.

![Firenet failure on bedhseets](https://github.com/papasanimohansrinivas/papasanimohansrinivas.github.io/raw/master/images/08_08_2020_1.jpg)

I started talking to my friends and family, one of them  **Jagadeeswar Reddy** suggested to test on different fire colours and materials.And his point was real world 

fire are different colours and textures .At the same time i was afraid  to try to train my own model and dropped the project for a while.


## September 2020

I got switched to different team and to some different work than regular deployment and i was ok with it.And when i was free on one saaurday afternoon and 

thinking i wanted to try to train latest state of the art Detr object detection on fire detection. Over the weekend i am able to train detr from facebook.I tested 

on the previous images of fire i collected . It failed like where yolo also failed. My dad is also helping here and there setting up the demo fire at home when 

ever necessary.In stead of sticking to the same model and i started to searching to other models to train . I was hit up with semi new model called efficientdet 

d0-d7. I spent some reaserch to get source code to train on the model.I trained the model efficientdet d0 , effiecient d3 with transfer learning freezing the 

backbone and also training the backbone too.


## October 2020

In october i started to mention project to  my close friend **Sai Bhargav** and he introduced me our college friend **vishwateja**.We discussed in length about 

deployment aspects and that dataset has to be large for the project.I have got a feeling that it would be a good time to discuss it with **Shekhar**










