Personal Information Manager (PIM)
📘 Overview

The Personal Information Manager (PIM) is a beginner-friendly Python project built in Jupyter Notebook.
It allows users to store, manage, search, and export personal details such as name, age, city, and hobbies — all in a neatly formatted and interactive way.

This project demonstrates the fundamentals of Python Object-Oriented Programming (OOP), dataclasses, and file handling using JSON and Pandas for CSV export.

🧩 Features

✅ Add new personal records (Name, Age, City, Hobbies)
✅ View all stored records in a formatted way
✅ Search by Name, City, or Hobby
✅ Save data to a JSON file for reuse
✅ Load previously saved data automatically
✅ Export all data to a CSV file using Pandas
✅ Clean and easy-to-understand Python code

🛠️ Tech Stack
Component	Description
🐍 Python 3	Core Programming Language
📓 Jupyter Notebook	Development & Demonstration
📦 Pandas	Data Handling & CSV Export
💾 JSON	Data Storage Format
🧱 Dataclasses	Structured Data Management
📁 Project Structure
Personal-Information-Manager/
│
├── personal_info_manager.ipynb   # Jupyter Notebook source code
├── pim_records.json              # Saved JSON data file (auto-created)
├── pim_records.csv               # Exported CSV data file (auto-created)
├── README.md                     # Project documentation
└── requirements.txt              # Python dependencies

🚀 Getting Started
1️⃣ Clone the Repository
git clone https://github.com/<your-username>/Personal-Information-Manager.git
cd Personal-Information-Manager

2️⃣ Install Required Libraries
pip install pandas


(Other required libraries like json and dataclasses are built into Python 3)

3️⃣ Open the Project

Open Jupyter Notebook:

jupyter notebook


Then open the file:

personal_info_manager.ipynb

🧠 How It Works
➕ Add a New Record
pim.add_person("Ashwini Umande", 22, "Pune", "Coding, Reading, Cycling")

📜 Display All Records
pim.display_all()

🔍 Search a Record
pim.search("Pune")  # or "Ashwini", "Reading", etc.

💾 Save Records to JSON
pim.save_to_json("pim_records.json")

📂 Load Records from JSON
pim.load_from_json("pim_records.json")

📊 Export to CSV
df.to_csv("pim_records.csv", index=False)

🖥️ Example Output
📘 Record 1
Name: Ashwini Umande
Age: 22
City: Pune
Hobbies: Coding, Reading, Cycling

📘 Record 2
Name: Rohan Kumar
Age: 25
City: Delhi
Hobbies: Football, Cooking

📘 Record 3
Name: Sneha Patil
Age: 23
City: Mumbai
Hobbies: Dancing, Painting

🧾 Sample Output Files
pim_records.json
[
    {
        "name": "Ashwini Umande",
        "age": 22,
        "city": "Pune",
        "hobbies": ["Coding", "Reading", "Cycling"]
    },
    {
        "name": "Rohan Kumar",
        "age": 25,
        "city": "Delhi",
        "hobbies": ["Football", "Cooking"]
    }
]

pim_records.csv
name	age	city	hobbies
Ashwini Umande	22	Pune	['Coding', 'Reading', 'Cycling']
Rohan Kumar	25	Delhi	['Football', 'Cooking']
🧰 Skills Demonstrated

✅ Python Class & Object-Oriented Concepts

✅ JSON File Handling

✅ Data Serialization / Deserialization

✅ Working with Lists and Loops

✅ Pandas DataFrame Conversion

✅ Clean Code & Documentation Practices

👩‍💻 Author

Name: Ashwini Umande
Role: Python Developer / AI-ML Enthusiast
