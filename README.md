Classes: 
	MainActivity
		This classes purpose is to initalise the home screen and add media to the database
		It implements onClickListeners to monitor the buttons which allows the user to select other options
		
	DatabaseManager
		This class contains main purpose is to initialise a connection the database,
		it also contains all CRUD operations relevant to the database.
		Contains custom methods for retrieving either all media or selected media.
		Also includes methods which are called upon to update table data dynamically
		
	DatabaseHelper
		This class is used to create the database and its table with its respective columns
		
	Media
		This class is used to store attributes for the media object
		which will contain retrieved columns from the table in the database.
		Allows other classes to readily access the data on demand
		
	View
		This class is used to initalise a dataset which will be used to display media in listform.
		Also includes search functionaility which dynamically updates the list depending on the search query
	
	ListAdapter
		This class recieved the dataset initalised from the View class and populates the views in the layout file
		
	
	MediaActivity
		This class is used to operate the expandedview layout which is activated upon trying to expand a list item
		Displays singular media object more details than in list form.
		Includes functionality for adding media items to users list and modifying the users episode count using included buttons
		
	AddCustomMedia
		This classes purpose is to allow the user to manually add their own media to the database
		Has editText boxes for all fields in media object including functionality for taking their own photographs using the android camera API
		which will be displayed on the media item when viewed
		
		
Demo Video: https://youtu.be/dG7WgM8y4EA
