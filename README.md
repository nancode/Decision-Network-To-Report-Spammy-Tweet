# Decision-Network-To-Report-Spammy-Tweet
This decision network tries to detect and report spam tweets. Depending on the observed input (tweet features) one fo the action is suggested to the user
1.	Report the User 
2.  Unfollow the user
3.  Continue following the user

The probability of the occurrence of the observable variables flow through the system in the direction of causality and the counter causal direction to estimate the likelihood of a given tweet being a spam one. 
The characteristics of a spam tweet take form of the nature nodes and the decision node of whether based on the observed characteristic, what action should be performed. The utility node measures the quality of the future tweets assuming the action being done.  

There is a link between all the characteristics and the action node as the decision maker can observe all the variables from a given tweet that he or she is presented with. It is also crucial to note that various variables such as graphical features suggestion, which could be used to detect the likelihood of the tweet being a spam one cannot be connected to the action node as they are non-observable features and cannot contribute to the decision made.

The utility node here measures the quality of the tweets concerning to the user satisfaction which will be directly impacted by the action of the user and analyzing the characteristics of the tweet.

