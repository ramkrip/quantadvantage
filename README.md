# Loophole-Robust Quantum Advantage

This repository contains code and data supporting our study of **benchmark-dependent, loophole-robust certification of quantum advantage**.

The project develops a task-level analogue of measurement dependence in Bell tests. It quantifies how much benchmark-correlated classical side information would be required to reproduce an observed quantum–classical score gap.

## Repository contents

- `Non_local_games.ipynb` — implementation and analysis of CHSH, Mermin–GHZ, and Mermin–Peres magic-square benchmarks on IBM quantum hardware.
- `Quantum_Nonlocal_Games.zip` — raw and readout-mitigated count data for the nonlocal-game experiments.
- `ad_hoc_benchmark.ipynb` — Havlíček-style quantum-kernel benchmark and construction-side dependence audit.
- `Ad_hoc_new_15_20.zip` — data and outputs for the ad hoc benchmark using 15 training and 20 test examples per class.

## Requirements

The notebooks are intended for Python/Jupyter or Google Colab and use packages including:

```bash
pip install qiskit qiskit-aer qiskit-ibm-runtime numpy pandas scipy scikit-learn matplotlib
```

IBM hardware execution requires an IBM Quantum account. Store credentials using environment variables, Colab secrets, or the Qiskit account manager; do not place API tokens directly in notebooks.

## Reproducing the analyses

1. Clone or download the repository.
2. Extract the corresponding data archive.
3. Open the desired notebook.
4. Update local data paths and backend settings as needed.
5. Run the notebook cells in order.

The included archived results can be used to reproduce the reported figures and benchmark-dependence analyses without rerunning the hardware experiments.

## Citation

Please cite the associated manuscript when using this code or data. Citation details will be added after publication.

