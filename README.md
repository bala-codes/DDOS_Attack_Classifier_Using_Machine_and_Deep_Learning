# DDOS ATTACK CLASSIFIER USING MACHINE AND DEEP LEARNING.

[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)

In this repo, I've built a Machine and deep learning based classifiers (Ensemble) to distinguish the DDOS Attacks based on the networks parameters.

Dataset Available [here](https://www.unb.ca/cic/datasets/nsl.html)

Types of attacks classified are : 

attack = [['Normal'],
          ['neptune','back','land','pod','smurf','teardrop','mailbomb','apache2','processtable','udpstorm','worm'],
          ['ipsweep','nmap','portsweep','satan','mscan','saint'],
          ['ftp_write','guess_passwd','imap','multihop','phf','spy','warezclient','warezmaster','sendmail','named','snmpgetattack','snmpguess','xlock','xsnoop','httptunnel'],
          ['buffer_overflow','loadmodule','perl','rootkit','ps','sqlattack','xterm']]
          
Machine Learning algorithms (sklearn) used in this projects, 
  
- [DecisionTreeClassifier](http://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html)
- [RandomForestClassifier](http://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)
- [KNeighborsClassifier](http://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)

## After Hyperparameters tuning in ML Models, the best Ensemble Score is 99%
## In Neural Network , the final Score is 99%

Run it for yourself part 1 @ [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bala-codes/DDOS-ATTACK-CLASSIFIER-USING-ML-AND-DL-MODELS/blob/master/codes/Part%201%20DDOS%20ATTACK%20ML%20AND%20DL%20MODEL%20TRAINING%20%26%20TESTING.ipynb) and part 2 @ [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bala-codes/DDOS-ATTACK-CLASSIFIER-USING-ML-AND-DL-MODELS/blob/master/codes/Part%202%20DDOS%20ATTACK%20ML%20AND%20DL%20MODELS%20SINGLE%20INPUT%20TESTING.ipynb)


