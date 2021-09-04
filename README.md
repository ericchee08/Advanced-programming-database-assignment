# Advanced-programming-database-assignment
During my "Advanced Programming" university CS module, an assignment was set to develop a prototype application that demonstrates how data from a given data set can be formatted, cleaned, and used to generate specific outputs from a client.

##Functional requirements 

- A means to load the initial data set (which consists of three CSV files) and translate it into a suitable format, either XML, or JSON or an entity relationship structure (not CSV) 
- A means to back up the data in this format using either files or a database. This should preserve the current state of the data when the program is closed.
- A process for cleaning and preparing the initial data set, managing inconsistences, errors, missing values and any specific changes required by the client (see below)
- A graphical user interface(s) for interacting with the data enable the user to:
•Load and clean the initial data seto    
•Load and save the prepared data seto    
•Use the prepared data set to generate output and visualisationso    
•Manipulate the range of values used to generate output and visualisations

It should be assumed that this program will be able to handle other sets of data generated from the same source, i.e. data with the same column row headings but containing different values and anomalies. However, the application is not required to be generic (work with multiple unknown data sets). Given this best practice regarding code reuse, encapsulation and a well-defined programming interface should be applied where applicable.

##Non-Functional requirements 

The GUI interface provides appropriate feedback to confirm or deny a user’s actions•The application manages internal and user-generated errors

##Technical Requirements 

- The application is built using Python 3.7.* and above
- The application uses advanced APIs such as: NumPy, panda, Seaborn, Matplotlib
- The application runs within the anaconda environment using a Jupyter notebook
- The application or its parts do not run concurrently, do NOT use Python threads
