# Attention Mechanism Simulation

This notebook implements a basic attention mechanism to demonstrate its functionality using a simple RGB matrix as an input. It includes steps for creating random matrices for RGB channels, computing attention weights, and applying the attention mechanism in a simulated environment.

## Notebook Overview

This implementation demonstrates the following key steps of the attention mechanism:

1. **Generate Input RGB Values**: Random values representing RGB channels are generated.
2. **Flatten the RGB Channels**: The channels are flattened and combined into a matrix.
3. **Compute Attention Weights**: Using randomly initialized weights for Queries (Q), Keys (K), and Values (V), the attention mechanism computes the attention score matrix.
4. **Apply Softmax**: The softmax function is applied to normalize the attention scores.
5. **Compute Weighted Average**: The dot product between attention weights and values is calculated to get the attention output.
6. **Reconstruct Output**: Finally, the output is transformed back into RGB space with a learnable output weight and a skip connection to preserve original pixel information.

## How to Run

1. Install the required libraries:
   ```bash
   pip install numpy scipy
   ```
2. Run the code in a Python environment or Jupyter notebook.

## References

- [Cross Attention | Method Explanation | Math Explained](https://youtu.be/aw3H-wPuRcw?si=5dcFiQghCMCpudTA)
- [Visual Guide to Transformer Neural Networks - (Episode 2) Multi-Head & Self-Attention](https://youtu.be/mMa2PmYJlCo?si=pknw3h31wnvrlW1u)
