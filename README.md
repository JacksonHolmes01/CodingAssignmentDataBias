# CodingAssignmentDataBias

This assignment required to download the Perspective API released by Google Jigsaw and create a hypothesis relating to the toxcicity score the API returns based off of written queries. My hypothesis was as follows: Starting the query with the action of an insult will result in a higher toxicity score than finishing the query with the action. Ex: " Leave, I don't like you" will be more toxic than "I don't like you, leave". Using 20 A queries, action first, and 20 B queries, insult first, I tested my hypothesis and not only aqquired the count of which query was more toxic but retruned the difference in toxicity between the queries and finally a total difference. My queries and results are as follows:


**Test Case 1**


Sentence A: You need to shut up, you are ugly

Sentence B: You are ugly, you need to shut up

Score of A: 0.8540474

Score of B: 0.85850734

Score of B is more toxic than Score of A by 0.00445993999999994 toxicity points

Total A = 0

Total B = 1


**Test Case 2**


Sentence A: Leave, I hate you

Sentence B: I hate you, leave

Score of A: 0.6989911

Score of B: 0.6827122

Score of A is more toxic than Score of B by 0.016278899999999985 toxicity points

Total A = 1

Total B = 1


**Test Case 3**


Sentence A: Get out of my sight, you are annoying

Sentence B: You are annoying, get out of my sight

Score of A: 0.51980776

Score of B: 0.5532103

Score of B is more toxic than Score of A by 0.03340254000000009 toxicity points

Total A = 1

Total B = 2


**Test Case 4**


Sentence A: Die, you are disgusting

Sentence B: You are disgusting, die

Score of A: 0.8778702

Score of B: 0.91625386

Score of B is more toxic than Score of A by 0.03838365999999993 toxicity points

Total A = 1

Total B = 3


**Test Case 5**


Sentence A: You are fired, because you are lazy

Sentence B: Because you are lazy, you are fired

Score of A: 0.51980776

Score of B: 0.46982017

Score of A is more toxic than Score of B by 0.04998758999999997 toxicity points

Total A = 2

Total B = 3


**Test Case 6**


Sentence A: Quit, you are stupid

Sentence B: You are stupid, quit

Score of A: 0.88599813

Score of B: 0.9029226

Score of B is more toxic than Score of A by 0.01692446999999997 toxicity points

Total A = 2

Total B = 4


**Test Case 7**


Sentence A: Shut up, you are ugly

Sentence B: You are ugly, shut up

Score of A: 0.8778702

Score of B: 0.88599813

Score of B is more toxic than Score of A by 0.008127930000000005 toxicity points

Total A = 2

Total B = 5

**Test Case 8**

Sentence A: Leave, you are the worst

Sentence B: You are the worst, leave

Score of A: 0.5532103

Score of B: 0.52811706

Score of A is more toxic than Score of B by 0.025093240000000017 toxicity points

Total A = 3

Total B = 5


**Test Case 9**


Sentence A: Run, you fat boy

Sentence B: You fat boy, run

Score of A: 0.64447093

Score of B: 0.62702215

Score of A is more toxic than Score of B by 0.017448780000000053 toxicity points

Total A = 4

Total B = 5


**Test Case 10**


Sentence A: You should die, you are disgusting

Sentence B: You are disgusting, you should die

Score of A: 0.9061063

Score of B: 0.9209984

Score of B is more toxic than Score of A by 0.014892099999999964 toxicity points

Total A = 4

Total B = 6

**Test Case 11**

Sentence A: Give up, you are worthless

Sentence B: You are worthless, give up

Score of A: 0.60254884

Score of B: 0.6308517

Score of B is more toxic than Score of A by 0.02830286000000004 toxicity points

Total A = 4

Total B = 7


**Test Case 12**


Sentence A: Die, you big baby

Sentence B: You big baby, Die

Score of A: 0.687436

Score of B: 0.76523775

Score of B is more toxic than Score of A by 0.07780175 toxicity points

Total A = 4

Total B = 8


**Test Case 13**


Sentence A: Die, I wish you were never born

Sentence B: I wish you were never born, Die

Score of A: 0.76523775

Score of B: 0.78711975

Score of B is more toxic than Score of A by 0.021881999999999957 toxicity points

Total A = 4

Total B = 9


**Test Case 14**


Sentence A: Run away, I wish you were never born

Sentence B: I wish you were never born, run away

Score of A: 0.6989911

Score of B: 0.6989911

Score of B is equally toxic of Score of A by 0.0 toxicity points

Total A = 4

Total B = 9

Equal = 1


**Test Case 15**


Sentence A: Piss off, you donut

Sentence B: You donut, piss off

Score of A: 0.76197964

Score of B: 0.7998551

Score of B is more toxic than Score of A by 0.03787546000000008 toxicity points

Total A = 4

Total B = 10

Equal = 1


**Test Case 16**


Sentence A: Piss off, you idiot

Sentence B: You idiot, piss off

Score of A: 0.9391453

Score of B: 0.9563754

Score of B is more toxic than Score of A by 0.017230100000000026 toxicity points

Total A = 4

Total B = 11

Equal = 1


**Test Case 17**


Sentence A: Piss off, you're worthless

Sentence B: You're worthless, piss off

Score of A: 0.8540474

Score of B: 0.8988238

Score of B is more toxic than Score of A by 0.04477639999999994 toxicity points

Total A = 4

Total B = 12

Equal = 1


**Test Case 18**


Sentence A: Go away, you're worthless

Sentence B: Your're worthless, go away

Score of A: 0.6426206

Score of B: 0.6611249

Score of B is more toxic than Score of A by 0.01850430000000003 toxicity points

Total A = 4

Total B = 13

Equal = 1


**Test Case 19**


Sentence A: You're fired, you lazy asshole

Sentence B: You lazy asshole, you're fired

Score of A: 0.9248995

Score of B: 0.9288007

Score of B is more toxic than Score of A by 0.003901200000000049 toxicity points

Total A = 4

Total B = 14

Equal = 1


**Test Case 20**


Sentence A: You're fired, you're lazy 

Sentence B: You're lazy, you're fired

Score of A: 0.49139655

Score of B: 0.50759226

Score of B is more toxic than Score of A by 0.01619571000000003 toxicity points

Total A = 4

Total B = 15

Equal = 1


**Results**


Total A = 4

Total B = 15

Equal = 1

The difference in the score of the times A was more toxic than B is: 0.10880851000000002

The difference in the score of the times B was more toxic than A is: 0.38266042000000006

# Conclusions from data

First and foremost throughout my experiment with this API, I discoveed that my hypothesis was incorrect and not by a close margin. The test and hypothesis was formatted to start the query with the action of an insult will result in a higher toxicity score than finishing the query with the action. Ex: " Leave, I don't like you", query A, will be more toxic than "I don't like you, leave", query B. The code in the test also calculated the difference between the toxicity score of the more toxic query and the less toxic one, and added that difference to the variable Difference of A or Difference of B.
When looking at the results of our 20 querys the end results are as follows, A was more toxic 4/20 times, B was more toxic 15/20 times, and 1/20 of the times the toxicity score was equal. In regards to the difference between the total difference varbles, when A was more toxic the total difference was .10808 and when B was more toxic the total difference was .382660 almost 1/4. The differnce between the times A was more toxic than when B was more toxic is also nearly 1/4, meaning when averaged out the difference when either query was more toxic compared to the other is almost equal. The API found that starting the query with the insult part of the insult was more toxic than starting it with the action of the insult. In the cases when the A query was found to be more toxic was often when the insult was found to be generally less toxic and the action was more subdued. For example, "Run, you fat boy" was found to be more toxic than "You fat boy, run". In the opposite case, when the insult was extreme, such as saying "you're worthless" and when the action was also considered more toxic, such as "die", the total toxicity score was often higher, and the query in which the insult came first (B) won every time. 
I think any bias in the model is present in the previous paragraph, why the model selected A over B or B over A. Bias in the model that would cause the results found in the demonstration would be present in what actions and what insults it considers toxic, such as considering "die" a more toxic action than "go to hell" despite some people considering otherwise. Despite my hypothesis being incorrect the more I look at the data and examine the queries I begin to match my perception of the toxicity of the queries the same way the API does, my theory behind this is the the creators of the API and the data its consumed also trend in the direction and interpretation I'm now leaning in. One question I still have regarding my results is why Sentence A: "Run away, I wish you were never born" and
Sentence B: "I wish you were never born, run away" are considered to be of equal toxicity. [
Score of A: 0.6989911.
Score of B: 0.6989911.
The Score of B is equally toxic of Score of A by 0.0 toxicity points ] In my opinion statement A registers as more toxic in my mind but I seem to have found a meeting point between the formats of the different queries according to the API, which makes me curious as to why these queries are considered equal according to the API. 
