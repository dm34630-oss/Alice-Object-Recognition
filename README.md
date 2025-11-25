# Alice-Object-Recognition
An object recognition software inspired by KAYA Vision Cameras. This software can currently detect 60 objects, and requires 2 different webcams to successfully run. This uses a partial custom made LLM I've been working on called AL1-TP1, also known as Alice. (COCO also helped with this creation too, I did end up ripping a small piece of the code from there.) IF you want to load a custom model, you'll need to train it and import it into TF.js

# HOW TO USE
Go into a basic HTML environment and start the code. Make sure you are in an area with good lighting, as it cannot detect things within the dark as of this current version. Start and switch to one of your webcams, and it should work. If it doesn't, the most likely problem is that the model hasn't loaded yet, you can view the status by looking at the text next to the webcam. If it says "loading", wait 10-30 seconds. If it gives you an error, refresh. You can also insert images, it cannot detect gifs yet.

(For school project, co.lab Exhibition)
