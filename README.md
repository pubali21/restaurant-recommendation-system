# Restaurant Recommendation System
A Content-Based Filtering web application that recommends restaurants to users based on their input preferences. 

## Features
✅ Restaurant recommendation based on user-input preferences (e.g., cuisine, location, budget)

✅ Uses CountVectorizer and Cosine Similarity for content-based filtering

✅ User-friendly UI built with HTML, CSS, Bootstrap, and JavaScript

✅ Real-time search and result updates

✅ CSV-based data source (no external database needed)

## Tech Stack
Frontend: HTML, CSS, Bootstrap, JavaScript

Backend: Python, Flask

Data Processing: Pandas, Scikit-learn

Recommendation Logic: CountVectorizer, Cosine Similarity


## Prerequisites

- Flask and Pandas should be installed
- Path variables should be added appropriately for running Flask

## Steps to start the Application

- Run the **Restro.ipynb** file to generate fresh pkl files
- Run the **app.py** file

## How it Works

- On opening the application on the browser, Top 50 recommended restaurants are displayed
- Search the restaurant you prefer and get the details of the restaurant alongwith 5 other recommended restaurants as per your search
