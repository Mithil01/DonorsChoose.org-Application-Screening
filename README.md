# DonorsChoose.org-Application-Screening

DonorsChoose.org receives hundreds of thousands of project proposals each year for classroom projects in need of funding. A large number of volunteers is needed to manually screen each submission before it's approved to be posted on the DonorsChoose.org website.

The goal of the competition is to predict whether or not a DonorsChoose.org project proposal submitted by a teacher will be approved, using the text of project descriptions as well as additional metadata about the project, teacher, and school. DonorsChoose.org can then use this information to identify projects most likely to need further review before approval.

Solution pynb files:

    ->  There are 3 files wherein 3 different models are used
    
    1) Naive Bayes algorithm  on set one(numerical + categorical featurizations(OHE) + TFIDF(Essay)) and set two(numerical + categorical featurizations(OHE) + BOW(Essay)).
    
    2) Decision Tree classifier on set one(numerical + categorical featurizations(OHE) + TFIDF(Essay))  and set two(numerical + categorical featurizations(OHE) +TfIdfweightedW2V(Essay)). 
    
    3) Gradient Boosting Classifier on set one(numerical + categorical featurizations(OHE) + TFIDF(Essay))  and set two(numerical + categorical featurizations(Response coding) +TfIdfweightedW2V(Essay)). 
