---
layout: page
permalink: /participants/
title: Participants
nav: true
nav_order: 1
toc:
  sidebar: left
---

## Speakers
<div class="row row-cols-2 projects pt-3 pb-3">
  {% include horizontal_talk.html
     url="https://people.ucas.ac.cn/~zhengxy?language=en"
     name="Prof. Xiaoying Zheng"
     title="FAST Telescope’s High‑Speed Data Stream Processing & Coherent De‑dispersion for SKA‑mid"
     affiliation="Shanghai Advanced Research Institute, CAS"
     abstract="Coherence de-dispersion is extremely important for the discovery of highly dispersed millisecond pulsars, and the processing method of traditional small telescopes, which relies on saving data before computing, is difficult to cope with massive data streams of SKA-mid. Moreover, quasi real-time stream processing is limited by multiple bottlenecks, such as the access to observed raw data streams, the high complexity of coherence de-dispersion, and the bandwidth of disk I/O. To address these challenges, this report proposes to use DPDK (Data Plane Development Tool Kit) technology to break through the bottleneck of data transmission, realize the parallel optimization of pulsar search coherent de-dispersion algorithm on GPU-CPU heterogeneous architecture, and propose a scheme to replace hard disks with Optane persistent memory to optimize disk data throughput. The proposed method has been implemented for verification on the FAST (Five Hundred Aperture Sphere Telescope) Telescope, one of the pathfinder facilities of SKA-MID. The implemented high-speed radio astronomical data stream processing and coherent De-dispersion achieved near 0 packet loss data access for 38 GB/s observation data streams and 10 parallel de-dispersions to identify pulsar candidates." %}

  {% include horizontal_talk.html
     url="/participants/"
     name="Dr. Shoupeng Wang"
     title="Transformer Algorithm for Pile-up Correction in Synchrotron Spectroscopic Detection"
     affiliation="Shanghai Synchrotron Radiation Facility (SSRF)"
     abstract="In high-flux synchrotron radiation experiments, the pile-up effect significantly degrades the energy resolution and data accuracy of spectroscopic detection systems. This issue becomes particularly pronounced under high count rate conditions, where traditional pile-up correction algorithms often suffer from limited recognition accuracy and adaptability. To address these challenges, this paper proposes a pile-up identification method based on a Transformer deep learning architecture, and implements a heterogeneous electronics system that integrates FPGA and GPU computing. The system utilizes a digital pulse processor (DPP) equipped with a Xilinx Zynq UltraScale+ MPSoC for real-time signal processing, while the GPU is employed for Transformer model training and parameter optimization. Offline testing demonstrates that the system maintains stable pile-up correction performance across a wide count rate range (from several kcps to Mcps), achieving an energy resolution of approximately 130 eV at a high input rate of 1 Mcps. Furthermore, the system exhibits strong resilience to noise and signal distortions, indicating its broad application potential for real-time pile-up correction in high-flux synchrotron X-ray fluorescence and absorption spectroscopy experiments." %}

  {% include horizontal_talk.html
     url="/participants/"
     name="Dr. Yue Zhang"
     title="Progress on the SLEGS Beamline Nuclear Resonance Fluorescence Spectrometer"
     affiliation="Shanghai Synchrotron Radiation Facility (SSRF)"
     abstract="This report will describe the development and testing of the NRF spectrometer at the SLEGS beamline, which produces polarized, quasi-monochromatic gamma-rays via inverse Compton scattering. The spectrometer, configured with HPGe and LaBr3 detectors, demonstrated excellent energy resolution and stability. The spectrometer is now operational for user experiments studying photonuclear reactions in fundamental and applied nuclear physics." %}
	 
  {% include horizontal_talk.html
	url="https://faculty.sist.shanghaitech.edu.cn/zhengjie/index.htm"
	name="Prof. Jie Zheng"
	title="Explainable AI for Discovery of Synthetic Lethal Anti-Cancer Drug Targets Based on Large Language Models"
	affiliation="ShanghaiTech University"
	abstract="The discovery of anti-cancer drug targets is of fundamental importance for cancer medicine. Synthetic lethality (SL) is a type of genetic interaction typically between two genes, which is that perturbations to both genes will kill a cell but perturbation to one gene alone will not. It is a gold mine of anti-cancer drug targets since targeting an SL partner of a gene with cancer-specific abnormality can selectively kill cancer cells without harming normal cells. Wet-lab screening methods usually have high cost, while statistical and machine learning methods cannot fully utilize the prior knowledge or lack clear explanations. We have developed a series of deep learning methods using Graph Neural Networks (GNNs), Knowledge Graphs (KGs) and Large Language Models (LLMs) to predict SLs and understand the underlying mechanisms. For instance, we developed NexLeth, the first dataset and framework for generating natural language explanations of SL mechanisms by fusing knowledge graphs and prompt engineering on pre-trained language models (e.g. GPT). Then, we proposed SL-MERK, an LLM-based framework that integrates GraphRAG (Graph Retrieval-Augmented Generation) with knowledge graph for generating natural language explanations of SL mechanisms. These studies demonstrated the power of LLMs for explainable recommendation of SL-based anti-cancer drug targets, with potential for accelerating cancer precision medicine." %}

  {% include horizontal_talk.html
	url="https://en.sce.ac.il/faculty/tom"
	name="Dr. Tom Trigano"
	title="Machine Learning for Activity Estimation in Spectroscopy Signals"
	affiliation="Shamoon College of Engineering"
	abstract="The field of nuclear spectroscopy has received considerable interest in the last decades, particularly due to the exponential development of novel Machine Learning (ML) and Deep Learning (DL) techniques. However, the lack of annotated data often prevents their use at a large scale. In this presentation, we show how ML/DL methods can be used to extract the activity of a radioactive source directly from the time signal. Although simple, this illustration demonstrates that much remains to be done to fully leverage the potential of ML/DL techniques." %}

{% include horizontal_talk.html
    url="https://www.linkedin.com/in/thierry-montagu-982b0210/"
    name="Dr. Thierry Montagu"
    title="Variance-Stabilizing Transformations for Shot-Noise Count-Rate Estimation via the Delta Method"
    affiliation="Exail robotics"
    abstract="The Shot Noise process is a well-known stochastic process in physics, particularly in nuclear physics, as it effectively models particles (photons, neutrons, etc.) impinging on detectors. The intensity λ of the Shot noise is related to the count rate (typically the number of particles detected per second). For very high count rates, individual detections and the first and second cumulants of the shot noise allow us to estimate the count rate. It is noted that the variance of the estimators of the first two cumulants of the Shot Noise process is a function of their expectations. This property also holds for the two 'plug-in' estimators of the intensity λ based on the two preceding estimators; this property is called heteroscedasticity in statistics. In order to make this variance independent of λ, variance-stabilizing transformations are constructed using the Delta Method for the estimators used in neutron measurements." 
%}
</div>


