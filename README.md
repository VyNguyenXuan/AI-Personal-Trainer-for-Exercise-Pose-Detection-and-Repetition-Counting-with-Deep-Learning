# AI-Personal-Trainer-for-Exercise-Pose-Detection-and-Repetition-Counting-with-Deep-Learning
AI models (Yolov8 or Bi-LSTM ) with in built simple exercise error detection as well as repitition counting and a local web host
The team started this out as a project for university graduation but we are still working on this to try making it into a full app for such so the current 2 model might not be out final best result, anything can change
# Models
# 1.Bi-LSTM + Attention
To run this, it will require you to run the finallized-mediapipe-demo.ipynb to train a new weight depends on what exercise you want to train. Details on how to do so is included in the document.
Try to have fun with the frame sequence tinkering, our code set it to 30 frames based on our 5 exercises but depends on what exercises you picked , you can try it from 5/10/15/30/60/90, but generally as far as we can see , the training gets better on the lower side of the frame sequence

Run load.ipynb to put your weight file in and your video in, it should be able to run , do check out the comments made in code to avoid problems.
One thing to note is this code does not rely on GPU so if you want to hasten your work , you could improve this by having cuda for GPU activation for the code (this thing we are still working so we havent publish it yet).

# 2.Yolov8s
Same thing as the first model but now if you want to train, use the train_GGcolab.ipynb 
Note that is code DOES rely on GPU to run smoothly, so be careful with this.
