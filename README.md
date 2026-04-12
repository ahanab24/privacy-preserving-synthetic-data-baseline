VeilData: Privacy-Preserving Synthetic Financial Data Generator

Implementation Overview

Basic Synthetic Data Pipeline:

- Performed simple analysis on financial-style data to understand basic patterns
- Built a random synthetic data generator using simple rules and Indian lending logic (including FOIR-based calculations)
- Generated synthetic records for experimentation

Evaluation:
- Compared real vs synthetic data using KS test
- Results showed basic level similarity with expected deviations due to simple generation approach

Extended Attempt:
- Tried improving the generator using a basic GAN model
- Applied a simple differential privacy concept for privacy awareness
- Both approaches were experimental and basic in implementation

Limitations:
- Rule-based generator is not highly realistic
- GAN and DP implementations are very basic and experimental
- Rare patterns are not well captured
- Evaluation limited to KS test only

Future Work:
- Improve generator using better GAN models
- Add stronger privacy-preserving techniques
- Use more evaluation metrics beyond KS test
- Apply to larger real-world lending datasets
