# MobilenetLearningCurves
The Repo contains the training history of Mobilenet pretained model that was developed for a image classification problem.
The Learning curves clearly shows its overfitting. What kind of finetuning can be done to improve the model results?
model.compile(optimizer=Adam(lr=0.0001), loss='categorical_crossentropy', metrics=['accuracy'])
I ran 20 Epochs for CPU(shows better results than GPU for real time predictions)
40 Epochs for GPU(TeslaV100)
