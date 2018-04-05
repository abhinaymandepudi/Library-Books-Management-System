## LIBRARY MANAGEMENT SYSTEM

**1. Introduction
2. Book Search
3. Book Loans**

```
3.1. Books Checkout
3.2. Books Check-in
```
**4. Borrow Books**

```
4.1. Account Creation
4.2. Borrower History
```
**5. Fines
1. Introduction**

Library Management System provides the basic functionalities of library like

1. Search
2. Check in, check out
3. Add borrower
4. Fines
5. Borrower’s History
2. **Book	Search**

```
Search Implementation is supported using substring matching and also 3 different ways using
```

```
ISBN, Title and Author fields.
```
3. **Book Loans**
    3.1. **Books Checkout**

```
The user can check out the books by entering the CARD ID.
```

```
The user can check out a maximum of 3 books at a time. If the user reaches a borrow limit of 3,
the user has to return the books that he/she has checked out earlier and then proceed for a new
check out. The user cannot checkout a book copy that is not available as the checkout button is
disabled in this case. If the user has an unpaid fine or currently overdue book, an error message
is displayed.
```
```
3.2. Books Check-in
```
```
The user can check-in a book by locating it under the ‘Check In’ tab and entering either the book
information (book name or ISBN) or borrower’s information (borrower’s card id or loan ID).
When the required books are displayed, the user can select a particular book to check-in. Also ,
the due date is shown to the user for the books.
```
4. **Borrow Books**

```
4.1. Account Creation
```
```
A new borrower can create an account by providing the details like Name, SSN, Address, Phone
Number etc. When the user clicks the submit button, a new borrower record is created in the
system. Once a borrower is registered, he/she will not be allowed to register again in the system.
```

**4.2. Borrower History**

```
A user can find the borrower history under the ‘Borrower History’ tab on the web page by entering
only the borrower card ID as borrowers are allowed to possess exactly one library card.
```

5. **Fines**

```
The details of fines for different books for a particular borrower can be known by searching with
the borrower card ID. The total fine a particular borrower has to pay is displayed then and the
user can pay the fine by clicking the ‘Pay’ button.
Also the fines history for a particular user is displayed.
```

