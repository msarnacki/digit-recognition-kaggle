Digit recognition Kaggle challenge + my own function that takes photo from your drive and tells what digit is on it.

This is two part project:
-first is creating and training model that has to recognize digits. I made it using Yassine Ghouzam's kernel. Link: https://www.kaggle.com/yassineghouzam/introduction-to-cnn-keras-0-997-top-6. It is a great model and all credits go to Yassine Ghouzam.
-second part is me trying some new things with images in python. I ended up creating function that takes path to photo and model as arguments and returns digit that is on photo. It works pretty good, especially when photo is bright, there is good contrast between digit and background. Photo should preferably have similiar resolution to being square but work also with different types of resolution.
  
  I made also a GUI program with Python and Tkinter that uses this model and function. Here is link to repository:
