# AI Career Guide Software Documentation
## 1. BUSINESS BACKGROUND

The Department of Education has recognised the need to enhance career guidance for high school learners in government schools across South Africa, and they've asked GIT-ATHON group to develop an A.I. Career Guide Chatbot that will assist learners in making informed career decisions. This partnership aims to integrate A.I. platforms into educational institutions nationwide, bridging the gap between education and employment. By offering personalised job and career suggestions, 
skill-building resources, and helping individuals make informed career decisions. The A.I. Career Guide Chatbot is a robot powered by neural network models, unsupervised machine learning algorithms, and natural language processing (NPL).

### 1.1. Vision

- Empowering high school learners through guided career navigation.
- Enabling growth through guided career exploration.


### 1.2. Mission

The mission of the A.I. solution is to provide high school learners with a transformative career journey by offering personalised career guidance software. We aim to equip learners with the insights needed to make informed decisions, navigate career transitions, and achieve their professional aspirations.

## 2. IDENTIFY THE PROBLEM

The A.I. Career Guide has been developed to tackle the pressing issue of career exploration among high school learners. The existing traditional career guidance events have contributed to a rise in school dropouts as learners feel demotivated due to the limited career options presented to them. These events cater only to a select group of individuals, neglecting the diverse interests and aspirations of many learners.

- **Lack of information**
  
The A.I. career guide holds the potential to revolutionise the education industry. By utilising unsupervised machine learning algorithms, Natural Processing Language (NPL) and Neural Network Models, the system encompasses a wide array of career libraries. This enables the system to effectively group careers based on learners' specific interests and provides them with a comprehensive range of options to consider. 

- **Career selection assistance**

One of the key advantages of the A.I. career guide is its ability to offer educational content that equips learners with valuable information about various career paths. By doing so, it empowers learners to make informed decisions and pursue their goals with confidence. 

- **Biases**
  
The career guide will assist learners with technical skills that are not covered in the conventional education systems, covering various industries.

- **Cost** 
The system will assist disadvantaged learners who are not capable of attending career guidance expose.

## 3. 3. BENEFITS OF SOLVING THE PROBLEM

- **Availability:** The system will and should be available all day every day, This will enable students and Learners to be able to access it at any given time and it will also give the learners the assistance and support they will need.
  
- **Scalability:** The system can handle multiple queries with learners simultaneously.
  
- **Increasing Career options:** Learners will be exposed to a variety of career paths, therefore reducing the saturation in different career paths.
  
- **Reducing Cost:** If a learner does not have the time, funds, and access to a career guidance counsellor, the system will be a perfect alternative

## 5. THE PURPOSE FOR OUR AI SOLUTION

The purpose of the A.I. Career Guide software is to help learners make informed career-related decisions based on their skills, preferences, strengths and 
weaknesses. This partnership is aimed at integrating A.I. platforms into educational institutions nationwide, bridging the gap between education and employment. By offering personalised job and career suggestions, skill-building resources, and helping individuals make informed career decisions.
      
## 6. MACHINE LEARNING APPROACH
Machine Learning is defined as the study of computer programs that leverage algorithms and statistical models to learn through inference and patterns without 
explicit programming.

## Type of Machine Learning:
- **Unsupervised Machine Learning**
  
It is a type of machine learning that utilises unlabelled data to train machines. The model then learns from this data, creates a pattern, and returns an output. It is commonly used to solve clustering and association problems. Our system utilises this technique, enabling learners to provide their interests, strengths, and weaknesses. The model then expertly makes connections with the data and correlates it to prospective career paths.

- **Natural Language Processing (NLP)**
  
NLP is an A.I. tool that allows computers to understand and interpret human language. The system can find and retrieve relevant information from a large text. This will be beneficial for our system as it can retrieve the necessary information from the paragraphs that users enter.

- **The K-means algorithm**
  
To provide appropriate career paths, our system must be capable of clustering diverse data using the K-means learning algorithm. The K-means algorithm is a type of unsupervised learning that clusters data according to their similarities. Our system will utilise this algorithm to group learners' interests, strengths, and weaknesses into distinct career paths.

## 7. DATA (REQUIREMENTS)

- **Skills & Career Data:** The system collects and group different type of skills data (soft and hard skills) using K-means clustering and store them in a local database. The system will then utilise machine learning algorithms and data analysis to refine career recommendations based on user interactions and outcomes.
  
- **Dimensionality Reduction:** The system uses this technique to reduce nonrelevant features by using the K-nearest neighbour algorithm to find similar careers based on learners' interests and skills.
  
- **User Interaction Data:** The user will type a sentence in a textbox on the interface, establishing connections between specific skills and careers or 
industries based on the learner's interests. Then, it will store the feedback on the learner profile for future reference.

- **Contextual Data Understanding:** The guide will use Natural Language Processing (NLP) to interpret the text entered by the learner on the textbox and compare it with the careers and skills on the learner's profile then provide personalised recommendations to the learner.
  
- **Training Data:** During the training stage developers were constantly creating lists of questions that they ask the system until it showed readiness by providing accurate feedback. The machine learnt from this stage until it gave accurate responses.

## 8. CONSTRAINTS AND RISKS
### 8.1. Constraints
- **Data Availability:** The accuracy of career recommendations will depend on the quality and quantity of data available for various career options.
  
- **Algorithm Complexity:** The balance of clustering and classification algorithms with real-time performance can be a challenge.
  
- **Limited learning:** The A.I. Career Guide's ability to learn can be limited by the scope of data it's trained on and may not immediately capture changing 
job market trends.

- **Interpersonal Evaluation:** Assessing interpersonal skills accurately through algorithms can be complex, as some skills require careful consideration to 
fully understand.

- **Budget:** The hardware required for the development of the system may be costly.
  
- **Time:** The Chabot is a complicated system and requires a long time to be able to function best.
  
### 8.2. Risks
- **Inaccurate recommendations:** If the clustering and classification algorithms are not properly trained, the software could provide irrelevant career 
suggestions.

- **Bias:** The A.I. Career Guide could favour certain career options due to biased training data, which could lead to unfair recommendations.
  
- **Lack of user engagement:** If the recommendations are not accurate, learners might not find the software useful, which will lead to a low adoption rate.
  
- **Market Changes:** Changes in the job market due to technological advancement or economic changes might cause the software to give less relevant recommendations.
  
- **Security:** If the system is not properly secured, it could be hacked and give out false information or engage in malicious activities.

### 9. TOOLS
▪ **Version control:** GitHub
▪ **Programming Language:** Python
▪ **Design Software:** Figma
▪ **Coding platform:** Visual Studio code

### 11. MODEL
Our system will use the Natural Language Processing (NLP) model for optimum performance and also to understand and interact with users.

▪ **Collecting and Preparing Data:** Compile a dataset that is relevant to educational pathways, job descriptions and user queries.

▪ **Text classification for user intents:** Label user query categories and train the model to recognise the learner's intents. 

▪ **Text Generation for Responses:** Use ruled-based responses to ensure that responses are informative, concise, and contextually relevant.

▪ **User Texting and Evaluation:** Test the chatbot with real users to gather feedback and evaluate the chatbot’s performance to identify areas for 
improvement.

▪ **Personalisation:** The User data will be learned to personalise the required and close-range response. This will be considered using past events, 
searches and future interactions.

### 11. TIMES SERIES ANALYSIS ON DATA

## 12. SOLUTION TECHNIQUES

To develop the A.I. Career Guide Chatbot several solution techniques can be utilised. Our system will use the following techniques:

▪ **Neural Network Models (NNM)**
▪ **Recommender Systems (R.S.)**
▪ **Natural Language Processing (NLP)**

NLP techniques have been used to understand and interpret learner's questions and provide relevant and accurate responses, we have also used NNM to facilitate more precise and intricate analysis of learner data, these models can be used for tasks like career path prediction, skills development assessments and identifying emerging job trends. Recommender systems have been utilised to personalise job and career suggestions according to learner's interests, skills, and preferences.

### 13. NATURAL LANGUAGE PROCESSING (NLP)

▪ The NLP component of the A.I. Career Guide Chatbot will enable the system to understand and interpret natural language queries from learners, extract 
important information, and provide relevant responses and guidance. 

▪ It also assists the Chatbot with maintaining content during learner queries or conversations, which makes the learner feel like they are getting assistance 
from a human career guide advisor.

▪ Utilising the NLP has also assisted in text summarisation which assists in summarising long texts such as industry reports, job descriptions or 
educational content, This has assisted the Chatbot in providing accurate and easy-to-understand information, which will save them time and stress in 
understanding complex information.

### 14. DEEP LEARNING

**Recurrent Neural Networks**

The RNNs were used to sequence modelling the Chatbot applications which has enabled it to understand and generate text sequences in a conversational context. 

**RNN has offered our Chatbot several advantages such as:**

▪ Understanding context
▪ Capturing sequential dependencies
▪ Generating Language Responses
▪ Adapting to different conversation lengths

**The RNN in our Career Guide Chatbot consists of three main layers which are:**

▪ Input Layers 
▪ Recurrent Layers 
▪ Output Layers 

### 14.1. Input Layers

- The input layer receives the input data, which can be a learner's question 
or query about their career.
- It encodes the input information and prepares it for processing in the 
subsequent layers.

### 14.2. Recurrent Layers

- This processes sequential data by maintaining a hidden state that captures information from previous time steps. 
- In the career guide, Chatbot will take the encoded input from the input layer and process it to understand the meaning and context of the 
learner's career-related question.
- It checks the history of previous inputs and uses them to generate relevant responses and utilises recurrence in the network to capture temporal 
dependencies and contextual information.

### 14.3. Output Layers

- The output layers take the information from the hidden layers and generate the responses to the learner’s questions.
- They generate responses based on the processed information from the recurrent layer.

### 14.4. Model Training

▪ We implemented our RNN using Microsoft Azure cloud service and locally with Google TensorFlow.
▪ Both frameworks achieved similar performance and allowed users to manually define the RNN with Python.
▪ The advantage of Azure is that it allows the user to simultaneously run several RNN training processes with different data or network parameters and easily compares their performance. 
▪ The training process is faster in Azure compared to training with computers using a Core i5 CPU. 
▪ The Tensor Flow runs locally, though the training speed depends on the hardware and it is impractical simultaneously to train several models on a single computer. 
▪ All the trained weights are accessible, which makes Tensor Flow suitable for model analysis. 
▪ We used Azure for RNN model design and TensorFlow for experimental evaluation.

### REFERENCES

**1. Books**

1.1. "Deep Learning" by Ian Goodfellow, Yoshua Bengio, and Aaron Courville: This book covers various deep learning topics, including RNNs, in detail. It provides comprehensive explanations and examples of RNN architectures and their applications.

1.2. "Natural Language Processing with Python" by Steven Bird, Ewan Klein, and Edward Loper: This book provides a practical introduction to NLP using 
the Python programming language. It covers various NLP techniques, including tokenisation, part-of-speech tagging, parsing, and sentiment analysis

1.3. "Pattern Recognition and Machine Learning" by Christopher M. Bishop: This textbook covers various machine learning algorithms, including clustering techniques like K-means. It provides a comprehensive overview of the algorithm and its implementation.

**2. Links**

www.mygreatlearning.com/blog/what-is-machine-learning/
   
www.ibm.com/topics/recurrent-neural-networks#:~:text=the%20next%20step-
,What%20are%20recurrent%20neural%20networks%3F,data%20or%20time%20
series%20data
