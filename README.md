# IR20222_A1_16

Q1 :

Libraries Used : pandas, glob , os , nltk, re , numpy 

PreProcessing Steps : 
 1. We convert the text to lowercase.
 2. Then we remove punctuations from the data using nltk.
 3. In the next step we remove the stopwords and blank tokens.
 4. Then we perfrom stemmization on the given data.



Q2 :

With the help of library like os we open the file conatining our data.

Libraries used : pandas , os , re, numpy , nltk

Pre-Processing : With the help of libraries like nltk and re, we performed the pre-processing steps that included :

1. Converting the data to lower case using .lower() function
2. Then we remove stopwords from the dataset using nltk_stopwords lib
3. With the help of re library we were able to remove puctuations and white space from the dataset


We created a dictonary positonal_index which contained our terms as keys and their location and freq as values.

To check if the phase query exist :
We will first preprocess our phase_query and then we will see whether the terms exist in our dict or not.
Here instead of directly accesing dict with dict["query"] we will use dict.get("query") because in first case
if term does not exist it raises an error while in the 2nd case it returns None.

 

