---
excerpt: Vision-based ball balancing system using PID control
layout: project
title: Beam Balancer
header:
  overlay_image: /assets/images/beam_balancer/beam_balancer_diagram.png
  overlay_filter: 0.4
  caption: "Vision-based ball balancing system"
---
<!-- 
## Overview
Designed and built a tabletop robotic system capable of balancing a
ping-pong ball along a beam using computer vision and closed-loop
control under strict size constraints.

## Tools
- SolidWorks
- Computer vision (HSV thresholding)
- PID control
- 3D printing
- Laser cutting

## What I Did
- Designed the mechanical frame and linkage system in SolidWorks
- Derived kinematic relationships between servo and beam angle
- Implemented vision-based ball tracking using HSV thresholding
- Tuned PID gains for fast and stable convergence
- Integrated mechanical, sensing, and control subsystems
- Assisted with assembly and iterative testing

## Outcome
Successfully achieved stable, responsive ball balancing within tight
size constraints. The project demonstrated effective integration of
mechanical design, vision sensing, and control theory. -->

<!-- <div class="project-flow">

  <div class="project-row">
    <div class="project-image">
        <video width="320" height="240" controls>
            <source src="/mechatronics-portfolio/assets/images/beam_balancer/Video.mov" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>
    <div class="project-text">
      <h3>Overview</h3>
      <p>
        Vision-based closed-loop control system for balancing a ping-pong
        ball along a beam using a single servo motor.
      </p>
    </div>
  </div>

  <div class="project-row reverse">
    <div class="project-text">
      <h3>What I Did</h3>
      <ul>
        <li>Mechanical and linkage design</li>
        <li>Kinematic derivation</li>
        <li>Vision-based tracking</li>
        <li>PID tuning</li>
      </ul>
    </div>
    <div class="project-image">
      <img src="/mechatronics-portfolio/assets/images/beam_balancer/diagram.png" alt="Assembled system">
    </div>
  </div>

  <div class="project-row">
    <div class="project-image">
      <img src="/mechatronics-portfolio/assets/images/beam_balancer/beam_balancer_diagram.png" alt="Vision tracking">
    </div>
    <div class="project-text">
      <h3>Outcome</h3>
      <p>
        Achieved stable real-time ball balancing within strict size and
        actuation constraints.
      </p>
    </div>
  </div>

</div> -->


<div class="project-flow">

  <!-- Row 1: Overview + Video -->
  <div class="project-row">
    <div class="project-image">
      <video controls>
        <source src="{{ '/assets/images/beam_balancer/Video.mov' | relative_url }}" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </div>

    <div class="project-text">
      <h3>Overview</h3>
      <p>
        Designed and built a tabletop robotic system capable of balancing
        a ping-pong ball along a beam using vision-based feedback and
        closed-loop control. The project required tight integration of
        mechanical design, kinematic analysis, computer vision, and PID
        control under strict size constraints.
      </p>

      <p><strong>System Focus:</strong></p>
      <ul>
        <li>Vision-based sensing of ball position</li>
        <li>Single-actuator beam control</li>
        <li>Fast, stable closed-loop response</li>
      </ul>
    </div>
  </div>

  <!-- Row 2: Role + Constraints -->
  <div class="project-row reverse">
    <div class="project-text">
      <h3>My Role & Design Constraints</h3>

      <p><strong>My Contributions</strong></p>
      <ul>
        <li>Designed structural frame and linkage system in SolidWorks</li>
        <li>Derived kinematic relationships between servo angle and beam angle</li>
        <li>Implemented HSV-based computer vision for ball tracking</li>
        <li>Tuned PID gains to minimize overshoot and oscillations</li>
        <li>Participated in assembly, testing, and iteration</li>
      </ul>

      <p><strong>Key Constraints</strong></p>
      <ul>
        <li><strong>Size:</strong> 200 × 190 × 90 mm operating volume</li>
        <li><strong>Actuation:</strong> Single servo motor</li>
        <li><strong>Stability:</strong> Central beam pivot for symmetric response</li>
        <li><strong>Manufacturing:</strong> Laser-cut acrylic and 3D-printed parts</li>
      </ul>
    </div>

    <div class="project-image">
      <img src="{{ '/assets/images/beam_balancer/diagram.png' | relative_url }}"
           alt="Beam balancer mechanical layout">
    </div>
  </div>

  <!-- Row 3: Engineering Process + Outcome -->
  <div class="project-row">
    <div class="project-image">
      <img src="{{ '/assets/images/beam_balancer/beam_balancer_diagram.png' | relative_url }}"
           alt="Control and vision diagram">
    </div>

    <div class="project-text">
      <h3>Design & Engineering Process</h3>

      <p>
        The mechanical system was fully designed in SolidWorks around a
        centrally pivoted beam actuated via a two-bar linkage driven by a
        single servo motor. Linkage geometry was selected to maximize angular
        resolution while remaining within the height constraint.
      </p>

      <p>
        Kinematic equations were derived to map servo angle to beam angle,
        enabling accurate feedforward control. A camera-based vision system
        using HSV colour thresholding and shape detection tracked the ball’s
        position robustly under varying lighting conditions.
      </p>

      <p>
        A PID controller regulated ball position along the beam. Gains were
        tuned experimentally to reduce oscillations, minimize overshoot, and
        achieve fast convergence to the beam center. Iterative testing refined
        both mechanical alignment and control performance.
      </p>

      <p><strong>Outcome:</strong> Stable real-time ball balancing achieved
        within strict size, actuation, and manufacturing constraints.</p>

      <p><strong>Skills & Tools:</strong><br>
        SolidWorks · Mechanical Design · Kinematic Analysis · PID Control ·
        Computer Vision · 3D Printing · Laser Cutting · System Integration
      </p>
    </div>
  </div>

</div>
