# VTA Transit Network Analysis

This project focuses on analyzing the **VTA transit network** using graph theory and network analysis techniques. The analysis leverages tools such as Gephi and custom scripts to evaluate the resiliency and structure of the transit network.

---

## Table of Contents
- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Data](#data)
- [Tools and Libraries](#tools-and-libraries)
- [Usage](#usage)

---

## Introduction

The goal of this project is to analyze and enhance the resiliency of the VTA transit network. The project includes:
- Generating the network structure in GML format.
- Exploring key network metrics such as centrality, clustering, and connectivity.
- Visualizing the transit network for better insights.

---

## Project Structure

The repository is organized as follows:
/data

- transit_network_inbound_multi2.gml # orignal GML file of the transit network /scripts
- gtfs_vta_network_data.gml # The updated network dataset
- VTA_Network.ipynb # Python script for network analysis 
- /gtfs_vta # Bus route information includes stops, schedule, and runtime etc.

- ---

## Data

The primary dataset is the **VTA transit network** GTFS data, which has been converted to a GML file for analysis. Data includes:
- Nodes: Stations/stops in the network.
- Edges: Connections (routes) between stations.

---

## Tools and Libraries

The following tools and libraries were used for this project:
- [Gephi](https://gephi.org/) - For network visualization and analysis.
- Python (with the following libraries):
  - [NetworkX](https://networkx.org/) - For graph analysis.
  - [Matplotlib](https://matplotlib.org/) - For visualizing results.
  - [Pandas](https://pandas.pydata.org/) - For handling data.
  -  https://github.com/Data-Monkey/GTFS-NetworkX/blob/master/GTFStoGraph.py - for sequencing stops

---

## Usage

1. Clone the repository:
(TBD)

