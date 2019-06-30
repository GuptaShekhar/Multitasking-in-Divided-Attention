# Multitasking-in-Divided-Attention
### Attention
Attention, in psychology is the concentration of awareness on some phenomenon to the exclusion of other stimuli. Attention is best described as the sustained focus of cognitive resources on information while filtering or ignoring extraneous information.
#### Types of Attention
- Focused attention
- Sustained attention
- Selective attention
- Alternating attention
- Divided attention
## Divided Attention
Divided attention could be defined as our brain’s ability to attend to two different stimuli at the same time, and respond to the multiple demands of your surroundings. Divided attention is a type of simultaneous attention that allows us to process different information sources and successfully carry out multiple tasks at a time. When you divide your attention, the efficiency with which you do these actions is decreased, and you will almost certainly perform poorly. Interference is the term used to describe when a person has a hard time attending to two stimuli at a time. We see interference when the brain is only able to process a certain amount of information. However, cognitive training can help improve divided attention, and as a consequence, the ability to do more than one activity at a time.

### Attention Assessment
To measure divided attention,I attempt to formalize a method for analyzing one game which is designed to challenge player's ability to attend to multiple dimensions of stimuli simultaneously. I have created a game consisting of 3 tasks in which a user has to simultaneously response to all 3 tasks in a sequential order. This game runs for around 12 minutes.
In this test, given a randomly generated stimuli which keeps on changing and one to respond for the target stimuli. With help of this GUI, I have collected the data from several people.

In this work we have developed three distinct task which will have spatial identification test, color and number test (1.png), which will monitor the attention level by using visual effect and multi-tasking. 
###### Task 1
we try to measure the attention level of a user related to spatial movement of stimuli(2.png).
A user has to press the specified key at instant, the target stimuli occur. In this test, there is predefined input which will keeps on changing randomly at the time interval of 750 milliseconds. This whole process of test occur in order i.e., firstly angle determination test is done (task 1), then color selection test (task 2) and then number selection test (task 3) (Figure 3.1). Each test is of 3 seconds and this is repeated 20 times. If a user is unable to respond within that 6 seconds, either he missed it or unable to act, it will be considered as wrong outcome. If user is fast and smart enough to act decisively and press right key for that target stimuli, answer is recorded as true, otherwise false value is stored in database.
#### Proposed Algorithm
To classify the divided attention in 3 category namely Low, Average and High divided attention, we have applied the following steps after collecting the data:
- Remove the inconsistent data from dataset.
- Label the data based on the mean and standard deviation of the attention score.
- Apply machine learning model to classify the attention type (Low, Average, High).
- Analyze the output and trends in academic performance and divided attention.
