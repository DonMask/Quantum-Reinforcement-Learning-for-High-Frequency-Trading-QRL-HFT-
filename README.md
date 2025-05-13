# Quantum Reinforcement Learning for High-Frequency Trading

This repository contains the full implementation and documentation for the project **Quantum Reinforcement Learning for High-Frequency Trading**, exploring the integration of quantum computing with deep reinforcement learning algorithms in high-frequency market environments.

> **DOI**: [10.5281/zenodo.15384978](https://doi.org/10.5281/zenodo.15384978)

## Overview

This work investigates the use of quantum-enhanced fidelity metrics and reinforcement learning agents in the context of high-frequency trading (HFT). The project benchmarks performance using real market data and simulated qubit fidelity noise. Theoretical models and simulations are detailed in the LaTeX documentation.

## Repository Structure

```
.
├── code/
│   ├── benchmark_hft.py
│   ├── generate_report.py
│   └── quantum_fidelity.py
├── data/
│   ├── benchmark_manila.json
│   └── results.json
├── .zenodo.json
├── LICENSE
├── Q-TradeRL.pdf
├── README.md
├── main.tex
└── references.bib
```

## How to Run

```bash
# 1. Benchmark RL agent
python code/benchmark_hft.py

# 2. Simulate quantum fidelity noise
python code/quantum_fidelity.py

# 3. Generate performance report
python code/generate_report.py
```

## Citation

If you use this work, please cite:

```bibtex
@misc{berger2025quantum,
  author       = {Teodor Berger},
  title        = {Quantum Reinforcement Learning for High-Frequency Trading},
  year         = 2025,
  doi          = {10.5281/zenodo.15384978},
  url          = {https://doi.org/10.5281/zenodo.15384978}
}
```

## License

This project is licensed under the MIT License.

## Contact

## Contact

For questions or collaboration, contact Teodor Berger at bergerteodor@googlemail.com.
