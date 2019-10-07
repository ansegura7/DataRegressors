# Keras: Regression with Neural Networks
Project that performs the regression of a continuous variable (oil) from a set of associated variables. The Keras framework is used to easily create a TensorFlow Neural Network.

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
| 8 | Qinj | Operational | m3 | Numerical |
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
