
# Lightning Talks: Data Science Methodology

## signac: a simple, open-source, data management framework  
*Alyssa Travitz, Graduate Student (PhD), Macromolecular Science and Engineering, University of Michigan*  

Data science projects frequently involve complex file-based workflows acting on large, highly dynamic data spaces. We present signac, a non-intrusive, open-source Python framework that enables researchers to efficiently operate on file-based data spaces while keeping track of all relevant metadata. The signac framework provides all components required to create a well-defined, collectively accessible data space and to implement reproducible workflows. The serverless data management and lightweight workflow model ensure that workflows are easily transferrable between laptops and high-performance computing environments. The data model is well suited for managing data spaces involved with high-dimensional parameter searches or hyperparameter optimization of machine learning models. The signac approach not only increases research efficiency, it also improves reproducibility and lowers barriers for data sharing by transparently enabling the robust tracking, selection, and searching of data by its metadata.  

## Non-IID Graph Neural Networks  
*Yiqi Wang, Graduate Student (PhD), Computer Science & Engineering, Michigan State University*  

Graph classification is an important task on graph-structured data with many real-world applications. The goal of graph classification task is to train a classifier using a set of training graphs. Recently, Graph Neural Networks (GNNs) have greatly advanced the task of graph classification. When building a GNN model for graph classification, the graphs in the training set are usually assumed to be identically distributed. However, in many real-world applications, graphs in the same dataset could have dramatically different structures, which indicates that these graphs are likely non-identically distributed. Therefore, in this paper, we aim to develop graph neural networks for graphs that are not non-identically distributed. Specifically, we propose a general non-IID graph neural network framework, i.e., Non-IID-GNN. Given a graph, Non-IID-GNN can adapt any existing graph neural network model to generate a sample-specific model for this graph. Comprehensive experiments on various graph classification benchmarks demonstrate the effectiveness of the proposed framework. We will release the code of the proposed framework upon the acceptance of the paper.   

## TDA with Mapper - Improving Available Software  
*Danielle Barnes, Graduate Student (PhD), Computational Mathematics, Science & Engineering, Michigan State University*  

Mapper is a topological data analysis algorithm that has been used in a wide-variety of applications across different research domains allowing insight beyond statistical methods. Multiple open-source implementations are available, each with limitations for our type of analysis. 

Our aim was to apply Mapper to large, high-dimensional data sets with the benefit of an easy to use graphical interface.  Using a seed grant award from the Center for Social and Business Analytics, we extended open-source packages to redevelop a prototype Mapper software we used extensively for data analysis to allow for easier, faster analysis with larger datasets.  Additionally, software features were enhanced to allow for easier predictive analysis using output from the Mapper algorithm.  

Preliminary results show significant performance increases from the original prototype, with additional potential for parallel computation.This presentation will show performance benchmarks, example data analysis, and a demo of the Mapper software.  

## Detecting Bifurcations in Dynamical Systems with Topological Data Analysis  
*Sarah Tymochko, Graduate Student (PhD), Computational Mathematics, Science & Engineering, Michigan State University* 

Bifurcations in a dynamical system are drastic behavioral changes that are caused by minor changes to a parameter of the system. Being able to detect the parameter values for which these bifurcations occur is essential to understanding the system overall. Certain types of bifurcations, specifically Hopf bifurcations, induce limit cycles in the state space of the dynamical system. Visually, this means the state space goes from being stable, with not much change from one time step to the next, to behavior where the soltuion traces out a larger, circular shape over time. 

Topological data analysis (TDA) is a field with tools that are especially useful for quantifying circular features in data using concepts from algebraic topology. Using these tools, we can detect the changes in behavior caused by Hopf bifurcations. We develop a one-step method of capturing topological changes in the state space caused by varying the bifurcation parameter.  
