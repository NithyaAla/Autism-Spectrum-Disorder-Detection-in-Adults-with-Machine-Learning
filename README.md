# Autism-Spectrum-Disorder-Detection-in-Adults-with-Machine-Learning
Autism, or Autism Spectrum Disorder (ASD), refers to a broad range of conditions characterized by challenges with social skills, repetitive behaviors, speech, and nonverbal communication. It is a developmental disability caused by differences in the brain, so people with ASD may also have different ways of learning, moving, or paying attention.
Although the symptoms generally appear in the first two years of life, autism can be diagnosed at any age. It is difficult to detect autism in adults because the symptoms of ASD in these individuals are often subtle or the adult has learned compensatory strategies for navigating the social landscape. There is no established procedure for diagnosing ASD in adults.
This project aims to detect autism in adults based on their answers to an autism screening questionnaire, AQ-10. Adults with suspected autism who do not have a learning disability can take the AQ-10 test and answer the following questions with Definitely Agree, Slightly Agree, Slightly Disagree, or Definitely Disagree.
1. 	I often notice small sounds when others do not
2. 	I usually concentrate more on the whole picture, rather than the small details
3. 	I find it easy to do more than one thing at once
4. 	If there is an interruption, I can switch back to what I was doing very quickly
5. 	I find it easy to ‘read between the lines’ when someone is talking to me
6. 	I know how to tell if someone listening to me is getting bored
7. 	When I’m reading a story I find it difficult to work out the characters’ intentions
8. 	I like to collect information about categories of things (e.g. types of car, types of bird, types of train, types of plant etc)
9. 	I find it easy to work out what someone is thinking or feeling just by looking at their face
10.  I find it difficult to work out people’s intentions

Based on the answers to the above questions, an individual is scored 1 point for Definitely or Slightly Agree on each of items 1, 7, 8, and 10 and is scored 1 point for Definitely or Slightly Disagree on each of items 2, 3, 4, 5, 6, and 9. The final score from the AQ-10 test is stored in the result variable along with the demographic information in a dataset.
This dataset is used to design a classifier that detects whether a person has ASD or not using supervised machine learning models namely Decision Trees, Random Forest, Support Vector Machines (SVM), K-Nearest Neighbors (KNN), Naive Bayes (GaussianNB), and Logistic Regression. A feed-forward Neural Network which is a linear binary classifier, otherwise known as Multi Layer Perceptron is developed and the performance of all the models is evaluated.

This work is based on Prof. Fadi Thabtah’s article, Autism Spectrum Disorder Screening: Machine Learning Adaptation and DSM-5 Fulfillment and Dr. Kanad Basu’s article, Machine learning approaches to the classification problem of autism spectrum disorder.

