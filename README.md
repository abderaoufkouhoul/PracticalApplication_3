# Practical Application 3

# Business Objectives 

Here we are using ML classifiers algorithms to examine the results of a bank 17 marketing campaigns over many years. From the dataset, 88% is the rate of clients declining the bank offers. 
From marketing policy, this rate is a major indicator of inefficient  marketing policies and justifies the need of machine learning analysis for:

Therefore, the main objectives are:    
    Figure out features contributing more to clients acceptance.  
    Figure out common characteristics of clients declining the bank's offers.  
    Improve clients acceptance rate.  
    Reduce the cost by targeting clients with high probability of accepting offers.  
    Focus bank's resource(personal, calls, time, money ..) on targeted clients.  
    Improve  the bank marketing policy by analyzing characteristics of client declining offers for future policy improvement and financial investment.  

The dataset in question has 21  features which are described in the attached file.  



# Summary of classification algorithms performances


# Main Findings
While examining the output tree of DecisionTreeClassifier, we notice that only 05 features among the  initial 21 features are sufficient to obtain 90 % accuracy. Therefore, building another model with only 05 features
will reduce classifiers run-time while maintaining an accuracy above the baseline.
These 05 features are:
1. nr_employed
2. duration
3. pdays
4. day_oftheweek
5. contact 
