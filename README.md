# qec-from-scratch
 
A quantum error-correction stack built from scratch, one step at a time: from a toy quantum simulator to error-correcting codes and a machine-learning decoder.
 
I come from software engineering and classical machine learning, and I'm building every piece myself rather than calling into existing libraries.

## Status
 
**v0.0 (October 2026):** single-qubit simulator. A qubit as a NumPy array, the NOT and Hadamard gates as matrices, and measurement probabilities.

Next: multi-qubit states, then noise, then the repetition code.
 
## Setup
 
```
git clone https://github.com/Rhejna/qec-from-scratch.git
cd qec-from-scratch
python -m venv .venv
source .venv/bin/activate      # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```
