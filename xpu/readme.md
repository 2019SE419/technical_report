xPU(xxx Processing Unit): functional processing unit for certain usage
=======================

## Introduction

FPGA(Field Programmable Gate Array)

## A 

1. **Accelerated Processing Units**: 

	Craft from AMD, integrating CPU and GPU on single chip,
	which supports flexibly scheduling between CPU and GPU on motherboard without dependency of northbridge.

<div align="center">
<img src="apu.jpg" width="80%" />
</div>
<br>

2. **Audio Processing Unit**: 

	Aimed for audio signal processing.
	Very common in sound cards.

## B

1. **Brain Processing Unit**:

	Craft from Horizon Robotics, coming from a Beijing company found in 2005.
	Aimed for IoT rather than robot, meaning brains of artifact intelligence.

<div align="center">
<img src="bpu.jpg" width="80%" />
</div>
<br>

2. **Biological Processing Unit**:

	Microprocessor consists of biological parts of I/O device, control unit, etc,
	which works as simulating living things.

	> **Biological process** are the processes vital for a living organism to live, 
	> and that shape its capacities for interacting with its environment. 
	> Biological processes are made up of many chemical reactions or other events 
	> that are involved in the persistence and transformation of life forms.

<div align="center">
<img src="bio-recongition.png" width="80%" />
</div>
<br>

3. **Bio-Recognition Processing Unit**:

	Except for specific ASIC chips, the most common bio-recognition is basically working on
	the combination of CPU and DPU.

	> A **biosensor** is an analytical device, used for the detection of a chemical substance, 
	> that combines a biological component with a physicochemical detector.

## D

1. **Deep-Learning Processing Unit**:

	DPU is not a propriety term for a certain company.
	There are many companies working on DPU,
	such as:

	- Deephi Tech:
	A company located in Beijing. Their neural network processor based on FPGA is named as DPU.
	They have developed two DPUs till now, Aristotle architecture for CNN and Cartesian architecture for DNN/RNN.

	<div align="center">
	<img src="dpu.jpg" width="80%" />
	</div>

	- TensTorrent: 
	A company located in Toronto, working on high-performance processor for deep-learning and intelligent hardware.
	Technical staff comes from NVDIA and AMD.

2. **Deep Learning Unit**:

	Registered by Fujitsu for their own AI chips.
	DLU consists of many small DPUs and several larger master cores(controlling access to DPUs and memory).
	Each DPU includes 16 DPE(Deep-Learning Processing Element)s, so that there are totally 128 elements working for SIMD instructions.

<div align="center">
<img src="dlu.jpg" width="80%" />
</div>
<br>

3. **Dataflow Processing Unit**:

	The deep learing accelerator developed by [Wave Computing](https://wavecomp.ai/) is named as **Dataflow Processing Unit**.
	DPU is integrated with 1024 clusters, with each cluster related to single fully customized layout.
	Each cluster consists of 8 arithmetic elements and 16 PEs,
	in which PEs are implemented asynchronously driven by data flow rather than clock signal,
	for which being named as **Dataflow Processor**.

	> With craft of TSMC 16nm FinFET, DPU die square of 400mm^2, internal single port of at least 24MB,
	> power consumption of about 200W, equivalent frequency up to 10 GHz and peformance up to 181TOPs.

<div align="center">
<img src="dfu.jpg" width="80%" />
</div>
<br>

4. **Data-storage Processing Unit**:

	Master chip for SSD developed by [DapuStor](http://www.dputech.com/) in Shenzhen.

5. **Digital Signal Processor**:

	DSPs are designed by TI, Qualcomm, CEVA, Tensilica, ADI, Freescale, etc.
	Contrasted with CPU, DSP improves its digital computing peformance by increasing parallelism,
	like SIMD, VLIW, SuperScalar.


## E

1. **Emotion Processing Unit**:
	
	The first emotion synthesis engine providing robots with emotions was developed by [Emoshape](https://emoshape.com/).
	**EPU** is based on **MCU**, combined with **API** and cloud native enhanced learning algorithm,
	which helps machines understand what they're watching and reading in terms of emotions.
	With **NLG** and **WaveNet**, machines can express their emotions.

<div align="center">
<img src="epu.jpg" width="80%" />
</div>
<br>

## F

1. **Floating Point Unit**:

	Commonly integrated in modern high-performance CPU, DSP and GPU.

## G

1. **Graphics Processing Unit**:

	<div align="center">
	<img src="gpu.png" width="80%" />
	</div>
	<br>

	A graphics processing unit (GPU) is a specialized electronic circuit designed to rapidly manipulate and alter memory to accelerate the creation of images in a frame buffer intended for output to a display device. 
	GPUs are used in embedded systems, mobile phones, personal computers, workstations, and game consoles. 
	Modern GPUs are very efficient at manipulating computer graphics and image processing. 
	Their highly parallel structure makes them more efficient than general-purpose central processing units (CPUs) for algorithms that process large blocks of data in parallel. 
	In a personal computer, a GPU can be present on a video card or embedded on the motherboard. 
	In certain CPUs, they are embedded on the CPU die.

	The term "GPU" was coined by Sony in reference to the PlayStation console's Toshiba-designed Sony GPU in 1994.
	The term was popularized by Nvidia in 1999, who marketed the GeForce 256 as "the world's first GPU".
	It was presented as a "single-chip processor with integrated transform, lighting, triangle setup/clipping, and rendering engines".
	Rival ATI Technologies coined the term "visual processing unit" or VPU with the release of the Radeon 9700 in 2002.

	- NVIDIA

	- AMD

	- Mali from ARM

	- PowerVR from Imagination

	- Adreno from Qualcomm

	- Vivante from VeriSilicon

	- Apple

2. **Graph Streaming Processor**:

	![thinci](./thinci.png)

	Proposed by [ThinCI(think-eye)](https://www.thinci.com/).
	Aimed for the application on auto-driving.
	Using a variety of structural techniques to achieve paralleling at the level of
	task, thread, data and instruction.
	With craft of TSMC 28nm HPC+, power consumption about 2.5W.

## H

1. **Holographic Processing Unit**:

	![hpu](./hpu.jpg)

	Developed by **Microsoft** for its own applications of Hololens.
	The first generation uses the craft of 29nm HPC and customized extension with 24 Tensilica DSP.
	The HPU supports 5-way cameras, a 1-way depth sensor (Depth sensor) and a 1-way motion sensor (Motion Sensor).

## I

1. **Intelligence Processing Unit**:
	
	There are two companies declaring the name IPU:

	- [Graphcore](https://www.graphcore.ai/)

	![graphcore](./graphcore.jpg)

	The IPU from Graphcore is aimed for graph computing.
	Graphcore believes that Graph is a very natural representation of knowledge models and corresponding algorithms, 
	so Graph is the basic representation of machine intelligence, applicable to both neural networks, 
	Bayesian networks and Markov fields, and possible future new models and algorithms.

	- [Mythic](https://www.mythic-ai.com/)

	> Mythic's intelligence processing unit (IPU) adds best-in-class intelligence to any device.

	Mythic claims to reduce power consumption to 1/50. The reason why they are so confident is because they use the "processing in memory" structure.

	![PIM chip](./pim.png)

	At each clock cycle, the pipelined ALU can either load data from memory or store data to memory, but not both
	at the same time. Also, on each clock cycle, the MU produces three outputs that can be either selected for storage
	(under mask control) or selected for recirculation.
	Additionally, data can be sent to other processors via the routing network.
	The processor can input data through a multiplexer
	(MUX) from either the parallel prefix network, the global
	OR network, the partitioned OR network, or the internal
	mask/register control.

2. **Image Processing Unit**:
	
	<div align="center">
	<img src="ipu.jpg" width="80%" />
	</div>
	<br>

	Some static image processing modules of SOC chips are called IPUs,
	also ISPs(Image Signal Processor),
	which are used to process the output signals of camera devices
	such as cameras, and implements functions such as noise reduction, demosaicing, HDR, and color management.

## K

1. **Knowledge Processing Unit**:

	Declared by [Canaan](https://canaan.io/) for its AI chip in 2017,
	which integrating artificial neural network and high performance processor in single chip
	to provide heterogeneous, real-time, offline artificial intelligence application services.

## M

1. **Micro Processing Unit**:

	![MPU](https://en.wikichip.org/w/images/5/53/IPO_%28input-process-output%29.svg)

	A microprocessor (µP) or a Microprocessing Unit (MPU) is a device that implements the core elements of a computer system on a single integrated circuit, or as a few integrated circuits operating as a cohesive unit, designed for the processing digital data.

	Modern microprocessors typically incorporate the functionality of a clock, central processing unit (CPU), arithmetic logic unit (ALU), floating point unit (FPU), control unit (CU), memory management unit (MMU), interrupts, input/output interfaces, and cache. Specialized microprocessor may also serve as graphical processing units (GPUs), signal processing units (DSPs), neural processing unit (NPUs), microcontrollers, etc.

2. **Mind Processing Unit**:
	
	An eternal tale.

3. **Memory Protection Unit**:

	![mem-protection](https://community.arm.com/cfs-file/__key/communityserver-blogs-components-weblogfiles/00-00-00-37-85/582Untitled.png)

	The Memory Protection Unit (MPU) is a programmable unit that allows privileged software, typically an
	OS kernel, to define memory access permission. It monitors transactions, including instruction fetches
	and data accesses from the processor, which can trigger a fault exception when an access violation is
	detected.

## N

Neural-Network Processing Unit

Neural/Neuromorphic Processing Unit

Network Processing Unit

## O

Optical-Flow Processing Unit

## P

Physical Processing Unit

## Q

Quantum Processing Unit

## R

Resistive Processing Unit

Ray-tracing Processing Unit

## S

Streaming Processing Unit

Speech-Recongnition Processing Unit

Smart Processing Unit

Space Processing Unit

## T

Tensor Processing Unit

## U

Universe Processing Unit

## V

Vision Processing Unit

Visual Processing Unit

Video Processing Unit

Vector Processing Unit

## W

Wearable Processing Unit

Wisdom Processing Unit

## X

X means everything

## Z

**Zylin CPU**: 
CPU of Zylin, a Norwegian company. 
[Reference Github page zylin/zpu](https://github.com/zylin/zpu).
> The worlds smallest 32 bit CPU with GCC toolchain,
> which means 'Taking up very little resources and the architecture itself is small.'

## Reference

1. [Wikipedia](https://en.wikipedia.org/wiki/Main_Page)
2. 知乎 [零基础看懂全球AI芯片: 详解"xPU"](https://zhuanlan.zhihu.com/p/28325678)
3. [The biological microprocessor, or how to build a computer with biological parts](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3962179/)
4. [Emoshape](https://emoshape.com/)
5. [Processing in Memory: The Terasys Massively Parallel PlM Array](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=375174)
6. [Wikichip](https://en.wikichip.org)
7. [Memory Protection Unit (MPU)](https://static.docs.arm.com/100699/0100/armv8m_architecture_memory_protection_unit_100699_0100_00_en.pdf)
