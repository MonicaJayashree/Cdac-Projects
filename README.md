# Secure Online Exams with Face Recognition & Analytics

The project aims to develop a comprehensive system for online exam authentication using face recognition techniques, coupled with data analysis and visualization for candidate performance insights. By combining deep learning models for biometric authentication and leveraging Python and Tableau for analytics and visualization, this project aims to enhance the security, integrity, and analytical capabilities of online exams.

Here we're using a smart learning method called "One-Shot Learning." This way, the computer can recognize you even with just a few pictures of your face. Our project is all about using this clever mix of face recognition and one-shot learning to make online exams more secure and honest.

To build a face recognition system, I will make use of:

1.Siamese Networks

2.the Triplet loss function, described in the FaceNet article by Schroff et al 2015

3.Transfer learning, to save training time by making use of pretrained convolutional neural networks.

4.Keras interface for the TensorFlow library and Keras Applications pretrained models.

# One Shot Learning
In one shot learning, only one image per person is stored in the database which is passed through the neural network to generate an embedding vector. This embedding vector is compared with the vector generated for the person who has to be recognized. If there exist similarities between the two vectors then the system recognizes that person, else that person is not there in the database. 

# Data Analysis Using Visualisation
Student Answering pattern is analyzed using Visualization tools like Power BI. The student online examination logs are obtained, Pre-processed and visualized using Power BI. Data Mining, Data Pre-Processing and Data visualization with analytics have done.

Extract the Message log of student response in online examination, Pre-process it and Visualise Student Exam Answer Logs in an Interactive graphs and charts.

Visualization using Power BI involves creating interactive and informative visual representations of data to gain insights, tell a data-driven story, and facilitate better decision-making. 




