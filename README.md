# Spark-Tutorial-in-pySpark
![image](https://github.com/user-attachments/assets/28633e6e-4600-49db-a17b-fc378445e3ec)

This repository contains a comprehensive tutorial on Apache Spark using PySpark. The notebook provides step-by-step guidance for leveraging PySpark to handle big data and distributed computing efficiently. It is suitable for beginners and intermediate users who want to understand the basics and applications of PySpark.

# Vietnam War Bombing Operations Analysis
![image](https://github.com/user-attachments/assets/f891d224-4a13-49e6-99b6-10f972d420d1)

This repository analyzes the Vietnam War Bombing Operations Dataset, shedding light on air force missions during one of the most complex conflicts in modern history. Using this dataset, the project applies practical queries and analysis to uncover insights about bombing operations, aircraft, and mission details.

# Table of Contents
* Overview
* Dataset Description
* Bombing Operations
* Aircraft Glossary
* Project Features
* Setup and Installation
* Usage
* Insights and Analysis
* Contributing
* License

# 🌟 Overview
The Vietnam War (1955–1975) was a significant historical event involving extensive air force operations. This project leverages the THOR (Theater History of Operations Reports) database to explore and analyze aerial bombings during this period. The dataset provides comprehensive details on missions, aircraft, and operational aspects, making it an invaluable resource for historical and tactical analysis.

Key areas of analysis include:

* Trends in bombing operations over time.
* Aircraft models and their contributions.
* Weapon types and load weights used during missions.
* Mission patterns by time of day, location, and operation type.

# Data set description

**Bombing_Operations** [Get the dataset here](https://drive.google.com/a/epfl.ch/file/d/1L6pCQkldvdBoaEhRFzL0VnrggEFvqON4/view?usp=sharing)

- AirCraft: _Aircraft model (example: EC-47)_
- ContryFlyingMission: _Country_
- MissionDate: _Date of the mission_
- OperationSupported: _Supported War operation_ (example: [Operation Rolling Thunder](https://en.wikipedia.org/wiki/Operation_Rolling_Thunder))
- PeriodOfDay: _Day or night_
- TakeoffLocation: _Take off airport_
- TimeOnTarget
- WeaponType
- WeaponsLoadedWeight

**Aircraft_Glossary** [Get the dataset here](https://drive.google.com/a/epfl.ch/file/d/14dyBmcTBA32uXPxDbqr0bFDIzGxMTWwl/view?usp=sharing)

- AirCraft: _Aircraft model (example: EC-47)_
- AirCraftName
- AirCraftType

**Dataset Information:**

THOR is a painstakingly cultivated database of historic aerial bombings from World War I through Vietnam. THOR has already proven useful in finding unexploded ordnance in Southeast Asia and improving Air Force combat tactics:
https://www.kaggle.com/usaf/vietnam-war-bombing-operations

# 🚀 Usage
* Open the notebook Vietnam_War_Bombing_Operations.ipynb in Jupyter.
* Follow the step-by-step analysis to explore and understand the dataset.
* Modify the code for your own queries and visualizations.


# 🔍 Insights and Analysis

Example Questions Addressed:


1.Find all aircrafts of type "Light Bomber"

2.Find all bombing missions operated by "VIETMAN (SOUTH)"

3.Find aircraft, ,mission data, country Flying mission of those attacks in which the Take off location was "UDORN AB"

4.Find all bombing operation on the year 1971

5.Find the number of missions operated by each aircraft

6.Find the maximum attack time operated by each aircraft

7.Find the maximum attack time operated by each aircraft on a different target country

8.What were the most common aircraft models used during the Vietnam War?

9.Which operations saw the highest frequency of missions?

10.What were the trends in bombing operations over the years?

11.How did mission types vary by time of day and location?

12.What were the most frequently used weapons, and how much weight did they carry?

# 🤝 Contributing
Contributions are welcome! If you would like to improve the project or add new analyses:
* Fork the repository.
* Create a feature branch:

git checkout -b feature-name

* Commit your change
  git commit -m "Add your message here"
* Push to your branch and create a pull request.




