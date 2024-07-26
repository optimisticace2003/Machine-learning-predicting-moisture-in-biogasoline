

**BIOGASOLINE MOISTURE MEASUREMENT PROJECT**
This repository contains four research projects focused on measuring moisture presence in biogasoline using various algorithms for hyperparameter optimization. The main objective is to compare the efficiency and error rates of different algorithms to determine the best approach for detecting moisture in biogasoline.

**PROJECTS OVERVIEW**
**1. Moisture Measure with Hyperparameter Optimization in Biogasoline using a Novel GridSearch Cross-Validation in Comparison with Particle Swarm Optimization with Reduced Error Rate**
**Aim:** To find the moisture presence in biogasoline using the Novel Grid Search Cross-Validation (NGSCV) algorithm and compare it with Particle Swarm Optimization (PSO).

**Materials and Methods:**

Sample Size: 25 samples for each algorithm
Power Analysis: 80% power achieved using G power
Algorithms Used: NGSCV and PSO
Results:

NGSCV Error Rate: 86.5%
PSO Error Rate: 62.8%
Statistical Significance: p = 0.023 (Independent sample t-test p<0.05)
Conclusion: The NGSCV algorithm has an error rate of 86.2% compared to the PSO algorithm's 62.8%.

**2. Biogasoline Moisture Measure with Hyperparameter Optimization using Novel GridSearch Cross-Validation over Bayesian Optimization based on Error Rate**
**Aim:** To reduce the error rate in detecting the quality of biogasoline using NGSCV compared to Bayesian Algorithm (BA).

**Materials and Methods:**

Sample Size: 25 samples for each algorithm
Power Analysis: 80% power achieved using G power
Algorithms Used: NGSCV and BA
Results:

NGSCV Error Rate: 86.5%
BA Error Rate: 78.6%
Conclusion: The NGSCV algorithm is more efficient than the Bayesian Optimization in detecting the water content in biogasoline.

3. Optimizing Moisture Measurement in Biogasoline using A Novel GridSearch Cross-Validation Approach for Minimizing Average Error Rate Compared to Genetic Algorithm
**Aim:** To find the moisture presence in biogasoline using NGSCV and compare it with the Genetic Algorithm (GA).

**Materials and Methods:**

Sample Size: 25 samples for each algorithm
Power Analysis: 80% power achieved using G power
Algorithms Used: NGSCV and GA
Results:

NGSCV Accuracy: 86.2% (Error Rate: 13.8%)
GA Accuracy: 70.88% (Error Rate: 29.12%)
Statistical Significance: p = 0.02 (Independent sample t-test p<0.05)
Conclusion: The NGSCV algorithm has a better error rate of 86.2% compared to the GA algorithm's 70.88%.

**4. Reduction of Average Error Rate in Biogasoline Moisture Measures with Hyperparameter Optimization using a Novel GridSearch Cross-Validation against Cross Validation Optimization**

**Aim:** To compare NGSCV with Cross Validation (CV) in determining the moisture presence in biogasoline.

**Materials and Methods:**

Sample Size: 25 samples for each algorithm
Power Analysis: 80% power achieved using G power
Algorithms Used: NGSCV and CV
Results:

NGSCV Error Rate: 86.2%
CV Error Rate: 78.12%
Statistical Significance: p = 0.025 (Independent sample t-test p<0.05)
Conclusion: NGSCV has an error rate reduction to 13.8% compared to CV's 21.98%.

**Repository Content**
Source Code: Implementation of NGSCV, PSO, BA, GA, and CV algorithms.
Results: Detailed results and error rate analysis.
Documentation: Comprehensive guide on replicating the studies.


## Getting Started

| Command | Description |
|---------|-------------|
| `git clone https://github.com/yourusername/biogasoline-moisture-measurement.git` | Clone the repository |
| `cd biogasoline-moisture-measurement` | Navigate into the project directory |


**Install Dependencies:**
Ensure you have Python and the required libraries installed.

| Command | Description |
|---------|-------------|
| `pip install -r requirements.txt` | to install requirements in system |

**Run the Algorithms:**
Follow the instructions in the documentation folder to run each algorithm and analyze the results.
