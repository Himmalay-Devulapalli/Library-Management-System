# Library-Management-System

 Library Management system with attractive graphical user inteface developed using python oops concept, Tkinter, Fireabase.
 
# Features
 Splash Screen\
 Main Menu\
 QR Code Scan\
 Issue Book\
 Return Book\
 Renew Book\
 Student History\
 Notify Delay\
 Admin Access
 

# Splash Screen
The application starts with a splash screen that displays about 10 seconds
![alt text](https://github.com/Himmalay-Devulapalli/Library-Management-System/blob/main/images/splash_screen.png)

# Main Menu
This is the main window of the library management system where the access menu is displayed.

![alt text](https://github.com/Himmalay-Devulapalli/Library-Management-System/blob/main/images/Main_menu.png)

# QR Code Scan 


# Issue Book
![alt text](https://github.com/Himmalay-Devulapalli/Library-Management-System/blob/main/images/issue_book.png)

The Issue Book window has the entry options for issuing a book. The scan button will scan the qr code from student id card and student id is displayed automtically 
ensuring the proper useage of application.

![alt text](https://github.com/Himmalay-Devulapalli/Library-Management-System/blob/main/images/issue_book2.png)



# Return Book

The return book window provides the features for receiving the book back from student. The student ID must be scanned in order to fetch the details from database.
Details like issued date, return date, renew count, overdue will be displayed. Receive Book button action will reflect in the backend by updating the status of the book.

![alt text](https://github.com/Himmalay-Devulapalli/Library-Management-System/blob/main/images/return_book.png)

# Renew Book
The renew book window gives the inteface to renew the book. This will work only if the Student id is scanned. A book can only be renewed once.A warning will be raised if a book is tried to renew twice.

![alt text](https://github.com/Himmalay-Devulapalli/Library-Management-System/blob/main/images/renew_book.png)

# Student History
Student History window is designed to view the history of a student. The student id can be entered and all the previous operations of the student can be viewed in a tabular form.

![alt text](https://github.com/Himmalay-Devulapalli/Library-Management-System/blob/main/images/stud_hist.png)

# Send Delay Mails
This feature is provided to send notification mails to the students whose book duration is about to end oralready exceeded. yagmail module is used to send the mail using SMTP protocol.

![alt text](https://github.com/Himmalay-Devulapalli/Library-Management-System/blob/main/images/mails.png)

# Settings
The settings window gives access to the appliation settings and credentials. This window is secured by admin id and password.

![alt text](https://github.com/Himmalay-Devulapalli/Library-Management-System/blob/main/images/settings.png)

The settings window can only accessed by the authorized person as it contains the sesitive data of the application like database url, email id, email password, admin id, admin password. These credentials are stored locally in the config file using configparser module. The authorized person can modify details anytime.

![alt text](https://github.com/Himmalay-Devulapalli/Library-Management-System/blob/main/images/settings2.png)


