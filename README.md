# OrbitalMechanics - N Stage rocket calculator
[![EXAMPLE 1](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1cTd-lX3T6UKBu04zrcXPyZ0rLAMOeZWy?usp=sharing) To run this file, click the colab button here, sign in to your google account on the colab site and in the top menu select `Runtime->Run all`

The objective is to prepare a calculator capable to calculate performances of a n-stage launcher in the vertical launch (maximum n=8).

User will enter the following data for each stage:
- Specific impulse $𝐼_{𝑆𝑃} 𝑖$
- Total mass $𝑚_0 𝑖$
- Mass of propellant $𝑚_𝑃 𝑖$
- Consumption of propellant $\dot{m}_𝑃 𝑖$
  
The calculator will return the following data for each stage:
- Time of combustion $𝑡_𝑓$
- Increment of velocity $\Delta Vi$
- Increment of altitude $\Delta hi$
  
Moreover, the calculator will return:
- Total velocity after the last stage cut-off
- Total altitude after the last stage cut-off
- Total altitude at the moment of zero velocity
- Curves showing the distribution of velocity and altitude along the time of combustion
 
All aerodynamic forces can be neglected. Gravitational acceleration can be considered as constant, 𝑔0 = 9.81 𝑚/𝑠
2
(even at very high altitudes).
