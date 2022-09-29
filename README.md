# Bird Species Classification using Machine Learning Algorithms
This project is about classifying bird species using Machine Learning algortithms. There are many different types of birds like swimimming birds, wading birds, terrestrial birds, raptors etc. According to their living habits and environments, they are classified into different ecological groups. The appearances of the bairds that belongs to different ecological groups are different. The structure of their bones are different. In this project I will be using Machine Learning algorithms such as Random Forest, Support Vector Machines etc to classify the species of birds. The results will be evaluated using confusion matrix. The best model will be selected and deployed for inferencing.

## Dataset
This dataset contains 420 birds. Each bird is represeneted by 10 measurements which are the features of this dataset. The description is given below.

* id - Unique ID for each bird
* huml - Length of Humerus
* humw - Diameter of Humerus
* ulnal - Length of Ulna
* ulnaw - Diameter of Ulna
* feml - Length of Femur
* femw - Diameter of Femur
* tibl - Length of Tibiotarsus
* tibw - Diameter of Tibiotarsus
* tarl - Length of Tarsometatarsus
* tarw - Diameter of Tarsometatarsus
* type - label for the ecological groups

These labels are described as below.

* SW: Swimming Birds
* W: Wading Birds
* T: Terrestrial Birds
* R: Raptors
* P: Scansorial Birds
* SO: Singing Birds

## Requirement 
To run the jupyter notebook, Python 3 is required with the packages pandas, numpy, matplotlib, seaborn and scikit-learn. 
