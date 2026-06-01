---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

<style>
  .project-card {
    border: 1px solid #e1e4e8;
    border-radius: 8px;
    padding: 24px;
    margin-bottom: 30px;
    background-color: #ffffff;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }
  .project-card:hover {
    transform: translateY(-2px);
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }
  .portfolio-img-container {
    text-align: center;
    margin: 20px 0 10px 0;
  }
  .portfolio-img {
    max-width: 100%;
    height: auto;
    max-height: 400px;
    display: block;
    margin: 0 auto 8px auto;
    border-radius: 4px;
  }
  .portfolio-caption {
    font-style: italic;
    color: #555;
    font-size: 0.9em;
  }
  .tech-badge {
    background-color: #f3f4f6;
    color: #1f2937;
    padding: 4px 10px;
    border-radius: 4px;
    font-size: 0.85em;
    font-weight: 500;
    display: inline-block;
  }
</style>

## Research Projects

<div class="project-card">
  <h3>1. <a href="https://github.com/gopikagopikrishnan/ADAPT">ADAPT: Adaptive Depth-Agnostic Patch-wise Tunable Multibeamformer</a></h3>
  <p>An interpretable alternative to black-box CNNs that exploits physical priors for ultrasound beamforming under limited training data. ADAPT combines signal processing principles with learnable parameters, enabling depth-agnostic and tissue-aware reconstruction while maintaining explainability and robustness to out-of-distribution data.</p>
  
  <p><strong>GitHub Repository:</strong> <a href="https://github.com/gopikagopikrishnan/ADAPT">gopikagopikrishnan/ADAPT</a></p>
  <p><strong>Key Technologies:</strong> <span class="tech-badge">CNN</span> <span class="tech-badge">MATLAB</span> <span class="tech-badge">Ultrasound Signal Processing</span></p>

  <div class="portfolio-img-container">
    <img src="{{ '/images/adapt-diagram.png' | relative_url }}" class="portfolio-img" alt="ADAPT Method">
    <div class="portfolio-caption">Method flowchart showing patch-wise processing and apodization</div>
  </div>
</div>

<div class="project-card">
  <h3>2. Chipless RFID Tag Design</h3>
  <p>Compact planar multiresonator and U-shaped slot resonator designs for high-capacity chipless RFID tags in IoT applications. This IEEE APS-funded project focuses on developing scalable, cost-effective alternatives to chip-based RFID for inventory management and object tracking in distributed IoT systems.</p>
  
  <p><strong>Key Technologies:</strong> <span class="tech-badge">CST Studio</span> <span class="tech-badge">RF Tag Design</span></p>

  <div class="portfolio-img-container">
    <img src="{{ '/images/chiplessrfid.png' | relative_url }}" class="portfolio-img" style="max-width: 500px;" alt="Chipless RFID Resonator">
    <div class="portfolio-caption">Project Overview</div>
  </div>
</div>

<div class="project-card">
  <h3>3. SerDes Equalizer Subsystem</h3>
  <p>Design and development of an equalizer subsystem for a high-speed serializer-deserializer (SerDes) - B.Tech capstone project. The equalizer compensates for channel effects in high-speed serial links, enabling reliable data transmission at multi-Gbps rates in modern chip-to-chip communication.</p>
  
  <p><strong>Key Technologies:</strong> <span class="tech-badge">LTSpice</span> <span class="tech-badge">High Speed Communication Systems</span></p>

  <div class="portfolio-img-container">
    <img src="{{ '/images/serdes.png' | relative_url }}" class="portfolio-img" alt="SerDes Block Diagram">
    <div class="portfolio-caption">Project Overview with Area of my Work</div>
  </div>
</div>

<div class="project-card">
  <h3>4. <a href="https://github.com/gopikagopikrishnan/Elderly-Fall-Detection-and-Alert-System">Elderly Fall Detection & Alert System</a></h3>
  <p>Embedded system for real-time fall detection and emergency alerting, designed for elderly care applications. Uses accelerometer and gyroscope sensors to detect sudden movement patterns indicative of falls, triggering immediate alerts to caregivers.</p>
  
  <p><strong>GitHub Repository:</strong> <a href="https://github.com/gopikagopikrishnan/Elderly-Fall-Detection-and-Alert-System">gopikagopikrishnan/Elderly-Fall-Detection-and-Alert-System</a></p>
  <p><strong>Key Technologies:</strong> <span class="tech-badge">Embedded Systems</span> <span class="tech-badge">Sensor Integration</span> <span class="tech-badge">Proteus</span> <span class="tech-badge">C/C++</span></p>

  <div class="portfolio-img-container">
    <img src="{{ '/images/miniprjct.png' | relative_url }}" class="portfolio-img" style="max-width: 500px;" alt="Fall Detection System">
    <div class="portfolio-caption">Project System Architecture and Working</div>
  </div>
</div>

## Research & Summer Internship Projects

<div class="project-card">
  <h3>5. FPGA Cryptography System</h3>
  <p>Implemented an FPGA-based cryptography system programmed in Verilog HDL using Xilinx Vivado during a remote internship at IIT Guwahati. The system implements efficient encryption/decryption algorithms optimized for hardware deployment, demonstrating hardware acceleration for cryptographic operations.</p>
  
  <p><strong>Key Technologies:</strong> <span class="tech-badge">Verilog HDL</span> <span class="tech-badge">FPGA</span> <span class="tech-badge">Cryptography</span> <span class="tech-badge">Xilinx Vivado</span></p>

  <div class="portfolio-img-container">
    <img src="{{ '/images/iitg.png' | relative_url }}" class="portfolio-img" alt="FPGA Cryptography System">
    <div class="portfolio-caption">Project Overview with my Area of Work</div>
  </div>
</div>

## Software & Application Projects

<div class="project-card">
  <h3>6. <a href="https://github.com/gopikagopikrishnan/Haar-Classifier-and-LBPH-based-Attendance-System">Automated Attendance System</a></h3>
  <p>B.Tech minor project for automated attendance tracking using machine learning-based recognition techniques. Implements both Haar Cascade classifiers and Local Binary Pattern Histogram algorithm for real-time face detection and recognition.</p>
  
  <p><strong>GitHub Repository:</strong> <a href="https://github.com/gopikagopikrishnan/Haar-Classifier-and-LBPH-based-Attendance-System">gopikagopikrishnan/Haar-Classifier-and-LBPH-based-Attendance-System</a></p>
  <p><strong>Key Technologies:</strong> <span class="tech-badge">Python</span> <span class="tech-badge">OpenCV</span> <span class="tech-badge">Tkinter GUI</span></p>

  <div class="portfolio-img-container">
    <img src="{{ '/images/minor.png' | relative_url }}" class="portfolio-img" alt="ML Miniproject Design">
    <div class="portfolio-caption">Project Overview</div>
  </div>
</div>
