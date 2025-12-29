+++
date = '2025-12-28T00:00:00-07:00'
draft = false
title = 'Video Processing Convolution'
weight = 8
listImage = "images/convolutions.png"
image = "images/convolutions-content.png"
+++

I built a high-performance video processing system that applies various convolution filters to video files, enabling effects such as blurring, sharpening, and other image transformations. The project focused heavily on performance optimization through parallel computing techniques.

I implemented multiple parallelism strategies including SIMD (Single Instruction, Multiple Data) vectorization, OpenMP for shared-memory parallelization, and OpenMPI for distributed computing across multiple processors. Each technique was carefully optimized to maximize throughput and minimize processing time.

Through systematic optimization and parallelization, I achieved an 8x speedup compared to the initial naive implementation. This dramatic performance improvement demonstrates the importance of understanding hardware capabilities and applying appropriate parallel computing techniques. The project provided valuable experience in performance optimization, parallel programming, and understanding the trade-offs between different parallelization approaches.

**Technologies:** C, SIMD, OpenMP, OpenMPI
