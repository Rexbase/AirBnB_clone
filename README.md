**AirBnB Clone: The Console**

![hbnb](https://user-images.githubusercontent.com/37456764/204332091-29f1d557-e9a1-4970-be18-2b2ecebfc234.png)

**Overview:**

![clone](https://user-images.githubusercontent.com/37456764/204332114-ee06f78b-4830-4ea1-a3ed-9dcc5f362c2e.png)

Airbnb has revolutionized the hospitality industry, empowering people to rent out their spaces and explore unique accommodations. Our task is to clone Airbnb, focusing on creating the console with Python. The console plays a crucial role in the project as it allows us to create, destroy, show, save, and update our BaseModel. This framework is inheritable by other classes or categories.

**How to Start the Console:**

```bash
AirBnB_clone$ ./console.py
(hbnb)
(hbnb)
(hbnb) all
[]
```

**How to Use the Console:**

- To create a new user:

```bash
(hbnb) User.create()
f13ed552-549a-4e1b-8757-3842aaba9ccc
(hbnb) User.all()
["[User] (f13ed552-549a-4e1b-8757-3842aaba9ccc) {'updated_at': datetime.datetime(2017, 10, 4, 18, 21, 27, 164392), 'email': '', 'created_at': datetime.datetime(2017, 10, 4, 18, 21, 27, 164366), 'last_name': '', 'password': '', 'id': 'f13ed552-549a-4e1b-8757-3842aaba9ccc', 'first_name': ''}"]
```

- To show a specific user:

```bash
(hbnb) show User f13ed552-549a-4e1b-8757-3842aaba9ccc
[User] (f13ed552-549a-4e1b-8757-3842aaba9ccc) {'updated_at': datetime.datetime(2017, 10, 4, 18, 21, 59, 114711), 'email': '', 'created_at': datetime.datetime(2017, 10, 4, 18, 21, 59, 114685), 'last_name': '', 'password': '', 'id': 'f13ed552-549a-4e1b-8757-3842aaba9ccc', 'first_name': ''}
```

**To Destroy a User:**

The "destroy" command takes in two arguments: name and id.

```bash
(hbnb) create User
f13ed552-549a-4e1b-8757-3842aaba9ccc
(hbnb) show User f13ed552-549a-4e1b-8757-3842aaba9ccc
[User] (f13ed552-549a-4e1b-8757-3842aaba9ccc) {'id': 'f13ed552-549a-4e1b-8757-3842aaba9ccc', 'last_name': '', 'updated_at': datetime.datetime(2017, 10, 4, 19, 18, 40, 976205), 'email': '', 'created_at': datetime.datetime(2017, 10, 4, 19, 18, 40, 976174), 'password': '', 'first_name': ''}
(hbnb) destroy User f13ed552-549a-4e1b-8757-3842aaba9ccc
(hbnb) show User f13ed552-549a-4e1b-8757-3842aaba9ccc
** no instance found **

**To Update User Information:**

The "update" command is used to update User information.

```bash
(hbnb) update BaseModel f13ed552-549a-4e1b-8757-3842aaba9ccc first_name "Betty"
(hbnb) show BaseModel f13ed552-549a-4e1b-8757-3842aaba9ccc
[BaseModel] (f13ed552-549a-4e1b-8757-3842aaba9ccc) {'first_name': 'Betty', 'id': 'f13ed552-549a-4e1b-8757-3842aaba9ccc', 'created_at': datetime.datetime(2017, 10, 2, 3, 10, 25, 903293), 'updated_at': datetime.datetime(2017, 10, 2, 3, 11, 3, 49401)}
```

**Requirements:**

- Python Scripts
- Allowed editors: vi, vim, emacs
- All files should end with a new line
- The first line of all files should be exactly `#!/usr

/bin/python3`
- A mandatory README.md file at the root of the project folder
- Your code should follow pycodestyle (version 2.8.*)
- All files must be executable
- The length of your files will be tested using wc
- All modules, classes, and functions should have appropriate documentation

**Python Unit Tests:**

- Allowed editors: vi, vim, emacs
- All files should end with a new line
- Test files should be inside a folder named `tests`
- The unittest module should be used for testing
- All test files should have the extension `.py`
- Test files and folders should start with `test_`
- File organization in the `tests` folder should mirror your project
- All modules, classes, and functions should have appropriate documentation
