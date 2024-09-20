# 🚗 Car Rental Management System in Java
Welcome to the **Car Rental Management System**, a simple and efficient console-based program to rent and return vehicles, track availability, and calculate rental costs. The system is built with a modular and maintainable structure using **Object-Oriented Programming** principles. Robust input validation and error handling are included to ensure a smooth user experience.

## 🛠️ Features
- **Rent a Car**: Users can rent available cars from the system.
- **Return a Car**: Users can return a rented car, and the system calculates the total rental cost.
- **Track Availability**: The system maintains an updated list of available and rented cars.
- **Error Handling & Validation**: Ensures a seamless user experience with robust input validation and error management.

## 🚀 Getting Started
Follow the instructions below to clone, compile, and run the project on your local machine.

### Prerequisites
Make sure you have the following installed on your system:
- **Java Development Kit (JDK)** - version 8 or above

### 📥 Clone the Repository
```
git clone https://github.com/Saurav1928/Car-Rental-Management.git
```
- Navigate to the folder where you have clone the repo.
🔧 Compile the Program
```
javac Main.java
```
▶️ Run the Program
```
java Main
```
📋 Menu Options
Upon running the program, you will be presented with the following menu:
===== Car Rental System =====
1. Rent a Car
2. Return a Car
3. Exit
Enter your choice:

📝 How to Use
Rent a Car: Select option 1 and follow the prompts to choose and rent a car.
Return a Car: Select option 2 and follow the instructions to return a car and get the rental cost.
Exit: Choose option 3 to exit the program.

📂 Project Structure 

1. Car: Represents a vehicle with properties like ID, brand, model, price, and availability status.
2. Customer: Holds information about a customer, including their ID and name.
3. Rental: Manages the details of a car rental transaction, linking a car to a customer and rental duration.
4. CarRentalSystem: Orchestrates the overall functionality of the car rental system, handling car management, customer management, and rental processes.
5. Main.java: The entry point of the program, containing the user interface and menu logic.
