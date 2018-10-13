# collections-challenges
ArrayList and LinkedList in Java


1.	ArrayList challenge:

•	Create a program that implements a simple mobile phone with the following capabilities.
•	Able to store, modify, remove and query contact names.
•	You will want to create a separate class for Contacts (name and phone number).
•	Create a master class (MobilePhone) that holds the ArrayList of Contacts.
•	The MobilePhone class has the functionality listed above.
•	Add a menu of options that are available.
•	Options: 
o	Quit
o	Print list of contacts
o	Add new contact
o	Update existing contact
o	Remove contact and search/find contact.
•	When adding or updating be sure to check if the contact already exists (use name).
•	Be sure not to expose the inner workings of the Arraylist to MobilePhone (e.g. no ints, no .get(i) etc.)
•	MobilePhone should do everything with Contact objects only.

2.	LinkedList challenge:

•	Create a program that implements a playlist for songs.
•	Create a Song class having Title and Duration for a song.
•	The program will have an Album class containing a list of songs.
•	The albums will be stored in an ArrayList.
•	Songs from different albums can be added to the playlist and will appear in the list in the order they are added.
•	Once the songs have been added to the playlist, create a menu of options to:
-	Quit.
-	Skip forward to the next song.
-	Skip backwards to a previous song.
-	Replay the current song.
-	List the songs in the playlist.
•	A song must exist in an album before it can be added to the playlist (so you can only play songs that you own).
•	As an optional extra, provide an option to remove the current song from the playlist (HINT: listiterator.remove())
