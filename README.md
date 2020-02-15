# H8_PTP_Final_Image

In this notebook Project we try to solve simple Machine learning problem classificatin for Cats and Dogs
with 3 approching 

1. Create Machine Learning model from scratch ,here we create 3 block convo model to training the dataset dan predict the dataset test with re-use model

2. Create Machine learning model with utilise Application feature from Keras Tensorflow, here we re-use VGG16 model and then predict the dataset test with re-use model

3. Create Machine learnin model with utilise T-Hub feature from tensorflow. we use efficiennte model 


from above we can summary 
1. T-Hub is fastest way to find high accuracy and small training time, and also small memory consume, you can see the validity_accuracy with T-hub about 0.96 and around.

2. Application Feature is faster than our 3 block convo model. since its has optimum value of weight and the amout of training parameter is smaller than out 3 block convo model and this is the reason why make time training is relatif fast than 3 block convo model, from notebook you can see the validity_accuracy about 0.89

3. our 3 block convo model actually is good, but the training time and memory consume are higer than another approaching way.

but overall we can use all of them, depend on the capacity of dataset, memory and time training
