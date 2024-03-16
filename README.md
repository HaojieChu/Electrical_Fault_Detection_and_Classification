# Electrical_Fault_Detection_and_Classification

A transmission line is a crucial component within the power system, as it is essential for transmitting electrical power from the source area to the distribution network. In our modern era, the demand for power has increased exponentially. Therefore, it is crucial to minimize any potential faults within the power system, as electrical power is essential for our daily lives. The electrical power system is made up of several intricate, dynamic, and interacting components that are always vulnerable to electrical faults or disturbances.

In order for high-capacity electrical generating power plants and the grid to remain stable. fault detection and protection equipment operation have to happen as quickly as feasible. To minimise downtime, defects on transmission lines for the electrical power system must first be accurately identified and classified. Using machine learning algorithms can help in electrical fault detection and therefore aid in avoding electrical system outages.

Various machine learning algorithms are employed in this project which are

1. Decision Tree (DT)
2. Random Forest (RF)
3. Naive Bayes (NB)
4. k-Nearest Neighbour (kNN)
5. Support Vector Machine (SVM)

The performance of each machine learning model is assessed with metrics such as accuracy, precision, recall, and F-1 Score.

The simulation of the fault analysis is modelled by the power system and the diagram is retrieved from Kaggle. Four 11 x 10^3 V generators, one at each end of the transmission line, make up the power system. Transformers are positioned halfway along a transmission line to model and investigate different types of failures. The simulation of the circuit is performed under normal conditions and also under various fault conditions. At the power system's output side, the measured Line Voltage and Line Currents are collected. Nearly 12,000 data points are collected this way and then the data is labeled.

## Problem Statement

In electrical power systems, the reliable and safe operation of equipment is important for sustaining critical infrastructures. However, the increasing complexity of these systems pose a significant challenge in promptly identifying and classifying electrical faults. The absence of an efficient and automated fault detection and classification system results in extended downtimes, compromised safety, and suboptimal resource utilization for maintenance.

Current methodologies often rely on periodic manual inspections or rudimentary monitoring systems that are reactive in nature. These approaches not only fall short in providing real-time insights into the evolving health of the electrical network but also lack the ability to differentiate between various fault types. As a consequence, there is a need for an Electrical Fault Detection and Classification system that can intelligently identify, categorize, and localize faults in the electrical infrastructure.

## Objectives

1.   To perform analysis and understand each variable that leads to different electrical fault class.
2.   To train machine learning models that is able to classify and predict electrical fault class given inputs.
3.   To evaluate of performance of different machine learning models in predicting the electrical fault class.
4.   To deploy an electrical fault class prediction model as a dashboard for user to enter inputs and predict the fault class.

## Conclusion

In conclusion, the performance of various machine learning models was evaluated based on key metrics such as accuracy, precision, recall, and F1-score. The results indicate that the Decision Tree (DT) model achieved the highest accuracy at 88.15%, closely followed by the Random Forest (RF) model with an accuracy of 87.13%. Both DT and RF models demonstrated strong precision, recall, and F1-score values, suggesting a robust overall performance.

The Support Vector Machine (SVM) exhibited a slightly lower accuracy of 81.23% but demonstrated competitive precision and recall values. While the Naive Bayes (NB) model showcased reasonable metrics, it had a comparatively lower accuracy of 79.71%.

The K-Nearest Neighbors (KNN) model achieved an accuracy of 83.21%, accompanied by balanced precision and recall scores. It falls in between the Decision Tree/Random Forest and SVM/NB models in terms of overall performance.

In our project, cross validation is also performed and the accuracy scores are also obtained. we observe that the Decision Tree (DT) model exhibits consistently high performance across different folds, with accuracy scores ranging from 87.67% to 89.44%. The mean accuracy of 88.7% further validates its robustness and reliability in generalizing to unseen data.

Similarly, the Random Forest (RF) model demonstrates stable performance, with accuracy scores ranging from 87.03% to 88.30%. The mean accuracy of 88% suggests that the ensemble approach employed by the Random Forest contributes to a reliable and consistent predictive capability.

On the other hand, the Support Vector Machine (SVM) model displays a slightly lower mean accuracy of 81.1%, indicating a moderate but respectable performance. The cross-validated accuracy scores consistently hover around the 81% mark, reinforcing the model's ability to maintain stability across different subsets of the dataset.

The Naive Bayes (NB) model, with a mean accuracy of 79.6%, demonstrates reasonable consistency in performance. Although it trails behind the Decision Tree and Random Forest models, its stable accuracy scores across folds highlight its potential applicability, especially in scenarios where simplicity and interpretability are valued.

The k-Nearest Neighbour (kNN) model, with a mean accuracy of 82.9%, exhibits competitive performance. The accuracy scores ranging from 82.06% to 84.03% underscore the model's ability to capture patterns in the data effectively.

In summary, the Decision Tree and Random Forest models continue to showcase strong overall performance, with consistently high accuracy scores across folds. The Support Vector Machine, Naive Bayes, and k-Nearest Neighbour models also display commendable performance.

Finally, the best performing model which is the Decision Tree model has been deployed to a simple user dashboard that allow user to enter the inputs and get the prediction of the electrical class.

## Instruction  

To run the program, please follow the following instructions:

1. Download data and edit corresponding path in .ipynb file to retrieve the data
2. Run the `Electrical_Fault_Detection_and_Classification.ipynb` on Jupyter  


## Contact the Author  

If you got any enquiries or suggestions, I'm all ears :sunglasses:  

- **Institution:**  University of Malaya  :mortar_board: Data Science Graduate  
- **Author** Haojie Chu
- **Academic E-mail:** hjchuyu5@gmail.com
