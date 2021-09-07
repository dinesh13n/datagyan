#datagyan library
This library is focused on data mining and EDA process.

Objective :- Objective of this library is to simplify the EDA process, where user can use the available methods and get the results in few lines of code. 
We are Planning to add some more methods in future, so the user can leverage  that functionality.  

Package name for this library is datagyan, where we have below file structure.

datagyan
   |
   |
   --- datamining.py
           |
		   --- datainfo (Class)
				|
				|
				----- valuetable(df-> Dataframe)
				|
				----- nullvaluechart(df, plotwidth, plotheight, xlabelrotation, textfontsize, percent)
				
				
Description of class and methods :
	datamining.py -> This is library file, which has class and methods written in python language.
	datainfo -> This is class, which has multiple methods onit.
	valuetable -> This is method inside datainfo class. This method takes input as dataframe and calculate column value to get null value count, column datatypes and unique value 		count from all the columns. New dataframe is the output from the method.
	nullvaluechart -> This is another method on datainfo class, where this method takes dataframe as input and represent the bar chart of the null value count as output. This method has option to represent the bar chart with % of the null value count or with only null value count.
				