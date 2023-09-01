# AI Career Guide Software Documentation
## 1. BUSINESS BACKGROUND

The Department of Education has recognised the need to enhance career guidance for students, and they've looked for a company to leverage AI technology. This partnership is aimed at integrating AI platforms into educational institutions nationwide, bridging the gap between education and employment. By offering personalised job and career suggestions, skill-building resources, and helping individuals to make informed career decisions.

### 1.1. Vision

- Empowering high school learners through guided career navigation.
- Enabling growth through guided career exploration.

### 1.2. Mission

The mission of the AI software is to provide high school learners with a transformative career journey by offering personalised career guidance software. We aim to equip learners with the insights needed to make informed decisions, navigate career transitions, and achieve their professional aspiration.

## 2. BUSINESS OBJECTIVES

- Help people identify and find jobs that match their interests and skills.
-	Reduce the time and effort required for research and research activities.
-	Gives personal advice based on personal strengths and goals.
-	Taking pride in personal work and success as they will follow their passions.
-	Enhance workforce diversity and inclusion by recommending jobs that match an individual's unique abilities.
-	 Reduce the cost and complexity of career counseling programs by providing digital solutions.
-	Analysis of skill gaps and suggestions for skill development.

## 3. REQUIREMENTS SPECIFICATION
### Definition of Requirements

System requirements are the necessary specifications that are needed for an AI career guide system to be fully functional and complete. Requirements include natural language processing, unsupervised learning, Nearest Neighbors algorithm, Neural Network Model, K-Means Clustering, a learning loop, learning from interaction, career insights, skill assessment, career recommendation, privacy and data security, and a fallback mechanism. Acquiring all of the above-listed requirements will enable the system to accurately recommend relevant careers.

### Requirements Master List
**_Abbreviation and Definitions_**

**FR** = Functional requirements

**NFR** = Non-functional requirements

**SR** = Security requirements

### Functional Requirements
**_Functional requirements_** define what the system should do, including its inputs, processes, outputs, and interactions.

**FR1:** ***User Profile:*** To use the AI Career Guide system, users must create a profile and provide their personal information, including their name, email address, and password. This information will be securely stored, and users can access the system with a username and password each time they use it.

**FR2:** ***Natural Language Processing:*** The AI Career Guide system will capture and interpret user inputs in natural language.

**FR3:** ***Unsupervised Machine Learning:*** The system will be capable of learning from large amount of text data without human supervision, to continuously improve its responses and knowledge base.

**FR4:** ***Nearest Neighbors algorithm:*** The Nearest Neighbors algorithm will serve a valuable function in the AI career guide software as it will provide personalised recommendations and insights to learners based on similarities to their profile and preferences. Through the use of nearest neighbour algorithms, the system will be able to do skill gap analysis. By comparing the skills of a user with those of others who have successfully achieved the desired roles. This will enable learners to focus on acquiring the specific skills needed to excel in their chosen career path.

**FR5:** ***Neural Network Model:*** A neural network model will play an important role in the AI career guide software by enabling it to analyse complex relationships within career-related data, make accurate predictions, and provide personalised recommendations. Using neural networks, the AI Career software will process large amounts of data from users' profiles, including skills and interests. The model will identify patterns and relationships among these variables to create a map of a user's strengths, preferences, and potential career paths.

**FR6:** ***K-Means Clustering:*** The AI Career Guide system will use K-Means clustering, primarily focusing on grouping career-related data into clusters based on similarity. By using K-means clustering, the software can identify distinct user groups with similar characteristics. Each cluster will represent a different career interest or skill set, enabling more targeted recommendations.

**FR7:** ***Career Recommendation:*** The user will provide information to the system, which will be used to provide suitable career path suggestions. The system will offer a space where the user can input a brief paragraph about their interests and skills. Additionally, there will be a chart with a list of strengths and weaknesses, where the user will rate their abilities on a scale of 1-5. Based on this crucial information, the system will generate career path recommendations best suited to the user's skills and interests.

**FR8:** ***Career Insight:*** Provide insights on various career paths, job roles, and trends based on available data.

**FR9:** ***Speech Recognition:*** For individuals who have difficulty articulating their interests in writing, our system will include a speech recognition feature to aid them in conveying their passions.

### AI strategies:
Our system will utilize three AI strategies: unsupervised machine learning, natural language processing and neural network model
Unsupervised learning is a type of machine learning that utilizes unlabeled data to train machines. The model then learns from this data, creates a pattern, and returns an output. It is commonly used to solve clustering and association problems. Our system utilizes this technique, enabling learners to provide their interests, strengths, and weaknesses. The model then expertly makes connections with the data and correlates it to prospective career paths.

Natural language processing is an AI tool that allows computers to understand and interpret human language. One of its components is the ability to convert spoken language into text using speech recognition. This feature will benefit our system by aiding its speech recognition capabilities. The system can find and retrieve relevant information from a large text. This will be beneficial for our system as it can retrieve the necessary information from the paragraphs that users enter.

To provide appropriate career paths, our system must be capable of clustering diverse data using the K-means learning algorithm. The K-means algorithm is a type of unsupervised learning that clusters data according to their similarities. Our system will utilize this algorithm to group learners' interests, strengths, and weaknesses into distinct career paths.

### Non-functional Requirements
Non-functional requirements define how the system should behave in terms of its performance and usability.

**NFR1:** ***Reliability/feedback mechanism:*** The feedback and learning loop are a cycle of learning and improving skills. Our system provides users with the utmost benefit by consistently acquiring new information about the job market and skills through a learning loop. This guarantees that the feedback given is always current and relevant. The feedback loop will ensure timely feedback is provided to users.

**NFR2:** ***Security:*** The system will use data encryption which will ensure the users' data and career-related data are encrypted to prevent unauthorized access. 
The system will employ the secure communications protocol (HTTPS) to transmit data between the software and the user's device, thus preventing any risk of data exposure.

**NFR3:** ***Fallback:*** If the system encounters an error, it will provide a fallback response. The response will include an apology and a request for the user to provide an alternative solution or rephrase the data they previously entered.

**NFR4:** ***Feedback and Learning Loop:*** The system will ask users to provide feedback on the accuracy and helpfulness of the response, enabling the system to improve.

## 4. CONSTRAINTS
-	**Data Availability:** The accuracy of career recommendations will depend on the quality and quantity of data available for various career options. 
-	**Algorithm Complexity:** The balance of clustering and classification algorithms with real-time performance can be a challenge. 
-	**limited learning:** The AI Career Guide's ability to learn can be limited by the scope of data it's trained on and may not immediately capture changing job market trends.
-	**Interpersonal Evaluation:** Assessing interpersonal skills accurately through algorithms can be complex, as some skills require careful consideration to fully understand.

## 5. RISKS
-	**Inaccurate recommendations:** If the clustering and classification algorithms are not properly trained, the software could provide irrelevent career suggestions. 
-	**Bias:** The AI Career Guide could favour certain career options due to biassed training data, which could lead to unfair recommendations.
-	**Lack of user engagement:** If the recommendations are not accurate, learners might not find the software useful, which will lead to a low adoption rate.
-	**Market Changes:** Changes in the job market due to technological advancement or economic changes might cause the software to give recommendations that are less relevant.

## 6. PROBLEM DEFINITION
The AI Career Guide has been developed to tackle the pressing issue of career exploration among high school learners. The existing traditional career guidance events have contributed to a rise in school dropouts as learners feel demotivated due to the limited career options presented to them. These events cater only to a select group of individuals, neglecting the diverse interests and aspirations of many learners. 

In contrast, the AI career guide holds the potential to revolutionise the education industry. By utilising unsupervised machine learning algorithms, Natural Processing Language (NPL) and Neural Network Model, the system encompasses a wide array of career libraries. This enables the system to effectively group careers based on learners' specific interests and provides them with a comprehensive range of options to consider. 

One of the key advantages of the AI career guide is its ability to offer educational content that equips learners with valuable information about various career paths. By doing so, it empowers learners to make informed decisions and pursue their goals with confidence. 

Moreover, the AI career guide incorporates personalised recommendations based on learners' individual strengths and aptitudes. Through advanced algorithms, the system can analyse learners' profiles and provide tailored career suggestions that align with their unique attributes, fostering a sense of purpose and direction.

## 7. POSTER
![](https://github.com/GIT-ATHON-GROUP/AI-CareerGuide-DocumentationRepo/blob/lupin/AI%20Career%20Guide%20Software%20Poster.png)
