
# Simulating Network Models for E.Coli and C.Elegans

This project involves simulating and analyzing three types of network models—Random Graphs, Small World Networks, and Preferential Attachment Models—to understand the structural properties of the biological networks of *E.Coli* and *C.Elegans*. The simulations aim to replicate target metrics such as average path length and clustering coefficient.

## Network Models Simulated

### 1. Random Graph Model (Erdős-Rényi Model)
- **Purpose:** Simulate random connections between nodes to understand the impact of random wiring.
- **Metrics Calculated:**
  - Average Path Length
  - Clustering Coefficient
- **Visualization:** The graph is visualized using a spring layout.

### 2. Small World Model (Watts-Strogatz Model)
- **Purpose:** Reproduce the small-world properties seen in biological systems with high clustering and short path lengths.
- **Steps:**
  1. Generate a regular ring lattice.
  2. Rewire edges with a given probability to introduce randomness.
- **Metrics Calculated:**
  - Average Path Length
  - Clustering Coefficient
- **Visualization:** The graph is visualized using a spring layout.

### 3. Preferential Attachment Model (Barabási-Albert Model)
- **Purpose:** Mimic the scale-free networks where some nodes are highly connected due to preferential attachment.
- **Metrics Calculated:**
  - Average Path Length
  - Clustering Coefficient
- **Visualization:** Networks for *E.Coli* and *C.Elegans* are displayed side-by-side.

## Results
For each model and biological network (*E.Coli* and *C.Elegans*):
- The **average path length** and **clustering coefficient** are computed.
- The results are compared with the target metrics derived from empirical data.

## Visualization
Graphs for all models are plotted to provide an intuitive understanding of the network structure.

## Tools Used
- **Python Libraries:** 
  - `networkx` for graph generation and analysis.
  - `matplotlib` for visualization.
- **Framework:** Simulations follow a reproducible structure for consistency across network types.

## How to Run the Code
1. Ensure Python is installed on your system.
2. Install required libraries using:
   ```bash
   pip install networkx matplotlib
   ```
3. Execute the Python script provided to generate simulations and visualizations.


## License
This project is licensed under the MIT License.

