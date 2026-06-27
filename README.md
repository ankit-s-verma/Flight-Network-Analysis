# Flight Network Analysis

A Python-based data analysis project that explores the structure of global flight networks using graph theory and data visualization techniques. The project transforms airport and flight route datasets into network graphs and analyzes important properties such as degree distribution, betweenness centrality, assortativity, community structure, and spatial connectivity.

## Project Overview

Air transportation networks are complex systems that connect airports worldwide. This project models these connections as a graph where:

* **Nodes** represent airports.
* **Edges** represent direct flight routes.
* **Edge weights** represent flight frequencies or traffic volume.

Using NetworkX and geospatial visualization libraries, the project investigates structural characteristics of the flight network and demonstrates how network science can be applied to transportation systems.

---

## Features

* Data preprocessing and cleaning
* Flight network construction
* Network visualization
* Degree distribution analysis
* Betweenness centrality analysis
* Degree vs. Betweenness comparison
* Assortativity analysis
* Core community detection
* Cumulative distribution plots
* Percolation analysis
* Random spatial graph generation and hypothesis testing

---

## Technologies Used

* Python
* Pandas
* NumPy
* NetworkX
* Matplotlib
* Cartopy
* OpenPyXL
* Jupyter Notebook

---

## Project Structure

```
Flight-Network-Analysis/
│
├── Airports.csv
├── Flight Data.xlsx
├── Data Visualization.ipynb
└── README.md
```

---

## Dataset

The project uses two datasets:

### Airports.csv

Contains airport information including:

* Airport Code
* Airport Name
* City
* Country
* Latitude
* Longitude

### Flight Data.xlsx

Contains flight route information including:

* Source Airport
* Source City
* Source Country
* Destination Airport
* Destination City
* Destination Country
* Route Weight

---

## Analysis Performed

### Data Preprocessing

* Removed missing values
* Filtered invalid routes
* Removed zero-weight connections

### Network Construction

* Built a weighted graph using NetworkX
* Created airport-to-airport connectivity network

### Network Metrics

The following graph metrics are analyzed:

* Degree Distribution
* Betweenness Centrality
* Degree vs Betweenness
* Assortativity
* Core Community Size

### Additional Analysis

* Cumulative Degree Distribution
* Percolation Analysis
* Random Spatial Graph Comparison

---

## Sample Visualizations

The notebook generates several visualizations including:

* Flight route network
* Degree distribution
* Betweenness distribution
* Community structure
* Spatial network plots
* Percolation curves

> You can place exported figures inside an `images/` directory and display them here.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/flight-network-analysis.git
```

Install the required packages:

```bash
pip install pandas numpy matplotlib networkx cartopy openpyxl jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Data Visualization.ipynb
```

---

## Learning Outcomes

This project demonstrates:

* Data preprocessing using Pandas
* Graph modeling with NetworkX
* Network science concepts
* Geospatial visualization
* Statistical analysis of transportation networks
* Python-based exploratory data analysis

---

## Author

**Ankit Verma**

GitHub: https://github.com/ankit-s-verma
