# Medical-text-classification
Develop predictive models that can determine, given a medical abstract, which of 5 classes it falls in.

Medical abstracts describe the current conditions of a patient. Doctors routinely scan dozens or hundreds of abstracts each day 
as they do their rounds in a hospital and must quickly pick up on the salient information pointing to the patient’s malady. The 
aim of this project is to design assistive technology that can identify, with high precision, the class of problems described 
in the abstract. In the given dataset, abstracts from 5 different conditions have been included: digestive system diseases, 
cardiovascular diseases, neoplasms, nervous system diseases, and general pathological conditions.

The goal of this project is to develop predictive models that can determine, given a particular medical abstract, which one of 
5 classes it belongs to.

min-epsilon k-NN classifier:
  The min-epsilon k-NN classifier is defined similarly as the k-NN classifier with the exception that neighbors 2 to k are 
additionally restricted to have a minimum similarity of epsilon with the query object. In other words, neighbors are restricted 
by both number of neighbors and minimum similarity, but always at least one neighbor is retrieved.
