# ECE Project Portfolio

This repository showcases three academic and technical projects developed
as part of my Electronics and Communication Engineering studies. The
projects demonstrate practical experience across VLSI and CMOS circuit
design, embedded systems, and Generative Artificial Intelligence.

## Objective

These projects reflect my interest in applying electronics, embedded
systems, VLSI design, and emerging AI technologies to practical
engineering problems.

## Technical Areas

- Analog and Mixed-Signal VLSI
- CMOS Transistor-Level Circuit Design
- Cadence Virtuoso
- Embedded Systems
- ARM7 LPC2148
- Sensor Interfacing and ADC
- Stepper Motor Control
- Generative AI
- Computer Vision
- Natural Language Processing
- Diffusion Models
- Python

### 1. Phase-Locked Loop (PLL) Design

Designed and simulated a 16 MHz–1024 MHz Integer-N Phase-Locked Loop using UMC 180 nm CMOS technology in Cadence Virtuoso. The PLL consists of a Phase Frequency Detector, Charge Pump, passive second-order loop filter, current-starved ring VCO, and divide-by-64 frequency divider. The complete transistor-level design was integrated and simulated to generate an output frequency of approximately 1.02465 GHz, demonstrating frequency multiplication and closed-loop synchronization.

### 2. Temperature-Controlled Stepper Motor System

Developed an automated temperature-based cooling system using the ARM7 LPC2148 microcontroller, LM35 temperature sensor, ADC, and stepper motor with Embedded C in Keil µVision. The system continuously monitors ambient temperature through the LM35, processes the sensor data using the LPC2148 ADC, and compares it with a predefined threshold. Based on the temperature condition, the controller automatically operates the stepper motor to regulate the cooling mechanism.

### 3. Text-to-Video Generation using Generative AI

Developed a Generative AI-based text-to-video system that converts natural language prompts into coherent video sequences using the DAMO Text-to-Video MS-1.7B model. The system incorporates T5/CLIP text encoding, 3D denoising UNet, cross-attention, VAE-based latent representations, DPMSolverMultistep noise scheduling, and LoRA fine-tuning. The project demonstrated prompt-based video generation with spatial and temporal consistency while using LoRA for efficient adaptation to specific visual styles.
