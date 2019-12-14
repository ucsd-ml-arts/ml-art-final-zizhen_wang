# Final Project

Zizhen, ziw142@ucsd.edu

## Abstract Proposal

- My idea is from a movie called “Loving Vincent” which is an experimental animated biographical drama film. Each of the film's 65,000 frames is an oil painting on canvas, using the same technique as Van Gogh, created by a team of over 100 painters.[1] 
- ![](https://github.com/ucsd-ml-arts/ml-art-final-zizhen_wang/blob/master/vincent%20(2).jpg)
- I started to think I could generated a film by using style transfer to get the same effort. There are two reasons I choose Art Nouveau as my style transfer. Based on my project 3, I generated 14 different art style of modern arts, and Art Nouveau style generated result is my favorite one and also I think is one of successful results. Modern art includes artistic works produced during the period extending roughly from the 1860s to the 1970s, and denotes the style and philosophy of the art produced during that era. The term is usually associated with art in which the traditions of the past have been thrown aside in a spirit of experimentation. Modern artists experimented with new ways of seeing and with fresh ideas about the nature of materials and functions of art. A tendency away from the narrative, which was characteristic for the traditional arts, toward abstraction is characteristic of much modern art.[2] Modern artists experimented with new ways of seeing and with fresh ideas about the nature of materials and functions of art. This ideology is the same as that this course wants us to learn which is we need to use new things (machine learning) to generate new art works to insist on this spirit. Art Nouveau is one of representative styles in modern arts which were a sense of dynamism and movement, often given by asymmetry or "whiplash" curves, and the use of modern materials to create unusual forms and larger open spaces. It was often inspired by natural forms such as the sinuous curves of plants and flowers. The second reason is the storyline of this film Chungking Express. Every day, Cop 223 (Takeshi Kaneshiro) buys a can of pineapple with an expiration date of May 1, symbolizing the day he'll get over his lost love.[3] By his encounter with an Asian woman wearing a trench coat and a blond wig(Brigitte Lin),  he is instantly attracted, oblivious of the fact she's a drug dealer. Originally thinking that everything in "love" had a shelf life, he unexpectedly ushered in a short warmth of soul. The scene I picked showed they were relying on each other in the bar at the first night even though they are strangers.  I wanted to use the sense of dynamism and movement from Art Nouveau to show the warmth and the shortness.![](https://github.com/ucsd-ml-arts/ml-art-final-zizhen_wang/blob/master/content.jpg)![](https://github.com/ucsd-ml-arts/ml-art-final-zizhen_wang/blob/master/Art%20Nouveau_result.png)



## Project Report

- See ECE188_final.pdf [ECE188_final.pdf](https://github.com/ucsd-ml-arts/ml-art-final-zizhen_wang/blob/master/ECE188_final.pdf)

## Model/Data
- Content: one 11 second video cutting from the film Chungking Express by Wong Kar-wai https://drive.google.com/file/d/1gyJaZ2K49fw2qia3kkyq94DYDlxWLV0v/view?usp=sharing
- sytle: Art Nouveau       Femme a Marguerite   by Alphonse Mucha
- moduel: Style Transfer; Deep Dream; Ebsynth


## Code
- Jupyter notebooks: style_transfer_keras.ipynb [style_transfer_keras.ipynb](https://github.com/ucsd-ml-arts/generative-visual-zizhen-w/blob/master/style_transfer_keras.ipynb)
- Jupyter notebooks: dream.ipynb [dream.ipynb](https://github.com/ucsd-ml-arts/ml-art-final-zizhen_wang/blob/master/dream.ipynb)
- Ebsynth download: vswhere.exe and vcvarsall.bat and any set up for system. Or can download on the website: https://ebsynth.com/



## Results
- Test 3 Deep Dream:
https://drive.google.com/file/d/1vAeVPPLNpkl-RMFHOhaj3KR0Ik7b3HzW/view?usp=sharing
- Test 4 Style transfer:
https://drive.google.com/file/d/1UK9WICYDjbUX7H7aq1QlQTxmidVZhj5k/view?usp=sharing

We will see the deep dream video: the whole color is brighter and background is more clear. Also characters’ face details are more clear. However, the color difference and shadow is not good especially when the face moving, the color looks like a little bit strange.
The style transfer: the color difference is more intense and also character motion is much more smooth than deep dream. However, it lost more details such as the shape and emotions, but I like this one because it would be more close to the Art Nouveau which showed natural forms such as the sinuous curves of plants and flowers to express the warmth. Therefore, I picked up Test 4 as my final result.


## Technical Notes



## Reference
- Reference
- [1]https://en.wikipedia.org/wiki/Loving_Vincent
- [2]https://en.wikipedia.org/wiki/Art_Nouveau
- [3]https://www.imdb.com/title/tt0109424/plotsummary
- [4]https://medium.com/tensorflow/neural-style-transfer-creating-art-with-deep-learning-using-tf-keras-and-eager-execution-7d541ac31398
- [5]https://keras.io/applications/#vgg19
- [6]https://gombru.github.io/2019/01/14/miro_styletransfer_deepdream/
- [7]Stabilizing neural style-transfer for video https://medium.com/element-ai-research-lab/stabilizing-neural-style-transfer-for-video-62675e203e42
- [8]https://zeruniverse.github.io/fast-artistic-videos/
- [9]https://towardsdatascience.com/real-time-video-neural-style-transfer-9f6f84590832
- [10]https://dcgi.fel.cvut.cz/home/sykorad/ebsynth.html
- [11]https://github.com/jamriska/ebsynth


