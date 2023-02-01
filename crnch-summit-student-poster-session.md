# CRNCH Summit Poster Session
The CRNCH Student Poster Session will be held on Feburary 2nd, 2023 from ~12 to 1:15 PM. We are excited to have a large number of posters from our CRNCH students, and we also are thrilled to be able to feature the work of some of our [CRNCH PhD Fellowship winners](https://crnch.gatech.edu/content/crnch-fellowship).

We note that in some cases, we have not linked posters due to work being under submission or at the presenter's request. 

| Student Presenter, Student Authors | Poster Title | Advisor(s) | GT Department | [Poster] [Abstract] |
| ---------------------------------- | ------------ | ---------- | -------------|-------------------|
| Elton Pinto, Austin Adams | "Neko: A quantum map-filter-reduce programming language" |   Vivek Sarkar, Tom Conte, Jeffrey Young | ECE | [Poster](https://github.com/gt-crnch/crnch-summit-2023/blob/4172ba7ad9e9017ea3b2a6016c5de57386939f2b/student_poster_session/posters/Elton_Pinto_et_al_CRNCH_Summit_2023_Poster.pdf) [Abstract](#ep) |
| Ruobing Han, Jaewon Lee, Jun Chen, Bhanu Garg, Jeffrey Young, Mark Ahn, Xuele Zhou, John Lu, Haotian Sheng, Blaise Tine, Jaewoong Sim, Hyesoon Kim | "CuPBoP: CUDA for Parallelized and Broad-range Processors" |   Hyesoon Kim | ECE | [Poster]() [Abstract](#rh) |
| Pranav O. Mathews, Jennifer O. Hasler | "Physical Computing for Hopfield Networks on a Reconfigurable Analog IC" |   Dr. Jennifer Hasler | ECE | [Poster]() [Abstract](#pom) |
| Linhao Yang, Afolabi Ige, Jennifer Hasler, Hang Yang, Callie Hao | "Analog System High-level Synthesis to Physical Devices" |   Jennifer Hasler, Callie Hao | ECE | [Poster]() [Abstract](#ly) |
| Chaojian Li, Sixu Li, Yang (Katie) Zhao, Wenbo Zhu, Yingyan (Celine) Lin| "RT-NeRF: Real-Time On-Device Neural Radiance Fields Towards Immersive AR/VR Rendering" |   Yingyan (Celine) Lin | ECE | [Poster]() [Abstract](#cl) |
| Cheng Wan, Yang (Katie) Zhao, Yingyan (Celine) Lin| "MixGCN: Scalable GCN Training by Integrating Mixtures of Parallelism, Accelerators, and Experts Models" |   Yingyan (Celine) Lin | ECE | [Poster]() [Abstract](#cw) |
| Chaojian Li, Zhongzhi Yu, Yonggan Fu, Yongan Zhang, Yang Zhao, Haoran You, Qixuan Yu, Yue Wang, Yingyan (Celine) Lin| "HW-NAS-Bench: Hardware-aware Neural Architecture Search Benchmark" |   Yingyan (Celine) Lin | ECE | [Poster]() [Abstract](#clzy) |
| Patrick Lavin, Sudhanshu Agarwal, Ryan Lunch, Jeffrey Young, Richard Vuduc| "Multifidelity DRAM Simulation in SST" |   Jeffrey Young, Richard Vuduc | ECE | [Poster]() [Abstract](#pl) |
| Afolabi Ige, Jennifer Hasler| "Synthesizing Analog Computing ASICs with Programmable Standard Cells" |   Jennifer Hasler | ECE | [Poster]() [Abstract](#ai) |
| Mikhail Isaev, Nic McDonald, Jeff Young, Rich Vuduc| "ParaGraph: An application-simulator interface and toolkit for hardware-software co-design" |   Richard Vuduc | ECE | [Poster]() [Abstract](#mi) |
| Yonggan Fu, Yang Zhao, Yonggan Fu, Qixuan Yu, Yonggan Fu, Chaojian Li, Yonggan Fu, Yingyan (Celine) Lin| "2-in-1 Accelerator: Enabling Random Precision Switch for Winning Both Adversarial Robustness and Efficiency" |   Yingyan (Celine) Lin | ECE | [Poster]() [Abstract](#yf) |
| Haoran You, Cheng Wan, Yang Zhao, Zhongzhi Yu, Yonggan Fu, Jiayi Yuan, Shang Wu, Shunyao Zhang, Yongan Zhang, Chaojian Li, Vivek Boominathan, Ashok Veeraraghavan, Ziyun Li, Yingyan Lin| "EyeCoD: Eye Tracking System Acceleration via FlatCam-based Algorithm & Accelerator Co-Design" |   Yingyan (Celine) Lin | CS | [Poster]() [Abstract](#hy) |
| Yongan Zhang, Haoran You, Yonggan Fu, Tong Geng, Ang Li, Yingyan Lin | "G-CoS: GNN-Accelerator Co-Search Towards Both Better Accuracy and Efficiency" |   Yingyan (Celine) Lin | CS | [Poster]() [Abstract](#yz) |
| Francisco Munoz Martinez, Raveesh Garg, José L. Abellán, Manuel E Acacio, Clay Hughes, Siva Rajamanickam, Tushar Krishna | "Cycle Accurate Simulation of AI Applications using STONNE, SST-STONNE and OMEGA" |   Tushar Krishna | ECE | [Poster]() [Abstract](#fmm) |
| Albert Cho*, Anish Saxena*, Srikar Vanavasam | "Use CXL, not DDR, for Scalable Server Processors" |   Alexandros Daglis, Moinuddin Qureshi | ECE | [Poster]() [Abstract](#yz) |
| Rishov Sarkar, Cong (Callie) Hao | "LightningSim: Fast and Accurate Trace-Based Simulation for HLS" |   Cong (Callie) Hao | ECE | [Poster]() [Abstract](#rs) |
| Zhixin (Jack) Song, Bryan Gard, Spencer Bryngelson | "Solving Partial Differential Equations on Noisy Quantum Computers" |   Dr. Spencer H. Bryngelson | ECE | [Poster]() [Abstract](#zjs) |

## Student Abstracts:

<a id="ep">**Elton Pinto, Austin Adams - "Neko: A quantum map-filter-reduce programming language"**</a>

Programming quantum computers is hard. One has to painstakingly write code that builds a circuit using low-level quantum gates. In a way, writing a quantum program is analogous to writing assembly: it is tedious, error-prone, and hard to debug. The gate-level abstraction, albeit universal, is non-intuitive and too primitive to be used for rapidly prototyping large-scale quantum applications. There is a need to develop high-level abstractions that enable programmers to productively leverage the idiosyncrasies of quantum computing: quantum parallelism, interference, and entanglement.

In this ongoing work, I present Neko, a high-level quantum programming language that exposes a map-filter-reduce interface for exploiting quantum parallelism through the notion of first-class superpositions.


<a id="rh">**Ruobing Han, Jaewon Lee, Jun Chen, Bhanu Garg, Jeffrey Young, Mark Ahn, Xuele Zhou, John Lu, Haotian Sheng, Blaise Tine, Jaewoong Sim, Hyesoon Kim - "CuPBoP: CUDA for Parallelized and Broad-range Processors"**</a>

CuPBoP is an open source framework, which supports executing CUDA on non-NVIDIA devices. Currently, we are working on supporting CUDA on CPUs, Vortex GPUs, AMD GPUs, and Intel GPUs. By supporting CUDA on non-NVIDIA devices, we can support Single-Kernel-Multiple-Device execution on heterogeneous systems.


