# CPS rebrand copy 

## Concepts

### Decision support systems 

##### Workflow automation/process automation 

Explanation here

https://www.mckinsey.com/business-functions/digital-mckinsey/our-insights/intelligent-process-automation-the-engine-at-the-core-of-the-next-generation-operating-model



http://taxexecutive.org/bots-natural-language-processing-and-machine-learning/



https://www.comindware.com/blog-complete-basics-workflow-automation/



#### 



## Pages 

### Natural language processing

#### Definition

The use of computer algorithms to parse natural languages. 

Alternate: The application of computational techniques to the analysis and synthesis of natural language and speech. AKA: The use of different techniques from computer science (algorithms) to understand and manipulate human language and speech.

Alternate: The science of extracting meaning and learning from text data

- a sub-field of Artificial Intelligence focused on enabling computers to understand and process human languages, to get computers to a human-level understanding of language. Computers can't yet "read between the lines" to understand what the language is really trying to say. They don't have intuitive understanding of natural language. 
- Now, deep learning and recent advances in machine learning has enabled us to write programs to perform things like language translation, semantic understanding and text summarization. All these add value, making it easy to understand and perform computations on large text blocks without manual effort 

https://towardsdatascience.com/an-easy-introduction-to-natural-language-processing-b1e2801291c1

- NLP plays a critical role in supporting machine-human interactions (Source: https://becominghuman.ai/a-simple-introduction-to-natural-language-processing-ea66a1747b32)



#### Practical uses/applications

- Identifying different cohorts of users/customers (e.g. predicting churn, lifetime value, product preferences)

- Accurately  detecting and extracting different categories of feedback (positive and  negative reviews/opinions, mentions of particular attributes such as  clothing size/fit…)

- Classifying text according to intent (e.g. request for basic help, urgent problem)

  Source: https://blog.insightdatascience.com/how-to-solve-90-of-nlp-problems-a-step-by-step-guide-fda605278e4e

- Other applications include translation, chat bots and specific intricate analyses of text documents. Much of this is done using deep learning, specifically Recurrent Neural Networks (RNNs) and Long-Short Term Memory (LSTMs) networks - Source: https://towardsdatascience.com/an-easy-introduction-to-natural-language-processing-b1e2801291c1

- Language translations apps such as Google Translate; Word processors such as Microsoft Word and Grammarly that employ NLP to check grammatical accuracy of texts; interactive voice response apps used in call centers to respond to user requests; personal assistant apps such as OK Google, Siri, Cortana and Alexa (Source: https://becominghuman.ai/a-simple-introduction-to-natural-language-processing-ea66a1747b32)

#### Challenges

https://www.quora.com/What-are-the-major-open-problems-in-natural-language-understanding

- Ambiguity 
  Words are unique but can have different meanings depending on the context in which they are being evaluated, resulting in ambiguity. 
  	Lexical ambiguity 
  	Syntactic ambiguity
  	Semantic ambiguity
- Synonymy 
  We can express the same idea with different terms - e.g. the word "fine".
- Syntax 
  The structure of natural language takes into account several rules but also some irregularities in different cases. Sentences can be ordered in different ways but not every ordering of items is valid.
- Coherence
  We make coherence assumptions, which affect our interpretation
  e.g.: John likes Bill. He gave him an expensive Christmas present (Explanation or justification?)
- Coreference resolution
  The process of linking together mentions that relates to real-world entities.



#### Resources

- https://towardsdatascience.com/an-easy-introduction-to-natural-language-processing-b1e2801291c1
- https://becominghuman.ai/a-simple-introduction-to-natural-language-processing-ea66a1747b32
- https://www.digitalistmag.com/digital-economy/2017/02/20/simple-introduction-to-natural-language-processing-04906091
- https://spacy.io/api/doc
- https://docs.readthedocs.io/en/latest/intro/getting-started-with-sphinx.html
- https://textacy.readthedocs.io/en/latest/





#### CPS

A tool to help alleviate document processing bottleneck. In situations where people are doing tedious work on documents, natural language processing can help automate parts of the process so employees can work more efficiently (?)

We can do various work that requires interacting with natural language sources.

- Sentiment analysis
- Chatbots
- Document categorization
- Triage systems

We understand the underlying basic algorithms that are used in this  area which gives us an advantage in selecting algorithms and choosing  the right approaches to solving problems.

Solution: automation of tedious work 

Example situations and problems



Case Studies:

ie for Telco Services Australia: Took information about phone calls and categorized them based on the categories provided by client

Related competencies:

Machine learning 



### Data science

#### Definitions 

Data science is the use of statistical methods along with algorithms and knowledge of computer information systems to get insights from data. With the huge growth in the amount of available data, this field has grown significantly lately. - CPS

The computational science of extracting meaningful insights from raw data, then effectively communicating those insights to generate value. - Data science for Dummies 



#### Practical uses and applications 

Data science makes better decisions

- Self-driving cars will root out more than 2 million deaths caused by car accidents annually 
- Online search engines use data science algorithms to deliver the best result for our searches within fractions of seconds 
- Face recognition algorithms on social media like Facebook 
- Video games are designed using machine learning algorithms; in motion gaming, the computer analyzes your previous moves to shape up its game
- Fraud and risk detection/finance industry - customer profiling, past expenditures, etc. to analyze probabilities of risk and default
- Delivery logistics 
- Data science is also used in marketing, health care, government policies, etc.
- Future: self-driving cars and robots 

https://www.analyticsvidhya.com/blog/2015/09/applications-data-science/

#### Challenges 



#### Resources 



#### CPS

##### How we can provide value

Our strong mathematical background intersects with our strong software dev skills in this area. 

- We understand how to analyze data in a rigorous way 
- We can make software systems that seamlessly incorporate these statistical data analysis systems 

##### Relevant testimonials/projects 

Crucial skill: background in mathematics (elaborate on this)



##### Information for sales process 

People sometimes use the terms "Statistics" and "data science" interchangeably when talking about using rigorous methods to analyze data.



##### 





Related competencies:

[process automation](https://github.com/aapeliv/CPS/blob/master/competencies/process-automation.md) often a key enabler (or a key blocker of introducing) better data science opportunities



### Machine learning and artificial intelligence 

#### Definitions

##### Machine learning

- A sub-field of Artificial Intelligence
- Goal: Generally, to understand the structure of data and fit that data into models that can be understood and used by people. 
- Machine learning algorithms allow for computers to train on data inputs and use statistical analysis to output values that fall within a specific range
- ML facilitates computers in building models from sample data to automate decision making processes based on data inputs 

Humans can train machines can learn from past data and to do what humans can do, much faster. https://www.youtube.com/watch?v=ukzFI9rgwfU

More data > Better model > Higher Accuracy

Artificial intelligence 

Machines learn by machine learning methods:

- **Supervised learning**
  - Trains algorithms based on example input and output data labeled by humans
  - Algorithm learns by comparing actual output with taught output to find errors and modify the model
  - Uses patterns to predict values on additional unlabeled data
  - ie coins with different weights. the machine would learn which weight (feature) is associated with which currency (label)
    SL uses labeled data to train the model.
- **Unsupervised learning**
  - Provides the algorithm with no labeled data to allow it to find structure within its input data
  - Algorithm finds commonalities among input data
  - Goal: Could be as straightforward as discovering hidden patterns within a dataset. Could also have a goal of feature learning - allows machine to automatically discover representations needed to classify raw data
  - Without being told "correct answer" methods can look at complex, expansive, seemingly unrelated data and organize it in potentially meaningful ways
  - ie Data set with Cricket players and scores. Machine identifies player performance, plots data with wickets on x axis, runs on y axis. 
  - UL uses unlabeled data to train the model.
  - Reinforcement learning
    Rewards-based; Works on a feedback basis. Machine learns from feedback
  - 

Output is final result 

Today, much data is avialable online and being generated every minute. Memory handling capabilities of computers vastly increased; they process data without delay

#### Practical uses and applications

- Healthcare, diagnostic predictions
- Semantic analysis tech giants do on social media (facial recognition technology helps users tag and share photos of friends)
- Optical Character Recognition (OCR) tech converts images of text into movable type 
- Recommendation engines suggest which movies or tv shows to watch next based on user preferences
- Self-driving cars rely on ML to navigate may soon be available 

- Classifications like music suggestions 
- K-nearest neighbours algorithms 
- Supervised: Uses historical data to predict statistically likely future events ie historical stock market info to anticipate upcoming fluctuations; or to filter out spam emails. Tagged photos of dogs used as input data to classify untagged photos of dogs 
- Unsupervised: Transactional data, ie customers and purchases, picking similar attributes from customer profiles and types of purchases. Algorithm can determine women of a certain age range who buy unscented soaps are likely to be pregnant. Marketing campaign re pregnancy and baby products targeted to this audiences to increase purchases. Often used for anomaly detection inc. fraudulent credit card purchases, recommender systems for which products to buy next. 
- UL: Untagged photos of dogs used as input data for algorithm to find likenesses and classify dog photos together.

https://www.digitalocean.com/community/tutorials/an-introduction-to-machine-learning



#### Challenges

- Continuously developing field

#### Resources 



#### CPS







https://www.sas.com/en_ca/insights/analytics/machine-learning.html

Related competencies: 

Natural Language Processing 





### Process automation and optimization 

#### Definition



#### Practical uses and applications



#### Challenges



#### Resources



#### CPS 

Automation of tedious tasks can unlock a huge amount of value. Process automation makes up the majority of software while simultaneously remaining low profile.

```
90% of programming jobs are in creating Line of Business software: Economics 101: the price for anything (including you) is a function of the supply of it and demand for it.  Let’s talk about the demand side first.  Most software is not sold in boxes, available on the Internet, or downloaded from the App Store.  Most software is boring one-off applications in corporations, under-girding every imaginable facet of the global economy.  It tracks expenses, it optimizes shipping costs, it assists the accounting department in preparing projections, it helps design new widgets, it prices insurance policies, it flags orders for manual review by the fraud department, etc etc.  Software solves business problems.  Software often solves business problems despite being soul-crushingly boring and of minimal technical complexity.  For example, consider an internal travel expense reporting form.  Across a company with 2,000 employees, that might save 5,000 man-hours a year (at an average fully-loaded cost of $50 an hour) versus handling expenses on paper, for a savings of $250,000 a year.  It does not matter to the company that the reporting form is the world’s simplest CRUD app, it only matters that it either saves the company costs or generates additional revenue.
```

(source: <https://www.kalzumeus.com/2011/10/28/dont-call-yourself-a-programmer/>)

Process automation usually isn't high on software developers'/engineers' assessments of status. As a result, if you talked to many software developers, you would likely get a biased view of just how much line of business software is out there. Many more people will be much more likely to talk about the game they're working on or some "cool" open source library, etc., because these things interest them on a personal level.

To be able to work with the information about processes, you have to get that information into systems so you can use it easily. 

In the data science pyramid, we learn that getting good data into a system enables additional value.

https://github.com/aapeliv/CPS/blob/master/competencies/process-automation.md

Bottom layers of data acquisition and engineering are critical to get the maximum benefits out of advanced analytics. Many businesses get stuck getting data into and out of their systems - a problem greatly 

Case studies

Related competencies:

Data science is greatly enabled by better process automation (see data science pyramid)





#### 



#### 



### Mathematical optimization 

#### Definition 



#### Practical uses and applications 



#### Challenges 



#### Resources 



#### CPS



Related competencies: Machine learning has substantial overlap with the algorithms and techniques that can be 
used in applied problems in the mathematical optimization space.





Idea: Success stories 