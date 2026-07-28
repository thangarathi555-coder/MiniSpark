# MiniSparkRDD

## Overview
MiniSparkRDD is a simplified implementation of Apache Spark's Resilient Distributed Dataset (RDD) concept using Python. This project demonstrates how data is loaded, transformed, optimized, and executed through a Directed Acyclic Graph (DAG), similar to the working principles of Apache Spark.

## Features
- Load data from CSV files
- RDD-based data processing
- Lazy evaluation
- DAG (Directed Acyclic Graph) execution
- Query optimization
- Basic transformations and actions
- Modular Python implementation

## Project Structure

```
MiniSparkRDD/
│── Data/
│   └── amazon.csv
│
│── src/
│   ├── dag.py
│   ├── executor.py
│   ├── loader.py
│   ├── node.py
│   ├── optimizer.py
│   ├── parser.py
│   ├── rdd.py
│   └── utils.py
│
├── main.py
└── README.md
```

## Requirements

- Python 3.8 or above

## Installation

1. Clone the repository

```bash
git clone <repository-url>
```

2. Move into the project folder

```bash
cd MiniSparkRDD
```

3. Run the project

```bash
python main.py
```

## Dataset

The project uses the following dataset:

- `Data/amazon.csv`

This dataset is used to demonstrate RDD operations and query execution.

## Workflow

1. Load the dataset.
2. Parse the input operations.
3. Create RDD objects.
4. Build the DAG.
5. Optimize execution.
6. Execute transformations and actions.
7. Display the final output.

## Technologies Used

- Python
- Object-Oriented Programming (OOP)
- Apache Spark RDD Concepts
- CSV File Handling

## Learning Outcomes

This project helps understand:

- RDD architecture
- Lazy evaluation
- DAG execution
- Query optimization
- Distributed data processing concepts

## Future Improvements

- Support multiple datasets
- Additional RDD transformations
- Parallel execution
- Performance optimization
- Better visualization of DAG

## Author

**Thangarathi.A**

Bachelor of Computer Applications (BCA)

Kamaraj College

## License

This project is developed for educational and learning purposes.
