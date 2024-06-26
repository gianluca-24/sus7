# Statistics Under the Stars 7 - Hackathon

Our team composed of myself, Giorgio Bertone, Filippo Parlanti and Himel Ghosh has reached the second place in the "Statistics Under the Stars (SUS 7) Hackathon" organized by y-SIS (Statistical Society of Italy) by the University of Salento at Lecce, Italy sponsored by Adecco and received the “Best Objective Prediction” award (€600).  


![alt text](https://github.com/gianluca-24/gli_imBruttit_sus7/blob/main/img/awards.JPG)

## The challenge

The challenge consisted of solving a real-life problem. We were given 3 datasets: one for job vacancies, one for applicants, and one to join 5 different applicants to each job vacancy. Obviously, for each job only one candidate could be chosen while the same candidate could be chosen for multiple jobs.   

Essentially, this was a classification problem that required a lot of preprocessing of the given datasets in order to obtain a final version to train our model on. We took advantages of similarities to try to figure out how similar a candidate was to a certain job position, such that for each couple Job-Candidate our model will produce a certain probability, and then for each job position we will set to 1 the candidate with the highest probability (i.e., the chosen one) and to 0 all the others.  

We tried many different approaches. Our first naive approach was the LogisticRegression, then we moved to XGBoost but in the end we went with neural networks.
