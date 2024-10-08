---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Hello! I am currently a doctoral student from School of Mathematical Sciences, [Peking University](https://english.pku.edu.cn/), advised by [Prof.Heng Mao](https://www.math.pku.edu.cn/teachers/maoh/index.html). I got my B.Eng degree in Sept. 2019, from Department of Optoelectronic Science and Technology, [Harbin Institute of Technology](http://en.hit.edu.cn/). 

I have an undergraduate background in optoelectronic instruments and received extensive training in constructing optical imaging instruments during my Ph.D research. Additionally, my studies in the mathematics department has enhanced my ability to solve interdisciplinary problems using computational imaging techniques. Currently, I focus on breaking imaging limitations in biomedical imaging through advanced optical and mathematical computation approaches.

I am expected to receive my Ph.D degree on <strong>July 2025</strong>, assuming everything goes smoothly. I am currently seeking suitable <strong>postdoctoral</strong> research opportunities or other <strong>opening positions</strong>. Feel free to shoot me an email if you are interested in collaborating with me.

Research Interests
======
<ul>
  <li><strong>Advanced microscopic methods for high-resolution and deep-tissue imaging</strong></li>
  <li><strong>High-dimensional zebrafish brain imaging</strong></li>
  <li><strong>Adaptive optics in microscopy </strong></li>
</ul>

Research Projects
======
During my Ph.D. research, I am the primary student responsible for several research projects. And my work and contributions are as follows:

Computational Imaging in Label-free and Fluorescence Microscopy
------
In order to address the problems of time-consuming scanning and throughput limitation in the cell microarray, I developed a high-throughput and high-content array screening imaging system. By customizing an ultra-high throughput objective lens, it achieved more than four times the imaging throughput of commercial high-throughput objective lenses. However, only the hardware system is still constrained by trade-offs between resolution and field of view (FOV). Therefore, I further improved imaging throughput by utilizing Fourier ptychography microscopy (FPM) to achieve synchronous imaging of hundreds of live cells. This work has been published, <strong>Liang Chen</strong>, et al., <i>Optics and Lasers in Engineering</i>, [doi: 10.1016/j.optlaseng.2024.108055](https://doi.org/10.1016/j.optlaseng.2024.108055).

Additionally, based on this system, I conducted 3D tomography research for mouse embryo development. I hope to image deeper and break through the thickness of the zona pellucida by focusing on diffraction and scattering tomography models and reconstruction methods. Recently, I developed a structured illumination super-resolution imaging modality (SIM) based on this system. The whole system achieves both label-free and fluorescence modalities for living cells and tissue samples, allowing for comprehensive study of their structures and functions. Combining these dual modalities in reconstruction may address the issue of insufficient imaging depth in SIM caused by sample-induced aberrations. 

<strong>Key words</strong>: Label-free microscopy, High-throughput imaging, Fourier ptychography microscopy, High SBP objective lens, System calibration

<strong>Funding</strong>: National Major Research Instrumentation Program, National Natural Science Foundation in China (<strong>NSFC, Grant No.81827809</strong>), to develop a high-throughput and high-content array screening and imaging system for self-assembled cell microarray, participant.

<strong>Advisor</strong>: [Prof.Heng Mao](https://www.math.pku.edu.cn/teachers/maoh/index.html), [Prof. Jianzhong Xi](http://www2.coe.pku.edu.cn/subpaget.asp?id=19)

<br/><img src='/images/FPMSIM.png'>

<strong>Figure</strong>: The dual-modalities system with Fourier ptychography microscopy and structured illumination microscopy.

Lightsheet Microscopy in Zebrafish Brain Imaging
------
This scientific problem I have worked on is whole-brain functional imaging of zebrafish to reveal functions such as learning and memory. The brain size of zebrafish is 800×600×400 µm, and achieving at least single-neuron resolution while pursuing faster volumetric imaging speed has always been my goal. Single-photon light-sheet microscopy is currently the primary method used for whole brain functional studies in zebrafish. However, the wavelength used for illumination can activate optic neurons and their downstream circuits, leading to potential artificial results during functional imaging of the entire brain. The wavelength used in two-photon microscopy can avoid the visually sensitive band of zebrafish, making two-photon light-sheet microscopy ideal for whole brain imaging. However, it currently faces significant challenges. 

On the one hand, there is a lack of functional probes due to the absence of commercial high-throughput two-photon fluorescent protein screening systems. To address this, I have established a two-photon screening platform to evolve functional calcium probes with higher brightness(see the next section). On the other hand, to address aberrations in large-field, deep-tissue imaging, I developed adaptive optical detection and correction methods for the two-photon light-sheet microscopy. Using a point-scanning excitation, I utilized the sample’s fluorescence signal as a guide star to detect the wavefront in zebrafish's different brain regions. The obtained wavefront aberrations were used to control the deformable mirror for wavefront shaping and to perform subregional deconvolution of the light-sheet data. This work has been applied for Chinese Invention Patent (No. 202410709063.8).

<strong>Key words</strong>: Lightsheet microscopy, Large volumetric brain imaging, Two-photon imaging

<strong>Funding</strong>: National Major Research Instrumentation Program, National Natural Science Foundation in China (<strong>NSFC, Grant No.21927813</strong>), high-throughput two-photon fluorescent protein screening and the whole brain functional imaging system, participant.

<strong>Advisor</strong>: [Prof.Heng Mao](https://www.math.pku.edu.cn/teachers/maoh/index.html), [Prof. Liangyi Chen](https://future.pku.edu.cn/en//js/Faculty/InstituteMedicine/e215c13603434680a6f6c313a48f71f9.htm)

<br/><img src='/images/LightsheetV2.png'>

<strong>Figure</strong>: The lightsheet microscope for zebrafish whole-brain functional imaging.

A Two-photon Screening Platform for Fluorescent Protein
------
At present, fluorescent protein screening primarily focuses on single-photon probes, and there are no commercial high-throughput screening systems specifically designed for two-photon fluorescent proteins. I have established a complete screening platform and expect to obtain functional calcium probes with high brightness, large absorption cross-section, matching laser peak power, high fluorescence excitation efficiency and strong anti-bleaching ability.

I designed a platform that combines large field of view (FOV) stitching for macroscopic imaging and multi-site two-photon microscopic imaging, enabling high-throughput screening of proteins. The large FOV stitching module automatically locates the position of each bacterial colony. Using pre-calibrated transformation relationships, it controls the movement of the sample stage, positioning each colony sequentially at the central FOV of the one/two-photon scanning module for fluorescence imaging. After that, the fluorescence intensity of each colony is measured and calculated. To synchronize laser scanning control and image acquisition, I modified ScanImage ([Vidrio Technologies](https://www.mbfbioscience.com/products/scanimage)) and integrated all controls into a GUI panel. Further, utilizling the screened probe, functional imaging of the whole zebrafish brain can be achieved without artificial activation by excitation wavelength.

<strong>Key words</strong>: Macroscopic and microscopic imaging, Fluorescent protein screening, High-throughput screening

<strong>Funding</strong>: National Major Research Instrumentation Program, National Natural Science Foundation in China (<strong>NSFC, Grant No.21927813</strong>), high-throughput two-photon fluorescent protein screening and the whole brain functional imaging system, participant.

<strong>Advisor</strong>: [Prof. Pingyong Xu](http://english.ibp.cas.cn/pe/casyipam/201406/t20140618_122950.html)

<br/><img src='/images/ScreeningPlatformV2.png'>

<strong>Figure</strong>: The screening platform for fluorescent protein.

Adaptive Optics (AO) in Microscopy 
------
I have been developing a novel optical and reconstruction method to reduce the impact of scatter in deep tissue imaging. Recently, I have built a proof-of-principle AO system to validate my idea. At the same time, utilizing a self-built wavefront sensor and deformable mirrors (both Boston DM-Multi-3.5 and Alpao DM97-15), I implemented a series of advanced techniques in AO for microscopy.

<strong>Key words</strong>: Adaptive Optics, Real-time optical sensing and close-loop control, Deep tissue imaging

<strong>Funding</strong>: General Project, National Natural Science Foundation in China (<strong>NSFC, Grant No.32071458</strong>), Sparse volume illumination light field microscopy for rapid volumetric imaging on zebrafish whole brain, participant.

<strong>Advisor</strong>: [Prof.Heng Mao](https://www.math.pku.edu.cn/teachers/maoh/index.html), [Prof. Liangyi Chen](https://future.pku.edu.cn/en//js/Faculty/InstituteMedicine/e215c13603434680a6f6c313a48f71f9.htm)

<br/><img src='/images/AO.png'>

<strong>Figure</strong>: AO demonstration, real-time optical sensing and reconstruction.

Teaching Experiences
======
1. <strong>Digital Image Processing</strong>, Spring Semester 2023, teaching assistant
2. <strong>Bioinformatics Methods and Applications</strong>, Fall Semester 2022, teaching assistant
3. <strong>The Design and Analysis of Algorithm</strong>, Fall Semester 2021, teaching assistant
4. <strong>Digital Signal Processing</strong>, Fall Semester 2020, teaching assistant

Publications
======
<strong>Journals:</strong>

1. <strong>Chen Liang</strong>†, Fan Feng†, Ke Du, Dongdong Chen, Runjia Yang, Chang Lu, Shumin Chen, Jianzhong Jeff Xi, Heng Mao*. Computational label-free microscope through a custom-built high-throughput objective lens and Fourier ptychography. <i>Optics and Lasers in Engineering</i>, 176:108055, 2024. [DOI: 10.1016/j.optlaseng.2024.108055](https://doi.org/10.1016/j.optlaseng.2024.108055).

2.  Fan Feng†,* , <strong>Chen Liang</strong>†, Dongdong Chen, Ke Du, Runjia Yang, Chang Lu, Shumin Chen, Wenting He, Pingyong Xu, Liangyi Chen, Louis Tao, Heng Mao*. Moment-based space-variant Shack–Hartmann wavefront reconstruction. <i>Optics Communications</i>, 540: 129515, 2023. [DOI: 10.1016/j.optcom.2023.129515](https://doi.org/10.1016/j.optcom.2023.129515).

3. Fan Feng†,* , <strong>Chen Liang</strong>†, Dongdong Chen, Ke Du, Runjia Yang, Chang Lu, Shumin Chen, Liangyi Chen, Louis Tao, and Heng Mao*, Space-variant Shack–Hartmann wavefront sensing based on affine transformation estimation. <i>Applied Optics</i>, 61: 9342-9349, 2022. [DOI: 10.1364/AO.471225](https://doi.org/10.1364/AO.471225).

<strong>Conferences:</strong>

1. <strong>Chen Liang</strong>, Fan Feng, Pingyong Xu and Heng Mao*, Hybrid Illumination Angle Calibration for Fourier Ptychography Microscope, in <i>Optica Imaging Congress 2024</i>, paper JM4A.14, accepted. [PDF is here](../files/FPM_OSA2024.pdf).

2. Fan Feng*, <strong>Chen Liang</strong>, High-resolution Space-variant Shack–Hartmann Wavefront Reconstruction, in <i>Optica Imaging Congress 2024</i>, paper OF1F.5, accepted. [PDF is here](../files/Feng_OSA2024.pdf).

<strong>Patents:</strong>

1. <strong>Chen Liang</strong>, Fan Feng, Pingyong Xu, Wenting He, A multi-modality microscope and method for deep tissue sample imaging, Invention, No.202410709063.8, Application Date June 3, 2024.

2. <strong>Chen Liang</strong>, Hongrun Yang, Fan Feng, Pingyong Xu, Wenting He, Automated Imaging Device for Fluorescent Protein Screening, Invention, No.202411104252.9, Application Date August 13, 2024.

3. Fan Feng, <strong>Chen Liang</strong>, A method and device for measuring aberrations in optical components or imaging systems, Invention, No.202311517845.3, Application Date September 28, 2023.

4. Heng Mao, Runjia Yang, <strong>Chen Liang</strong>, Ke Du, Lintao Liang, Multi-color and uniform thin-layer laser illumination device and its application, Invention, No.202210239384.7, Application Date March 11, 2022.