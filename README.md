# CANDEV-Hackthon-2020
# CANDEV-Hackthon-2020

Business case : Royal Canadian Mounted Police (RCMP) seeks to find and refine the more specialized nature of our work (ranging from transnational organized crime to cybercrime),  and they require a more strategic and systematic way to:
1) Define the specific skills and competencies required to carry out particularly specialized tasks
2) Locate the education programs/courses that develop these skills and competencies
3) Isolate the tools that would best enable us to assess the required skills and competencies
4) Locate people across Canada who may already possess those skills and competencies 

Solution : We have provided them a solution with machine learning, AI and NLP based and it is as follows:
1. Resume filteration to matching the skills and providing the score at the end on the number of matches. We used text matching for implement this using python 
2. Text classification on the investigation report to discover new skills can use topic modelling (LDA) + sentimental  analysis ( VADER ) using NLP
3. Facial Expression Assessment observe the micro expression of face during the response time (OpenCV/ Image recognition) speech to text during the response on which topic modelling will be implemented using LDA then we will get topics from each answers to generate the sentimental analysis to predict the score for each answer and then both facial expression and speech2text results will be combined
4. Pymetrics Test (Imported the points from actual) which is a game-based recruiting tool that assesses the strengths of candidates and recommends the right careers and companies for them
5. Behavioural Aanlysis Cross Platform on social networking websites/ digital footprint


Progress of Implementation: We have implemented the few components:
1. We have implemented the Facial Experession Assesment using OpenCV and Tensorflow
2. We have implemented the voice recognition including Speech2Text using Google Recognizier which is creating JSON files
3. We have created the Automatic Resume Screening Sytsem for the front-end we have used the Flask and Docker and backend we have used the NLTK (Tokenization & Lemmetization) - Old Project Component Modified for this Hackathon

Future Tasks:
1. Integrate every component and produce the score for each type of test
2. Create a new Pymetric Test with Augment/Virtual Reality to generate more data for evaluation of the applicants EQ
3. Analytics over the Speech2Text data which will be in the MongoDB (Profile based data) for the semantic analysis
4. Produce the Automatic Skills Extractor System from the investigation Reports to keep the department uppdated as the crime's ways are also advancing

Above solution is also present in GitHub library and below is trhe link for the same:
LinkedIn: https://www.linkedin.com/in/arpit-rathore/

CANDEV-Hackthon-2020
