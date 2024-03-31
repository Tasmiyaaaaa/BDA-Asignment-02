**Fundamentals of Big Data Analytics**

**Assignment # 2**

**Documentation**

**Group Members:**
Faizan Aziz - 22I-1946
Tasmiya Asad - 22I-2060
Ziyan Murtaza - 22I-1998

**Importing required Libraries**

**Usage of libraries required included:**

CSV - reading and manipulating the dataset from the given CSV file.
NLTK – for efficient manipulation of the given text data
STRING – for a list of punctuations
COUNTER – for making counting easier
NUMPY – for vectors

**Reading Data**

Utilizing CSV library to read the data row by row and storing the required columns in a dicitonary

**Cleaning Data and Making Vocabulary**
           
Using NLTK for removing stopwards, punctuations and lower casing and then splitting the data.

Creating a vocabulary.

**Assigning Key Values**

Assigning a unique numerical value to the words present in the vocabulary.

**Conversion to the Keys Assigned**
    
Replacing the words in the document with their respective numerical value for further processing.

**Calculating IDF**
    
Calculating Inverse Document Frequency to assist in assigning the weights later on.

**Calculating TF**
           
Calculating Term Frequency for weights assigning.

**Defining Vectors**

Defining Vectors placing the weights of the words at their specific index with respect to the numerical values assigned to them.
Weights are calculated using formula – TF/IDF

**Processing The Query**
       
Convert the incoming query into a vector just as for the documents.
Multiply the vectors and the store the resultant

**Displaying the results**
   
Displaying all the documents that have a resultant value calculated by vector multiplication greater than 0.1.


