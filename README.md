# TV Script Generation

In this project, we generate our own [Simpsons](https://en.wikipedia.org/wiki/The_Simpsons) TV scripts using RNNs. We are using part of the [Simpsons dataset](https://www.kaggle.com/wcukierski/the-simpsons-by-the-data) of scripts from 27 seasons. The Neural Network we build will generate a new TV script for a scene at [Moe's Tavern](https://simpsonswiki.com/wiki/Moe's_Tavern).

## Dataset 
The original data set is downloaded from the [Simpsons dataset](https://www.kaggle.com/wcukierski/the-simpsons-by-the-data) of scripts from 27 seasons. It contains:

```
Roughly the number of unique words: 11492
Number of scenes: 262
Average number of sentences in each scene: 15.248091603053435
Number of lines: 4257
Average number of words in each line: 11.50434578341555
```

## Generated script 

Here is an example that the RNN model generated after training 60 epochs (it achieved training loss 0.165). The prime word is `moe_szyslak`

```
moe_szyslak: ah, she got homesick for her old life, diving for tourist pennies in a micronesian swamp.
homer_simpson: oh, cold shoulder, right! andalay!
moe_szyslak:(too big) hanh?!!!
all:(ad lib) oh, sweet mother fat tony.


moe_szyslak:(sighs) i think
barney_gumble: uh-oh. my wife was the last of the family-owned teams.
lenny_leonard: i tried to return my season ticket, but they wouldn't an day, ever will the pigs.
wayne: i'm really more like me, and get to dinner.
walther_hotenhoffer: nein... nein... nein... nein... nein... we got the cash. my clientele-- let it ring; /mr. plow is a ticket. my wife is, moe. i don't know nothin' about how i do anything.
moe_szyslak: i had to get edna out of springfield, and that's it?
moe_szyslak: no, i tells ya, homer.
homer_simpson:(looking at watch)
```

## Getting Started 

1. Clone the repository and navigate to the downloaded folder.
```	
https://github.com/TetsumichiUmada/tv_script_generation.git
cd tv_script_generation
```

2. Install required packages. 

```
pip install -r requirements.txt
```

3. Open the notebook.
```
jupyter notebook tv_script_generation.ipynb
```

## Acknowledgments
* [Udacity Deep Learning Nanodegree Program](https://www.udacity.com/course/deep-learning-nanodegree--nd101)
