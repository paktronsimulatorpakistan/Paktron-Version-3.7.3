# PKTron v3.7.3

PKTron is a Python quantum computing framework for simulation, algorithms, chemistry, machine learning, and hardware-realistic experimentation.

## Highlights in v3.7.3

### New Features
- Hardware calibration system
- Device drift simulation
- Dynamic circuits
- OpenQASM 3.0 import/export
- UCCSDSolver
- ADAPTVQESolver
- AdaptiveMPSSimulator
- Multi-GPU execution
- VirtualDistillation error mitigation
- Virtual quantum devices

## Install

```bash
pip install pktron
pip install pktron[gpu]
pip install pktron[chemistry]
pip install pktron[ml]
pip install pktron[full]

from pktron import QuantumCircuit, execute

qc = QuantumCircuit(2).h(0).cx(0,1)
result = execute(qc, shots=1000)

Core Modules

Quantum Circuits
Statevector Simulation
Density Matrix Simulation
Tensor Networks
Quantum Algorithms
Quantum Chemistry
Quantum Machine Learning
Error Correction
Error Mitigation
Hardware Realism
Benchmarking
New Hardware Features
CalibrationData
GateScheduler
DriftEngine
HardwareExecutionReport
DynamicCircuit
Research Tools
VQE
QAOA
Grover
Shor
UCCSD
ADAPT-VQE
BB84
QSVM
License

MIT License
print(result["counts"])
