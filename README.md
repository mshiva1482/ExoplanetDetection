# Exoplanet Detection 
### Finding exoplanets using Machine Learning

Exoplanets are planets that orbit a star outside of our own solar system. We look for exoplanets in the hopes of finding life outside of our own solar system. They also help us better understand the phenomenon that occurs in our own planet/solar system like weather and other natural phenomena like Storms, volcanoes etc. Another reason why exoplanets are so important is that it may help us find planets that are similar to earth and may even be habitable.

The problem lies in the actual detection of exoplanets because they are quite difficult to detect. This makes obtaining other data about such planets like temperature, radius etc. seem almost impossible. This is mostly because these planets are very far away (anywhere from a few lightyears to hundreds of thousands of lightyears away from earth) and do not emit light on their own. The fact that planets do not emit light means that trying to photograph a planet that is far away is neither practical nor possible. The Kepler mission, however, was able to overcome this problem. We know that all planets revolve around a star. Moreover, any object/planet that isn’t part of a star system would anyway be inhabitable making it irrelevant to find. Stars on the other hand emit light that can be seen and detected from long distances. Kepler would observe these stars closely and look for small dips in brightness of those stars when one or more of its planet's transits in front of it. The intensity of dip in brightness can be used to measure various data regarding that planet (For example - larger dip in brightness would mean that the observed planet is quite large). Thus, with this data we can detect exoplanets and better understand the space around us.

### Working of the Algorithm
A stacking classifier has been used to create a more robust and effective predictor. Although it can be computationally expensive, it can produce high levels of accuracy. The stack we have chosen in our case is Random Forest classifier, which is also an ensemble learning technique that is essentially a combination of multiple decision tree models, and Gradient Boosting algorithm which is a functional gradient algorithm that, in order to minimise a loss function, repeatedly chooses a function that leads in the direction of a weak hypothesis or negative gradient.

### Algorithm Flowchart
<img src="https://user-images.githubusercontent.com/71997088/235063377-496c035f-fa44-487c-99e0-d2b2c7a63b50.png", width = "363", height="540"/>


### Stacking Classifier Flowchart
![Stacking Classifier Flowchart](https://user-images.githubusercontent.com/71997088/235063098-37a8a1c6-c784-4b81-a1e0-1b702d0b8812.png)
