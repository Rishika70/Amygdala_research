# Amygdala_research

This repository contains a Python simulation exploring the dynamics of a metaphorical "mental state" over time, drawing inspiration from quantum mechanics.  This is a *conceptual* model and does not represent actual brain function.  It uses quantum-mechanical concepts as analogies to explore how a hypothetical mental state could evolve under the influence of various factors.

I am currently researching the impact of different parameters on the simulated mental state and how various combinations affect the overall outcome.  My goal is to better understand how these modeled influences might lead to long-term trends in the state. 


## Model Description

The model simulates the evolution of a mental state using a time-dependent Schrödinger-like equation, solved numerically using `scipy.integrate.solve_ivp`.

**Influences:** The model incorporates "ego," "shame," and "attention" as dynamic influences, each with its own:
* **Intensity:** Initial strength of the influence.
* **Decay/Growth Rate:**  How the intensity changes over time (some decay, others grow).
* **Frequency:**  Oscillatory behavior of the influence.

The combined effect of these influences determines how the mental state evolves over time. The mental state itself is represented by a complex number (`ψ`), visualized by its magnitude and real/imaginary components.

## Code Explanation

The code consists of:

1. **Libraries:** `numpy`, `matplotlib`, `scipy`.
2. **Constants and Parameters:** Defined parameters that control the initial state and time evolution.
3. **`time_evolution` function:** Defines the differential equation for the time evolution of the mental state.
4. **Simulation:**  Initializes the state, solves the differential equation, and extracts the evolution of the real and imaginary components, along with the magnitude.
5. **Plotting:**  Visualizes the time-dependent mental state.

## Future Work

* **More Complex Influences:** Exploring additional influences and their interaction mechanisms.
* **Parameter Exploration:** A more systematic study of the parameter space.
* **Enhanced Visualizations:** Improved plotting and analysis techniques.
* **Connections to Psychological Theories:** Investigation of how the model relates to established psychological frameworks.

## How to Run the Code

1. Ensure you have Python and the required libraries installed (`numpy`, `matplotlib`, `scipy`).
2. Run the Python script.

## Disclaimer

This is a simplified model; no conclusions about real brain function or psychological processes should be drawn from it. It is a research tool for exploring the potential interactions of dynamic influences on a simplified, metaphorical representation of a mental state.
