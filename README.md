# Face-Detector
HaarCascade Based Implementation


Haar Cascade is a machine learning object detection algorithm used to identify objects in an image or video and based on the concept of ​​ features proposed by Paul Viola and Michael Jones in their paper "Rapid Object Detection using a Boosted Cascade of Simple Features" in 2001.

Link to paper :<a href = "https://www.researchgate.net/publication/3940582_Rapid_Object_Detection_using_a_Boosted_Cascade_of_Simple_Features"> Rapid Object Detection using a Boosted Cascade of Simple Features</a>

It is a machine learning based approach where a cascade function is trained from a lot of positive and negative images. It is then used to detect objects in other images.

In file HaarCascades, it contains face features and what we are doing is just extracting those features then training it on our labeled model and applying rectangular bounding boxes around it. From that we make a model and test it on our test dataset.

For saving computation time, we can also save the model and load it for testing.


### Acknowledgement

<a href ="http://www.willberger.org/cascade-haar-explained/">Will berger Blog </a>
