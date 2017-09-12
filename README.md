# ArtificialIntelligence, MachineLearning, DeepLearning, CoreML, ARKit, IOT 

Described Info about Machine learning &amp; Artificial Intelligence in very simple way.



## Let's start with Machine learning

In short, machine learning algorithms are algorithms that learn (often predictive) models from data. I.e., instead of formulating "rules" manually, a machine learning algorithm will learn the model for you.


<br>
<img height="700" src="https://github.com/mukeshlokare/ImagesFiles/blob/master/ml1.png"/>
<br>

So, let me give you an example to illustrate what that means! Say you are interested in implementing a spam filter. The probably most conservative approach would be to let a person sort these emails manually. Now, the "traditional" programming approach would be to look at some example emails (and/or use your "domain knowledge") to come up with a chain of rules like

"if this email contains word X, label it as spam, else if email contains ..."

Now,  machine learning algorithms help you formulating these rules. Or in other words, (supervised) machine learning algorithms will look at a dataset of labeled emails (spam and non-spam) and derive rules from there to separate the two classes.

### So, what is Data Science then?

First of all, data science is a pretty ambiguous, ill-defined term and interdisciplinary field; and people mean (expect) different things in different contexts. In my opinion, in practice, data science is pretty much the same as what we've known as data mining or KDD (Knowledge Discovery in Databases). The typical skills of a data scientists are

* Computer science: programming, hardware understanding, etc.
* Math: Linear algebra, calculus, statistics
* Communication: visualization and presentation
* Domain knowledge


Where machine learning -- at its core -- is about the use and development of these learning algorithms, data science is more about the extraction of knowledge from data to answer particular question or solve particular problems.

Machine learning is often a big part of a "data science" project, e.g., it is often heavily used for exploratory analysis and discovery (clustering algorithms) and building predictive models (supervised learning algorithms). However, in data science, you often also worry about the collection, wrangling, and cleaning of your data (i.e., data engineering), and eventually, you want to draw conclusions from your data that help you solve a particular problem.

There are numerous examples of data science applications. Assume you are working for a credit company. Your boss gives you the task to find out whether a customer is creditworthy or not. You collect transaction data, maybe shipping records and customer ratings and so forth. Next, you'll probably use a machine learning algorithm to learn a predictive model. For example, let's assume you chose to grow a decision tree, and you concluded that this particular customer is not creditworthy. Finally, you prepare a nice presentation visualizing the decision tree to answer your boss' next question: Why is this customer not creditworthy..

### Diffrence between AI & Machine learning

Artificial Intelligence (AI) and Machine Learning (ML) are two very hot buzzwords right now, and often seem to be used interchangeably.

They are not quite the same thing, but the perception that they are can sometimes lead to some confusion. So I thought it would be worth writing a piece to explain the difference.

Both terms crop up very frequently when the topic is Big Data, analytics, and the broader waves of technological change which are sweeping through our world.

#### In short, the best answer is that:

Artificial Intelligence is the broader concept of machines being able to carry out tasks in a way that we would consider “smart”.

&,

Machine Learning is a current application of AI based around the idea that we should really just be able to give machines access to data and let them learn for themselves.


### Deep learning

You can think of deep learning, machine learning and artificial intelligence as a set of Russian dolls nested within each other, beginning with the smallest and working out. Deep learning is a subset of machine learning, which is a subset of AI.

Deep artificial neural networks are a set of algorithms setting new records in accuracy for many important problems, such as image recognition, sound recognition, recommender systems, etc.



### CoreML

Core ML is the foundation for domain-specific frameworks and functionality. Core ML supports Vision for image analysis, Foundation for natural language processing (for example, the 
NSLinguisticTagger
 class), and GameplayKit for evaluating learned decision trees. Core ML itself builds on top of low-level primitives like Accelerate and BNNS, as well as Metal Performance Shaders.
 
 <br>
<img height="150" src="https://github.com/mukeshlokare/ImagesFiles/blob/master/COREML1.png"/>
<br>
 

### ArKit

In iOS 11 introduces ARKit, a new framework that allows you to easily create unparalleled augmented reality experiences for iPhone and iPad. By blending digital objects and information with the environment around you, ARKit takes apps beyond the screen, freeing them to interact with the real world in entirely new ways.

#### What is argumented reality

ARKit provides a cutting-edge platform for developing augmented reality (AR) apps for iPhone and iPad. Get introduced to the ARKit framework and learn about harnessing its powerful capabilities for positional tracking and scene understanding. Tap into its seamless integration with SceneKit and SpriteKit, and understand how to take direct control over rendering with Metal 2.

- Argumented reality WWDC 2017 - Session : https://developer.apple.com/videos/play/wwdc2017/602/


Augmented reality (AR) describes user experiences that add 2D or 3D elements to the live view from a device's camera in a way that makes those elements appear to inhabit the real world. ARKit combines device motion tracking, camera scene capture, advanced scene processing, and display conveniences to simplify the task of building an AR experience.


#### Important in ArKit

* ARKit requires an iOS device with an A9 or later processor.
* To make your app available only on devices supporting ARKit, use the arkit key in the UIRequiredDeviceCapabilities section of your app's Info.plist. If augmented reality is a secondary feature of your app, use the isSupported property to determine whether the current device supports the session configuration you want to use.


### IOT

The Internet of Things (IoT) is a system of interrelated computing devices, mechanical and digital machines, objects, animals or people that are provided with unique identifiers and the ability to transfer data over a network without requiring human-to-human or human-to-computer interaction.

#### Paradigm:

The ‘thing’ in IoT could be a person with a heart monitor or an automobile with built-in-sensors, i.e. objects that have been assigned an IP address and have the ability to collect and transfer data over a network without manual assistance or intervention. The embedded technology in the objects helps them to interact with internal states or the external environment

oT platforms can help organizations reduce cost through improved process efficiency, asset utilization and productivity. With improved tracking of devices/objects using sensors and connectivity, they can benefit from real-time insights and analytics, which would help them make smarter decisions.

### Some extra ----- What is logistics :

 Quest to re-imagine how the world moves things.Logistics impacts every aspect of our daily lives, and yet technology in the logistic market is still archaic, resulting in billions of dollars of inefficiency and missed opportunities.
 
 - Logistics: http://www.transparencymarketresearch.com/logistics-market.html


### Following are some Machine Learning tutorial by me,

- CoreML: https://github.com/mukeshlokare/CoreMLSampleDemo


