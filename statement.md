# Problem Statement 
Manually keeping track of book availability and anticipated return dates can be laborious and prone to mistakes in a small library or college setting.  Librarians need a dependable tool to quickly update the inventory status (e.g., after a book is checked out or returned), and students need an easy way to find out if a book is currently in stock.

 The need for a digital, interactive system to manage the library's book inventory is addressed by this project, which offers unique features suited to the roles of a student and a librarian.
 
 # Scope of the project
 It's a straightforward Python command-line tool for managing book availability that can be used by both students and librarians.

 For students: You can quickly find out whether the book is currently available and how many copies are in stock by searching by title (such as "Calculus").  The system indicates the anticipated return date if it has been checked out.

 For librarians: Using the Book ID, you can quickly update the stock count (available copies), guaranteeing that the system's status is always correct when books are checked in or out.

 This project illustrates fundamental data management in a useful, interactive application by simulating the inventory using a list of dictionaries.

 # Target users
 1. Principal End Users (The Roles of the Library):

 Librarians and Library Employees:  Accurate inventory is their main objective.  When books are checked in or out, they use the system's Librarian interface to effectively update available copies and set the anticipated return date, keeping accurate records.

  Customers and college students must easily check the status of their books.  They can use the system to find the important anticipated return date for items that have been checked out or to search by title to view current availability and stock counts.

 2. Developer/Secondary Users:

  Novice Python Programmers:  This project is a great way to practice basic Python concepts like functionality separation and input validation, learn how to handle lists of dictionaries (simulating data), and implement a basic CLI structure.

  # High-level features
  1. Information and Storage
 In-Memory Inventory: This method simulates volatile data storage using a Python list of dictionaries called library_inventory.

 Detailed Records: Book_id, total_copies, available_copies, and return_date are all included in each book.

 2. Role-Based Interface Separated Access: Ensures functionality segregation by offering an interactive menu to choose between the Student and Librarian roles.

 3. Student Activities
 Intelligent Search: Enables partial-match, case-insensitive book title searches.

 Status Reporting: Instantaneously reports whether the book is NOT AVAILABLE or AVAILABLE NOW (with count), along with the anticipated return date if noted.

 4. Librarian Functions Inventory Update: This feature enables librarians to use the book_id to update the available_copies count.

 Validation: Makes sure the new count does not surpass the total number of copies and includes checks to prevent negative stock.
