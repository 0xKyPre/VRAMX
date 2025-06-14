# VRAMX  
An intelligent algorithm for transparent expansion of NVIDIA GPU memory via external media.
---

## Motivation  
NVIDIA GPUs have limited VRAM capacity, which can create bottlenecks in large-scale AI training, simulations, or data-intensive computations. Existing solutions often require manual management or hardware upgrades. VRAMX aims to provide a transparent, software-only approach to extend GPU memory by intelligently managing data movement between VRAM and external storage, enabling users to run larger workloads without hardware changes.

## Objective  
Develop an intelligent software algorithm that leverages CUDA Unified Memory to dynamically and transparently swap large data sets between GPU VRAM and external memory, without requiring any code modifications from the user.

## Technical Approach  
- Utilizes CUDA Unified Memory and Memory Advice APIs  
- Monitors and manages memory access patterns  
- Implements dynamic paging between VRAM and external storage  
- Modular design for easy integration and scalability

## Installation  
*This project requires an NVIDIA GPU with CUDA support.*  
1. Install NVIDIA drivers and CUDA toolkit (version X.Y or higher).  
2. Clone this repository.  
3. Build the project using the provided build scripts or `make`.  
4. Run example applications located in `/examples` (to be added).

## Testing & Evaluation  
- Compatible with NVIDIA GPUs supporting CUDA Compute Capability X.X and above.  
- Tested on CUDA versions X.Y, X.Z.  
- Initial benchmarks show promising improvements in workload size handling with minimal performance overhead (details and charts to be added).  

## License  
This project is licensed under the [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)](https://creativecommons.org/licenses/by-nc-nd/4.0/) license.

## Contact  
Kylian Preining — k.preining.vramx@gmail.com  
[LinkedIn](https://www.linkedin.com/in/kylianpreining)