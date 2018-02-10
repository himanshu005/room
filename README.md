****Components of Room****
	**We have 3 components they are**
		**_Entity_** : 
			  It’s nothing but a model class annotated with @Entity where all the variable will becomes column name for the table and name of the model class becomes name of the table.

		**_Database_**: 
			  This is an abstract class where you define all the entities that means all the tables that you want to create for that database.

		**_Dao_**: 
			  This is an interface which acts is an intermediary between the user and the database. All the operation to be performed on a table has to be defined here.