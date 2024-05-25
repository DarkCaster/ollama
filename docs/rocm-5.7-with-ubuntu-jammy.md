# Building on ubuntu jammy (22.04) with older ROCM

Add repositories from this instruction, use repo for ROCM version 5.7.3:

<https://rocm.docs.amd.com/projects/install-on-linux/en/latest/how-to/native-install/ubuntu.html>

You *must* also complete post-install instructions:

<https://rocm.docs.amd.com/projects/install-on-linux/en/latest/how-to/native-install/post-install.html>

Install packages

```sh
apt-get install --no-install-recommends \
rocm-gdb \
rocminfo \
rocm-utils \
rocm-llvm \
rocm-smi-lib \
hsa-amd-aqlprofile \
rocm-device-libs \
rocm-cmake \
rocprofiler \
rocm-debug-agent \
rocprofiler-dev \
hsa-rocr-dev \
hipify-clang \
hipcc \
rocm-core \
hip-runtime-amd \
rocm-opencl \
hip-dev \
hip-doc \
roctracer \
rocm-opencl-dev \
roctracer-dev \
hip-samples \
rocprofiler-plugins \
hsakmt-roct-dev \
rocm-dbgapi \
hsa-rocr \
amd-smi-lib \
rocm-clang-ocl \
rocm-ocl-icd \
amdgpu-core \
rocm-dev \
hipblas-dev \
hipblas \
rocsolver-dev \
rocsolver \
rocsparse \
rocblas \
rocsparse-dev \
rocblas-dev
```
