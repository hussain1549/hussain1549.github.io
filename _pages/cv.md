---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download a PDF copy of my CV]({{ base_path }}/files/Hussain_Ahmad_CV.pdf)

Education
======
* MSc in Electronics Engineering, University of Southern Denmark, Sønderborg, 2021 to 2023
* BSc in Electrical Engineering, Bahria University, Islamabad, 2015 to 2019

Work experience
======
* Feb 2022 to Feb 2026: Embedded Hardware and Software Developer, Bitzer Electronics, Sønderborg, Denmark
  * Built a high-throughput sensor validation system combining hardware, STM32 firmware in C, and Python diagnostic scripts for automated data collection and analysis.
  * Designed PCBs and managed end-to-end integration, covering schematics, layout, BOM, and production handoff, with clear technical documentation.
  * Implemented data logging, debugging, and structured test workflows that transfer directly to communication testbeds and reliable data collection.

* Aug 2019 to Sep 2021: Research Assistant, Sejong University, Seoul, South Korea
  * Designed and simulated distributed network algorithms in Python, focusing on real-time optimisation of resource allocation and latency in edge computing frameworks.
  * Applied reinforcement learning to optimise dynamic systems, achieving a 33 percent performance gain.
  * Developed an end-to-end communication system simulation in MATLAB, including modulators, channel models, and receivers for a 500 Mbps optical link.
  * Carried out detailed numerical simulations of signal propagation and impairment analysis.

Skills
======
* Programming and data: Python, MATLAB and Simulink, C and C++, Verilog, Git, Linux, NS-3, OMNeT++, data analysis, simulation workflows
* Methods: machine learning, reinforcement learning, quantitative modelling, experimental design
* Engineering: embedded systems, sensor data pipelines, diagnostics, debugging, PCB design, hardware and software co-design
* Wireless communication: 3GPP, 5G, 6G, mmWave, line-of-sight communication, mobile networks, edge computing, resource allocation, optimisation theory, URLLC

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Selected projects
======
* URLLC-oriented 6G edge networking simulator in Python and MATLAB, integrating realistic channel models, traffic patterns, and queueing delays, with reinforcement-learning based resource allocation and routing.
* Link-level PHY simulator with adaptive modulation and coding in MATLAB and C++, studying BER and BLER under AWGN and fading channels.
* FPGA-based baseband prototype for short-range communication in VHDL and C, including modulation, filtering, and synchronisation blocks.
* Embedded C and C++ firmware for real-time sensor communication on microcontroller and embedded Linux platforms with kHz-level sampling.

Languages
======
* English (professional proficiency)

References
======
* Dr. Saleem Aslam, Professor, Bahria University, Pakistan, saleem.buic@bahria.edu.pk
* Dr. Rashid Ali, Senior Lecturer, Department of Engineering Science, University West, Sweden, rashid.ali@hv.se
* Dr. Ammara Nasim, Associate Professor, Bahria University, Islamabadd, Pakistan, ammaranaseem.buic@bahria.edu.pk
