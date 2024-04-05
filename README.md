# Hotel-Booking-System

Hotel industry is one of the businesses which is growing rapidly and in order to attract the customers, the owners are providing various schemes and offers like offering complimentary breakfast, free car parking, free cancellation policy etc. In order for them to make necessary decisions to improve their business, they should study the data they collect from the customers and take necessary actions. In this project we aim to solve a few business case problems and predict the solutions that help both the customers and owners.

## Problem Definition:
For the purpose of this Project, we will be looking into:
1. The probability that a customer makes a cancellation.
2. Does the cancellation depend on the external factors - such as the lead time before the
booking, booking changes made, the deposit type, and the customer type.
3. Finding out if being a repeat customer changes the probability that a customer does
not cancel?

## Data Description:

This data set contains booking information for a city hotel and a resort hotel, and it includes 32 attributes and 119391 instances that could predict the probability of the customer making a cancellation based on external factors. It has information and variable names such as when the booking was made, length of stay, the lead time before the booking was made, the arrival date, if the booking was cancelled, the number of adults, children, and/or babies, and the number of available parking spaces, among other things.

Project Results:

● Among the four implemented models, Random Forest model gives the highest accuracy (87%) when applied on our dataset. It also has the highest F1 score with 90%. This model also gives highest sensitivity (93%), which shows that it is very good at classifying the true positive values, which in our case is “Is Cancelled”.

● Decision Tree is the next best model with an accuracy of 83% .This model gives both F-1 score and Sensitivity of 86%.

● KNN is the next best model with an accuracy of 82%. However, this model gives good sensitivity i.e 89%, which shows that it is very good at classifying the true positive values, which in our case is “Is Cancelled”.

● Logistic Regression is found to be the least performing model, with an accuracy of
only 75%.
