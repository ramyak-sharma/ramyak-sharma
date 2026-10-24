<h1 align="center">Ramyak Sharma</h1> <p align="center"> C++ developer </p> <p align="center"> <a href="https://www.linkedin.com/in/ramyak-sharma-334a1b207/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a> <a href="https://gitlab.com/ramyaksharma"><img src="https://img.shields.io/badge/GitLab-FC6D26?style=flat&logo=gitlab&logoColor=white" alt="GitLab"></a> <a href="https://blogs.scummvm.org/ramyak/"><img src="https://img.shields.io/badge/Blog-ScummVM-4a4a4a?style=flat" alt="ScummVM blog"></a> <a href="mailto:ramyaksharma1@gmail.com"><img src="https://img.shields.io/badge/Email-ramyaksharma1%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"></a> </p>

---

## Interests

- **Interpreters and runtimes**: bytecode interpreters, VM execution state, and how an engine schedules scripts, rendering and input
- **Debuggers and profilers**: building the tools that make other code understandable
- **Reverse engineering and preservation**: decoding old binary formats and getting old software running faithfully on modern machines
- **Computer graphics**: ray tracing, compositing and image processing
- **Low-level systems**: memory safety, sanitizers, and building computers up from logic gates
- **Parallel computing**: OpenMP and getting the most out of the hardware
- **3D perception**: LiDAR point clouds, and measuring whether a model actually helps the task downstream
- **ML from first principles**: tokenizers and reinforcement learning, built by hand instead of called from a library

---

## Open source

- **ScummVM** (GSoC 2026): the Macromedia Director engine and its Lingo interpreter, plus a visual debugger with a flamegraph execution tracer
- **Inkscape**: performance and UI fixes in the C++/GTK codebase, including a multi-minute freeze when flattening large groups

---

## Projects

| Project | What it is | Stack |
|---|---|---|
| [**Point-Cloud-denoiser**](https://github.com/ramyak-sharma/Point-Cloud-denoiser) | My capstone project: denoising LiDAR scans in simulated rain and fog with six methods. Includes RangeRestoreNet, a range-image network our team designed that runs at 22 Hz. The DGCNN closes 98% of the recoverable error, and the results show that Chamfer distance fails to predict 3D detection quality. | Python · PyTorch |
| [**RayTracer**](https://github.com/ramyak-sharma/RayTracer) | A CPU path tracer with a camera model, sphere intersection, and Lambertian and metal materials. | C++ |
| [**CPUSimulator**](https://github.com/ramyak-sharma/CPUSimulator) | An interactive logic-circuit sandbox, built as the first step toward a CPU made from gates. | C++ · raylib |
| [**BytePairEncoding**](https://github.com/ramyak-sharma/BypePairEncoding) | The BPE tokenizer behind GPT-style models, written from scratch, with a Graphviz tree of the merges. | C++ |
| [**image_processing**](https://github.com/ramyak-sharma/image_processing) | A convolution engine with eight kernels and three border modes, plus a frame-difference map for motion detection. | C++ |
| [**AI-pong**](https://github.com/ramyak-sharma/AI-pong) | Pong with a Q-learning agent that learns to play against a human or another AI. | Python |
| [**UCS645**](https://github.com/ramyak-sharma/UCS645) | Parallel computing coursework: SAXPY and an N-body Lennard-Jones simulation, sequential vs. OpenMP. | C++ · OpenMP |

---

## Toolbox

**Languages:** C++, C, Python<br>
**Debugging & tooling:** AddressSanitizer, Dear ImGui, CMake, Git, Buildbot<br>
**Graphics / UI:** SDL, raylib, GTK<br>
**ML:** PyTorch
