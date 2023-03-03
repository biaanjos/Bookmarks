# Bookmarks
React Native Group Project - Cross-Platform Mobile Development course - fall/2022 

An app to search for books and save them to read later

Objective:
The goal is to create a mobile-designed book-searching interface. 
The home page is a list of the current new-york-times best-sellers.
The search page allows the user to search for any book by either the book's title or the author's name. 
The search will return the first 10-20 books found using a Google API. 

When selecting a book, a dedicated display of the book's cover image, title, author, pub date, etc should be visible. 
A button to add the book to the favourites tab will be available for the user. 
When selecting the favourites tab, all books the user marked should be visible.

The history page shows the previous searches. If the user selects any previously searched entries, the user should be redirected to the search. Selecting a book in its history pulls up the individual display.

Platform:
Designed for Android and IOS, Android priority.

APIs: 
https://api.nytimes.com/svc/books/v3/lists/hardcover-fiction?response-format=json&api-key=yYyHlpxh9hNIObhzKkBH4eirfaqEW3QW

https://www.googleapis.com/books/v1/volumes?q=9780743273565+isbn&maxResults=1

The application meets all the criteria below:
#	Component	Criteria
1.		Redux Store	
	At least 15 different actions 
	At least three different reducers for three different components.
2.		Flexbox Layout System	
	Responsive to both iOS and Android devices
	Employ your creativity in designing a good UI that is responsive and attractive.
3.		Touchable Components	
	Custom buttons
	optional use of PanResopnder
4.		FlatList or SectionList	
	An interactable list is made up of valid and useful information for the user.
5.		API Calls	
	At least two different API calls. You can use fetch() or any other approach.
6.		Navigation 	
	At least five different pages/screens 
	You must use parameters to pass information between screens in at least two instances
7.		Modals	
	Two instances of using Modal
	At least one instance of using Alert
8.		Animations	
	At least five different animated values 
	At least 2 different composed animations using delay(), parallel(), sequence() or stagger() methods.
9.		Progress	
	Use of Progress bar in at least two different instances.
10.	    Project Config	
	The project has an appropriate name, version, and icon
