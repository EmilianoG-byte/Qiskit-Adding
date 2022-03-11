# Finding elements in an array that add up to an integer

This is the solution for the screening task #1 for the 5th cohort of the QC Mentorship program. The solution is based on the Addition circuit by Thomas Draper and the Grover Search Algorithm.

## Problem Statement:

Design a quantum circuit that finds the subsets where the sum is equal to the value 16 in the following vector [5,7,8,9,1]

## Solution:

The two solutions are given after measuring the register qubits of the whole circuit. These are:
- [01010] == [7,9] and 
- [01101] == [7,8,1]

![image](https://user-images.githubusercontent.com/57567043/157991180-4da2735f-4f73-4618-b6e9-4ecce549b0ba.png)

## Setup

To run the code in the jupyter notebook you first need 
create a new conda environment and activate it 

```bash
  conda create -n QUANTUM python=3
  conda activate QUANTUM
```
    
Then, you need to install the Qiskit package. This might
 vary depending on your OS and version, but in my 
 case I used:

```bash
 pip install 'qiskit[visualization]'
```
    
In order for the new environment to appear while using jupyter 
notebook, you need to set it manually:

```bash
 python -m ipykernel install --user --name QUANTUM --display-name "Python (QUANTUM)"
```
## Author

- Cristian Emiliano Godinez Ramirez [@https://github.com/EmilianoG-byte](https://github.com/EmilianoG-byte)
