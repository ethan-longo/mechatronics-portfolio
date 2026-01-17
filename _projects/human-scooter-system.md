---
title: Human Scooter System Modelling
excerpt: Dynamic modelling and simulation of a two-wheeled transporter
layout: project
# header:
#   overlay_image: /assets/images/background.png
#   overlay_filter: 0.4
---

<div class="project-flow">

  <!-- Row 1: Overview -->
  <div class="project-row">
    <div class="project-image">
      <img src="{{ '/assets/images/scooter/system-model.png' | relative_url }}" alt="Human scooter system model and dynamics">
    </div>

    <div class="project-text">
      <h3>Human Scooter System Modelling</h3>
      <p>
        This project focused on modelling and analyzing a two-wheeled human
        transporter system comparable to an inverted pendulum. The goal was to
        maximize upright travel distance without active feedback control.
      </p>
      <p>
        Using MATLAB, Simulink, and SimulationX, the system dynamics were derived,
        linearized, and evaluated through simulation to understand balance limits
        and instability mechanisms.
      </p>
      <div class="project-metrics">
        <span class="project-metric">Inverted pendulum model</span>
        <span class="project-metric">Open-loop dynamics</span>
        <span class="project-metric">MATLAB / Simulink</span>
        <span class="project-metric">SimulationX 3D</span>
      </div>
    </div>
  </div>

  <!-- Row 2: Role (reversed) -->
  <div class="project-row reverse">
    <div class="project-text">
      <h3>My Role</h3>
      <ul>
        <li>Derived equations of motion and linearized the system model</li>
        <li>Developed Simulink and SimulationX models for stability analysis</li>
        <li>Designed and parameterized 3D transporter and rider models</li>
        <li>Ran experiments varying thrust force and initial angles</li>
        <li>Contributed to analysis, results interpretation, and reporting</li>
      </ul>
    </div>

    <div class="project-image">
      <img src="{{ '/assets/images/scooter/diagram.png' | relative_url }}" alt="3D SimulationX scooter model">
    </div>
  </div>

  <!-- Row 3: Technical Focus -->
  <div class="project-row">
    <div class="project-text">
      <h3>Technical Focus</h3>
      <ul>
        <li><strong>System Dynamics:</strong> Nonlinear and linearized equations of motion</li>
        <li><strong>Modelling:</strong> State-variable models in MATLAB/Simulink</li>
        <li><strong>3D Simulation:</strong> Physics-based SimulationX environment</li>
        <li><strong>Optimization:</strong> Tuned thrust and angle parameters</li>
      </ul>
    </div>
  </div>

  <!-- Row 4: Outcome (reversed) -->
  <div class="project-row reverse">
    <div class="project-text">
      <h3>Outcome</h3>
      <p>
        The open-loop system achieved up to <strong>16.5 meters of stable forward
        motion</strong> before tipping. While the transporter was inherently
        unstable without feedback, optimization experiments provided insight into
        balance dynamics and control sensitivity.
      </p>
      <p>
        This work demonstrated the necessity of closed-loop control for practical
        operation and established a strong foundation for future controller
        implementation.
      </p>
      <p><strong>Skills & Tools:</strong> MATLAB, Simulink, SimulationX, system dynamics,
      linearization, 3D simulation, experimental analysis</p>
    </div>

  </div>

</div>
