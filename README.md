# Fashion-Apparel-Classification-DL

![alt text](https://github.com/zenopereira/Fashion-Apparel-Classification-DL/blob/master/Fashion-Apparel-Clasification-DL-Project.png)

### Introduction
Clothing in many cultures reflects characteristics such as age, social status, lifestyle and gender. Apparel is also an important descriptor in identifying humans, e.g. ”the man wearing an orange hat” or ”the woman in red high heels.” Given the role of clothing apparel in society, ”fashion classification” has many applications. For example, predicting the clothing details in an unlabeled image can facilitate the discovery of the most similar fashion items in an e-commerce database. Similarly, classification of a user’s favorited fashion images can drive an automated fashion stylist, which would provide outfit recommendations based on the predicted style of a user. Real-time clothing recognition can be useful in the surveillance context, where information about individuals clothes can be used to identify crime suspects. Fashion classification also facilitates the automatic annotation of images with tags or descriptions related to clothing, allowing for improved information retrieval in settings such as social network users photos.

### Objective
The objective of this project is to detect what type of image the user uploads based on fashion types, it can be trousers, hats, etc. and the model should predict it right using some deep learning techniques

### Multiclass classification
Whether it’s spelled multi-class or multiclass, the science is the same. Multiclass image classification is a common task in computer vision, where we categorize an image into three or more classes. In our case we would be condisdering multiclass classification for 10 different classes namely:
* Goggles
* Hat
* Jacket
* Shirt
* Shoes
* Shorts
* T-Shirt
* Trouser
* Wallet
* Watch

### Trained using transfer learning
Transfer learning is one of the handiest tools to use if you’re working on any sort of image classification problem. With transfer learning, we basically try to exploit what has been learned in one task to improve generalization in another. We transfer the weights that a network has learned at “task A” to a new “task B.” The general idea is to use the knowledge a model has learned from a task with a lot of available labeled training data in a new task that doesn't have much data. Instead of starting the learning process from scratch, we start with patterns learned from solving a related task.In transfer learning, we try to transfer as much knowledge as possible from the previous task the model was trained on to the new task at hand. This knowledge can be in various forms depending on the problem and the data. Transfer learning has several benefits, but the main advantages are saving training time, better performance of neural networks (in most cases), and not needing a lot of data.
