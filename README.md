# Deep learning project
This is the project for the deep learning course at University of Trento (Italy).  
This work was done with two other students friends of mine.
## Data
The project exploits video surveillance data, more precisely the Market1501 dataset. 
## Brief introduction
This work consists of two main tasks: 
* Design and implementation of a multi task classifier for attribute classification (age, gender and clothing).  
* Person re-identification, given a query image the goal is to retrieve all the images of the same person from the dataset.  
***
This repo contains:
* The colab notebooks.
* The report.
## How To Run The Code

You can open the colab notebooks from the links inside the papers.

The notebooks are auto-contained (they will download the dataset and install the required packages on their own), so you can just run "execute all" inside google colab.
Remember to select the GPU environment.

## Notebooks Summaries

- FINAL_TASK_1 : trains a NN based on resnet18 to classify people attributes, then it generates the .csv (running time: 5-6 mins).
- FINAL_TASK_2 : trains Bruna (Based on Residuals hUge Architecture) for 42 epochs (50-60 mins) then saves the weights locally.
- TASK2_INFERENCE : download our pretrained models (for both task 1&2) and uses them to retrieve people given a query  (45 mins).
- Others/SplitDataset : shows some stats on the split of the dataset.

- other resources: [Same Resources But In GDrive](https://drive.google.com/drive/folders/1S5_3uu1Yd4YjE0uVC6QyC0avDiJG6efS?usp=sharing)
