# CS-132

Project Report: Library Management System


Description of the Project:
The Library Management System project aims to provide a platform for managing books, patrons, transactions, and generating reports efficiently. The system allows librarians and admins to perform various operations such as adding books, updating quantities, handling fines, and more.

Structure of the Code:
The code consists of classes like `Book`, `Patron`, `Transaction`, `Librarian`, `Admin`, and `Library`. These classes are interconnected to manage different aspects of the library system. The code utilizes SQLite for database integration, ensuring data persistence across sessions.

Code Structure Analysis:
The codebase of the Library Management System project follows a well-organized structure, with distinct classes responsible for specific functionalities. The Book class handles book-related information such as title, author, ISBN, and quantity from the library inventory. On the other hand, the Library class manages functionalities like patron registration, borrowing books, and returning books.

Furthermore, the SQLite database integration in the project facilitates efficient data storage and retrieval. The database schema is appropriately designed to store information about books, patrons, borrowing history, and other relevant details. By leveraging SQLite, the system ensures data consistency and integrity, enabling seamless management of the library resources. I chose SQL because I recently did a Google Cybersecurity Certificate which taught me a little about SQL and I wanted to expand and learn more about it. I think for this project it got the job done.


Instructions for Full Functionalities:
To utilize the code's full functionalities:
1. Add books using the provided format.
2. Add patrons by entering their details.
3. Checkout books by providing the book's ISBN and the patron's ID.
4. Return books when necessary.
5. Generate reports to view details on books, patrons, and transactions.


Verification of Code Sanity:
The code includes error handling mechanisms and database management to maintain the integrity of operations. The use of SQLite for persistent storage ensures that data remains consistent and accurate throughout interactions.


Screenshots or Examples:
- Inputting details for adding books and patrons.
  
![image](https://github.com/Faahil/CS-132/assets/162076014/b01fb003-02cc-4b36-9eef-0caf1c1acb27)

![image](https://github.com/Faahil/CS-132/assets/162076014/3b443ddd-a671-4655-96c6-14caf1e2d840)


- Command line interactions for checking out and returning books.\
  
 ![image](https://github.com/Faahil/CS-132/assets/162076014/bf983d0b-09b3-4570-a977-da6862b2b3f8)

![image](https://github.com/Faahil/CS-132/assets/162076014/17e915ec-c43e-46e6-9b45-33885380c8b8)

 
- Displaying generated reports depicting book details, patron information, and transaction history.
  
![image](https://github.com/Faahil/CS-132/assets/162076014/ee9960ec-3a11-431c-9c2e-18a9b27bed4f)



Sample Scenarios:
1. Adding Books:
   - Add "Introduction to Python" with author "Mike Driscoll" and quantity 5.


![image](https://github.com/Faahil/CS-132/assets/162076014/c6dac46e-4c84-4e2b-a15c-70e63518c89b)

 
2. Checking Out Books:
   - Check out a book with ISBN "987654321" for patron "Bill Brown (ID: 0002)."


![image](https://github.com/Faahil/CS-132/assets/162076014/e22a2509-70f6-4099-9fbe-abdd1b077e60)

 
3. Generating Reports:
   - Access reports displaying book inventory, patron details, and transaction records.
 
![image](https://github.com/Faahil/CS-132/assets/162076014/3a9d9e6f-1b33-4f82-bdab-2c4e2d3a0a21)


![image](https://github.com/Faahil/CS-132/assets/162076014/9084efba-c4b0-4488-bc25-6b26f97fd7f7)


 
Discussion of Findings:
Throughout the project, challenges were faced in implementing the database structure and ensuring seamless interactions between classes. My most difficult issue was indention errors; I think it wasted a lot of my time and fried my brain. Other limitations include the lack of adding fines implementation functionality in the core system in the beginning. Areas for improvement involve enhancing the user interface for a better user experience and adding more robust error handling mechanisms.


The project showcases the effective utilization of object-oriented programming principles in building a functional Library Management System. The system can be further refined to meet evolving requirements and provide a more intuitive user experience which I hope I will be able to learn soon. 


User Interface Enhancements:
To enhance the user experience of the Library Management System, consider implementing a graphical user interface (GUI) in addition to the existing command-line interface (CLI). The GUI can provide users with a more intuitive and visually appealing way to interact with the system, offering features such as:



•	Interactive forms for adding or updating book information

•	Visual representations of the library inventory, borrowed books, and member details

•	Search functionality with filters for easy navigation and book lookup

•	Notifications for overdue books, pending requests, or system updates

•	By incorporating a GUI, the system will become more user-friendly and accessible to a wider range of users, thereby improving overall usability and satisfaction. Additionally, the GUI can enhance the aesthetic appeal of the application, making it more engaging and modern. Although this is not like Code.org or Java so I will need some time to learn all these. 


User Feedback and Usability Testing: 
Insights gathered from user feedback and usability testing sessions can influence/improve decisions, feature implementations, and bugs. I think the user feedback is always helpful because I feel it’s harder for the creator to find bugs, it's usually the user who will find all the mistakes. 

