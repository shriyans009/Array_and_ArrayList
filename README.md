# Array and ArrayList Operations in Java

This Java program provides functionality to manipulate arrays and ArrayLists. It includes the following features:

- **Segregate Even and Odd Numbers:** Separates even and odd numbers from an array into two distinct ArrayLists.
- **Find Two Neighboring Numbers with the Smallest Difference:** Finds two neighboring numbers in an array with the smallest difference.
- **Convert Array to ArrayList and Vice Versa:** Converts an array to an ArrayList and vice versa.

## Project Structure

The project consists of three Java files:

1. **`ArrayFunctions.java`**: Contains the main functionalities of the program.
2. **`Main.java`**: Acts as the entry point, where users can interact with the menu-driven program.
3. **`UserInput.java`**: Handles user input, specifically taking an array of five integers from the user.

## Features

### 1. Segregate Even and Odd Numbers
This functionality separates the even and odd numbers from an array into two different ArrayLists and displays them.

### 2. Find Two Neighboring Numbers with the Smallest Difference
This function finds the two neighboring numbers in an array with the smallest difference and prints the difference along with the numbers.

### 3. Convert Array to ArrayList and Vice Versa
This method demonstrates how to convert an array into an ArrayList and how to convert the ArrayList back to an array, printing the results for both conversions.

## How to Run the Program

1. Clone or download the repository to your local machine.
2. Compile the Java files using the following commands:

    ```bash
    javac UserInput.java ArrayFunctions.java Main.java
    ```

3. Run the `Main` class using the command:

    ```bash
    java Main
    ```

4. Follow the on-screen menu to choose an option.

## Sample Output

```bash
Menu:
1. Segregate Even and Odd Numbers
2. Find Two Neighboring Numbers with the Smallest Difference
3. Convert Array to ArrayList and Vice Versa
4. Exit
Please choose an option: 1
Enter five numbers: 
1 2 3 4 5
Even numbers: [2, 4]
Odd numbers: [1, 3, 5]
