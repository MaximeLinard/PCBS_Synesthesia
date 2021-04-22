# PCBS_Synesthesia

The purpose of this experiment is to test numerical synesthesia (which is a subphenomenon of synesthesia (https://fr.wikipedia.org/wiki/Synesth%C3%A9sie)).

When a non-synesthetic person looks at a grid filled with "5" among which there is a "2", it is difficult for him to identify it quickly.
However, for a person that have numerical synesthesia, the "2" can stand out much more clearly.

![image](https://user-images.githubusercontent.com/81753348/113288865-c67f4280-92ef-11eb-886f-31df559a3251.png)

I would like to try to program an experiment measuring the response time (time it takes a subject to see the "2" of all the "5") for various panels.

![image](https://user-images.githubusercontent.com/81753348/114065035-85ac9e00-989a-11eb-992c-fddda87ea725.png)

My prediction is that the RTs of people that have numeric synesthesia will be lower than other people RTs.
In order to avoid cheating (press SPACEBAR as soon as the participant see a pannel), ther are pannels without "5". (It's possible to set the number of pannels that present a "5" and the number of total pannels, for the demo it's only 8 on 10.)

Planning :

01/04 : V : Project creation

06/04 : V : Fixation Cross

08/04 : V : Stimulus apparition after a certain time + Press space bar to go on the next trial + RT measurement (list + mean + std) + Instruction pannel

15/04 : V : Random pannels creation 

22/04 : V : Set the definitive parameters of the experiement and make code adjustements for efficiency and intelligibility

Precision on the code :

- Finally I choose to make the participant look for a "5" in a pannel of "2" because to me it was more difficult (I had bigger RTs).
- The fixation cross has a random time of apparition in order to avoid habituation on the task.
- When there is a five on the pannel there is a Maximum delay (set to 4000 ms) after what if the praticipant didn't press the SPACEBAR is RT for the trial is the Maximum delay and the next trial start.
- When there is no five, the participant should not press the button. If the button is pressed, the RT is not recorded.  So if we have x trials with a five presented we will have a list of x RT. 
- The mean and standard deviation of each session is then printed, if I have time, I will code for an automatic saving of the data.

