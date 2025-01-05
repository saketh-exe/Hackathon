# Hackathon
This is a semi working prototype of our solution that we are developing to produce a non-traditional credibility score 


# How this works 
Mini models will Generate some values if logestic regression then value between 0 to 1
then we scale it to 0 to 100 
and we give weights for every output of mini models 
and based on these we calculate the final score 

what mini models we are using :
Timely Payments Model :- Payments made on time will contribute to a healthy score.
Savings Behavior Model:- more savings next month more credibility.
Job promotion Model:- If User can be promoted then he get more credibility. 
Social Media Sentiment Model:- if user is cyber Bullying he is about to face legal issues so his credibility is reduced.
Charitable Donations Model:- if he is donating then he is credible enough.

