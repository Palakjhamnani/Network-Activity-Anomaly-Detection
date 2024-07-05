Network Activity Anomaly Detection, by Consulting and Analytics Club, IIT Guwahati
 
Problem Statement 
The dataset contains detailed records of network activities, capturing various attributes associated with network connections. Each record is labeled to indicate whether the activity is normal or a "Neptune" attack, providing a foundation for binomial classification.

A Neptune attack, also known as a SYN flood attack, is a type of denial-of-service (DoS) attack where an attacker overwhelms a target system with a high number of SYN requests, causing the system to become unresponsive to legitimate traffic. It exploits the TCP handshake process to consume resources on the target machine.

The training set contains 86,845 rows, including whether the activity (column - Attack) is normal or not. Use this to train a Machine Learning model, then predict whether the 21,712 entries in the test set have a normal activity or not (Neptune).

Note: 

In the target variable (Attack), “normal” means normal activity (no attack) i.e., attack = 0

“neptune” means Neptune attack. i.e., attack = 1

The data contains two files: train.csv and test.csv

train.csv - which contains the training set observations. 86,845 rows, which have the target variable (attack) values as well for training the model.

test.csv - which contains the testing set observations. 21,712 rows, with the target column missing. Use the trained model to predict and submit the values of the target column.


Additionally, a sample-submission.csv file is provided to show you what your CSV submission should look like. Note that the header has 'attack' for the column name and the number of rows is equal to the number of rows in the test set.

attack: normal - 0

attack: neptune - 1
