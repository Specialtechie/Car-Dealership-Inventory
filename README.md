 # Car Dealership Inventory Tracker
**Overview**

The Car Dealership Inventory Tracker is a Python-based application that allows car dealerships to manage their inventory efficiently. The system supports adding, removing, searching, and marking cars as sold. The application is built using Tkinter for the graphical user interface and CSV for data storage.

**Features**
**Add Cars:** Users can add new cars to the inventory with details such as Make, Model, Year, Price, and Status.
**Remove Cars:** Cars can be removed from the inventory based on their model.
**Mark as Sold:** Cars can be marked as "Sold" when purchased.
**Search Cars:** Users can search for cars based on make, price, and year.
**View Inventory:** The system displays all available and sold cars in a tabular format.
**Persistent Storage**: Data is stored in a CSV file for easy retrieval and backup.
**Installation**
**Prerequisites** 
Ensure you have Python installed on your system. You can check this by running:
Python --version
If Python is not installed, download and install it from python.org.
**Clone the Repository**
git clone https://github.com/yourusername/car-inventory-tracker.git
cd car-inventory-tracker
**Install Dependencies**
This project uses only built-in Python libraries, so no additional dependencies are required.
**Usage**
Running the Application
To start the application, run:
carinventory.py
**User Interface**
Adding a Car: Enter the car details (Make, Model, Year, Price) and click the Add Car button.
Removing a Car: Select a car from the list and click Remove Car.
Marking a Car as Sold: Select a car and click Mark as Sold.
Searching for a Car: Enter search criteria and click Search.
**File Structure**
car-inventory-tracker/
│── inventory.csv   # Stores car inventory data
│── carin.py        # Main application script
│── README.md       # Project documentation
Contributing
Feel free to submit issues and pull requests to improve the project.
**License**
This project is licensed under the MIT License.
