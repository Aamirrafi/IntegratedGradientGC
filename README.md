# IntegratedGradientGCN



## Installing the dependencies
pip install -r requirements.txt

## Loading the dataset
We are using two datasets in our project:
- Cora (Nodes 2708, features 1433, Edges 5429)
- Citeseer (Nodes 3327, features 3703, Edges 4732)

## Creating and Training 
we used graph convolution model as classifier and was trained by splitting the data into 80% train and 20% split
We used l2 with (5e-4) parameter and dropout regularization 30% probability to avoid overfitting

## Integrated Gradient based Saliency Maps
- We passed our input data, models, and output decisions to an integrated gradient algorithm.
- This helpled identifying the most important nodes and edges of the graph network
## Visualization
- The stellergraph library in python was used to visualize the nodes and edges after an explanation of the GCN was obtained using Integrated Gradients method.



