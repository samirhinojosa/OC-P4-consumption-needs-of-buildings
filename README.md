# Anticipate the electricity consumption needs of buildings [OC-P4]

## **Problem to solve**

You work for **"the city of Seattle"**. To achieve its goal of being a neutral city in carbon emissions by 2050, your team is paying close attention to the emissions of buildings not intended for housing.

### **Problem of the city of Seattle**
Thorough readings were taken by your agents in 2015 and 2016. However, these readings are expensive to obtain, and from those already taken, you want to try to predict the CO2 emissions and the total energy consumption of buildings. for which they have not yet been measured.

## **Your mission**

You've just come out of a briefing meeting with your team. Here is a summary of your mission:

1. Perform a short exploratory analysis.
2. Test different prediction models in order to best answer the problem.

### **Considerations**

- The goal is to do without annual consumption readings (beware of data leaks), but nothing prevents you from deducing simpler variables (nature and proportions of energy sources used).
- Pay close attention to the treatment of the different variables, both to find new information (can we deduce interesting things from a simple address?) And to optimize performance by applying simple transformations to the variables (normalization, going to log, etc.).
- Set up a rigorous evaluation of regression performance, and optimize hyperparameters and ML algorithm choice using cross-validation

## **The data**

The datasets are availabe on the following links

- [**2015**](https://www.kaggle.com/city-of-seattle/sea-building-energy-benchmarking#2015-building-energy-benchmarking.csv)
- [**2016**](https://www.kaggle.com/city-of-seattle/sea-building-energy-benchmarking?select=2016-building-energy-benchmarking.csv)

Based on the official site of [**Seattle Open Data**](https://data.seattle.gov/), we can see the dataset **metadata** to know all features

- [**2015**](https://data.seattle.gov/dataset/2015-Building-Energy-Benchmarking/h7rm-fz6m)
- [**2016**](https://data.seattle.gov/dataset/2016-Building-Energy-Benchmarking/2bpz-gwpy)

On the other hand, we get the means of [**Energy Star Score**](https://www.energystar.gov/buildings/benchmark/analyze_benchmarking_results)

## **Repository file structure**

- cleaning_notebook.ipynb: Cleaning notebook
- modeling_notebook.ipynb: Notebook with predictions
- img: Images and graphs of the project
- supports: Folder with documents to support the work done
    - Project 4 presentation: Project presentation in French

### **Final note**

- The notebook is optimized to be used with **Jupyter lab**.
- The **datasets** should be located in folder called **datasets** in the root path