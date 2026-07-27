# Mini Spark RDD - Amazon Product Analysis

##  Project Overview

This project is a simple implementation of Spark's RDD (Resilient Distributed Dataset) concepts using Python. It demonstrates how operations like **filter**, **map**, and **collect** work on an Amazon product dataset.

The program reads an Amazon CSV dataset, creates an RDD, filters products based on category and rating, extracts product names, and displays the final result. :contentReference[oaicite:0]{index=0}

---

##  Project Structure

```
MiniSparkRDD/
│
├── Data/
│   └── amazon.csv
│
├── src/
│   ├── loader.py
│   ├── rdd.py
│   └── utils.py
│
├── main.py
└── README.md
```

---

##  Technologies Used

- Python 3.x
- CSV File Handling
- Custom RDD Implementation
- Functional Programming (Lambda Functions)

---

## Dataset

Dataset: **Amazon Products Dataset**

The dataset contains information such as:

- Product Name
- Category
- Rating
- Price
- Other product details

---

##  Features

- Load CSV dataset
- Create RDD object
- Filter products by category
- Filter products with rating greater than 4
- Map product names
- Collect and display results

---

##  Pipeline

The program performs the following operations:

1. Load Amazon CSV dataset.
2. Create an RDD.
3. Filter products whose category contains **Electronics**.
4. Filter products with rating greater than **4**.
5. Extract product names.
6. Collect and display the final output. :contentReference[oaicite:1]{index=1}

---

##  How to Run

1. Clone or download the project.

2. Place the dataset inside the **Data** folder.

3. Open terminal.

4. Run:

```bash
python main.py
```

---

## Example Output

```
1. Apple iPhone 15
2. Samsung Galaxy S24
3. Sony Wireless Headphones
4. Boat Bluetooth Speaker
...
```

(The actual output depends on the dataset.)

---

##  Learning Objectives

This project helps understand:

- What is an RDD?
- Filter Transformation
- Map Transformation
- Collect Action
- Data Processing Pipeline
- Functional Programming using Lambda Expressions

---

##  Future Enhancements

- Reduce operation
- FlatMap
- GroupBy
- SortBy
- Count
- Parallel Processing
- Command-line dataset input

---

