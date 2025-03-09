
# 📚 BookNest Library Hub

BookNest Library Hub is a library management system built using Tkinter and MySQL. It allows students to register, borrow and return books, report issues, and pay fines. Administrators can manage books, view user activities, and resolve book-related issues



## 🚀 Features
### 📌 Student Panel

- User Registration & Login: Students can register and log in to access the library system.
- View Available Books: Students can check the list of books available in the library.
- Borrow Books: Users provide their ID, name, book details (ID, name, author), and the system generates a receipt with:

   - Student ID
   - Student Name
   - Book ID
   - Book Name
   - Author Name
   - Borrow Date
   - Due Date
- Return Books: Students can return borrowed books.
- Book Issue Report: If a book has an issue (damaged or missing pages), users can report it.
- Fine Payment: If a book is returned after the due date, users must pay a fine before returning the book.
- Book Availability Restriction: A book can only be borrowed by one user at a time. Once returned, it becomes available for others.
- Logout: Users can securely log out from their accounts.
### 🔐 Admin Panel
- Admin Login: Admins can log in to manage library operations.
- View Student Details: Admins can check registered students and their borrowing history.
- Manage Books:
    - Add new books to the library.
    - View borrowed and returned book details.
    - Address book issues reported by students.
    - Update book availability after resolving issues.
## 🛠️ Technologies Used
- Python (Tkinter for GUI)
- MySQL (Database for managing users and books)

## 📖 Installation & Setup

 - ### Install Dependencies

```bash
  
  pip install mysql-connector-python

```
### Set Up the Database

  - Create a MySQL database.
  - Import the provided SQL file to set up tables.
## Screenshots

![1](https://github.com/user-attachments/assets/a7a805ba-a5c2-4c00-a720-e5270ae36234)

![2](https://github.com/user-attachments/assets/14a8780e-3477-4fa3-9c55-81604a969dc5)
![3](https://github.com/user-attachments/assets/c50b7708-a32d-4a55-bdf6-5f5dc286cb31)
![4](https://github.com/user-attachments/assets/9dfb1774-d5de-4ed8-8492-d97cbf5e6163)
