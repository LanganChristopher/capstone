# Capstone Project - ASL Alphabet CNN (Keras) Classification

American Sign Language (ASL) is a fascinating language used by many deaf, hard-of-hearing, and hearing individuals throughout the United States and other locations as well. I will be creating a Convolutional Neural Network model to accurately understand static images of the ASL alphabet. The beauty of ASL is that it is a visual language that includes 5 parameters to express the language through conversations, lectures, music, poetry, etc. The 5 parameters are handshapes, motion/movement, palm orientation, location and non-maunal markers (facial-expression). 

---

## Christopher Langan
<ul>
    <li><a target=_blank href="https://www.linkedin.com/in/langanchristopher7/">LinkedIn</a></li>
    <li><a target=_blank href="https://github.com/LanganChristopher">GitHub</a></li>
    <li><a target=_blank href="https://langanchristopher.github.io/">Portfolio</a></li>
    <li><a target=_blank href="https://medium.com/@langan.christopher7">Medium</a></li>
</ul>


---

# Problem Statement

Any type of sign language is a major necessity for access to communication for anyone that is deaf or hard of hearing. How can we create a model that can interpret American Sign Language static gestures, specifically the alphabet and accurately pin-point the correct letter? Can we bridge the gap between the deaf/hard of hearing individuals with hearing individuals? Is creating a model for the alphabet enough?    

<a target=_blank href="https://www.csd.org/about/statistics/">The facts of deaf/hard of hearing individuals and sign language.</a>

# Data

The data set I will be using is from <a target=_blank href="https://www.kaggle.com/grassknoted/asl-alphabet">Kaggle</a> and it is a collection of images from the alphabet of American Sign Language, separated into 29 classes. The 26 classes of the 29 are the letters from A-Z, and the other 3 classes are for <u>Space</u>, <u>Delete</u>, <u>Nothing</u>, this will help with our modeling.
The data set consists of 87,000 images in the training set, with 3,000 in each class and the testing set with 28 images with one of each class except <u>Delete</u>.

# Model Performance

Train Accuracy: 92.73%
Train Loss: 20.72%
Train Validation Accuracy: 97.84%
Train Validation Loss: 7.62%
Test Accuracy: 98.05%
Test Loss: 7.28%

# Conclusion/Recommendations

We use the Convolutional Neural Network modeling technique because it is one of the more well defined modeling methods for images.

The model has been able to accurately understand each letter of the alphabet. It is only the beginning of a long process to create something that can bridge the gap between people who can not hear and those who can through the use of American Sign Language. Creating a model for only the alphabet of ASL is not enough, considering it doesn't take into account numbers, words, full sentences, etc. 

A recommendation I would work towards is a different set of data. If I had the time, I would take the photos myself and ask others to sign the alphabet. I would take into consideration lighting to help with the modeling and many people's skin tone. However some of the letters from the data set I used isn't to the standards of the Deaf/Hard of Hearing community, like the letter 'f'. For the most part the data is generally ok, but if I could assume, the person that created the data set isn't deaf himself or not immerse in the Deaf/Hard of Hearing culture.

# What's Next?

The few next steps we could take are:
    Include numbers into our data. (The beauty of numbers is that we can sign numbers 0-999 with 1 hand.)
    Add in a data set full of words from basic to extreme words.
    Create a NLP model with the words data set. (1 sign could mean 5 different words, could be both a pos/neg thing)
    Make sure the parameters for that is able to pin point the context of the sentence.
    I would also want to create a model that specifically focus on each of the 5 ASL parameters to be even more accurate. 
    Such as:
        1.) Handshape
        2.) Movement
        3.) Palm Orientation
        4.) Location
        5.) Non-Manual Markers (Facial Expression)

The big goal is to be able to create an extremely accurate model to use as a backend for an phone app or some kind of camera that can provide real time American Sign Language closed captioning translation. Eventually reaching all sign language across the globe.

# Resources

<ul>
    <li><a target=_blank href="https://prezi.com/p/xzv2bimw7_z3/sign-language-using-machine-learning-and-nlp/">ASL Prezi Presentation</a></li>
    <li><a target=_blank href="https://arxiv.org/pdf/1812.01053.pdf">Large Scale Data and ASL Article</a></li>
    <li><a target=_blank href="https://arxiv.org/pdf/1811.11436.pdf">Sign Language Translation based on Human Keypoint Artible</a></li>
    <li><a target=_blank href="https://arxiv.org/pdf/1710.06836.pdf">Using Deep Convolutional Networks for
Gesture Recognition in American Sign Language Article</a></li>
    <li><a target=_blank href="https://arxiv.org/pdf/1801.10111.pdf">Video-based Sign Language Recognition Article</a></li>
    <li><a target=_blank href="https://medium.freecodecamp.org/weekend-projects-sign-language-and-static-gesture-recognition-using-scikit-learn-60813d600e79">Sign Language and Static Gesture Recognition with Scikit Learn Article</a></li>
</ul>


# Acknowledgments
<ul>
    <li><a target=_blank href="https://www.kaggle.com/dsilvadeepal/asl-alphabet-classification-with-cnn-keras">Kaggle 1</a></li>
    <li><a target=_blank href="https://www.kaggle.com/fegadeharish/asl-recognition-using-deep-learning">Kaggle 2</a></li>
    <li><a target=_blank href="https://www.kaggle.com/billy1624/asl-alphabet-classification">Kaggle 3</a></li>
    <li><a target=_blank href="https://www.kaggle.com/ayuraj/asl-recognizer">Kaggle 4</a></li>
    <li><a target=_blank href="https://www.kaggle.com/gargimaheshwari/asl-recognition-with-deep-learning">Kaggle 5</a></li>
</ul>

Inspiration: Do you know what they are saying?

