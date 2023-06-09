### Purpose of the Study

In this study, **6 different models** were tested on Titanic Data and the best model for survival prediction was determined based on ***Sex, Age, Parent-Child*** information.  
  
Models tested in order:  
- Logistic Regression
- Gaussian Naive Bayes (GaussianNB)
- Bernoulli Naive Bayes (BernoulliNB)
- Decision Tree
- Support Vector Machines (SVMs)
- Linear Regression
  
### Information About Data Properties

**Variable > Definition > Key**  
- ***survival*** = Survival > 0 = No, 1 = Yes  
- ***pclass*** = Ticket class > 1 = 1st, 2 = 2nd, 3 = 3rd   
- ***age*** = Age > Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5  
- ***sibsp*** = # of siblings / spouses aboard the Titanic  
Sibling (brother, sister, stepbrother, stepsister)  
Spouse = husband, wife (mistresses and fiancés were ignored)  
- ***parch*** = # of parents / children aboard the Titanic  
Some children travelled only with a nanny, therefore parch=0 for them  
- ***ticket*** = Ticket number  
- ***fare*** = Passenger fare  
- ***cabin*** = Cabin number  
- ***embarked*** = Port of Embarkation > C = Cherbourg, Q = Queenstown, S = Southampton  
