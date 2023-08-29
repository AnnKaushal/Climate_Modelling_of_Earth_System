# Climate_Modelling_of_Earth_System
# Climate Modeling of Earth's Systems: Exploring Coupled Interactions in a Long-Term Simulation

## Description

This Jupyter Notebook project presents a simplified approach to climate modeling framework that explores the intricate interactions between various key environmental factors over an extended timeframe of 1000 years. By incorporating a robust Runge-Kutta numerical method, Navier-Stokes Equation, CO2-Temperature Feedback, and Bayesian Parameter Estimation, the simulation delves into the mutual influences of greenhouse gas concentrations, solar radiation variations, ice melting dynamics, ocean circulation patterns, and wind effects on Earth's climate.

The primary goals of this project are as follows:

1. **Simulation of Climate Dynamics**: Utilizing a sophisticated numerical method, this project simulates the dynamic behavior of Earth's climate system over an extended period. The simulation provides a detailed look at how various environmental factors influence each other and, ultimately, the planet's climate.

2. **Insights into Long-Term Climate Changes**: The resulting visualizations from this project offer insights into the complex climate dynamics that drive long-term changes. Researchers, educators, and policymakers can use these visualizations to explore how Earth's systems interact and respond to altering environmental conditions over the span of centuries.

3. **Runge-Kutta Numerical Method**: The project showcases the importance of the Runge-Kutta numerical method in accurately solving systems of coupled differential equations commonly found in climate modeling and other scientific simulations.

4. **Realistic Surface Albedo Modeling**: The project incorporates realistic surface albedo coefficients (albedo_ice and albedo_water) to reflect the real-world complexity of surface reflectivity and its impact on the energy balance of the planet.

5. **Educational and Research Tool**: This simulation serves as a valuable educational and research tool, allowing users to study the ramifications of various climate-related factors and providing a nuanced understanding of how small changes in individual variables can trigger substantial global effects.

## Project Structure

This project is structured into three main sections, each exploring a different aspect of climate modeling:

### 1. Long-Term Climate Simulation using Runge-Kutta (rk4) Method

- This section simulates Earth's climate over a 1000-year period using a numerical method known as the Runge-Kutta (rk4) method.
- It models the interactions between greenhouse gas concentrations, solar radiation, ice melting, ocean circulation, and wind effects.
- Visualizations are provided to illustrate the changes in temperature, ice fraction, CO2 concentration, and ocean circulation effect over time.
- The Runge-Kutta method is employed to accurately compute these changes at each time step.

### 2. Climate Change Simulation using Navier-Stokes Equation

- This section offers a simplified climate change simulation using the Navier-Stokes equation and the energy conservation principle.
- It focuses on the dynamic response of temperature to external impacts and dissipation processes.
- Parameters such as temperature, external impact, and dissipation are adjusted to demonstrate the effects of these factors on climate change.
- The simulation provides insight into how changes in these parameters can lead to varying temperature trends.

### 3. Simplified Climate Change Simulation with CO2-Temperature Feedback

- This section presents a simplified simulation of the relationship between atmospheric CO2 concentration and global mean temperature.
- It incorporates the concept of CO2-temperature feedback and assumes linear relationships while disregarding many real-world complexities.
- The simulation shows how changes in CO2 emissions influence global temperature and CO2 concentration over time.
- Both CO2 concentration and temperature are plotted to visualize their trends.

### 4. Bayesian Parameter Estimation for Climate Models

- This section employs Bayesian statistics to estimate parameters of a linear model representing the relationship between time and temperature and CO2 emissions.
- The goal is to find the best-fitting parameters that explain observed data while considering uncertainties and noise.
- Bayesian parameter estimation is conducted using a random walk Metropolis-Hastings algorithm.
- Visualizations illustrate the observed data, true model, and estimated model for both temperature and CO2 emissions.

## Getting Started

To run and interact with this Jupyter Notebook project, follow these steps:

1. Ensure you have Python and Jupyter Notebook installed on your system.

2. Clone or download this project repository to your local machine.

3. Open a command prompt or terminal window and navigate to the project directory.

4. Launch Jupyter Notebook by running the command:
   ```
   jupyter notebook
   ```

5. In your web browser, navigate to the Jupyter Notebook interface and open this notebook file (`.ipynb`).

6. Execute each code cell in the notebook by clicking on the cell and then pressing `Shift + Enter`. Follow the instructions within the notebook sections.

7. Explore the visualizations and insights provided by each section of the project.

## Requirements

This project requires the following Python libraries:

- NumPy
- Matplotlib

You can install these libraries using `pip` if they are not already installed on your system:

```
pip install numpy matplotlib
```
## Author

- Author: Anandita Kaushal
- Contact: 20bce034@nith.ac.in
