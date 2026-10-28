# 📊 1. Project Title

# NumPy Analyzer

A Python-based command-line application for creating, analyzing, and manipulating NumPy arrays.

## 📝 2. Project Description

NumPy Analyzer is a menu-driven Python application developed using the NumPy library. It allows users to create and perform various operations on 1D, 2D, and 3D arrays through a simple interactive interface.

The project demonstrates fundamental NumPy operations, including array indexing, slicing, mathematical calculations, searching, sorting, filtering, combining, splitting, and statistical analysis.

It is designed to help beginners understand NumPy arrays and their applications in data analysis.

## ✨ 3. Features

| Feature | Description |
|---|---|
| 🔢 Array Creation | Create 1D, 2D, and 3D NumPy arrays. |
| 🎯 Indexing | Access individual elements using index positions. |
| ✂️ Slicing | Extract specific portions of arrays. |
| ➕ Mathematical Operations | Perform addition, subtraction, multiplication, and division. |
| 🔍 Searching | Search for specific values and find their index positions. |
| 📈 Sorting | Sort array elements using NumPy. |
| 🎚️ Filtering | Filter elements based on greater-than and less-than conditions. |
| 🔗 Array Combining | Combine arrays using vertical stacking. |
| 🧩 Array Splitting | Split arrays into multiple sub-arrays. |
| 📊 Statistical Operations | Calculate the sum, mean, and median of array elements. |
| 🖥️ Interactive Menu | Navigate between operations through a menu-driven interface. |

## 🛠️ 4. Technologies Used

- 🐍 Python
- 🔢 NumPy
- 💻 Visual Studio Code (VS Code)
- 🔄 Git
- 🌐 GitHub

## 🚀 5. Installation and How to Run

### Prerequisites

- Python 3 installed on your system.
- pip package manager.
- Visual Studio Code (recommended).
- Git (optional, for cloning the repository).

### Step 1: Download or Clone the Project

Clone the repository using Git:

```bash
git clone <your-repository-url>
```

Navigate to the project directory:

```bash
cd numpy-analyzer
```

Alternatively, download the project files and open the folder in VS Code.

### Step 2: Install NumPy

Open the terminal in VS Code and execute:

```bash
python -m pip install numpy
```

### Step 3: Run the Program

Save the Python code in a file named `main.py` and execute:

```bash
python main.py
```

If your system uses the `python3` command, run:

```bash
python3 main.py
```

### Step 4: Use the Application

1. Select **1** to create a NumPy array.
2. Choose the array dimension: 1D, 2D, or 3D.
3. Enter the required elements.
4. Select an operation from the main menu.
5. Follow the on-screen instructions.
6. Select **6** to exit the application.

## 📂 6. Project Structure

```
│
├── main.py
├── output.png
├── README.md
```

### 🧩 Main Functions

| Functions | Description |
|---|---|
| `DataAnalytics` | Main class responsible for managing array operations. |
| `create_array()` | Takes user input and generates arrays of different dimensions. |
| `indexing_operations()` | Allows users to access individual elements and extract array sections. |
| `math_operation()` | Applies arithmetic operations between two arrays. |
| `search_arr()` | Searches for values, arranges elements in sorted order, and filters data. |
| `combine_arrays()` | Joins two arrays vertically or divides an array into smaller parts. |
| `aggregate_operations()` | Computes basic statistical values such as sum, mean, and median. |
| `main_menu()` | Presents the available features and operation choices. |
| `start_program()` | Runs the application and manages user selections until exit. |

## 🖼️ 7. Project Output

![Project output](output.png)

## 👩‍💻 8. Author / Developer

**Author:** Pansuriya Princy

**Project Name:** NumPy Analyzer

---

