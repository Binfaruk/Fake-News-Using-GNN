

# Fake News Detection using Graph Neural Networks (GNN)  

This project aims to detect fake news by leveraging the power of Graph Neural Networks (GNN). By analyzing the relationships between news articles, publishers, and users, the model captures contextual and structural information to improve classification accuracy.  

## Table of Contents  
1. [Overview](#overview)  
2. [Dataset](#dataset)  
3. [Features](#features)  
4. [Installation](#installation)  
5. [Usage](#usage)  
6. [Contributing](#contributing)  

## Overview  
Fake news spreads rapidly and impacts society negatively. This project uses Graph Neural Networks to build a graph-based representation of news, incorporating relationships between articles, sources, and user interactions. The model learns these relationships to identify fake news effectively.  

## Dataset  
The project uses the [FakeNewsNet Dataset](https://github.com/KaiDMML/FakeNewsNet/tree/master/dataset). It includes data from two fact-checking platforms (PolitiFact and GossipCop) with information on news content, social context, and user engagement.  

## Features  
- **Graph-based Representation:** Converts news data into graphs with nodes (articles, users, sources) and edges (interactions, citations).  
- **Graph Neural Networks:** Utilizes GNN to learn from graph structures and improve classification.  
- **Fake News Classification:** Predicts whether a news article is fake or real.  

## Installation  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/fake-news-detection-gnn.git  
   cd fake-news-detection-gnn  
   ```  
2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  

## Usage  
1. Prepare the dataset: Download the FakeNewsNet dataset and place it in the `data/` folder.  
2. Preprocess the data and create graph structures:  
   ```bash  
   python preprocess.py  
   ```  
3. Train the GNN model:  
   ```bash  
   python train.py  
   ```  
4. Evaluate the model:  
   ```bash  
   python evaluate.py  
   ```  

## Contributing  
Contributions are welcome! If you have ideas to improve the project, feel free to open an issue or submit a pull request.  

