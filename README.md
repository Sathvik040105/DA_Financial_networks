# Community Detection in Financial Networks Using Stochastic Block Model  

## Community detection in Trade Data
### Overview

This project analyzes international trade relationships using network analysis and community detection algorithms to identify trading blocks and patterns.

The code implements:
- Country name standardization between different data sources
- Network analysis of international trade relationships
- Community detection using the Weighted Stochastic Block Model (WSBM)
- Visualization of trade communities and network structure

![image](https://github.com/user-attachments/assets/ec1b83c1-28f2-4390-95af-8b28d0794421)
communities generated for n blocks = 16

![image](https://github.com/user-attachments/assets/c9b9fd9b-c9ab-46af-bc39-49682e4a7844)
communities generated for n blocks = 12

## Community Detection in Indian Stock Data ( NIFTY 150 )
### Overview

This project analyzes the relationships between stocks in India's NIFTY 150 index using network analysis and community detection techniques. The analysis includes correlation-based edge weights and identifies trading communities using the Weighted Stochastic Block Model (WSBM).

### Key Features
- Correlation network construction from stock price data
- Community detection using WSBM
- Interactive network visualization
- Hierarchical clustering analysis

### Data Processing
1. Data Collection
   - Stock data for NIFTY 150 companies from yfinance
   - Cleaning and preprocessing time series data
   - Computing pairwise correlations

2. Network Construction
   - Edge weights based on stock price correlations
   - Threshold filtering for significant relationships
   - Network normalization techniques

3. Community Detection
   - Implementation of WSBM algorithm
   - Parameter optimization for community detection
   - Validation of community structures

### Visualizations
1. Network Graph
   - Color-coded communities
   - Edge weights showing correlation strength
   - Interactive spring layout
   - Node labels for stock identification

2. Hierarchical Clustering
   - Dendrogram visualization
   - Distance-based clustering
   - Community relationship analysis

![image](https://github.com/user-attachments/assets/877d3593-6526-4be5-824c-e33026f046eb)
Dendogram for communities obtained

![image](https://github.com/user-attachments/assets/b2d6c16c-a621-4bc7-b3d2-268fd196f2ea)
graph of communities visualized

We can see it is able to correctly identify various sectors in NIFTY as communities. 

## Contributions

| **Contribution**               | **Names of Contributors**                          | **GitHub Usernames**            |
|--------------------------------|---------------------------------------------------|----------------------------------|
| **Research and Ideation**      | Ishaq                                            | IshaqHamza                      |
| **Data Sourcing**              | Rohit, Ishaq                                     | irenicquasar, IshaqHamza        |
| **Trade Database Construction**| Nagasai                                         | Nagasai561                      |
| **Data Engineering**           | Nagasai, Shankar                                 | Nagasai561, OmegaSun18          |
| **Community Generation Code**  | Rohit, Sathvik                                   | irenicquasar, Sathvik040105     |
| **Stock Communities Visualization** | Sathvik, Rohit, Nagasai                     | Sathvik040105, irenicquasar, Nagasai561 |
| **Trade Communities Visualization** | Rohit                                     | irenicquasar                    |
| **Inference**                  | Ishaq                                            | IshaqHamza                      |
