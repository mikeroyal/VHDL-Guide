<h1 align="center">
 <img src="">
  <br />
  VHDL Guide
</h1>

#### A guide covering VHDL including the applications, libraries and tools that will make you a better and more efficient with VHDL development.

**Note: You can easily convert this markdown file to a PDF in [VSCode](https://code.visualstudio.com/) using this handy extension [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf).**

<p align="center">
<img src="">
<br />
</p>

<p align="center">
<img src="">
<br />
Register-transfer level (RTL) Hardware Design with VHDL
</p>

# Table of Contents

1. [VDHL Learning Resources](https://github.com/mikeroyal//VHDL-Guide#VDHL-Learning-Resources)

2. [VDHL Tools](https://github.com/mikeroyal//VDHL-Guide#VHDL-Tools)

3. [OpenCL Development](https://github.com/mikeroyal/VHDL-Guide#opencl-development)

4. [Virtualization Tools](https://github.com/mikeroyal/VHDL-Guide#virtualization-tools)

5. [Emulation Tools](https://github.com/mikeroyal/VHDL-Guide#emulation-tools)

6. [Firmware Development](https://github.com/mikeroyal/VHDL-Guide#firmware-development)

7. [MATLAB Development](https://github.com/mikeroyal/VHDL-Guide#matlab-development)

8. [Verilog/SystemVerilog Development](https://github.com/mikeroyal/VHDL-Guide#VerilogSystemVerilog-development)

9. [Assembly Development](https://github.com/mikeroyal/VHDL-Guide#assembly-development)

10. [C/C++ Development](https://github.com/mikeroyal/VHDL-Guide#cc-development)

11. [Electric charge, field, and potential](https://github.com/mikeroyal/VHDL-Guide#electric-charge-field-and-potential)

     - Charge and electric force (Coulomb's law): Electric charge, field, and potential
     - Electric field: Electric charge, field, and potential
     - Electric potential energy, electric potential, and voltage: Electric charge, field, and potential

12. [Circuits](https://github.com/mikeroyal/VHDL-Guide#Circuits)

    - Ohm's law and circuits with resistors: Circuits
    - Circuits with capacitors: Circuits

13. [Magnetic forces, magnetic fields, and Faraday's law](https://github.com/mikeroyal/VHDL-Guide#magnetic-forces-magnetic-fields-and-Faradays-law)

    - Magnets and Magnetic Force: Magnetic forces, magnetic fields, and Faraday's law
    - Magnetic field created by a current: Magnetic forces, magnetic fields, and Faraday's law
    - Electric motors: Magnetic forces, magnetic fields, and Faraday's law
    - Magnetic flux and Faraday's law

14. [Electromagnetic waves and interference](https://github.com/mikeroyal/VHDL-Guide#electromagnetic-waves-and-interference)

    - Introduction to electromagnetic waves: Electromagnetic waves and interference
    - Interference of electromagnetic waves


# VDHL Learning Resources
[Back to the Top](https://github.com/mikeroyal/VHDL-Guide#table-of-contents)

[VHDL](https://en.wikipedia.org/wiki/VHDL) is a hardware description language specifically for designing physical and digital circuitry.

[Very Large-Scale Integration (VLSI)](https://en.wikipedia.org/wiki/Very_large_scale_integration) is the process of creating an integrated circuit (IC) by combining millions of MOS transistors onto a single chip.

[Central Processing Unit (CPU)](https://en.wikipedia.org/wiki/Central_processing_unit) is a circuit that's composed of multiple cores that executes instructions comprising a computer program. The CPU performs basic arithmetic, logic, controlling, and input/output (I/O) operations specified by the instructions in the program. This is different from other external components such as main memory, I/O circuitry, and graphics processing units (GPUs).

[Vector Processor](https://en.wikipedia.org/wiki/Vector_processor) is a central processing unit (CPU) that implements an instruction set where its instructions are designed to operate efficiently and effectively on large one-dimensional arrays of data called vectors.

[Application Specific Integrated Circuits (ASICs)](https://en.wikipedia.org/wiki/Application-specific_integrated_circuit) is an integrated circuit (IC) chip customized for a particular use in embedded systems, mobile phones, personal computers, professional workstations, rather than intended for general use.

[Single Instruction, Multiple Data (SIMD)](https://en.wikipedia.org/wiki/SIMD) is a type of parallel processing that describes computers with multiple processing elements that perform the same operation on multiple data points simultaneously.

[Top VHDL Courses Online | Udemy](https://www.udemy.com/topic/VHDL/)

[Introduction to VHDL | Udemy](https://www.udemy.com/course/introduction-to-vhdl/)

[FPGA & ASIC Design Using VHDL](https://www.doulos.com/content/training/vhdl_design_training.php)

[Hardware Description Languages for FPGA Design | Coursera](https://www.coursera.org/learn/fpga-hardware-description-languages)

[Hardware Description Languages for FPGA Design | Coursera](https://www.coursera.org/lecture/fpga-hardware-description-languages/intro-to-vhdl-finite-state-machine-W0Q6C)

[Intel® FPGA Technical Training Catalog](https://www.intel.com/content/www/us/en/support/programmable/support-resources/fpga-training/catalog.html?s=Newest)

[Getting Started with FPGA Programming with VHDL | Pluralsight](https://www.pluralsight.com/courses/fpga-vhdl-programming-getting-started)


# VDHL Tools
[Back to the Top](https://github.com/mikeroyal/VHDL-Guide#table-of-contents)

[VHDLweb](https://vhdlweb.com) is an online VHDL simulator and coding exercise tool. Anyone is welcome to view and work through the problems, but at present your work will not be saved beyond a single browser session.

[Logisim evolution](https://github.com/logisim-evolution/logisim-evolution) is an educational software for designing and simulating digital logic circuits.

[GHDL](https://github.com/ghdl/ghdl) is an open-source analyzer, compiler, simulator and (experimental) synthesizer for VHDL, a Hardware Description Language (HDL). GHDL is not an interpreter it allows you to analyse and elaborate sources for generating machine code from your design.

[Clash](https://clash-lang.org/) is a functional hardware description language that borrows both its syntax and semantics from the functional programming language Haskell. The Clash compiler transforms these high-level descriptions to low-level synthesizable VHDL, Verilog, or SystemVerilog.

[SpinalHDL](https://github.com/SpinalHDL/SpinalHDL) is a Scala based HDL (Hardware Description Language) used to describe digital hardware.

[TerosHDL](https://github.com/TerosTechnology/vscode-terosHDL) is an open source IDE for HDL devlopers with functionalities commonly used by software developers. The IDE consist in a bunch of tools and on top of them is the VSCode plugin.

[Synopsys® SpyGlass®](https://www.synopsys.com/verification/static-and-formal-verification/spyglass.html) is a platform that provides designers with insight about their design, early in the process at RTL. It functions like an interactive guidance system for design engineers and managers, finding the fastest and least expensive path to implementation for complex SoCs.

[SymbiFlow](https://symbiflow.github.io) is a fully open source toolchain for the development of FPGAs of multiple vendors. Currently, it targets the Xilinx 7-Series, Lattice iCE40, Lattice ECP5 FPGAs, QuickLogic EOS S3 and is gradually being expanded to provide a comprehensive end-to-end FPGA synthesis flow.

[LabVIEW FPGA](https://www.ni.com/en-us/shop/software/products/labview-fpga-module.html) is a software add-on for LabVIEW that you can use to more efficiently and effectively design FPGA-based systems through a highly integrated development environment, IP libraries, a high-fidelity simulator, and debugging features.

[Apio](https://github.com/FPGAwars/apio) is a multiplatform toolbox, with static pre-built packages, project configuration tools and easy command interface to verify, synthesize, simulate and upload your verilog designs.

[IceStorm](https://github.com/YosysHQ/icestorm) is a project that aims at documenting the bitstream format of Lattice iCE40 FPGAs and providing simple tools for analyzing and creating bitstream files.

[Icestudio](https://icestudio.io/) is a visual editor for open FPGA boards. Built on top of the Icestorm project using Apio.

[FuseSoC](https://github.com/olofk/fusesoc) is an award-winning package manager and a set of build tools for HDL (Hardware Description Language) code and FPGA/ASIC development.

[OpenWiFi](https://github.com/open-sdr/openwifi) is an open-source IEEE802.11/Wi-Fi baseband chip/FPGA design.

[PipeCNN](https://github.com/doonny/PipeCNN) is an OpenCL-based FPGA Accelerator for Large-Scale Convolutional Neural Networks (CNNs). Currently, there is a growing trend among developers in the FPGA community to utilize High Level Synthesis (HLS) tools to design and implement customized circuits on FPGAs.

[Verilator](https://verilator.org/) is an open-source SystemVerilog simulator and lint system.

[Verilog to Routing(VTR)](https://verilogtorouting.org/) is a collaborative project to provide a open-source framework for conducting FPGA architecture and CAD Research & Development. The VTR design flow takes as input a Verilog description of a digital circuit, and a description of the target FPGA architecture.

[PlatformIO](https://platformio.org/) is a professional collaborative platform for embedded development with no vendor lock-in. It provides support for multiplatforms and frameworks such as IoT, Arduino, CMSIS, ESP-IDF, FreeRTOS, libOpenCM3, mbed OS, Pulp OS, SPL, STM32Cube, Zephyr RTOS, ARM, AVR, Espressif (ESP8266/ESP32), FPGA, MCS-51 (8051), MSP430, Nordic (nRF51/nRF52), NXP i.MX RT, PIC32, RISC-V.

[PlatformIO for VSCode](https://marketplace.visualstudio.com/items?itemName=platformio.platformio-ide) is a plugin that provides support for the PlatformIO IDE on VSCode.

[Tock](https://www.tockos.org/) is an embedded operating system designed for running multiple concurrent, mutually distrustful applications on Cortex-M and RISC-V based embedded platforms. Tock's design centers around protection, both from potentially malicious applications and from device drivers.

[OpenTimer](https://github.com/OpenTimer/OpenTimer) is a High-Performance Timing Analysis Tool for VLSI Systems.

[LLVM](https://github.com/llvm/) is a library that has collection of modular/reusable compiler and toolchain  components (assemblers, compilers, debuggers, etc.). With these components LLVM can be used as a compiler framework, providing a front-end(parser and lexer) and a back-end (code that converts LLVM's representation to actual machine code).

[TinyGo](https://tinygo.org/) is a Go compiler(based on LLVM) intended for use in small places such as microcontrollers, WebAssembly (Wasm), and command-line tools.

[Chipyard](https://chipyard.readthedocs.io/en/latest/) is an open source framework for agile development of Chisel-based systems-on-chip. It will allow you to leverage the Chisel HDL, Rocket Chip SoC generator, and other [Berkeley](https://berkeley.edu/) projects to produce a RISC-V SoC with everything from MMIO-mapped peripherals to custom accelerators.

[The Eclipse Embedded CDT](https://github.com/eclipse-embed-cdt/eclipse-plugins) is a collection of plug-ins for Arm & RISC-V C/C++ developers.
[Unicorn](https://github.com/unicorn-engine/unicorn) is a lightweight, multi-platform, multi-architecture CPU emulator framework(ARM, AArch64, M68K, Mips, Sparc, X86) based on [QEMU](https://www.qemu.org/).

[Keystone](https://github.com/keystone-engine/keystone) is a lightweight multi-platform, multi-architecture(Arm, Arm64, Hexagon, Mips, PowerPC, Sparc, SystemZ & X86) assembler framework.

[Reko](https://github.com/uxmal/reko) is a decompiler for machine code binaries.

[Renode](https://renode.io/) is [Antmicro's](https://antmicro.com) virtual development framework for multinode embedded networks (both wired and wireless) and is intended to enable a scalable workflow for creating effective, tested and secure IoT systems.


# OpenCL Development
[Back to the Top](https://github.com/mikeroyal/VHDL-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/130368400-7b6a82d3-ed03-4158-ade4-d7fc6cc9960a.png">
  <br />
</p>

## OpenCL Learning Resources

[Open Computing Language (OpenCL)](https://www.khronos.org/opencl/) is an open standard for [parallel programming](https://www.coursera.org/lecture/parprog1/introduction-to-parallel-computing-zNrIS) of heterogeneous platforms consisting of CPUs, GPUs, and other hardware accelerators found in supercomputers, cloud servers, personal computers, mobile devices and embedded platforms.

[OpenCL | GitHub](https://github.com/OpenCL/)

[Khronos Group | GitHub](https://github.com/KhronosGroup/)

[Khronos Technology Courses and Training](https://www.khronos.org/developers/training/)

[OpenCL Tutorials - StreamHPC](https://streamhpc.com/knowledge/for-developers/tutorials/)

[Introduction to Intel® OpenCL Tools](https://software.intel.com/content/www/us/en/develop/articles/introduction-to-intel-opencl-tools.html)

[OpenCL | NVIDIA Developer](https://developer.nvidia.com/opencl)

[Introduction to OpenCL on FPGAs Course | Coursera](https://www.coursera.org/learn/opencl-fpga-introduction)

[Compiling OpenCL Kernel to FPGAs Course | Coursera](https://www.coursera.org/lecture/opencl-fpga-introduction/compiling-opencl-kernel-to-fpgas-g7MnU)

## OpenCL Tools, Libraries and Frameworks

[RenderDoc](https://renderdoc.org) is a stand-alone graphics debugger that allows quick and easy single-frame capture and detailed introspection of any application using Vulkan, D3D11, OpenGL & OpenGL ES or D3D12 across Windows, Linux, Android, Stadia, or Nintendo Switch™.

[GPUVerify](https://streamhpc.com/knowledge/tools/gpuverify/) is a tool for formal analysis of GPU kernels written in OpenCL and CUDA. The tool can prove that kernels are free from certain types of defect, including data races.

 [OpenCL ICD Loader](https://github.com/KhronosGroup/OpenCL-ICD-Loader) is an Installable Client Driver (ICD) mechanism to allow developers to build applications against an Installable Client Driver loader (ICD loader) rather than linking their applications against a specific OpenCL implementation.

[clBLAS](https://github.com/clMathLibraries/clBLAS) is a software library containing BLAS functions written in OpenCL.

[clFFT](https://github.com/clMathLibraries/clFFT) is a software library containing FFT functions written in OpenCL.

[clSPARSE](https://github.com/clMathLibraries/clSPARSE) is a software library containing Sparse functions written in OpenCL.

[clRNG](https://github.com/clMathLibraries/clRNG) is an OpenCL based software library containing random number generation functions.

[CLsmith](https://github.com/ChrisLidbury/CLSmith/) is a tool that  makes use of two existing testing techniques, Random Differential Testing and Equivalence Modulo Inputs (EMI), applying them in a many-core environment, OpenCL. Its primary feature is the generation of random OpenCL kernels, exercising many features of the language. It also brings a novel idea of applying EMI, via dead-code injection.

[Oclgrind](https://github.com/jrprice/Oclgrind) is a virtual OpenCL device simulator, including an OpenCL runtime with ICD support. The goal is to provide a platform for creating tools to aid OpenCL development. In particular, this project currently implements utilities for debugging memory access errors, detecting data-races and barrier divergence, collecting instruction histograms, and for interactive OpenCL kernel debugging. The simulator is built on an interpreter for LLVM IR.

[NVIDIA® Nsight™ Visual Studio Edition](https://developer.nvidia.com/nsight-visual-studio-edition) is an application development environment for heterogeneous platforms which brings GPU computing into Microsoft Visual Studio. NVIDIA Nsight™ VSE allows you to build and debug integrated GPU kernels and native CPU code as well as inspect the state of the GPU and memory.

[Radeon™ GPU Profiler](https://gpuopen.com/rgp/) is a performance tool that can be used by developers to optimize DirectX®12, Vulkan® and OpenCL™ applications for AMD RDNA™ and GCN hardware.

[Radeon™ GPU Analyzer](https://gpuopen.com/rga/) is a compiler and code analysis tool for Vulkan®, DirectX®, OpenGL® and OpenCL™.

[AMD Radeon ProRender](https://www.amd.com/en/technologies/radeon-prorender) is a powerful physically-based rendering engine that enables creative professionals to produce stunningly photorealistic images on virtually any GPU, any CPU, and any OS in over a dozen leading digital content creation and CAD applications.

[NVIDIA Omniverse](https://developer.nvidia.com/nvidia-omniverse-platform) is a powerful, multi-GPU, real-time simulation and collaboration platform for 3D production pipelines based on Pixar's Universal Scene Description and NVIDIA RTX.

[Intel® SDK For OpenCL™ Applications](https://software.intel.com/content/www/us/en/develop/tools/opencl-sdk.html) is an offload compute-intensive workloads. Customize heterogeneous compute applications and accelerate performance with kernel-based programming.

[NVIDIA NGC](https://ngc.nvidia.com/) is a hub for GPU-optimized software for deep learning, machine learning, and high-performance computing (HPC) workloads.

[NVIDIA NGC Containers](https://www.nvidia.com/en-us/gpu-cloud/containers/) is a registry that provides researchers, data scientists, and developers with simple access to a comprehensive catalog of GPU-accelerated software for AI, machine learning and HPC. These containers take full advantage of NVIDIA GPUs on-premises and in the cloud.

[NVIDIA cuDNN](https://developer.nvidia.com/cudnn) is a GPU-accelerated library of primitives for [deep neural networks](https://developer.nvidia.com/deep-learning). cuDNN provides highly tuned implementations for standard routines such as forward and backward convolution, pooling, normalization, and activation layers. cuDNN accelerates widely used deep learning frameworks, including [Caffe2](https://caffe2.ai/), [Chainer](https://chainer.org/), [Keras](https://keras.io/), [MATLAB](https://www.mathworks.com/solutions/deep-learning.html), [MxNet](https://mxnet.incubator.apache.org/), [PyTorch](https://pytorch.org/), and [TensorFlow](https://www.tensorflow.org/).

[NVIDIA Container Toolkit](https://github.com/NVIDIA/nvidia-docker) is a collection of tools & libraries that allows users to build and run GPU accelerated Docker containers. The toolkit includes a container runtime [library](https://github.com/NVIDIA/libnvidia-container) and utilities to automatically configure containers to leverage NVIDIA GPUs.

# Virtualization Tools
[Back to the Top](https://github.com/mikeroyal/VHDL-Guide#table-of-contents)

[HVM (Hardware Virtual Machine)](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/virtualization_types.html) is a virtualization type that provides the ability to run an operating system directly on top of a virtual machine without any modification, as if it were run on the bare-metal hardware.

[PV(ParaVirtualization)](https://wiki.xenproject.org/wiki/Paravirtualization_(PV)) is an efficient and lightweight virtualization technique introduced by the Xen Project team, later adopted by other virtualization solutions. PV does not require virtualization extensions from the host CPU and thus enables virtualization on hardware architectures that do not support Hardware-assisted virtualization.

[Network functions virtualization (NFV)](https://www.vmware.com/topics/glossary/content/network-functions-virtualization-nfv) is the replacement of network appliance hardware with virtual machines. The virtual machines use a hypervisor to run networking software and processes such as routing and load balancing. NFV allows for the separation of communication services from dedicated hardware, such as routers and firewalls. This separation means network operations can provide new services dynamically and without installing new hardware. Deploying network components with network functions virtualization only takes hours compared to months like with traditional networking solutions.

[Software Defined Networking (SDN)](https://www.vmware.com/topics/glossary/content/software-defined-networking) is an approach to networking that uses software-based controllers or application programming interfaces (APIs) to communicate with underlying hardware infrastructure and direct traffic on a network. This model differs from that of traditional networks, which use dedicated hardware devices (routers and switches) to control network traffic.

[Virtualized Infrastructure Manager (VIM)](https://www.cisco.com/c/en/us/td/docs/net_mgmt/network_function_virtualization_Infrastructure/3_2_2/install_guide/Cisco_VIM_Install_Guide_3_2_2/Cisco_VIM_Install_Guide_3_2_2_chapter_00.html) is a service delivery and reduce costs with high performance lifecycle management Manage the full lifecycle of the software and hardware comprising your NFV infrastructure (NFVI), and maintaining a live inventory and allocation plan of both physical and virtual resources.

[Management and Orchestration(MANO)](https://www.etsi.org/technologies/open-source-mano) is an ETSI-hosted initiative to develop an Open Source NFV Management and Orchestration (MANO) software stack aligned with ETSI NFV. Two of the key components of the ETSI NFV architectural framework are the NFV Orchestrator and VNF Manager, known as NFV MANO.

[Magma](https://www.magmacore.org/) is an open source software platform that gives network operators an open, flexible and extendable mobile core network solution. Their mission is to connect the world to a faster network by enabling service providers to build cost-effective and extensible carrier-grade networks. Magma is 3GPP generation (2G, 3G, 4G or upcoming 5G networks) and access network agnostic (cellular or WiFi). It can flexibly support a radio access network with minimal development and deployment effort.

[OpenRAN](https://open-ran.org/) is an intelligent Radio Access Network(RAN) integrated on general purpose platforms with open interface between software defined functions. Open RANecosystem enables enormous flexibility and interoperability with a complete openess to multi-vendor deployments.

[Open vSwitch(OVS)](https://www.openvswitch.org/)is an open source production quality, multilayer virtual switch licensed under the open source Apache 2.0 license. It is designed to enable massive network automation through programmatic extension, while still supporting standard management interfaces and protocols (NetFlow, sFlow, IPFIX, RSPAN, CLI, LACP, 802.1ag).

[Edge](https://www.ibm.com/cloud/what-is-edge-computing) is a distributed computing framework that brings enterprise applications closer to data sources such as IoT devices or local edge servers. This proximity to data at its source can deliver strong business benefits, including faster insights, improved response times and better bandwidth availability.

[Multi-access edge computing (MEC)](https://www.etsi.org/technologies/multi-access-edge-computing) is an Industry Specification Group (ISG) within ETSI to create a standardized, open environment which will allow the efficient and seamless integration of applications from vendors, service providers, and third-parties across multi-vendor Multi-access Edge Computing platforms.

[Virtualized network functions(VNFs)](https://www.juniper.net/documentation/en_US/cso4.1/topics/concept/nsd-vnf-overview.html) is a software application used in a Network Functions Virtualization (NFV) implementation that has well defined interfaces, and provides one or more component networking functions in a defined way. For example, a security VNF provides Network Address Translation (NAT) and firewall component functions.

[Cloud-Native Network Functions(CNF)](https://www.cncf.io/announcements/2020/11/18/cloud-native-network-functions-conformance-launched-by-cncf/) is a network function designed and implemented to run inside containers. CNFs inherit all the cloud native architectural and operational principles including Kubernetes(K8s) lifecycle management, agility, resilience, and observability.

[Physical Network Function(PNF)](https://www.mpirical.com/glossary/pnf-physical-network-function) is a physical network node which has not undergone virtualization. Both PNFs and VNFs (Virtualized Network Functions) can be used to form an overall Network Service.

[Network functions virtualization infrastructure(NFVI)](https://docs.vmware.com/en/VMware-vCloud-NFV/2.0/vmware-vcloud-nfv-reference-architecture-20/GUID-FBEA6C6B-54D8-4A37-87B1-D825F9E0DBC7.html) is the foundation of the overall NFV architecture. It provides the physical compute, storage, and networking hardware that hosts the VNFs. Each NFVI block can be thought of as an NFVI node and many nodes can be deployed and controlled geographically.

[Virtualization-based Security (VBS)](https://docs.microsoft.com/en-us/windows-hardware/design/device-experiences/oem-vbs) is a hardware virtualization feature to create and isolate a secure region of memory from the normal operating system.

[Hypervisor-Enforced Code Integrity (HVCI)](https://docs.microsoft.com/en-us/windows-hardware/drivers/bringup/device-guard-and-credential-guard) is a mechanism whereby a hypervisor, such as Hyper-V, uses hardware virtualization to protect kernel-mode processes against the injection and execution of malicious or unverified code. Code integrity validation is performed in a secure environment that is resistant to attack from malicious software, and page permissions for kernel mode are set and maintained by the hypervisor.

[KVM (for Kernel-based Virtual Machine)](https://www.linux-kvm.org/page/Main_Page) is a full virtualization solution for Linux on x86 hardware containing virtualization extensions (Intel VT or AMD-V). It consists of a loadable kernel module, kvm.ko, that provides the core virtualization infrastructure and a processor specific module, kvm-intel.ko or kvm-amd.ko.

[QEMU](https://www.qemu.org) is a fast processor emulator using a portable dynamic translator. QEMU emulates a full system, including a processor and various peripherals. It can be used to launch a different Operating System without rebooting the PC or to debug system code.

[Hyper-V](https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/) enables running virtualized computer systems on top of a physical host. These virtualized systems can be used and managed just as if they were physical computer systems, however they exist in virtualized and isolated environment. Special software called a hypervisor manages access between the virtual systems and the physical hardware resources. Virtualization enables quick deployment of computer systems, a way to quickly restore systems to a previously known good state, and the ability to migrate systems between physical hosts.

[VirtManager](https://github.com/virt-manager/virt-manager) is a graphical tool for managing virtual machines via libvirt. Most usage is with QEMU/KVM virtual machines, but Xen and libvirt LXC containers are well supported. Common operations for any libvirt driver should work.

[oVirt](https://www.ovirt.org) is an open-source distributed virtualization solution, designed to manage your entire enterprise infrastructure. oVirt uses the trusted KVM hypervisor and is built upon several other community projects, including libvirt, Gluster, PatternFly, and Ansible.Founded by Red Hat as a community project on which Red Hat Enterprise Virtualization is based allowing for centralized management of virtual machines, compute, storage and networking resources, from an easy-to-use web-based front-end with platform independent access.

[HyperKit](https://github.com/moby/hyperkit) is a toolkit for embedding hypervisor capabilities in your application. It includes a complete hypervisor, based on [xhyve](https://github.com/mist64/xhyve)/[bhyve](https://bhyve.org/), which is optimized for lightweight virtual machines and container deployment. It is designed to be interfaced with higher-level components such as the [VPNKit](https://github.com/moby/vpnkit) and [DataKit](https://github.com/moby/datakit). HyperKit currently only supports macOS using the [Hypervisor.framework](https://developer.apple.com/library/mac/documentation/DriversKernelHardware/Reference/Hypervisor/index.html) making it a core component of Docker Desktop for Mac.

[Intel® Graphics Virtualization Technology (Intel® GVT)](https://github.com/intel/gvt-linux) is a full GPU virtualization solution with mediated pass-through, starting from 4th generation Intel Core (TM) processors with Intel processor graphics(Broadwell and newer). It can be used to virtualize the GPU for multiple guest virtual machines, effectively providing near-native graphics performance in the virtual machine and still letting your host use the virtualized GPU normally.

[Apple Hypervisor](https://developer.apple.com/documentation/hypervisor) is a frameowrk that builds virtualization solutions on top of a lightweight hypervisor, without third-party kernel extensions. Hypervisor provides C APIs so you can interact with virtualization technologies in user space, without writing kernel extensions (KEXTs). As a result, the apps you create using this framework are suitable for distribution on the [Mac App Store](https://www.appstore.com/).

[Apple Virtualization Framework](https://developer.apple.com/documentation/virtualization) is a framework that provides high-level APIs for creating and managing virtual machines on Apple silicon and Intel-based Mac computers. This framework is used to boot and run a Linux-based operating system in a custom environment that you define. It also supports the [Virtio specification](https://www.redhat.com/en/virtio-networking-series), which defines standard interfaces for many device types, including network, socket, serial port, storage, entropy, and memory-balloon devices.

[Apple Paravirtualized Graphics Framework](https://developer.apple.com/documentation/paravirtualizedgraphics) is a framework that implements hardware-accelerated graphics for macOS running in a virtual machine, hereafter known as the guest. The operating system provides a graphics driver that runs inside the guest, communicating with the framework in the host operating system to take advantage of Metal-accelerated graphics.

[Cloud Hypervisor](https://github.com/cloud-hypervisor/cloud-hypervisor) is an open source Virtual Machine Monitor (VMM) that runs on top of [KVM](https://www.kernel.org/doc/Documentation/virtual/kvm/api.txt). The project focuses on exclusively running modern, cloud workloads, on top of a limited set of hardware architectures and platforms. Cloud workloads refers to those that are usually run by customers inside a cloud provider. Cloud Hypervisor is implemented in [Rust](https://www.rust-lang.org/) and is based on the [rust-vmm](https://github.com/rust-vmm) crates.

[VMware vSphere Hypervisor](https://www.vmware.com/products/vsphere-hypervisor.html) is a bare-metal hypervisor that virtualizes servers; allowing you to consolidate your applications while saving time and money managing your IT infrastructure.

[Xen](https://github.com/xen-project/xen) is focused on advancing virtualization in a number of different commercial and open source applications, including server virtualization, Infrastructure as a Services (IaaS), desktop virtualization, security applications, embedded and hardware appliances, and automotive/aviation.

[Ganeti](https://github.com/ganeti/ganeti) is a virtual machine cluster management tool built on top of existing virtualization technologies such as Xen or KVM and other open source software. Once installed, the tool assumes management of the virtual instances (Xen DomU).

[Packer](https://www.packer.io/) is an open source tool for creating identical machine images for multiple platforms from a single source configuration. Packer is lightweight, runs on every major operating system, and is highly performant, creating machine images for multiple platforms in parallel. Packer does not replace configuration management like Chef or Puppet. In fact, when building images, Packer is able to use tools like Chef or Puppet to install software onto the image.

[Vagrant](https://www.vagrantup.com/) is a tool for building and managing virtual machine environments in a single workflow. With an easy-to-use workflow and focus on automation, Vagrant lowers development environment setup time, increases production parity, and makes the "works on my machine" excuse a relic of the past. It provides easy to configure, reproducible, and portable work environments built on top of industry-standard technology and controlled by a single consistent workflow to help maximize the productivity and flexibility of you and your team.

[Parallels Desktop](https://www.parallels.com) is a Desktop Hypervisor that delivers the fastest, easiest and most powerful application for running Windows/Linux on Mac (including the new [Apple M1 chip](https://www.apple.com/newsroom/2020/11/apple-unleashes-m1/)) and ChromeOS.

[VMware Fusion](https://www.vmware.com/products/fusion.html) is a Desktop Hypervisor that deliver desktop and ‘server’ virtual machines, containers and [Kubernetes clusters](https://www.vmware.com/topics/glossary/content/kubernetes-cluster) to developers, and IT professionals on the Mac.

[VMware Workstation](https://www.vmware.com/products/workstation-pro.html) is a hosted hypervisor that runs on x64 versions of Windows and Linux operating systems; it enables users to set up virtual machines on a single physical machine, and use them simultaneously along with the actual machine.

# Emulation Tools
[Back to the Top](https://github.com/mikeroyal/VHDL-Guide#table-of-contents)

[Verdi® Protocol Analyzer](https://www.synopsys.com/verification/debug/verdi-protocol-analyzer.html) is a simulator independent, protocol and memory aware debug environment that enables users to quickly debug with any verification environment and easily share simulation results across teams. It gives users a graphical view of the transfers, transaction, packets and handshaking of a protocol. It highlights relationships across the hierarchy, visually unraveling the complex behavior of highly interleaved traffic. Also, enables engineers to quickly understand protocol activity, identify bottlenecks and debug unexpected behavior. Errors, warnings and messages are annotated to rapidly identify problems in the simulation.

[Synopsys’ Verdi® HW SW Debug](https://www.synopsys.com/verification/debug/verdi-hw-sw-debug.html) is a simulator tool that enables embedded software-driven SoC verification by providing a synchronized multi-window view of the design’s behavior of both hardware and software. It combines an instruction accurate embedded processor, RTL, C and assembly visibility for a comprehensive SoC debug solution.

[Synopsys Euclide](https://www.synopsys.com/verification/ide/euclide.html) is a Integrated Development Environment (IDE) that enables engineers to find bugs earlier and optimize code for design and verification flows by identifying complex design and testbench compliance checks during SystemVerilog and Universal Verification Methodology (UVM) development. Euclide accelerates correct-by-construction code development through context specific autocompletion and content assistance that is tuned for Synopsys VCS® simulation, Verdi® debug, and ZeBu® emulation, helping engineers to improve code quality during the entire project development cycle.

[Simvision](https://www.cadence.com/en_US/home/tools/system-design-and-verification/debug-analysis/simvision-debug.html) is unified graphical debugging environment within Cadence® Xcelium™ Parallel Logic Simulation, Cadence SimVision™ Debug supports signal-level and transaction-based flows across all IEEE-standard design, testbench, and assertion languages. It also supports concurrent visualization of hardware, software, and analog domains. It can be used to debug digital, analog, or mixed-signal designs written in Verilog, SystemVerilog, VHDL, and SystemC® languages or a combination thereof.

[Cadence® Palladium®](https://www.cadence.com/en_US/home/tools/system-design-and-verification/emulation-and-prototyping/palladium.html) is a set of emulation platforms that provides early software development, hardware/software verification and debug, and in circuit emulation.  It provides the highest debug productivity early in the design cycle when the RTL is still changing.

[Veloce Hardware-assisted Verification System](https://eda.sw.siemens.com/en-US/ic/veloce/) is a simulator tool that's used for the rapid verification of highly sophisticated, next-generation integrated circuit (IC) designs. It is the first complete, integrated offering that combines best-in-class virtual platform, hardware emulation, and Field Programmable Gate Array (FPGA) prototyping technologies and paves the way to leverage the latest powerful hardware-assisted verification methodologies.

[Synopsys ZeBu® EP1](https://www.synopsys.com/verification/emulation.html) is the industry’s fastest billion gates emulation system. It delivers 10 MHz emulation performance using Synopsys’ proven direct connect architecture to optimize design communication to accelerate the hardware and software verification for SoC designs of up to 2 billion gates. With ZeBu EP1 users can achieve unmatched performance while supporting all familiar emulation use cases, including early software bring-up, hybrid, hardware/software debug, simulation acceleration, performance validation and in-circuit emulation.

[SystemVerilog DPI (Direct Programming Interface)](https://verificationguide.com/systemverilog/systemverilog-dpi/) is an interface which can be used to interface SystemVerilog with foreign languages. These Foreign languages can be C, C++, SystemC as well as others. DPI allows the user to easily call functions of other language from SystemVerilog and to export SystemVerilog functions, so that they can be called in other languages.

[SystemVerilog Assertions](https://verificationguide.com/systemverilog/systemverilog-assertions/) is primarily used to validate the behavior of a design. An assertion is a check embedded in design or bound to a design unit during the simulation. Where warnings or errors are generated on the failure of a specific condition or sequence of events.

[SystemVerilog Functional Coverage](https://www.chipverify.com/systemverilog/systemverilog-functional-coverage) is a measure of what functionalities/features of the design have been exercised by the tests. This can be useful in constrained random verification (CRV) to know what features have been covered by a set of tests in a regression.

[Verilog-to-Routing (VTR) project](https://docs.verilogtorouting.org/en/latest/vtr/) is a world-wide collaborative effort to provide a open-source framework for conducting FPGA architecture and CAD research and development. The VTR design flow takes as input a Verilog description of a digital circuit, and a description of the target FPGA architecture.

[Verilog Power Estimation](https://docs.verilogtorouting.org/en/latest/vtr/power_estimation/) is performed within the VPR executable; however, additional files must be provided. In addition to the circuit and architecture files, power estimation requires files detailing the signal activities and technology properties.

[Cadence® SpeedBridge® Adapters](https://www.cadence.com/en_US/home/tools/system-design-and-verification/emulation-and-prototyping.html) is a tool that provides efficient driver and application-level testing. It's designed for pre-silicon RTL and integration of ASICs and systems on chip (SoCs), the solution can reproduce post-silicon bugs, as the design runs in the actual target system. The solution verifies emulated designs with the actual ASIC/SoC software/hardware, driver development, and application development, and runs with existing software and software test programs.

[Universal Verification Methodology (UVM)](https://verificationguide.com/uvm/) is a consists of class libraries needed for the development of well constructed, reusable SystemVerilog based Verification environment. In simple words, UVM consists of a set of base classes with methods defined in it, the SystemVerilog verification environment can be developed by extending these base classes. It will refer the UVM base classes as UVM Classes. [Accelerated UVM Testbenches](https://verificationacademy.com/courses/systemverilog-testbench-acceleration).

# Firmware Development
[Back to the Top](https://github.com/mikeroyal/VHDL-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/126912889-d86e3171-471a-4c05-b6bf-36a70080ab7c.png">
  <br />
</p>

## Firmware Learning Resources

[Firmware](https://en.wikipedia.org/wiki/Firmware) is a software program that comes embedded in a piece of hardware such as a keyboard, hard drive, BIOS, or a video card. It usually provides basic functions of a device and sometimes only provide services to higher-level software.

[Online Embedded Systems Courses | Harvard University](https://online-learning.harvard.edu/subject/embedded-systems-1)

[Internet of Things Graduate Program | Stanford Online](https://online.stanford.edu/programs/internet-things-graduate-program)

[Embedded Systems Certificate | UCSC Silicon Valley Extension](https://www.ucsc-extension.edu/certificates/embedded-systems/)

[Embedded Systems Technology (EET) | ODU Online](https://online.odu.edu/programs/embedded-systems-engineering-technology-eet)

[Learn Embedded Systems with Online Courses and Classes | edX](https://www.edx.org/learn/embedded-systems)

[Top Embedded Systems Courses Online | Udemy](https://www.udemy.com/topic/embedded-systems/)

[Top Embedded C Courses Online | Coursera](https://www.coursera.org/courses?query=embedded%20c)

[Embedded Systems | Udacity Free Courses](https://www.udacity.com/course/embedded-systems--ud169)

[Embedded Linux Online Course - Arm®](https://www.arm.com/resources/education/online-courses/embedded-linux)

[Software Development Online Courses | Coursera](https://www.coursera.org/browse/computer-science/software-development)

[Top Software Engineering Courses | Coursera](https://www.coursera.org/courses?query=software%20engineering&index=prod_all_products_term_optimization&completemode=undefined&page=1)

[Learn Software Development with Online Courses and Lessons | edX](https://www.edx.org/learn/software-development)

## Firmware Tools, Libraries, and Frameworks

[Coreboot](https://doc.coreboot.org/getting_started/index.html) is a replacement for your BIOS / UEFI with a strong focus on boot speed, security and flexibility. It is designed to boot your operating system as fast as possible without any compromise to security, with no back doors.

[TianoCore](https://www.tianocore.org/) is a community project supporting an open source implementation of the Unified Extensible Firmware Interface (UEFI). EDK II is a modern, feature-rich, cross-platform firmware development environment for the UEFI and UEFI Platform Initialization (PI) specifications.

[EDK II](https://github.com/tianocore/tianocore.github.io/wiki/EDK-II) is a modern, feature-rich, cross-platform firmware development environment for the UEFI and PI specifications .

[OpenWrt Project](https://openwrt.org/) is a Linux operating system targeting embedded devices. Instead of trying to create a single, static firmware, OpenWrt provides a fully writable filesystem with package management.

[OpenSK](https://github.com/google/OpenSK) is an open-source implementation for security keys written in Rust that supports both FIDO U2F and [FIDO2](https://fidoalliance.org/fido2/) standards.

[Linux Vendor Firmware Service(LVFS)](https://fwupd.org) is a secure portal which allows hardware vendors to upload firmware updates.

[fwupd](https://github.com/fwupd/fwupd) is a simple daemon to allow session software to update firmware. The goal og project is to make updating firmware on Linux automatic, safe and reliable.

[CHIPSEC](https://chipsec.github.io/) is a framework for analyzing the security of PC platforms including hardware, system firmware (BIOS/UEFI), and platform components. It includes a security test suite, tools for accessing various low level interfaces, and forensic capabilities. It can be run on Windows, Linux, Mac OS X and UEFI shell.

[Secure boot](https://docs.microsoft.com/en-us/windows-hardware/design/device-experiences/oem-secure-boot) is a security standard developed by members of the PC industry to help make sure that a device boots(Unified Extensible Firmware Interface (UEFI) BIOS) using only software(such as bootloaders, OS, UEFI drivers, and utilities) that is trusted by the Original Equipment Manufacturer (OEM).

[Trusted Platform Module (TPM](https://docs.microsoft.com/en-us/windows/security/information-protection/tpm/trusted-platform-module-overview) is a technology module designed to provide hardware-based, security-related functions. A TPM chip is a secure crypto-processor that is designed to carry out cryptographic operations.

[Intel® oneAPI Base Toolkit](https://software.intel.com/content/www/us/en/develop/tools/oneapi/base-toolkit.html) is a foundational kit that enables developers of all types to build, test, and deploy performance-driven, data-centric applications across CPUs, GPUs, and FPGAs. For more specialized workloads, use the Base Kit with one or more add-on toolkits.

[Intel® oneAPI HPC Toolkit](https://software.intel.com/content/www/us/en/develop/tools/oneapi/hpc-toolkit.html) is toolkit that delivers fast DPC++, C++, Fortran, OpenMP, and MPI applications that scale.

[Intel® oneAPI IoT Toolkit](https://software.intel.com/content/www/us/en/develop/tools/oneapi/iot-toolkit.html) is a toolkit for building high-performing, efficient, reliable solutions that run at the network’s edge.

[Intel® oneAPI Rendering Toolkit](https://software.intel.com/content/www/us/en/develop/tools/oneapi/rendering-toolkit.html) is a toolit for accelerating High-Fidelity Rendering and Visualization Applications with Powerful Libraries.

[Intel® AI Analytics Toolkit](https://software.intel.com/content/www/us/en/develop/tools/oneapi/ai-analytics-toolkit.html) is a toolkit that helps you achieve end-to-end performance for AI workloads.

[Intel® Distribution of OpenVINO™ Toolkit](https://software.intel.com/content/www/us/en/develop/tools/openvino-toolkit.html) is a toolkit that you help you harness the full potential of AI across multiple Intel® architectures.

[System76 Firmware](https://github.com/pop-os/system76-firmware) is a software package that has a CLI(command-line inferface) tool for installing firmware updates. Also, included is the system76-firmware-daemon package, which has a systemd service that exposes a DBUS API for handling firmware updates.

[Firmware Manager](https://github.com/pop-os/firmware-manager) is a generic framework and GTK UI for firmware updates from [system76-firmware](https://github.com/pop-os/system76-firmware) and [fwupd](https://github.com/fwupd/fwupd), written in Rust.

[Heimdall](https://github.com/Benjamin-Dobell/Heimdall) is a cross-platform open-source tool suite used to flash firmware (aka ROMs) onto Samsung mobile devices.

[Nexmon](https://github.com/seemoo-lab/nexmon) is a C-based firmware patching framework for Broadcom/Cypress WiFi chips that enables you to write your own firmware patches, for example, to enable monitor mode with radiotap headers and frame injection.

[Firmware Analysis Toolkit](https://github.com/attify/firmware-analysis-toolkit) is a toolkit built in order to help security researchers analyze and identify vulnerabilities in IoT and embedded device firmware. This is built in order to use for the ["Offensive IoT Exploitation"](https://www.attify-store.com/collections/training/products/offensive-iot-exploitation) training conducted by [Attify](https://attify.com/).

[Firmware Analysis and Comparison Tool](https://github.com/fkie-cad/FACT_core) is a tool intended to automate most of the firmware analysis process. It unpacks arbitrary firmware files and processes several analyses. Additionally, it can compare several images or single files.

[Mellanox firmware update and query utility](https://www.mellanox.com/support/firmware/mlxup-mft) is a utility that enables scanning the server machine for available Mellanox adapters and indicates whether firmware update is required for each adapter.

[Mellanox FlexBoot](https://www.mellanox.com/products/adapter-software/flexboot) is a multiprotocol remote boot technology that delivers unprecedented flexibility in how IT Managers can provision or repurpose their datacenter servers. FlexBoot enables remote boot over InfiniBand or Ethernet using Boot over InfiniBand, over Ethernet, or Boot over iSCSI (Bo-iSCSI). Combined with Virtual Protocol Interconnect (VPI) technologies available in ConnectX®-3 and onwards adapters, FlexBoot gives IT Managers the flexibility to deploy servers with one adapter card into InfiniBand or Ethernet networks with the ability to boot from LAN or remote storage targets.

[QMK Toolbox](https://github.com/qmk/qmk_toolbox) is a Toolbox companion for [QMK](https://qmk.fm/) Firmware. It provides a collection of flashing tools packaged into one app. It supports auto-detection and auto-flashing of firmware to keyboards.

[QMK(Quantum Mechanical Keyboard) Firmware](https://github.com/qmk/qmk_firmware) is an open-source keyboard firmware for Atmel AVR and [Arm](https://www.arm.com/) USB controllers, and more specifically, the [OLKB product line](https://olkb.com/), the [ErgoDox EZ keyboard](https://ergodox-ez.com/), and the [Clueboard product line](https://clueboard.co/).

[TMK Keyboard Firmware](https://github.com/tmk/tmk_keyboard) is keyboard firmwares for Atmel AVR and [Arm](https://www.arm.com/) Cortex-M.

# MATLAB Development
[Back to the Top](https://github.com/mikeroyal/VHDL-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/94306473-de809e80-ff27-11ea-924b-0a6947ae38bc.png">
  <br />
</p>

## MATLAB Learning Resources

[MATLAB](https://www.mathworks.com/products/matlab.html) is a programming language that does numerical computing such as expressing matrix and array mathematics directly.

[MATLAB Documentation](https://www.mathworks.com/help/matlab/)

[Getting Started with MATLAB ](https://www.mathworks.com/help/matlab/getting-started-with-matlab.html)

[MATLAB and Simulink Training from MATLAB Academy](https://matlabacademy.mathworks.com)

[MathWorks Certification Program](https://www.mathworks.com/services/training/certification.html)

[Apache Spark Basics | MATLAB & Simulink](https://www.mathworks.com/help//compiler/spark/apache-spark-basics.html)

[MATLAB Hadoop and Spark | MATLAB & Simulink](https://www.mathworks.com/products/compiler/hadoop-and-spark.html)

[MATLAB Online Courses from Udemy](https://www.udemy.com/topic/matlab/)

[MATLAB Online Courses from Coursera](https://www.coursera.org/courses?query=matlab)

[MATLAB Online Courses from edX](https://www.edx.org/learn/matlab)

[Building a MATLAB GUI](https://www.mathworks.com/discovery/matlab-gui.html)

[MATLAB Style Guidelines 2.0](https://www.mathworks.com/matlabcentral/fileexchange/46056-matlab-style-guidelines-2-0)

[Setting Up Git Source Control with MATLAB & Simulink](https://www.mathworks.com/help/matlab/matlab_prog/set-up-git-source-control.html)

[Pull, Push and Fetch Files with Git with MATLAB & Simulink](https://www.mathworks.com/help/matlab/matlab_prog/push-and-fetch-with-git.html)

[Create New Repository with MATLAB & Simulink](https://www.mathworks.com/help/matlab/matlab_prog/add-folder-to-source-control.html)

[PRMLT](http://prml.github.io/) is Matlab code for machine learning algorithms in the PRML book.

## MATLAB Tools, Libraries, Frameworks

**[MATLAB and Simulink Services & Applications List](https://www.mathworks.com/products.html)**

[MATLAB in the Cloud](https://www.mathworks.com/solutions/cloud.html) is a service that allows you to run in cloud environments from [MathWorks Cloud](https://www.mathworks.com/solutions/cloud.html#browser) to [Public Clouds](https://www.mathworks.com/solutions/cloud.html#public-cloud) including [AWS](https://aws.amazon.com/) and [Azure](https://azure.microsoft.com/).

[MATLAB Online™](https://matlab.mathworks.com) is a service that allows to users to uilitize MATLAB and Simulink through a web browser such as Google Chrome.

[Simulink](https://www.mathworks.com/products/simulink.html) is a block diagram environment for Model-Based Design. It supports simulation, automatic code generation, and continuous testing of embedded systems.

[Simulink Online™](https://www.mathworks.com/products/simulink-online.html) is a service that provides access to Simulink through your web browser.

[MATLAB Drive™](https://www.mathworks.com/products/matlab-drive.html) is a service that gives you the ability to store, access, and work with your files from anywhere.

[MATLAB Parallel Server™](https://www.mathworks.com/products/matlab-parallel-server.html) is a tool that lets you scale MATLAB® programs and Simulink® simulations to clusters and clouds. You can prototype your programs and simulations on the desktop and then run them on clusters and clouds without recoding. MATLAB Parallel Server supports batch jobs, interactive parallel computations, and distributed computations with large matrices.

[MATLAB Schemer](https://github.com/scottclowe/matlab-schemer) is a MATLAB package makes it easy to change the color scheme (theme) of the MATLAB display and GUI.

[LRSLibrary](https://github.com/andrewssobral/lrslibrary) is a Low-Rank and Sparse Tools for Background Modeling and Subtraction in Videos. The library was designed for moving object detection in videos, but it can be also used for other computer vision and machine learning problems.

[Image Processing Toolbox™](https://www.mathworks.com/products/image.html) is a tool that provides a comprehensive set of reference-standard algorithms and workflow apps for image processing, analysis, visualization, and algorithm development. You can perform image segmentation, image enhancement, noise reduction, geometric transformations, image registration, and 3D image processing.

[Computer Vision Toolbox™](https://www.mathworks.com/products/computer-vision.html) is a tool that provides algorithms, functions, and apps for designing and testing computer vision, 3D vision, and video processing systems. You can perform object detection and tracking, as well as feature detection, extraction, and matching. You can automate calibration workflows for single, stereo, and fisheye cameras. For 3D vision, the toolbox supports visual and point cloud SLAM, stereo vision, structure from motion, and point cloud processing.

[Statistics and Machine Learning Toolbox™](https://www.mathworks.com/products/statistics.html) is a tool that provides functions and apps to describe, analyze, and model data. You can use descriptive statistics, visualizations, and clustering for exploratory data analysis; fit probability distributions to data; generate random numbers for Monte Carlo simulations, and perform hypothesis tests. Regression and classification algorithms let you draw inferences from data and build predictive models either interactively, using the Classification and Regression Learner apps, or programmatically, using AutoML.

[Lidar Toolbox™](https://www.mathworks.com/products/lidar.html) is a tool that provides algorithms, functions, and apps for designing, analyzing, and testing lidar processing systems. You can perform object detection and tracking, semantic segmentation, shape fitting, lidar registration, and obstacle detection. Lidar Toolbox supports lidar-camera cross calibration for workflows that combine computer vision and lidar processing.

[Mapping Toolbox™](https://www.mathworks.com/products/mapping.html) is a tool that provides algorithms and functions for transforming geographic data and creating map displays. You can visualize your data in a geographic context, build map displays from more than 60 map projections, and transform data from a variety of sources into a consistent geographic coordinate system.

[UAV Toolbox](https://www.mathworks.com/products/uav.html) is an application that provides tools and reference applications for designing, simulating, testing, and deploying unmanned aerial vehicle (UAV) and drone applications. You can design autonomous flight algorithms, UAV missions, and flight controllers. The Flight Log Analyzer app lets you interactively analyze 3D flight paths, telemetry information, and sensor readings from common flight log formats.

[Parallel Computing Toolbox™](https://www.mathworks.com/products/matlab-parallel-server.html) is a tool that lets you solve computationally and data-intensive problems using multicore processors, GPUs, and computer clusters. High-level constructs such as parallel for-loops, special array types, and parallelized numerical algorithms enable you to parallelize MATLAB® applications without CUDA or MPI programming. The toolbox lets you use parallel-enabled functions in MATLAB and other toolboxes. You can use the toolbox with Simulink® to run multiple simulations of a model in parallel. Programs and models can run in both interactive and batch modes.

[Partial Differential Equation Toolbox™](https://www.mathworks.com/products/pde.html) is a tool that provides functions for solving structural mechanics, heat transfer, and general partial differential equations (PDEs) using finite element analysis.

[ROS Toolbox](https://www.mathworks.com/products/ros.html) is a tool that provides an interface connecting MATLAB® and Simulink® with the Robot Operating System (ROS and ROS 2), enabling you to create a network of ROS nodes. The toolbox includes MATLAB functions and Simulink blocks to import, analyze, and play back ROS data recorded in rosbag files. You can also connect to a live ROS network to access ROS messages.

[Robotics Toolbox™](https://www.mathworks.com/products/robotics.html) provides a toolbox that brings robotics specific functionality(designing, simulating, and testing manipulators, mobile robots, and humanoid robots) to MATLAB, exploiting the native capabilities of MATLAB (linear algebra, portability, graphics). The toolbox also supports mobile robots with functions for robot motion models (bicycle), path planning algorithms (bug, distance transform, D*, PRM), kinodynamic planning (lattice, RRT), localization (EKF, particle filter), map building (EKF) and simultaneous localization and mapping (EKF), and a Simulink model a of non-holonomic vehicle. The Toolbox also including a detailed Simulink model for a quadrotor flying robot.

[Deep Learning Toolbox™](https://www.mathworks.com/products/deep-learning.html) is a tool that provides a framework for designing and implementing deep neural networks with algorithms, pretrained models, and apps. You can use convolutional neural networks (ConvNets, CNNs) and long short-term memory (LSTM) networks to perform classification and regression on image, time-series, and text data. You can build network architectures such as generative adversarial networks (GANs) and Siamese networks using automatic differentiation, custom training loops, and shared weights. With the Deep Network Designer app, you can design, analyze, and train networks graphically. It can exchange models with TensorFlow™ and PyTorch through the ONNX format and import models from TensorFlow-Keras and Caffe. The toolbox supports transfer learning with DarkNet-53, ResNet-50, NASNet, SqueezeNet and many other pretrained models.

[Reinforcement Learning Toolbox™](https://www.mathworks.com/products/reinforcement-learning.html) is a tool that provides an app, functions, and a Simulink® block for training policies using reinforcement learning algorithms, including DQN, PPO, SAC, and DDPG. You can use these policies to implement controllers and decision-making algorithms for complex applications such as resource allocation, robotics, and autonomous systems.

[Deep Learning HDL Toolbox™](https://www.mathworks.com/products/deep-learning-hdl.html) is a tool that provides functions and tools to prototype and implement deep learning networks on FPGAs and SoCs. It provides pre-built bitstreams for running a variety of deep learning networks on supported Xilinx® and Intel® FPGA and SoC devices. Profiling and estimation tools let you customize a deep learning network by exploring design, performance, and resource utilization tradeoffs.

[Model Predictive Control Toolbox™](https://www.mathworks.com/products/model-predictive-control.html) is a tool that provides functions, an app, and Simulink® blocks for designing and simulating controllers using linear and nonlinear model predictive control (MPC). The toolbox lets you specify plant and disturbance models, horizons, constraints, and weights. By running closed-loop simulations, you can evaluate controller performance.

[Vision HDL Toolbox™](https://www.mathworks.com/products/vision-hdl.html) is a tool that provides pixel-streaming algorithms for the design and implementation of vision systems on FPGAs and ASICs. It provides a design framework that supports a diverse set of interface types, frame sizes, and frame rates. The image processing, video, and computer vision algorithms in the toolbox use an architecture appropriate for HDL implementations.

[SoC Blockset™](https://www.mathworks.com/products/soc.html) is a tool that provides Simulink® blocks and visualization tools for modeling, simulating, and analyzing hardware and software architectures for ASICs, FPGAs, and systems on a chip (SoC). You can build your system architecture using memory models, bus models, and I/O models, and simulate the architecture together with the algorithms.

[Wireless HDL Toolbox™](https://www.mathworks.com/products/wireless-hdl.html) is a tool that provides pre-verified, hardware-ready Simulink® blocks and subsystems for developing 5G, LTE, and custom OFDM-based wireless communication applications. It includes reference applications, IP blocks, and gateways between frame and sample-based processing.

[ThingSpeak™](https://www.mathworks.com/products/thingspeak.html) is an IoT analytics service that allows you to aggregate, visualize, and analyze live data streams in the cloud. ThingSpeak provides instant visualizations of data posted by your devices to ThingSpeak. With the ability to execute MATLAB® code in ThingSpeak, you can perform online analysis and process data as it comes in. ThingSpeak is often used for prototyping and proof-of-concept IoT systems that require analytics.

[SEA-MAT](https://sea-mat.github.io/sea-mat/) is a collaborative effort to organize and distribute Matlab tools for the Oceanographic Community.

[Gramm](https://github.com/piermorel/gramm) is a complete data visualization toolbox for Matlab. It provides an easy to use and high-level interface to produce publication-quality plots of complex data with varied statistical visualizations. Gramm is inspired by R's ggplot2 library.

[hctsa](https://hctsa-users.gitbook.io/hctsa-manual) is a software package for running highly comparative time-series analysis using Matlab.

[Plotly](https://plot.ly/matlab/) is a Graphing Library for MATLAB.

[YALMIP](https://yalmip.github.io/) is a MATLAB toolbox for optimization modeling.

[GNU Octave](https://www.gnu.org/software/octave/) is a high-level interpreted language, primarily intended for numerical computations. It provides capabilities for the numerical solution of linear and nonlinear problems, and for performing other numerical experiments. It also provides extensive graphics capabilities for data visualization and manipulation.

# Verilog/SystemVerilog Development
[Back to the Top](https://github.com/mikeroyal/VHDL-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/102273517-4b785480-3ed7-11eb-910a-113821428f17.png">
  <br />

</p>

## Verilog/SystemVerilog Learning Resources

[Verilog](https://verilog.com/) is a Hardware Description Language(HDL) used to design and document electronic systems. Verilog HDL allows designers to design at various levels of abstraction.

[SystemVerilog](https://www.systemverilog.io/) is an extension of Verilog with many of the verification features that allow engineers to verifythe design using complex testbench structures and random stimuli in simulation.

[Verilog Book Shelf](https://verilog.com/v-books.html)

[Verilog HDL Basics training from Intel](https://www.intel.com/content/www/us/en/programmable/support/training/course/ohdl1120.html)

[SystemVerilog for Design and Verification](https://www.cadence.com/en_US/home/training/all-courses/82143.html)

[Verilog HDL Programming Courses on Udemy](https://www.udemy.com/topic/verilog-hdl-programming/)

[Top Verilog Programming Courses on Coursera](https://www.coursera.org/courses?query=verilog)

[Verilog course for Engineers on Technobyte](https://technobyte.org/verilog-course-tutorials/)

[Verilog Tutorials and Courses on hackr.io](https://hackr.io/tutorials/learn-verilog)

[Designing With Verilog Certification from the Xilinx Learning Center](https://xilinxprod-catalog.netexam.com/Certification/35916/designing-with-verilog)

[Learning Verilog for FPGA Development on LinkedIn Learning](https://www.linkedin.com/learning/learning-verilog-for-fpga-development)

[SystemVerilog tutorial on ChipVerify](https://www.chipverify.com/systemverilog/systemverilog-tutorial)

## Verilog/SystemVerilog Tools

[Apio](https://github.com/FPGAwars/apio) is a multiplatform toolbox, with static pre-built packages, project configuration tools and easy command interface to verify, synthesize, simulate and upload your verilog designs.

[IceStorm](https://github.com/YosysHQ/icestorm) is a project that aims at documenting the bitstream format of Lattice iCE40 FPGAs and providing simple tools for analyzing and creating bitstream files.

[Icestudio](https://icestudio.io/) is a visual editor for open FPGA boards. Built on top of the Icestorm project using Apio.

[EDA Playground](https://www.edaplayground.com) is a online code for programming your Verilog projects.

[PlatformIO](https://platformio.org/) is a professional collaborative platform for embedded development with no vendor lock-in. It provides support for multiplatforms and frameworks such as IoT, Arduino, CMSIS, ESP-IDF, FreeRTOS, libOpenCM3, mbed OS, Pulp OS, SPL, STM32Cube, Zephyr RTOS, ARM, AVR, Espressif (ESP8266/ESP32), FPGA, MCS-51 (8051), MSP430, Nordic (nRF51/nRF52), NXP i.MX RT, PIC32, RISC-V.

[PlatformIO for VSCode](https://marketplace.visualstudio.com/items?itemName=platformio.platformio-ide) is a plugin that provides support for the PlatformIO IDE on VSCode.

[Chisel](https://www.chisel-lang.org/) is a hardware design language that facilitates advanced circuit generation and design reuse for both ASIC and FPGA digital logic designs. Chisel adds hardware construction primitives to the [Scala](https://www.scala-lang.org/) programming language, providing designers with the power of a modern programming language to write complex, parameterizable circuit generators that produce synthesizable Verilog.

[Clash compiler](https://www.clash-lang.org/) is a functional hardware description language that borrows both its syntax and semantics from the functional programming language Haskell. The Clash compiler transforms these high-level descriptions to low-level synthesizable VHDL, Verilog, or SystemVerilog.

[Verilator](https://verilator.org/) is an open-source SystemVerilog simulator and lint system.

[Verilog to Routing(VTR)](https://verilogtorouting.org/) is a collaborative project to provide a open-source framework for conducting FPGA architecture and CAD Research & Development. The VTR design flow takes as input a Verilog description of a digital circuit, and a description of the target FPGA architecture.

[Cascade](https://github.com/vmware/cascade) is a Just-In-Time Compiler for Verilog from VMware Research. Cascade executes code immediately in a software simulator, and performs compilation in the background. When compilation is finished, the code is moved into hardware, and from the user’s perspective it simply gets faster over time.

[OpenTimer](https://github.com/OpenTimer/OpenTimer) is a High-Performance Timing Analysis Tool for VLSI Systems.

# Assembly Development
[Back to the Top](https://github.com/mikeroyal/VHDL-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/101415607-18154480-389d-11eb-80e8-17a5c57e480f.png">
  <br />
</p>

## Assembly Learning Resources

[Assembly](https://en.wikipedia.org/wiki/Assembly_language) is a low-level programming language. It uses mnemonic codes and labels to represent machine-level code with each instruction corresponding to just one machine operation.

[RISC-V Foundation](https://riscv.org/) is a non-profit corporation controlled by its 500 members(NVIDIA, Google, Samsung, Raspberry Pi, SiFive, Canonical, and Western Digital) to drive forward the adoption and implementation of the free and open RISC-V instruction set architecture (ISA).

[Intel® 64 and IA-32 Architectures Software Developer’s Manual](https://software.intel.com/content/www/us/en/develop/articles/intel-sdm.html)

[Introduction to x64 Assembly from Intel](https://software.intel.com/content/www/us/en/develop/articles/introduction-to-x64-assembly.html)

[x86 Assembly Language Reference Manual for Open Solaris](https://docs.oracle.com/cd/E19120-01/open.solaris/817-5477/index.html)

[AMD64 Architecture Programmer’s Manual Volume 1-5](https://www.amd.com/system/files/TechDocs/40332.pdf)

[AMD GPU ISA documentation](https://gpuopen.com/documentation/amd-isa-documentation/)

[AMD Developer Guides, Manuals, and ISA Documents](https://developer.amd.com/resources/developer-guides-manuals/)

[Assembler language from IBM](https://www.ibm.com/support/knowledgecenter/en/SSLTBW_2.1.0/com.ibm.zos.v2r1.asma400/asmr102112.htm)

[The Assembler language on z/OS from IBM](https://www.ibm.com/support/knowledgecenter/zosbasics/com.ibm.zos.zappldev/zappldev_25.htm)

[MIPS Architecture & Technology from Wave Computing](https://wavecomp.ai/mips-technology/)

[Assemblies in .NET](https://docs.microsoft.com/en-us/dotnet/standard/assembly/)

[Microsoft Macro Assembler reference](https://docs.microsoft.com/en-us/cpp/assembler/masm/microsoft-macro-assembler-reference)

[Compiler Intrinsics and Assembly Language from Microsoft](https://docs.microsoft.com/en-us/cpp/intrinsics/compiler-intrinsics-and-assembly-language)

[x86 and amd64 instruction Reference](https://www.felixcloutier.com/x86/)

[Intro to x86 Assembly Language Programming](https://cs.lmu.edu/~ray/notes/x86assembly/)

[Learn Assembly Programming courses on Udemy](https://www.udemy.com/topic/assembly-language/)

[Assembly Languages and Assemblers courses on Coursera](https://www.coursera.org/lecture/build-a-computer/unit-6-1-assembly-languages-and-assemblers-l4EGm)

[Intro to Assembly Language from MIT](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/index.htm)

# C/C++ Development
[Back to the Top](https://github.com/mikeroyal/VHDL-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/115297894-961e0d80-a111-11eb-81c3-e2bd2ac9a7cd.png">
  <br />
</p>

## C/C++ Learning Resources

[C++](https://www.cplusplus.com/doc/tutorial/) is a cross-platform language that can be used to build high-performance applications developed by Bjarne Stroustrup, as an extension to the C language.

[C](https://www.iso.org/standard/74528.html) is a general-purpose, high-level language that was originally developed by Dennis M. Ritchie to develop the UNIX operating system at Bell Labs. It supports structured programming, lexical variable scope, and recursion, with a static type system. C also provides constructs that map efficiently to typical machine instructions, which makes it one was of the most widely used programming languages today.

[Embedded C](https://en.wikipedia.org/wiki/Embedded_C) is a set of language extensions for the C programming language by the [C Standards Committee](https://isocpp.org/std/the-committee) to address issues that exist between C extensions for different [embedded systems](https://en.wikipedia.org/wiki/Embedded_system). The extensions hep enhance microprocessor features such as fixed-point arithmetic, multiple distinct memory banks, and basic I/O operations. This makes Embedded C the most popular embedded software language in the world.

[C & C++ Developer Tools from JetBrains](https://www.jetbrains.com/cpp/)

[Open source C++ libraries on cppreference.com](https://en.cppreference.com/w/cpp/links/libs)

[C++ Graphics libraries](https://cpp.libhunt.com/libs/graphics)

[C++ Libraries in MATLAB](https://www.mathworks.com/help/matlab/call-cpp-library-functions.html)

[C++ Tools and Libraries Articles](https://www.cplusplus.com/articles/tools/)

[Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)

[Introduction C++ Education course on Google Developers](https://developers.google.com/edu/c++/)

[C++ style guide for Fuchsia](https://fuchsia.dev/fuchsia-src/development/languages/c-cpp/cpp-style)

[C and C++ Coding Style Guide by OpenTitan](https://docs.opentitan.org/doc/rm/c_cpp_coding_style/)

[Chromium C++ Style Guide](https://chromium.googlesource.com/chromium/src/+/master/styleguide/c++/c++.md)

[C++ Core Guidelines](https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md)

[C++ Style Guide for ROS](http://wiki.ros.org/CppStyleGuide)

[Learn C++](https://www.learncpp.com/)

[Learn C : An Interactive C Tutorial](https://www.learn-c.org/)

[C++ Institute](https://cppinstitute.org/free-c-and-c-courses)

[C++ Online Training Courses on LinkedIn Learning](https://www.linkedin.com/learning/topics/c-plus-plus)

[C++ Tutorials on W3Schools](https://www.w3schools.com/cpp/default.asp)

[Learn C Programming Online Courses on edX](https://www.edx.org/learn/c-programming)

[Learn C++ with Online Courses on edX](https://www.edx.org/learn/c-plus-plus)

[Learn C++ on Codecademy](https://www.codecademy.com/learn/learn-c-plus-plus)

[Coding for Everyone: C and C++ course on Coursera](https://www.coursera.org/specializations/coding-for-everyone)

[C++ For C Programmers on Coursera](https://www.coursera.org/learn/c-plus-plus-a)

[Top C Courses on Coursera](https://www.coursera.org/courses?query=c%20programming)

[C++ Online Courses on Udemy](https://www.udemy.com/topic/c-plus-plus/)

[Top C Courses on Udemy](https://www.udemy.com/topic/c-programming/)

[Basics of Embedded C Programming for Beginners on Udemy](https://www.udemy.com/course/embedded-c-programming-for-embedded-systems/)

[C++ For Programmers Course on Udacity](https://www.udacity.com/course/c-for-programmers--ud210)

[C++ Fundamentals Course on Pluralsight](https://www.pluralsight.com/courses/learn-program-cplusplus)

[Introduction to C++ on MIT Free Online Course Materials](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-096-introduction-to-c-january-iap-2011/)

[Introduction to C++ for Programmers | Harvard ](https://online-learning.harvard.edu/course/introduction-c-programmers)

[Online C Courses | Harvard University](https://online-learning.harvard.edu/subject/c)

## C/C++ Tools, Libraries and Frameworks

[AWS SDK for C++](https://aws.amazon.com/sdk-for-cpp/)

[Azure SDK for C++](https://github.com/Azure/azure-sdk-for-cpp)

[Azure SDK for C](https://github.com/Azure/azure-sdk-for-c)

[C++ Client Libraries for Google Cloud Services](https://github.com/googleapis/google-cloud-cpp)

[Visual Studio](https://visualstudio.microsoft.com/) is an integrated development environment (IDE) from Microsoft; which is a feature-rich application that can be used for many aspects of software development. Visual Studio makes it easy to edit, debug, build, and publish your app. By using Microsoft software development platforms such as Windows API, Windows Forms, Windows Presentation Foundation, and Windows Store.

[Visual Studio Code](https://code.visualstudio.com/) is a code editor redefined and optimized for building and debugging modern web and cloud applications.

[Vcpkg](https://github.com/microsoft/vcpkg) is a C++ Library Manager for Windows, Linux, and MacOS.

[ReSharper C++](https://www.jetbrains.com/resharper-cpp/features/) is a Visual Studio Extension for C++ developers developed by JetBrains.

[AppCode](https://www.jetbrains.com/objc/) is constantly monitoring the quality of your code. It warns you of errors and smells and suggests quick-fixes to resolve them automatically. AppCode provides lots of code inspections for Objective-C, Swift, C/C++, and a number of code inspections for other supported languages. All code inspections are run on the fly.

[CLion](https://www.jetbrains.com/clion/features/) is a cross-platform IDE for C and C++ developers developed by JetBrains.

[Code::Blocks](https://www.codeblocks.org/) is a free C/C++ and Fortran IDE built to meet the most demanding needs of its users. It is designed to be very extensible and fully configurable. Built around a plugin framework, Code::Blocks can be extended with plugins.

[CppSharp](https://github.com/mono/CppSharp) is a tool and set of libraries which facilitates the usage of native C/C++ code with the .NET ecosystem. It consumes C/C++ header and library files and generates the necessary glue code to surface the native API as a managed API. Such an API can be used to consume an existing native library in your managed code or add managed scripting support to a native codebase.

[Conan](https://conan.io/) is an Open Source Package Manager for C++ development and dependency management into the 21st century and on par with the other development ecosystems.

[High Performance Computing (HPC) SDK](https://developer.nvidia.com/hpc) is a comprehensive toolbox for GPU accelerating HPC modeling and simulation applications. It includes the C, C++, and Fortran compilers, libraries, and analysis tools necessary for developing HPC applications on the NVIDIA platform.

[Thrust](https://github.com/NVIDIA/thrust) is a C++ parallel programming library which resembles the C++ Standard Library. Thrust's high-level interface greatly enhances programmer productivity while enabling performance portability between GPUs and multicore CPUs. Interoperability with established technologies such as CUDA, TBB, and OpenMP integrates with existing software.

[Boost](https://www.boost.org/) is an educational opportunity focused on cutting-edge C++. Boost has been a participant in the annual Google Summer of Code since 2007, in which students develop their skills by working on Boost Library development.

[Automake](https://www.gnu.org/software/automake/) is a tool for automatically generating Makefile.in files compliant with the GNU Coding Standards. Automake requires the use of GNU Autoconf.

[Cmake](https://cmake.org/) is an open-source, cross-platform family of tools designed to build, test and package software. CMake is used to control the software compilation process using simple platform and compiler independent configuration files, and generate native makefiles and workspaces that can be used in the compiler environment of your choice.

[GDB](http://www.gnu.org/software/gdb/) is a debugger, that allows you to see what is going on `inside' another program while it executes or what another program was doing at the moment it crashed.

[GCC](https://gcc.gnu.org/) is a compiler Collection that includes front ends for C, C++, Objective-C, Fortran, Ada, Go, and D, as well as libraries for these languages.

[GSL](https://www.gnu.org/software/gsl/) is a numerical library for C and C++ programmers. It is free software under the GNU General Public License. The library provides a wide range of mathematical routines such as random number generators, special functions and least-squares fitting. There are over 1000 functions in total with an extensive test suite.

[OpenGL Extension Wrangler Library (GLEW)](https://www.opengl.org/sdk/libs/GLEW/) is a cross-platform open-source C/C++ extension loading library. GLEW provides efficient run-time mechanisms for determining which OpenGL extensions are supported on the target platform.

[Libtool](https://www.gnu.org/software/libtool/) is a generic library support script that hides the complexity of using shared libraries behind a consistent, portable interface. To use Libtool, add the new generic library building commands to your Makefile, Makefile.in, or Makefile.am.

[Maven](https://maven.apache.org/) is a software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information.

[TAU (Tuning And Analysis Utilities)](http://www.cs.uoregon.edu/research/tau/home.php) is capable of gathering performance information through instrumentation of functions, methods, basic blocks, and statements as well as event-based sampling. All C++ language features are supported including templates and namespaces.

[Clang](https://clang.llvm.org/) is a production quality C, Objective-C, C++ and Objective-C++ compiler when targeting X86-32, X86-64, and ARM (other targets may have caveats, but are usually easy to fix). Clang is used in production to build performance-critical software like Google Chrome or Firefox.

[OpenCV](https://opencv.org/) is a highly optimized library with focus on real-time applications. Cross-Platform C++, Python and Java interfaces support Linux, MacOS, Windows, iOS, and Android.

[Libcu++](https://nvidia.github.io/libcudacxx) is the NVIDIA C++ Standard Library for your entire system. It provides a heterogeneous implementation of the C++ Standard Library that can be used in and between CPU and GPU code.

[ANTLR (ANother Tool for Language Recognition)](https://www.antlr.org/) is a powerful parser generator for reading, processing, executing, or translating structured text or binary files. It's widely used to build languages, tools, and frameworks. From a grammar, ANTLR generates a parser that can build parse trees and also generates a listener interface that makes it easy to respond to the recognition of phrases of interest.

[Oat++](https://oatpp.io/) is a light and powerful C++ web framework for highly scalable and resource-efficient web application. It's zero-dependency and easy-portable.

[JavaCPP](https://github.com/bytedeco/javacpp) is a program that provides efficient access to native C++ inside Java, not unlike the way some C/C++ compilers interact with assembly language.

[Cython](https://cython.org/) is a language that makes writing C extensions for Python as easy as Python itself. Cython is based on Pyrex, but supports more cutting edge functionality and optimizations such as calling C functions and declaring C types on variables and class attributes.

[Spdlog](https://github.com/gabime/spdlog) is a very fast, header-only/compiled, C++ logging library.

[Infer](https://fbinfer.com/) is a static analysis tool for Java, C++, Objective-C, and C. Infer is written in [OCaml](https://ocaml.org/).

# Electric charge, field, and potential
[Back to the Top](https://github.com/mikeroyal/VHDL-Guide#table-of-contents)

     - Charge and electric force (Coulomb's law): Electric charge, field, and potential
     - Electric field: Electric charge, field, and potential
     - Electric potential energy, electric potential, and voltage: Electric charge, field, and potential

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127784122-2c0e9166-ff73-44cf-a5b5-62d76aba80c7.png">
  <br />
</p>

 **Electric Potential Energy. Source: [sparkfun](https://learn.sparkfun.com/tutorials/what-is-electricity/electric-potential-energy)**

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127784121-8f89a787-1674-4db4-ba46-b2f280706dd9.png">
  <br />
</p>

# Circuits
[Back to the Top](https://github.com/mikeroyal/VHDL-Guide#table-of-contents)

    - Ohm's law and circuits with resistors: Circuits
    - Circuits with capacitors: Circuits

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127784127-ad587152-0c0d-4671-b29d-9231889899ff.png">
  <br />
</p>

 **Electric Circuits. Source: [sdsu-physics](http://sdsu-physics.org/physics180/physics180B/Chapters/electric_currents.htm)**

  <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127784128-941e1cf9-0cff-4702-b97b-f827d9489a20.png">
  <br />
</p>

 **Symbols of Circuits .Source: [andrewpover.co.uk](https://andrewpover.co.uk/category/physics/)**

# Magnetic forces, magnetic fields, and Faraday's law
[Back to the Top](https://github.com/mikeroyal/VHDL-Guide#table-of-contents)

    - Magnets and Magnetic Force: Magnetic forces, magnetic fields, and Faraday's law
    - Magnetic field created by a current: Magnetic forces, magnetic fields, and Faraday's law
    - Electric motors: Magnetic forces, magnetic fields, and Faraday's law
    - Magnetic flux and Faraday's law

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127784132-d4b67030-9e04-41f1-90d2-98b7c6beebe8.png">
  <br />
</p>

 **Magnetic Field. Source: [vecteezy](https://www.vecteezy.com/vector-art/593998-physics-science-about-the-movement-of-magnetic-fields-positive-and-negative)**

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127784663-28e8ad0e-aa9d-4dbf-b285-0b2976de2d3e.png">
  <br />
</p>

 **Amphere's Law. Source: [sdsu-physics](https://sdsu-physics.org/physics180/physics196/Topics/magneticFields30.html)**

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127784666-dd53913b-33c9-4ddd-8cf1-b8fa398bf3de.png">
  <br />
</p>

 **Farady's law. Source: [sdsu-physics](http://sdsu-physics.org/physics180/physics196/Topics/faradaysLaw.html)**

# Electromagnetic waves and interference
[Back to the Top](https://github.com/mikeroyal/VHDL-Guide#table-of-contents)

    - Introduction to electromagnetic waves: Electromagnetic waves and interference
    - Interference of electromagnetic waves

  <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127785050-a98f0812-d723-49b9-9796-ac05bb64804a.png">
  <br />
</p>

 **Electromagnetic Wave. Source: [differencebetween](https://www.differencebetween.com/difference-between-wave-and-particle-nature-of-light/)**

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127785051-1a86c310-0e09-4f8b-be8e-99770dd0301e.png">
  <br />
</p>

   **EMI Spectrum. Source: [electrical4u](https://www.electrical4u.com/electromagnetic-interference/)**

## Contribute

- [x] If would you like to contribute to this guide simply make a [Pull Request](https://github.com/mikeroyal/VHDL-Guide/pulls).


## License

[Back to the Top](https://github.com/mikeroyal/VHDL-Guide#table-of-contents)

Distributed under the [Creative Commons Attribution 4.0 International (CC BY 4.0) Public License](https://creativecommons.org/licenses/by/4.0/)

