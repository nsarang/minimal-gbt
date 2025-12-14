# minimal-gbt

A minimal implementation of Gradient Boosted Trees (LightGBM/XGBoost/CatBoost) built from scratch for educational purposes and experimentation.

**Blog post with full explanation:** [link-to-your-blog-post]

## Features

- Histogram-based splitting
- Multi-output trees (regression, classification, uncertainty estimation)
- Leaf-wise growth
- Categorical features (target statistics, Fisher's ordering)
- L1/L2 regularization
- GOSS sampling
- Missing value handling (XGBoost style)
- Path smoothing with exponential decay

## Installation
```bash
pip install numpy pandas numba scikit-learn framedisplay --quiet
```

## Structure
```
src/
├── gbm.py            # Main model class
├── data.py           # Data preprocessing
├── tree.py           # Tree and node structures
├── grower.py         # Tree building logic
├── distributions.py  # Loss functions
└── utils.py          # Utilities
```

## License

AGPL-3.0 License. See LICENSE file for details.