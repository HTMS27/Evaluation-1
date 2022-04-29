This repository consists of 4 solutions that are part-1(3 questions) part-2(1question) and the names of code files are named accordingly.
The solutions of the Bonus questions are written in this readme file.

Libraries used:

Pandas--For reading the datasets and analysis on the dataset
transformers -- For sentiment analysis
re		-- For question 1 and preprocessing the text
happytransformer -- For Finding Grammatically correct statements.
flask --- for deploying the model.
werkzeug.utils ----



***For Deploying question:

I will share my  link of the deployed model after opening the link you will be asked the upload a CSV file with the format of the given file after uploading
Click the submit button and the next page containing the result which consists of positive reviews along with ratings.

Link: https://ht17ms174-v5v8pzz6o2cnu8ae.socketxp.com
Note: If the server is down please let me know because there can be a chance of a problem from my end. This link is created by using SocketXp


For other codes, You need to import the dataset and run all the cells accordingly.




---BONUS Points------


1. The difficult problem that I have solved till now is my MS THESIS project. 
In this project, I worked on the Twitter data where I collected the tweets related to the Indian Judiciary, on this collection I am trying to classify the abusive tweets related to Indian judges
So till now, there has not been any dataset constructed yet. So when a person using abusive language or foul language or local language identifying these kinds of tweets is a difficult
task and also the complexity of natural language constructs makes this task challenging. Here I have explored multiple methods and mostly used approach was the active learning approach.
And also I have done user analysis which means why a user posts these kinds of tweets, whether he is politically biased or intensionally created an account for trolling. 
So there was a paper which is published at the AAAI conference which is of a similar task that is finding text related to trolling of some community. Till now I have constructed 500 tweets.
This is the description of my difficult problem.



2. To show set is subspace it should satisfy all three properties
	i) closed under addition
	ii)closed under scalar multiplication
	iii) 0 belongs to set

combining i) and ii) i.e c*a+b must belong to set ( where c is scalar and a,b belongs to set)


*The set of pairs (a, a + 1) for all real a

Counter Example : (3,2) and (5,4) belongs to given set
			but (3,2)+(5,4) = (8,6) does not  belongs to (a,a+1) 

So it is not satisfying closed under addition property.

  Therefore the given set is not a subspace.   //




*The set of pairs (a, b) for all real a ≥ b

Counter Example: (2,1) belongs to given set 
			but -1*(2,1) = (-2,-1) does not belong to (a,b) a ≥ b

So it fails to satisfy the closed under scalar multiplication 

	Therefore the given set is not a subspace. //



* The  set  of  pairs (a, 2a)  for all real a

let (x,y) and (s,t) belongs to given set i.e (x,2x) and (s,2s)
then (x,2x)+(s,2s)=(x+s,2(x+s)) belongs to given set   --closed under addition

let (x,y) belongs to given set i.e (x,2x)
then a*(x,2x) = (ax,2(ax)) belongs to given set 	--closed under scalar multiplication

0 belongs to given set i.e (0,2*0)=(0,0)  		-- zero belongs to given set

So, It satisfies all three properties.

Therefore given set is Subspace   //



* The set of pairs (a, b) for all non-negative real a,b

Counter Example: (1,2) belongs to the given set i.e 1 and 2 are non-negative real

but		-1*(1,2) = (-1,-2) does not belongs to given set.

So it fails to satisfy the closed under scalar multiplication property.

Therefore given set is not a Subspace. //


					----------------------- So only the 3rd set is the subspace.-----------------------------

