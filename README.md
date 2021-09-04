# Advanced-programming-database-assignment
During my "Advanced Programming" university CS module, an assignment was set to develop a prototype application that demonstrates how data from a given data set can be formatted, cleaned, and used to generate specific outputs from a client brief. The given datasets consists over 1 million data values combined about restuaurants - committed violations, inspections scores, location information, owner information, etc. 

### For detailed explanation of system please have a read of my final report.

My approach to this assignment was to first import and analyse the three given datasets (violations.csv, inspections.csv and inventory.csv). Once I understood the datasets, data pre-processing techniques were implemeneted. I ensured the required client output values were generated correctly using various data visualisation techniques. 

When the backend of the project was complete, I implemented tkinter module for my graphical user interface with my code. Before I began the frontend design, I developed several draft  designs through wireframing using Lucidchart.

Lastly, the use of MongoDB as my database where I was able to store and load my data.

## Functional requirements 

- A means to load the initial data set (which consists of three CSV files) and translate it into a suitable format, either XML, or JSON or an entity relationship structure (not CSV) 
- A means to back up the data in this format using either files or a database. This should preserve the current state of the data when the program is closed.
- A process for cleaning and preparing the initial data set, managing inconsistences, errors, missing values and any specific changes required by the client (see below)
- A graphical user interface(s) for interacting with the data enable the user to:
•Load and clean the initial data set    
•Load and save the prepared data set
•Use the prepared data set to generate output and visualisation   
•Manipulate the range of values used to generate output and visualisations

It should be assumed that this program will be able to handle other sets of data generated from the same source, i.e. data with the same column row headings but containing different values and anomalies. However, the application is not required to be generic (work with multiple unknown data sets). Given this best practice regarding code reuse, encapsulation and a well-defined programming interface should be applied where applicable.

## Non-Functional requirements 

- The GUI interface provides appropriate feedback to confirm or deny a user’s actions
- The application manages internal and user-generated errors

## Technical Requirements 

- The application is built using Python 3.7.* and above
- The application uses advanced APIs such as: NumPy, panda, Seaborn, Matplotlib
- The application runs within the anaconda environment using a Jupyter notebook
- The application or its parts do not run concurrently, do NOT use Python threads

### Wireframe - Lucid Chart

![image](https://user-images.githubusercontent.com/58150120/132091516-7e186d50-30d2-4fc7-aacd-4d40575447ea.png)

### Application - tkinter GUI 

![image](https://user-images.githubusercontent.com/58150120/132091613-2d84b7ec-6ebf-472d-9488-bc5ed8632650.png)

### Data Visualisation example - Matplotlib

![image](https://user-images.githubusercontent.com/58150120/132091559-ba441912-8288-4dc3-81e0-1eeae5004c44.png)

### Program flowchart - Lucid Chart

![image](https://user-images.githubusercontent.com/58150120/132091594-a22d6375-ea85-4cef-9158-1320107a26da.png)

### File extracting, storing and converting from MongoDB Database, with threading - Lucid Chart

![image](https://user-images.githubusercontent.com/58150120/132091505-6de6d341-d5b9-42bb-b634-c8f1b9f2fffb.png)


