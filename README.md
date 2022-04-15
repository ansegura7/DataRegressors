# Data Regressors
Ongoing project that performs the regression of a continuous variable (oil rate) from a set of associated variables using different ML and DL techniques, such as linear regression, time series, or neural networks.

## Analysis
<details open>
<summary>1. <a href="https://ansegura7.github.io/DataRegressors/pages/DataProfiling" target="_blank" >Data Exploration and Profiling</a></summary>
<ul>
	<li>Data Exploration</li>
	<li>Descriptive Statistics</li>
	<li>Data Profiling</li>
</ul>
</details>
<details open>
<summary>2. <a href="https://ansegura7.github.io/DataRegressors/pages/TimeSeries" target="_blank" >Time Series</a></summary>
<ul>
	<li>Visual Analytics</li>
	<li>Base Line</li>
	<li>Time Series Analysis</li>
    <li>Box-Jenkins Analysis</li>
    <li>Holt-Winters Analysis</li>
    <li>Compare Models</li>
</ul>
</details>
<details open>
<summary>3. <a href="https://ansegura7.github.io/DataRegressors/pages/RandomForestR" target="_blank" >Random Forest Regression</a></summary>
<ul>
	<li>Quick example</li>
</ul>
</details>
<details open>
<summary>4. <a href="https://ansegura7.github.io/DataRegressors/pages/RegressionNN" target="_blank" >NN Regression</a></summary>
<ul>
	<li>Load and show data</li>
	<li>Prepare the data to Learn</li>
	<li>Create Train/Validation/Test datasets</li>
    <li>Train Model</li>
    <li>Make predictions and calculate error</li>
    <li>Plot Results</li>
</ul>
</details>

## Data
The dataset used is composed of a group a group of operational and PVT variables for oil wells.

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

All datasets used in this project can be viewed in this <a href="https://github.com/ansegura7/DataRegressors/tree/master/data">folder</a>.

## Dependencies
To install these packages with conda, run the following commands:

``` console
 conda install -c conda-forge pandas-profiling
 conda install -c conda-forge keras
 conda install -c anaconda pydot
```

## Contributing and Feedback
Any kind of feedback/suggestions would be greatly appreciated (algorithm design, documentation, improvement ideas, spelling mistakes, etc...). If you want to make a contribution to the course you can do it through a PR.

## Authors
- Created by Segura Tinoco, Andrés
- Created on Oct 4, 2019
- Updated on Apr 15, 2022

## License
This project is licensed under the terms of the <a href="https://github.com/ansegura7/DataRegressors/blob/master/LICENSE">MIT license</a>.
