# Get Next Line

![Project Header Image]
<div align="center">
  <img src="https://drive.google.com/uc?id=13fb13GcGJBTMfbp22F_Oajd6EblK2UGF" alt="get_next_line Header" width="100%">
</div>

## 📝 Project Description

Get Next Line is a C programming project that implements a function to read lines from a file descriptor efficiently. The main goal is to create a function `get_next_line()` that reads a line from a file descriptor each time it's called.

## ✨ Key Features

- Reads lines from a file descriptor one at a time
- Works with both file and standard input reading
- Uses a configurable buffer size
- Handles multiple file descriptors (bonus part)
- Demonstrates the use of static variables in C

## 🛠 Compilation

Compile the project with the following command:

```bash
cc -Wall -Wextra -Werror -D BUFFER_SIZE=42 get_next_line.c get_next_line_utils.c
```

Note: The `BUFFER_SIZE` can be modified during compilation.

## 📋 Requirements

- Written in C
- Follows the Norm coding standards
- No memory leaks
- Proper memory management
- Handles various buffer sizes

## 🚀 Mandatory Part

- Function prototype: `char *get_next_line(int fd)`
- Returns a line read from the file descriptor
- Returns `NULL` when nothing more to read or on error

## 🌟 Bonus Part

- Manage multiple file descriptors simultaneously
- Use only one static variable
- Additional files: 
  - `get_next_line_bonus.c`
  - `get_next_line_bonus.h`
  - `get_next_line_utils_bonus.c`

## 📦 Files to Submit

- `get_next_line.c`
- `get_next_line_utils.c`
- `get_next_line.h`

## 🧪 Testing

Recommended to create test programs to verify:
- Different buffer sizes
- Various file types
- Multiple file descriptors
- Edge cases

## 📌 Notes

- Avoid using `lseek()`
- No global variables allowed
- Undefined behavior if file descriptor changes between calls

## 💡 Learning Objectives

- Understand static variables in C
- Implement efficient file reading
- Practice memory management
- Handle file descriptor reading

## License

[Your License Here]
