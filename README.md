# Oral-Cancer-Detection
In this Project, we used the VGG19, ResNet50, and InceptionV3 architectures for our models. These architectures each stand for a unique method of deep learning and image recognition.

VGG19, which uses 19 layers to extract characteristics from pictures, is renowned for being both straightforward and efficient. Contrarily, ResNet50 introduces the idea of residual learning and makes deep network training simpler by permitting the inclusion of residual blocks. The inception modules in InceptionV3 are renowned for effectively allowing the network to collect multi-scale characteristics. When addressing a range of patterns inside photos, this architecture excels.

We made the decision to build an ensemble in order to improve the overall performance and resilience of our model. The predictions of several different models are combined in an ensemble model, which often improves accuracy and generalisation. In our example, we created an ensemble model to combine the benefits of VGG19, ResNet50, and InceptionV3.

The training weights of every individual model are combined to create an ensemble. Through this process, the ensemble model may take advantage of the various insights and knowledge that the three architectures have amassed. By doing this, we hoped to produce a model that was more reliable and accurate for the particular duties related to our project.
