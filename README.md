♻️ Eco-Points Recycling Tracker

A simple Java console application that allows households to log recycling events, earn eco-points, and generate community recycling reports.
It uses object serialization to persist household data between program runs.
--
✨ Features

🏠 Register Households with unique ID, name, and address.

📦 Log Recycling Events by material type (plastic, glass, metal, paper) and weight.

📋 Display Registered Households with join date.

📑 View Household Recycling Events with total weight and points.

🏆 Generate Reports showing:

   -Household with highest eco-points

   -Total community recycling weight

💾 Data Persistence: Saves all households and events to a file (households.ser) for future runs.
--
🛠️ Technologies Used

-Java 17+

-Object Serialization (Serializable)

-Collections Framework (HashMap, ArrayList)

-LocalDate API
--
📂 Project Structure

EcoPointsRecyclingTracker/

│── RecyclingEvent.java   # Represents a single recycling event

│── Household.java                   # Represents a household with recycling history

│── EcoPointsRecyclingTracker.java   # Main application logic

│── households.ser                   # Auto-generated file storing saved data

--
▶️ How to Run

-Clone the repository:

    git clone https://github.com/Mohamedahmed716/EcoPointsRecyclingTracker.git
    cd EcoPointsRecyclingTracker


-Compile the project:

    javac *.java


-Run the program:

    java EcoPointsRecyclingTracker
--
📖 Usage Example
=== Eco-Points Recycling Tracker ===
1. Register Household
2. Log Recycling Event
3. Display Households
4. Display Household Recycling Events
5. Generate Reports
6. Save and Exit
Choose an option: 1

Enter household ID: H001
Enter household name: Ahmed Family
Enter household address: 123 Green Street
Household registered successfully on 2025-08-27
--
🚀 Future Improvements

Add leaderboard ranking of households.

Introduce material-specific multipliers (e.g., metal earns more points).

Generate CSV/PDF reports for exporting.

Add a GUI or web interface.
