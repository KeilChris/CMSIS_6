# CMSIS-DSP {#mainpage}

**CMSIS-DSP** is an open-source software library that implements common compute processing functions optimized for use on Arm Cortex-M and Cortex-A processors. The library covers such compute categories as (list not exhaustive):

- Basic mathematics (real, complex, quaternion, linear algebra, fast math functions)
- DSP (filtering)
- Transforms (FFT, MFCC, DCT)
- Statistics
- Classical ML (Support Vector Machine, Distance functions for clustering, ...)

## Access to CMSIS-DSP

CMSIS-DSP is actively maintained in a GitHub repository and is also published as a standalone release in CMSIS Pack format.

- [**CMSIS-DSP GitHub Repo**](https://github.com/ARM-software/CMSIS-DSP) provides the full source code as well as releases in CMSIS-Pack format.
- [**CMSIS-DSP Documentation**](https://arm-software.github.io/CMSIS-DSP/latest/) explains how to use the library and describes the implemented functions in details.

## Key Features and Benefits

- CMSIS-DSP covers a broad set of compute functions common for use in embedded systems.
- Supports operations on 8-bit integers, 16-bit integers, 32-bit integer and 32-bit floating-point values.
- Provides vectorized versions of most algorthms for [Arm Helium Technology](https://developer.arm.com/Architectures/Helium) and of most f32 algorithms for [Arm Neon Technology](https://developer.arm.com/Architectures/Neon).
- Includes test framework.
- Provides examples demonstating how to use the library functions.
