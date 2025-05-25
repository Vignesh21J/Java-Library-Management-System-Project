# Library Management System

A simple *console-based Java application* that simulates the core features of a library system, including managing books and members. The project supports two roles: *Admin* and *User*, each with their own capabilities.

---


## Features

### Admin
- Login with predefined credentials.
- Add new books.
- Update existing book details.
- Remove books.
- Add new members.
- View all books and members.

### User
- Login (auto-register if not already a member).
- Borrow books (max limit: 5 at a time).
- Return borrowed books.
- View all books and members.

---

## Roles

### Admin Credentials
- *Username:* HardCoded
- *Password:* HardCoded

### User Access
- Simply enter a username to log in.
- If the user is new, the system auto-creates a member profile.

---

## Getting Started

### Prerequisites
- Java JDK 8 or above
- IDE or terminal to run Java programs

### How to Run
1. Clone or download the project.
2. Navigate to the oops_project directory.
3. Compile the program:
   ```bash
   javac LibraryManagementSystem.java
