Project Description: Hotel/Restaurant Inventory and Sales Management System
Overview:
This project is a console-based inventory and sales management system for a hotel or restaurant. It allows users to manage and track inventory of various items and monitor sales and collections in real-time.

Features:
Inventory Management:

Tracks the availability of different items such as rooms, pasta, burgers, noodles, shakes, and chicken rolls.
Maintains two sets of variables:
Q<item>: Quantity of items available in stock.
S<item>: Quantity of items sold.
Menu and Ordering:

Presents a menu of options where users can select items they wish to order.
Users specify the quantity of each item they want to order.
Before confirming an order, the system checks if sufficient stock is available (Q<item> - S<item>). If not, it alerts the user about the available stock.
Sales and Collection Tracking:

Tracks total sales and collection for each item:
Total_<item>: Accumulated sales amount for each item.
Provides a summary option (case 7) that displays:
Remaining stock for each item.
Quantity sold for each item.
Total collection for the day (sum of all sales).
User Interface:

Utilizes a text-based interface:
Outputs information using cout.
Accepts user input using cin.
Presents options in a structured menu format (switch statement) for user interaction.
Functionality and Flow:

Implements basic error handling to manage scenarios where users attempt to order more items than available.
Includes an exit option (case 8) to terminate the program.
Potential Enhancements:

Improved error handling to gracefully handle invalid inputs.
Integration with a database or file system to persist data across sessions.
Implementation of a graphical user interface (GUI) for better usability.
Addition of administrative features such as adding new items, modifying prices, etc.
Implementation:
Language: C++
Execution: The program executes in a loop (goto p;) to allow continuous operation until the user chooses to exit (case 8).
Development Considerations: Ensure clear and intuitive user prompts and messages to enhance user experience and understanding.
Conclusion:
This project serves as an introductory example of a basic inventory and sales management system, demonstrating fundamental programming concepts such as variables, conditional statements, loops, and user input/output handling in C++. It provides a structured approach to managing inventory and tracking sales, which can be expanded and enhanced for more sophisticated applications.
