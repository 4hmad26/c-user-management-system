# User Management System (C)

##  Repository Name

c-user-management-system

---

##  About This Project

This is a **simple console-based User Management System** written in **C language**.

The program allows users to:

* Register with a username and password
* Login using registered credentials
* Exit the program safely

All user data is stored **temporarily in memory** while the program is running.

---

##  Features

* Written in **pure C**
* Uses **structures (struct)**
* Uses **arrays and strings**
* Menu-driven interface
* Beginner-friendly logic

---

## How It Works

* `User` structure stores username and password
* Maximum **10 users** can be registered
* Credentials are checked using `strcmp()`
* Uses `fgets()` safely for input handling

---

##  How to Compile & Run

1. Make sure GCC is installed
2. Compile the program:

```
gcc user_management.c -o user_management
```

3. Run the program:

```
./user_management
```

---

##  Menu Options

```
1. Register
2. Login
3. Exit
```

---

##  Limitations

* User data is **not saved permanently**
* Password is **visible while typing**
* Supports only **10 users**

---

##  Author

Mohd Ahmad
(BCA Student)
