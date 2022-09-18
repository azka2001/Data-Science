DATA SCIENCE WEEK 1

AZKA AHMAD
	TASK 1 – 30TH AUGUST  
	WHAT IS DATA SCIENCE?

NEED FOR DATA SCIENCE
-	Self-driving cars, needed in airline systems such as having proper data of weather to predict whether flights will be leaving so passenger’s time is saved, learning passenger preferences and using that to give promotional offers etc
-	Companies making use of this: FedEx
-	Major need of data science:
1.	Better decision making
2.	Predictive analysis
3.	Pattern discovery
-	Data science can be used to answer questions by considering the data of factors relating to a situation, eg analysis done by Netflix to see people’s preferences of shows and thus recommending those shows or appropriate ads related to that 
-	How to go about with data science: 
1.	Analyze the data enough to know what type of questions to ask
2.	Model an algorithm to appropriately answer the questions
3.	Run the data to get the visualizations to present the analysis and insight of the data
	DIFF BETWEEN BUSINESS INTELLGENCE AND DATA SCIENCE
Business intelligence was done upon structured data such as one in RDMS and thus required the creation of a data warehouse to be studied in a unified system. More analytical in nature, just to prove a hypothesis for example. Requires less stats and more visualization. Work is on historical data
Data science uses both structured and unstructured data and then you perform analysis on that. You try to understand on a deeper level how the data represents the happening of a process. Involves a greater number of stats. Work on historical data with other info to create predictions 
	PREREQUISITES FOR DATA SCIENCE
-	Curiosity
-	Common sense and creativity to analyses data from new ways 
-	Communication skills 
Others include:
-	Machine learning 
-	Mathematical modelling 
-	Statistics 
-	Computer programming, usually python
-	Databases 
	TOOLS/SKILLS USED IN DATA SCIENCE 
For data analysis
-	Python, stats 
-	SAS, Jupyter notebook, excel 
	For data warehousing 
-	ETL, SQL
-	Aws redshift
	For data visualization
-	R, python libraries 
-	Jupyter notebook, tableau 
	For machine learning 
-	Algebra, algos
-	Spark ml lib etc
	WHAT DOES A DATA SCIENTIST DO 
Have real world problems, gather the data, format it properly and process and analyze it, feed it into the analytical system, receive an output and design it to present it 
	MACHINE LEARNING ALGOS
Regression (is more on continuous values) -> clustering(unsupervised learning technique) -> decision tree(used for classification and makes it easier to tell why a certain object is classified in a way) -> support vector machine(classification) -> naïve baiyes
	LIFECYCLE OF A DATASCIENCE PROJECT
-	Understand the problem and its relating factors, concepts 
-	Prepare and gather your data (data munging/manipulation) explore the data, there may be gaps in the data etc
-	Data preparation: data integration, data transformation, data reduction, data cleaning 
-	If we have missing values: if the data is large and only a couple are missing, remove them; take the mean value and fill that in instead, median value; split the data into parts, 
-	Model planning: deciding what algorithm you’ll apply to the data, exploratory data analysis which is a deeper understanding of our data set and what things need to be fixed in that, using histograms, plots etc to see trends 
You train the model and then test the data so that we can know whether the model works 
Tools: R, python, MATLAB, SAS
-	Model building: linear regression model etc, eg how the process works by coming up with a relation between an independent and dependent variable , you use test data to check whether the model works or not, we can use libraries like pandas and numpy in python
-	Communicate the result to concerned people with a presentation 
	DEMAND FOR DATA SCIENTISTS?
-	Required in gaming, healthcare, finance, marketing, tech where the industry is greatly consumer based 

	TASK 2 - 31ST AUGUST

BASICS OF PROBABILITY 
-	Probability: Measure of the likelihood of an event. 
-	You need to find the entire sample space to find the probability which is:
-	Probability = number of ways an event can occur/possible number of outcomes 
-	Mutually exclusive event: an experiment where one outcome is possible, eg you can only get a head or a tail if you toss a coin, no overlap in the venn diagram 
-	When you have to find the probability of a scenario, first check whether it’s a mutually exclusive event or not 
-	 Additive rule for mutually exclusive events is adding the probability of each event 
-	p(A or B) = p(a) + p(b)
-	Additive rule for non-mutually exclusive events:
-	First find the probability of the first event asked, then the second event, then finding the intersection probability, and so your formula will be adding the first two probabilities and subtracting the intersection probability
-	P(a or b) = p(a)+ p(b) – p(a intersection b)
-	Multiplicative rule
-	Independent event: each individual event is not dependent on each other, no of total outcomes do not reduce
-	Dependent event: the total sample space may decrease after one event, there is dependency between events, no of total outcomes do reduce 
-	OR means either one, AND means one after the other 
-	For independent events: p(a and b) = p(a) x p(b)
-	For dependent events, we use conditional probability : p(a and b) = p(a) x p(b/a) <- probability of b given a
-	Eg, if we remove one card, we’re left with 51 in the deck, so the sample space for p(b/a) will be from 51
-	In machine learning, via probability a model will be able to predict where a new data point will belong in classification

	TASK 3 - 1ST SEPTEMBER

COMBINATORICS
-	This focuses upon the combination of objects that belong to a countable set and may have constraints surrounding them as well. 
-	Addition, Subtraction and Inclusion Exclusion fall under major categories through which combinatorics can be done. Sub categories which stem from these include the use of permutations and combinations 
-	A further example can be as to how to arrange a line of people at a bank so that people borrowing and depositing money can easily be catered to without the bank running out of money

	TASK 4 - 2ND SEPTEMBER

•	LEARNING PYTHON
HELLO, WORLD!
-	Print function,
-	print(“Hello, World!”) parentheses required for python3
-	Python indentation requires 4 spaces
•	VARIABLES AND TYPES
-	Every variable in python is an object, python is an object-oriented language 
-	It supports integers and floating-point numbers 
-	Eg of an integers 
-	myInteger = 8
-	Strings can either be declared in double or single quotes (double quotes make it easier to integrate apostrophes)
-	Name = “azka”
-	Operators such as + can be used to concatenate strings and add integers
-	You can assign values to two variables on a single line, eg a,b = 3,4 
You cannot concatenate or mix two different types of variables
•	LISTS
-	These are similar to arrays and can contain any type of variables. 
Ways to declare a list:
1.	Mylist = [0,10,20]
2.	You can perform multiple functions on lists such as append(value) which adds on a value to the list
