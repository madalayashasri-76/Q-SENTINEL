# Q-SENTINEL: Quantum-Based Network Attack Detection

## Project Overview
Q-SENTINEL is a prototype exploring classical machine learning and quantum machine learning for network intrusion detection using Qiskit.

## Objectives
- Identify normal and malicious network traffic.
- Compare a classical Random Forest classifier with a quantum-kernel SVM.
- Explore generalization to an attack family excluded from training.

## Technologies Used
- Python
- IBM Qiskit
- Qiskit Machine Learning
- Scikit-learn
- Pandas and NumPy
- Matplotlib and Seaborn
- Google Colab

## Dataset
The project uses the NSL-KDD network intrusion detection dataset.

## Implementation
1. Load and prepare the dataset.
2. Train a classical Random Forest baseline.
3. Create a quantum feature map.
4. Train a quantum-kernel SVM.
5. Compare evaluation metrics.
6. Evaluate the classical model on an excluded `ipsweep` attack family.

## Repository Contents
- `Q-SENTINEL_Zero_Day_Detection_ipynb_.ipynb` — notebook implementation
- `Q_SENTINEL_Experiment_Results.csv` — model comparison metrics
- `Q_SENTINEL_Unseen_Attack_Predictions.csv` — unseen-attack experiment predictions

## Limitations
This is an experimental prototype using a public dataset. Testing on an excluded attack family does not establish reliable real-world zero-day detection. The quantum-kernel experiment uses a small simulated quantum workflow and does not demonstrate a quantum speedup.

## Future Improvements
- Improve unseen-attack detection and false-alarm control.
- Evaluate on additional attack families and datasets.
- Explore execution on IBM Quantum hardware where available.

## References
- [Qiskit documentation](https://docs.quantum.ibm.com/)
- [NSL-KDD dataset information](https://www.unb.ca/cic/datasets/nsl.html)

