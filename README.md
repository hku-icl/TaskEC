# Task-Preserving Embodied Communication through Multirotor Actuation

Video demonstrations accompanying the manuscript **"Task-Preserving Embodied Communication through Multirotor Actuation."**

**Paper:** [arXiv (TBD)](https://arxiv.org/)

## Video Demonstration

Uploading Task-Preserving-Embodied-Communication-Demo.mp4…

## Overview

An unmanned aerial vehicle (UAV) can communicate without transmitting a data-bearing radio signal. By encoding information in its physical actions, the UAV enables a remote sensor to recover messages through observation. This principle, known as *embodied communication*, introduces a new communication opportunity, but raises a fundamental question: how can an agent communicate while preserving its primary control task?

This work develops task-preserving embodied communication through multirotor actuation. The key insight is that different rotor-speed allocations can generate the same commanded thrust and body torques while producing distinct micro-Doppler signatures in reflected radio signals. This allows a multirotor UAV to encode information without altering its prescribed flight-control commands.

At the receiver, decoding is complicated by unlabeled blade-pass frequencies and unknown, time-varying control commands. We develop a control-profiled set-matching receiver that recovers messages without identifying individual rotors or estimating the control trajectory. We further establish finite-observation identifiability and robust detection guarantees, and design communication codebooks under actuator and switching constraints.
