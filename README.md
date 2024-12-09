Fundamentals of software engineering 1
 Project description
 Library Management System
 Students are required to create a fully functioning library management system as a console
 application using either C++ or Java. This system will be completed over 3 phases.
 This system should allow us to perform library management operations such as adding
 books, borrowing books, returning books, and searching for books. Also, the system
 allows for the management of user accounts.
 This system should have 3 different views. We should be able to login as admin, students,
 and librarian. Each of them should be provided a menu that contains functionalities specific
 to them.
 The system will store its data in text files. The students are required to write the application
 such that it can handle storing/deleting/retrieving data in/from the text files. These text
 files will act as our database so that user data will persist in between system runs.
 System Description:
 A library management system should, firstly, allow users to sign up and create accounts.
 The users should specify their personal details and their role (admin, user, librarian). After
 creating an account, a user should be able to log in using their credentials and, according to
 their role, be greeted by a menu containing functionalities related to them.
 Any user should be able edit their personal profile information like username, password,
 age, and gender. However, The user shouldn't be able to edit their role. An admin should
 be able to manage other accounts. An admin can delete/ban/unban a user or librarian
 account, and can change their passwords.
 The system should allow appropriate users to add and remove books from the storage. To
 add a book the user needs to add details such as name, genre, and number of copies.
 The system should allow users to send a request to borrow a book. If the book is available
 the book should be marked as borrowed, otherwise it should be recorded that the user is
 interested in such a book.
 A user should also be able to request an extension to his current borrowing period. This
 request will be accepted if the user doesn't have any overdue books or any unpaid fines.
 The user is allowed a max of 3 extensions. Each extension gives the user an extra week.
 The system will provide a way for the user to return the book and the book shall be marked
 as available after completion. The system will allow the user to rate the books and leave a
 review for each book. Users shall be able to search for books by name or genre. Also, they
 should be able to sort the results by name or by rating.
Furthermore, a user should be able to view reviews for a book. A user can request to
 calculate their total fine based on how long a book is overdue and how many books are
 overdue. The fine is calculated as 1 dollar for each day the book is overdue. Also, the
 system should display the details of the fine (each overdue book and the fine it contributed).
 Finally, The system will send a notification to users if a book they are interested in is now
 available and will notify the users if one of their books is now overdue.
 Phase 1 deliverables :
 ● Asimple SRSdocument that contains:
 ○ At least 15 functional requirements.
 ○ 5nonfunctional requirements.
 ○ Create the use case diagram for the system.
 ● Write 4 formal use case descriptions of the most complex use cases in the system.
 ● Create a github repository for the project. All team members should be added as
 collaborators. SRS document should be present in the github repo.
 ● Create a jira project containing 2 sprints and the Epics that describe the 15
 functional requirements extracted above. Appropriately create user stories and tasks
 from the Epics. Each task must be assigned to at least 1 member. Distribute the
 workload evenly over the two sprints. The tasks status and general progress should
 constantly be updated as you perform tasks. Each sprint will take 10 days.
