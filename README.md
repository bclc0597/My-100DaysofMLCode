# 100-days-of-ML-code-challenge? - LOG
My #100DaysofMLCode?

## Day 0 : Jan 27 , 2020

**Initial thoughts** : Honestly I have no idea what im getting into and what this will turn out, I have always wanted to dig into machine learning and be good at this, but I always got distracted and never committed enough to really get things going on. Through some little pieces of efforts here and there, I have learned these myself online so far: CS50 - learned Python and C and other basic stuff; Andrew Ng's Machine Learning course, I actually completed the course and have a little notebook of the notes of everything I learned there (that frankly I am pretty proud of), FastAI: first 2 lessons and never really got further than that, I swear I have already done set up the Jupyter Notebook and Gcloud Instance environment a handful of times. Each time either something gets updated or it has been too damn long for me to remember how things work so I have to set things up all over again and again (which is what is happening right now). Now Im stuck again because I switched to a new computer and have never touched the things I should have been working on (FastAI & stuff) since September till now I guess.

**Expectations this time** : I guess the 100 days of ML challenge will be one attempt for me to get things going, I heard a great deal of gd things about this, I sincerely hope I can get this going and never look back. What I really want and hope to achieve: I want to be an expert/novice in machine learning, that I am good enough to at least know all the up-to-date techniques on different branch of ML and deep learning, I want to be good enough to be able to say one day, oh I should try work on this, decide on my own project, do it and get it to work whenever I want. There are already a list of things I have always dreamed of creating, e.g. a model that can play poker, one that can predict bet exchange price fluctuations, one that can have a decent rate of success of predicting stock market, one that predict the outcome of a race etc. Apart from responsibilities and my own schedule, I really hope this can become a habit that I feel compelled to do everyday, and I have by the end I will achieve at least something to my satisfaction. Also hopefully in this 100 days I will have done a project or 2 of my own.
 
**Today's Progress** : Not much I guess: reading the Github guide (I never actually knew how to use Github even tho I have had an account since like 2018), setting up this repo as a start (an alright start), tried to open up my old Gcloud instance Jupyter Notebook but failed, realised seems my new laptop (was gonna write has never been set up on the Gcloud thing), but then literally right at this moment as I was writing this page, I remember which terminal I had to use (Ubuntu), pasted the command to try and literally got it to work right now. I am already feeling much better about this lmao. That is a gd introduction day of some sort, but tmr is the real deal I guess, that only if I really start to work seriously tmr I can call that a great start.

**Thoughts** : I figured to really write down every bit of advice to myself that comes to my mind anytime that can motivate myself to work on this or improve the general efficiency of work progress here. Don't slack off this time u lazy fucker. 

Also found a page of 100DOMLC from a guy who proposed what u can study on each day, seems worth a peek everyday, link: https://github.com/Avik-Jain/100-Days-Of-ML-Code/blob/master/Code/Day%201_Data%20PreProcessing.md

**Advice of today** :
- literally no need to specify or think about how much effort Im gonna put in this time before starting to work, think oh 15 minutes or so would be fine first, and literally just do it
- "consistent efforts, however small, can help someone go a long way" - a random redditor

**Things to check out**: 
- the Deep Learning talk from Youtube, on the state of technology
- print notes of FastAI, get papers pictures whatever that may motivate u n stick it on the board to create a sort of work station
- email to ask for a chat with professor

**Expectation of tmr**: Do FastAI lesson 2 work (set up web app or something), maybe watch a bit of lesson 3 and of coz, update the 100DOMLC diary
- but first, clean your desk to even have a chance of making a proper work station


## Day 1 : Jan 28 , 2020

**Today's Progress** : After some 3 hours of efforts, I did my own dataset and trained my own resnet34 model for a tennis/badminton racket distinguisher, according to Lesson 2 of FastAI. Haven't really done the web app part with Render. Also cleaned my desk and printed something useful. Note: exported the weights and stuff into export.pkl, use this tmr for production.

**Thoughts** : Met with quite a few challenge with the codes, had some difficulties understanding certain terms and codes but I guessed it worked out. I guess a habit of research like looking at documentation and searching for answers online can go a long way.

**Questions**: how to statistically see the production results of my model, instead of just testing the model with pictures one at a time... **Is there a way to test my new model on the previous CV set?** Tried to see CV loss but learn.lr_finder() and learn.recorder.plot_loss() won't work anymore... (Learner Object has no attribute 'lr_finder'/'recorder') hmm...

**Expectation of tmr**: Finish the web app, and start learning of lesson 3 of FastAI


## Day 2 : Jan 29 , 2020

**Today's Progress** : Did the Render App thing, took a while to set up the accounts and web service. Still no answer to how to statistically see my model performance yet, even if its on my own CV set. Also watched half an hour of lesson 3, on multi-labels n stuff, a thing is the code on the lesson notebook has been updated and changed a bit and something Jeremy said in video is not there anymore, a bit confusing sometimes.

**Thoughts**: Lesson 4 is on tabular data, which is my primary interest! I wonder if its more difficult by having more different scenarios in different projects? The resnets for photo recognition seems to make image recognition quite easy already. Hope I can learn much from tabular data too, n hope its not that difficult.

**Expectation of tmr**: finish lesson 3 and maybe start working on it

## Day 3 : Jan 30 , 2020

**Today's Progress** : Did a bit more of lesson 3, found myself always pausing the video and checking the notebook and notes, I guess thats not problematic in a learning process (I hope), just finished planet satelite image part. Today was busy, had matches and stuff so didn't spend too much time on it
**Thoughts**: Jeremy compared his model performance to a Kaggle competition leaderboard, pretty cool, hope I can know how to do that soon and participate in Kaggle competitions with similar topic as those Im interested in. Also figured maybe learner.recorder.plot_losses() can see model loss on CV set plus training set? May solve yesterday's question in mind.

**Expectation of tmr**: for real, finish lesson 3 at least


## Day 4 : Jan 31 , 2020

**Today's Progress** : Finished lesson 3, introduced to a few concepts that I kinda know but not concretely, did diff image classifications such as image regression, segmentation etc, considering if i should try to do another little work on these topics, or should i just continue to lesson 4 and learn new things. Also learned that sigmoid function is already an outdated activation function, now we use Rectified Linear Unit most of the time for deep learning according to Jeremy.
**Thoughts**: Learned a cool website, neuralnetworksanddeeplearning.com, reading that page will definitely strengthen my understanding on the concept.

**Expectation of tmr**: consider if should work on lesson 3 or just continue watching lesson 4, hmm


## Day 5 : Feb 1 , 2020

**Today's Progress** : Did one hour of Lesson 4, reached the half way point for Part 1 of the course, now will dig deeper into the theories and structure. Accidentally deleted the cloud instance, all my notes lost T.T
**Thoughts**: Jeremy's idea on NN on tabular data is interesting, he said 90% of the time can use NN for Tab data. Pinterest is an example he said, less maintenance, less hand crafted feature too! The usual way of Tab data is by Logistic Regression/ XGBoost/ Random Forest. Also learned about AutoML, e.g. Jeremy used a Random Forest to predict his parameter on the result of his NLP learner, which is sick (even tho he is not a fan of AutoML)
**Expectation of tmr**: Finish Lesson 4 and see if theres work to follow


## Day 6 : Feb 2 , 2020

**Today's Progress** : Finished Lesson 4, plus half of Lesson 5
**Thoughts**: Things are getting difficult, Lesson 5 starts really going into the codes for the NN, we now supposedly already know how to do everything basics with codes, construct NN/update/forward/gradients/Momentum/matrix multiplication etc. There are many terms that I am not confident about, like what exactly collaborative filtering is about, vector embedding, one hot encoding, how matrix multiplication really whats (is knowing the dimension of outcomes enough?) and many more. Jeremy suggest already try applying these knowledges to solve SGD of Lesson 2 and MNIST of Lesson 5, if I can figure that all out I think that will be a good start for real.
**Expectation of tmr**: Finish lesson 5 and understand it by doing some work on it.


## Day 7 : Feb 3 , 2020

**Today's Progress** : Finished Lesson 5, also bc many things r covered I revisited Lesson 4 & 5 from NN structure, collab filtering to tabular, kinda figured out what embedding really is, have some understanding of the terms now
**Thoughts**: Yet to know and apply whats learned, the codes still look scary and complex, looks like need tons of documentation and debugging when implementing. But lets try implementing the stuff on tab data and also SGD Lesson 2. Is it possible to start doing some tabular data little projects already?
**Expectation of tmr**: Built NN module or use Optim Pytorch module to implement SGD Lesson 2 and maybe Lesson 5

## Day 8 : Feb 4 , 2020

**Today's Progress** : Revisited Lesson 5, listened to the lessons again with the printed jupyter notebooks. Understand how the lesson 5 different ways of constructing a NN works now, even though when I try to implement that to Lesson 2 simple GD, some difficulties happen with the data compatibility.
**Thoughts**: Structure of data seems diverse, need diff structure to do diff ways. numpy(), tensor() etc... Shd I try use different things on MNIST Lesson 5 tmr? Also maybe the machine learning course for coders from Jeremy will help know more about creating compatible databunch?
**Expectation of tmr**: Decide to do work on Lesson 5 MNIST or not, then start Lesson 6

## Day 9 : Feb 5 , 2020

**Today's Progress** : Done half an hour of lesson 6, many terms and little tricks introduced so progress isnt fast
**Thoughts**: Data pre-processing is not a subject of this course, need to go to Machine Learning for Coders course by Jeremy. I guess this might also answer my doubts on data formats and preparation. Good candidate for next course to study, (or fastai part 2?) Also tabular data seems to have the most basic NN architecture. Also learned about time series, Jeremy said most of the time the state-of-the-art ways to deal with it is to create metadata relating to the Time, so NN will consider them, interesting and less complicated than I imagine.
**Expectation of tmr**: Do more of lesson 6, if not all of it


## Day 10 : Feb 6 , 2020

**Today's Progress** : Done half of lesson 6, new terms again, mainly on newer ideas of regularization: batch normalization, data augmentation and dropout, will learn more about CNN next half
**Thoughts**: I discovered that many newly researched/invented techniques are implemented into fastai libraries already, which means using that we can already make decent models with decent results if we know how. Probably should start machine learning for coders by Jeremy too after this course? Deep Learning Specialization uses tensorflow which seems will soon be replaced, hmm...
Also my focus & efficiency drops significantly when lacking sleep, should get enough sleep everyday.
**Expectation of tmr**: Finish lesson 6
