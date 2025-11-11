## Problem:

- Input: psi: np.ndarray of size $2^{2^n}$, complex, normalized (up to floating error).
- Output: QuantumCircuit on n qubits (no classical bits) that prepares psi from |0^n>.
- Constraint: Only 1Q gates and multi-controlled Rz. We realize uniformly-controlled Ry by basis-changes plus multiplexed Rz.
- How to Use:
  - prepare_state_circuit(psi: np.ndarray) -> QuantumCircuit
