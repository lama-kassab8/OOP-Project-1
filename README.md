# Library Management System 

This is my project for the OOP Final Project. It's a fully working Library Management System that runs in the terminal.

It lets users register, view available items, borrow stuff, return them, and even reserve DVDs and books. Everything is stored in JSON so data doesn’t disappear when the program ends.


#  What it does:

- Shows all available items in the library
- Lets users search for an item by its title or type
- Allows users to register (random user ID is generated)
- Users can borrow and return items
- DVDs and books can be reserved (others can’t)
- Everything gets saved into `.json` files before exiting



# Project structure:
Within the Final OOP Project directory, you'll find two .py files(main.py and exceptions.py) and a Files folder in which you'll find:
    - book.py
    - dvd.py
    - library_item.py
    - library.py
    - magazine.py
    - reservable.py
    - user.py
When the program runs for the first time, you'll find items.json and users.json.

---

# How to run it:

1. Open terminal.
2. Run `main.py`.
3. Pick an option from the menu and follow what it says.

---

# Important notes:

- The program keeps running until you choose to exit.
- Before quitting, it saves all changes to `items.json` and `users.json`.
- Only DVDs and books can be reserved, not magazines.
- Custom exceptions are raised for different cases, like if an item isn't found or is already borrowed, but I handled the printed messages in the main menu itself.
