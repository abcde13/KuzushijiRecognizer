
## Plan of attack

 - [x] Do some exploratory analysis, so you can view any image and it's bounding boxes
 - [x] Setup fastai datablock api to read train/validation sets.
 - ~~[ ] Setup how to transform output of CNN into output for submission~~
 - ~~[ ] See how a simple RNN performs. Don't need online learning, so accuracy over speed.~~
 - ~~[ ] See where I am, rinse and repeat? Study more FastAI courses, see if I can improve this score~~
 - [x] Build an initial character recognition network from scratch, on subset
 - [x] Examine hooks network from scratch, see what is was looking for?
 - [x] Try to build a character recognition network for all chars
 - [ ] Build object recognition from subset
 - ~~[ ] With small object recognition model, classified boxes, then feed them into small character recognition model~~
 - [ ] Repeat for large model


The strikethroughs are inteded to show what I had PLANNED on doing, but as my learning evolved, so did my understanding
of what I wanted to do next

## Notebooks

*exploratory_analysis* takes a peek at the initial data, and renders a sample

*prepare_character_set* contains code for creating the dataset and exploring a 2 class cnn.

*character_recognizer* has a 10 class CNN

*character_recognzier_v2* has the full CNN for all Kuzushiji characters

*object_recognizer_v1* contains initial attempts to do full character object detection on a page