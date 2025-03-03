# SNHUProjects2025

- CS210-Maximo Winfield 

- Instructor: Cynthia Marcello 

- 3/2/2025 

# Corner Grocer Item Tracking Program

## Project Summary
The **Corner Grocer Item Tracking Program** is a **C++ application** designed to analyze and process **grocery transaction records** from a text file. The program reads an input file containing **purchased items**, calculates the **frequency of each item**, and creates a **backup frequency file** (`frequency.dat`). Additionally, it provides a **menu-based interface** that allows users to:

1. Search for a specific item's frequency.
2. Print a complete list of item frequencies.
3. Display a **histogram** using asterisks to represent item counts.
4. Exit the program.

## Strengths and Accomplishments
I believe I did particularly well in:
- **Data Handling Efficiency**: The use of **maps (`std::map`)** allows for quick frequency lookups.
- **File Operations**: Implementing file I/O operations to read and write **frequency data** ensures the program can process external input and create persistent backups.
- **User Input Validation**: Handling invalid inputs prevents unexpected behavior.
- **Modular Design**: Encapsulating logic within the `ItemTracker` class promotes **code reuse and maintainability**.

## Areas for Improvement
To improve the program, I would:
- **Enhance Input Validation**: More robust validation could be added to handle **case sensitivity** (e.g., treating "Apple" and "apple" as the same item).
- **Optimize File Handling**: Using **unordered maps** (`std::unordered_map`) instead of `std::map` could improve performance for large datasets due to **faster lookups**.
- **Improve User Interface**: Implementing **color-coded output** or a more intuitive command-line UI would improve **usability**.

## Challenges and How I Overcame Them
One of the biggest challenges was ensuring that **file I/O operations** were handled properly, especially when reading from and writing to external files. To overcome this:
- I used **error handling** (`if (!fin) { cerr << "Error opening file"; }`).
- I **tested with different input files** to ensure the program handled various cases.
- I referenced **C++ documentation** and used online resources like **cplusplus.com** and **Stack Overflow**.

## Transferable Skills
This project reinforced several **important programming skills** that are transferable to future projects:
- **Working with Data Structures**: Understanding **maps** and their efficiency will be useful in other programming tasks.
- **File I/O Operations**: Reading, writing, and processing **external files** is a fundamental skill for software development.
- **User Interaction & Input Handling**: Properly handling user input to prevent errors is essential in real-world applications.

## Code Maintainability & Readability
I focused on **keeping the code modular and well-documented**:
- **Encapsulated logic** within the `ItemTracker` class.
- **Added comments** to explain functionality.
- Used **meaningful variable names** for clarity.
- Followed **consistent indentation and formatting** for readability.

---

### GitHub Repository
[📌 Corner Grocer Item Tracking Program](https://github.com/DaBest890/SNHUProjects2025/)
