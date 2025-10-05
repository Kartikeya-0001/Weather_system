# Weather Data Storage System

# Overview

A Weather Data Storage System designed to systematically collect, store, and manage weather-related data such as temperature, humidity, and atmospheric conditions using 2D arrays and Abstract Data Types (ADTs). This project demonstrates the ability to handle both complete and sparse datasets efficiently.

# Objectives

* To implement weather data storage using 2D lists in Python.
* To demonstrate Object-Oriented Design through classes and methods.
* To perform data insertion, retrieval, and traversal efficiently.
* To handle sparse data using sentinel values.

# Features

* Store temperature data for multiple cities and years
* Retrieve temperature by specifying city and year
* Display data in row-major and column-major order
* Handle missing (sparse) data using sentinel value -9999
* Demonstrates OOP and data abstraction concepts

# How It Works

1. Initialization: Create a list of years and cities.
2. Data Insertion: Use populateArray() to store temperature for each city and year.
3. Sparse Handling: Replace missing entries with a sentinel value using handleSparseData().
4. Access Patterns: Display data using rowMajorAccess() or columnMajorAccess().
5. Retrieval: Get a specific record using retrieve(city, year).

# Example Code

<img width="480" height="260" alt="Screenshot 2025-10-05 183744" src="https://github.com/user-attachments/assets/fb593517-bb54-40a2-9750-c0646174e569" />

# Time and Space Complexity

* Insert: O(1)
* Delete: O(n × m)
* Retrieve: O(n × m)
* Space: O(n × m)

# Screenshot

<img width="449" height="170" alt="Screenshot 2025-10-05 183810" src="https://github.com/user-attachments/assets/9983acd6-fd0c-4469-a411-a3d9bf09b3f9" />

# Author

Kartikeya Drall

2401720014

B.Sc (H) Computer Science

Data Structure Theory Assignment-1
