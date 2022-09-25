# Grocery-Basket-Android-App
## Android Studio Grocery Shopping App Fully Working  with Local Database

Grocery Basket Android app is created as a wonderful solution for creating a list of grocery items with price calculated with quantity using Rich UI.

It is an Andorid Application that uses MVVM (Model View ViewModel) was used for architectural patterns, Room for database, Coroutines and RecyclerView to display the list of items. 

***LiveData:*** A data holder class that can be observed. Always holds/caches the latet version of data, and notifies its observers when data has changed. LiveData is lifec-ycle aware. UI components just observe relevant data and don't stop or resume observation. LiveData automatically manages all of this since it's aware of the relevant lifecycle status changes while observing. ViewModel: Acts as a communication center between the Repository (data) and the UI. The UI no longer needs to worry about the origin of the data. ViewModel instances survive Activity/Fragment recreation.

***Repository:*** A class that you create that is primarily used to manage multiple data sources. 

***Entity:*** Annotated class that describes a database table when working with Room. 

***Room database:*** Simplifies database work and serves as an access point to the underlying SQLite database (hides SQLiteOpenHelper). The Room database uses the DAO to issue queries to the SQLite database.

***SQLite database:*** On device storage. The Room persistence library creates and maintains this database for you. 

***DAO:*** Data access object. A mapping of SQL queries to functions. When you use a DAO, you call the methods, and Room takes care of the rest. 

***RecyclerView:*** It is a container and is used to display the collection of data in a large amount of dataset that can be scrolled very effectively by maintaining a limited number of views. Coroutines: Coroutines are lightweight thread, we use a coroutine to perform an operation on other threads, by this our main thread doesn't block and our app doesn't crash.

You can use this Android app as to make a list of you are going tu buy when you go shopping. This app make easy for user to make a list of products. App design is so simple any individual with the android devie can easily work with this app.

***Output Files:***

**1] Home Screen ->**
![Home Screen](https://user-images.githubusercontent.com/109810660/192148149-88477faf-b0d5-4825-83a3-3dcf2d28b0ed.jpg)

**2] Add Item Window ->**
![Add Item in the List Activity](https://user-images.githubusercontent.com/109810660/192148193-1f718fec-2082-4785-9010-c003268d2655.jpg)

**3] Inserted Item In The List ->**
![Item Inserted in the List](https://user-images.githubusercontent.com/109810660/192148231-65297dab-68d6-4a2b-a683-497a6926219c.jpg)

**4] Deleted Item From The List ->**
![Item Deleted From the List](https://user-images.githubusercontent.com/109810660/192148252-2a9d72fe-7813-4ecd-8d98-549581a60d1d.jpg)

**YOU CAN WATCH THE PROJECT WALKTHROUGH VIDEO BY CLICKING LINK BELOW**

https://drive.google.com/file/d/1Rhx9D-d9SM5DLZzfaHbTJH3ngFPV1XZl/view?usp=sharing
