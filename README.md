# Quantum Fractional-Step Lattice Boltzmann Method (QFS-LBM)
Supplementary code for the publication: Xiao Yang, Yang Liming, Shu Chang, Du Yinjie. A Stable and General Quantum Fractional-Step Lattice Boltzmann Method for Incompressible Flows. arXiv preprint arXiv:2603.00558. 2026. 
# Abstract
Quantum computing shows substantial potential in accelerating simulations and alleviating memory bottlenecks in computational fluid dynamics (CFD), owing to its inherent properties of superposition and entanglement. The lattice Boltzmann method (LBM), being largely algebraic in nature, has inspired the development of various quantum LBMs. However, most existing approaches fix the relaxation time at τ = 1, thereby confining a given mesh resolution to simulations at a single Reynolds number. Although our earlier quantum lattice kinetic scheme (LKS) lifted this restriction, it suffers from instability at high Reynolds numbers. To address this challenge, we propose a quantum fractional-step LBM (FS-LBM). In this framework, the predictor step is implemented on a quantum circuit using the standard LBM formulation, while the corrector step is performed classically. The relaxation time is retained at τ = 1 to ensure seamless compatibility with existing quantum LBMs. Benchmark simulations of representative two- and three-dimensional incompressible isothermal and thermal flows demonstrate that the quantum FS-LBM achieves accuracy and convergence orders consistent with its classical counterpart, while significantly outperforming the quantum LKS in both precision and stability. Notably, this work presents the first quantum LBM simulation of three-dimensional incompressible thermal flows.
# Citation
@article{xiao2026stable,
  title={A Stable and General Quantum Fractional-Step Lattice Boltzmann Method for Incompressible Flows},
  author={Xiao, Yang and Yang, Liming and Shu, Chang and Du, Yinjie},
  journal={arXiv preprint arXiv:2603.00558},
  year={2026}
}
