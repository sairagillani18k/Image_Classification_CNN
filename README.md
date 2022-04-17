# Image_Classification_CNN
Image classification by using CNN 

Will classify images of cats and dogs by using Sequential Model. Will import Sequential model from tensor flow. 

Step 1: Import all libraries 
Step 2: Download the data and unzip it and keep it in the same folder where your notebook is.
Step 3: Divide data a=in Train and test -- 2000 images are in train set and 200 in tets set
Step 4 : Reshape Data 
Step 5: Normalize data and bring them it in the range of 0 to 255
Step 6: Define Sequential Model - Conv 2D layer -- MaxPooling -- Conv2D -- MaxPooling -- Flatten -- Dense layer with 64 neurons-- Ouput layer with sigmoid and 1 neuron.
Step 7: Compile Model  -- Set loss function as Binary Cross Entropy , Adam Optimizer , accuracy metrics
Step 8: Model.fit
Step 9 :Model . Evaluate
Step 10:Make individual prediction on test data 




