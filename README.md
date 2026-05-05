## Hi there 👋

- 🌱 My current research focuses on: AI for Computer Graphics, especially AI for accelerating geometric computing and numerical solvers.
- 📫 How to reach me: Contact me via email `zherui_yang@mail.ustc.edu.cn`. [Zhihu](https://www.zhihu.com/people/adversarr)
- 🚀 I'm working on [gsx](https://github.com/Adversarr/gsx), an efficient, multiplatform 3DGS rendering/training library.

### Research 

1. "Learning Sparse Approximate Inverse Preconditioners for Conjugate Gradient Solvers on GPUs" (NeurIPS 2025): [code](https://github.com/Adversarr/LearningSparsePreconditioner4GPU) It explores the possibility that GNNs learn to improve & accelerates Sparse Approximate Inverse (SPAI) preconditioners, with practical wall-clock acceleration and GNN-SPAI architectural alignment.
2. "Learning Laplacian Eigenspace with Mass-Aware Neural Operators on Point Clouds" (SIGGRAPH 2026 Conference): [code](https://github.com/Adversarr/NEO) It use neural operator to learn the eigen-space of Laplacian operator (which defines "Fourier modes" on manifolds), achieving high efficiency while maintaining accuracy and robustness.
3. "Simple yet Effective: Low-Rank Spatial Attention for Neural Operators" (ICML 2026): [code](https://github.com/Adversarr/LRSA-Operator) By analyzing SOTA neural operators, we propose a simple attention block that removes inductive bias and improves overall performance.

### OSS Works

1. [mathprim](https://github.com/Adversarr/mathprim): tiny header-only tensor library, along with many optimization/solver implementations (Cholesky, ICPCG, L-BFGS, and more).
2. [ssim](https://github.com/Adversarr/ssim): tiny & simple simulator, built on mathprim. Reach out my zhihu [blog](https://zhuanlan.zhihu.com/p/722554540) to see how fast it is!
3. [tinygs](https://github.com/Adversarr/tinygs): Blazing fast 3D Gaussian Splatting (3DGS) implementation, pure C++/CUDA, with async dataloading, tile-based rendering, and highly optimized CUDA rendering kernels.
