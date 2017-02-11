## Developing a File Transfer Program using Python

### Objective

In this course I was introduced to SQLite and integrating it with Python, as well as tkinter and creating a front end for an application.

The final drill was do the three following tasks:

* Create a database table that tracks the time and date files were last transfered
* Create a GUI for the app, with displays for source and destination folders and date/time files were last transfered
* Create a function that walks through the files in the selected source folder and compares them with the last saved date/time, copying only the ones created or modified since then to the destination folder

### Steps Taken

First I created the GUI, using tkinter's grid geometry method to place the widgets and add functionality to the buttons. Then I created the functions behind the buttons which create the database table the first time it's used. I then created the functions that walk through the source folder, comparing the creation and modification dates to the saved date (or 24 hours ago for the first run) and copy the files to the destination folder.

### Results

Having had experience with SQL already it was easy to work with SQLite and develop the database commands needed to create the simple table needed. It took some research to figure out the functions that walk through the folder, and it took a lot of learning to figure out how to use tkinter and build GUIs.

[Return to Profile Homepage](https://github.com/HenryTech/Portfolio)
