# Keras: Regression with Neural Networks
Project that performs the regression of a continuous variable (oil) from a set of associated variables using a NN model. The Keras framework is used to easily create a TensorFlow Neural Network and make predictions.

## Analysis
<details>
<summary>1. <a href="https://ansegura7.github.io/Keras_RegressionNN/pages/DataProfiling" target="_blank" >Data Profiling</a></summary>
<ul>
	<li>Data Exploration</li>
	<li>Descriptive Statistics</li>
	<li>Data Profiling</li>
</ul>
</details>
<details open>
<summary>2. <a href="https://ansegura7.github.io/Keras_RegressionNN/pages/RegressionNN" target="_blank" >NN Regression with Keras</a></summary>
<ul>
	<li>Load and show datas</li>
	<li>Prepare the data to Learn</li>
	<li>Create Train/Validation/Test datasets</li>
    <li>Train Model</li>
    <li>Make predictions and calculate error</li>
    <li>Plot Results</li>
</ul>
</details>

# Data
The dataset used is made up of a group of operational and PVT variables for oil wells.

| # | Variable | Type | Unit | Data Type |
|---|---|---|---|---|
| 1 | WellID |  |  | Numerical |
| 2 | Date |  |  | Date |
| 3 | MethodID | Operational |  | Categorical |
| 4 | CHP | Operational | psi | Numerical |
| 5 | THP | Operational | psi | Numerical |
| 6 | Temp | Operational | Fahrenheit  | Numerical |
| 7 | Choke | Operational | inches | Numerical |
| 8 | Qinj | Operational | Mscf | Numerical |
| 9 | Bo | PVT |  | Numerical |
| 10 | Zed | PVT |  | Numerical |
| 11 | SpgO | PVT |  | Numerical |
| 12 | SpgGP | PVT |  | Numerical |
| 13 | Rel_Oper_Press | Operational |  | Numerical |
| 14 | Rel_Crit_Press | Operational |  | Numerical |
| 15 | WC | Operational |  | Numerical |
| 16 | Test_Oil | Well Test | bbls | Numerical |

## Dependencies

``` console
    conda install -c conda-forge keras
    conda install -c anaconda pydot
```

## Contributing and Feedback
Any kind of feedback/criticism would be greatly appreciated (algorithm design, documentation, improvement ideas, spelling mistakes, etc...).

## Authors
- Created by Segura Tinoco, Andrés
- Created on Oct 4, 2019

## License
This project is licensed under the terms of the MIT license.
