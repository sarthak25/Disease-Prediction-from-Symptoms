# Disease-Prediction-from-Symptoms
The aim of this project is to help people to figure the disease they might have based on the symptoms in their bodies currently.

Instead of going with a neural network approach for our recommendation system, I
decided to prioritize over the latency and time taken till output, and hence I built the
recommendation system based on Multinomial Naïve Bayes algorithm, which although
doesn’t provide accuracies as high as deep neural nets, can predict the disease in time to
not halt the chat application and maintain the consistency of the system.

This project provides a novel method that uses machine learning
technique, namely, Naïve Bayes classification algorithm for prediction of disease
followed by recommendation of specialists of the predicted disease. Using medical
profiles such as heart rate, blood pressure through sensors and other externally
observable symptoms such as fever, cold, headache etc. that patient has, prediction of
likelihood of a disease is done. Naïve Bayes algorithm takes these symptoms and
predicts disease. Furthermore, all the needful and adequate information regarding the
predicted disease as well as the recommended doctors is provided. Recommendation
suggests the location, contact and other necessary details of the disease specialists
based on the filters chosen by the user out of fewer fees, more experience, nearest
location and feedback reviews of the doctors. Thus user can get appropriate treatment
and necessary medical advice as fast as possible. Additionally, users provide their
feedback for the recommended doctors which are then added for analysis in order to
make further recommendations based on reviews.

A Naïve Bayesian classifier, is a model joint probability distribution over a set of
stochastic variables. Instances of the classification problem under study are presented
to the classifier as a combination of values for the feature variables. The classifier then
returns a posterior probability distribution over the class variable. Learning such a
classifier amounts to establishing the prior probabilities of the different classes and
estimating the conditional probabilities of the various features given each of the
classes. According to Bayes theorem of probability theory: - It is assumed that
attributes E1 to Em are class conditionally independent, which means it is often
assumed that after making the above assumption, the classifier is called Naïve Bayes.
