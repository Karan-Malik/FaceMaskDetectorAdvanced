# Detection of a facemask in real-time using deep learning methods: Prevention of Covid 19

## Authors
Gautam Siddharth Kashyap, Karan Malik, Samar Wazir and  Alexander E. I. Brownlee

## Abstract
A health crisis is raging all over the world with the
rapid transmission of the novel-coronavirus disease(Covid-19).
Out of the guidelines issued by the World Health Organisation
(WHO) to protect us against Covid-19, wearing a facemask is the
most effective. Many countries have necessitated the wearing of
face masks, but monitoring a large number of people to ensure
that they are wearing masks in a crowded place is a challenging
task in itself. The novel-coronavirus disease(Covid-19) has
already affected our day-to-day life as well as world trade
movements. By the end of April 2021, the world has recorded
144,358,956 confirmed cases of novel-coronavirus disease(Covid19) including 3,066,113 deaths according to the world health
organization(WHO). These increasing numbers motivate
automated techniques for the detection of a facemask in real-time
scenarios for the prevention of Covid-19. We propose a technique
using deep learning that works for single and multiple people in a
frame recorded via webcam in still or in motion. We have also
experimented with our approach in night light. The accuracy of
our model is good compared to the other approaches in the
literature; ranging from 74% for multiple people in a nightlight
to 99% for a single person in daylight


## Link to dataset
Download the dataset using this [link](https://drive.google.com/drive/folders/1PRDC-x0wXQJ2xIG3qEcKaRELQ9KDpYB6?usp=sharing).

After downloading the folder FMD_data, place the folder in the same directory as the code. For checking the structure of the data, please go through 'sample_data' from the repo. 

## Conclusion and Future-scope
In this paper, we proposed a technique for detecting facemasks
in a real-time scenario using deep learning methods. We have
combined two datasets, as specified in the Dataset section. A
Convolutional Neural Network (CNN) was trained on 3
categories of images - namely correct_mask, incorrect_mask,
and without_mask. With 10 epochs, we achieved a training
accuracy of 98.9%. The testing accuracy came out to be
98.74% for the 293 images in our test set. The model was then integrated with Haar Cascade facial
detection using OpenCV for detecting facemasks in real-time.
The integrated system was tested with images and videos
having single and multiple people in both daylights as well as
a nightlight. The accuracy in these cases was approximate:
1. 99% for a single person in a frame in daylight
2. 98% for multiple people in a frame in daylight
3. 88% for a single person in a frame in nightlight
4. 74% for multiple people in a frame in nightlight

Our model is competitive with the other published techniques
in terms of accuracy. Moreover, our proposed technique is less
complex in structure and in working and gives faster results. It
can be easily integrated with CCTV cameras or in drones to
monitor a large number of people for identification of
facemask and prevention of Covid-19 and other airborne
diseases.
However, the accuracy of our model can be improved in
nightlight, possibly by using better quality cameras. Further, it
can be improved in identifying the types of masks that a
person is using and also to identify the color of the mask in the
real-time scenario
