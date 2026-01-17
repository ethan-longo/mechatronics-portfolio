---
excerpt: Desing and implementaion of an autonomous beam balancing robot
layout: project
title: Beam Balancer
header:
  overlay_image: /assets/images/beam_balancer/beam_balancer_diagram.png
  overlay_filter: 0.4
---


<div class="project-flow">

  <!-- Row 1: Overview + Video -->
  <div class="project-row">
    <div class="project-image">
      <img src="{{'/assets/images/beam_balancer/photo.png' | relative_url }}"
           alt="Control and vision diagram">
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
    </div>
  </div>

  <!-- Row 2: Role + Constraints -->
  <div class="project-row reverse">
    <div class="project-text">
      <h3>My Role & Design Constraints</h3>

      <p><strong>My Role</strong></p>
      <ul>
        <li>Designed structural frame and linkage system in SolidWorks</li>
        <li>Derived kinematic relationships between servo angle and beam angle</li>
        <li>Developed a computer vision system using HSV colour filtering and shape detection for ball tracking</li>
        <li>Tuned PID gains to minimize overshoot and oscillations</li>
        <li>Contributed to assembly, testing, and iteration</li>
      </ul>

      <p><strong>Key Constraints</strong></p>
      <ul>
        <li><strong>Size:</strong> 200 × 190 × 90 mm operating volume</li>
        <li><strong>Actuation:</strong> Single servo motor</li>
        <li><strong>Stability:</strong> Central beam pivot for symmetric response</li>
        <li><strong>Manufacturing:</strong> Cost was limited to a maximum of $50</li>
      </ul>
    </div>

    <div class="project-image">
      <img src="{{ '/assets/images/beam_balancer/diagram.png' | relative_url }}"
           alt="Beam balancer mechanical layout">
    </div>
  </div>

  <!-- Row 3: Engineering Process + Outcome -->
  <div class="project-row">
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
    </div>

    <div class="project-image">
      <img src="{{ '/assets/images/beam_balancer/beam_balancer_diagram.png' | relative_url }}"
           alt="Control and vision diagram">
    </div>
  </div>


  <!-- Row 3: Engineering Process + Outcome -->
  <div class="project-row">
    <div class="project-image">
      <video controls>
        <source src="{{ '/assets/images/beam_balancer/Video.mov' | relative_url }}" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </div>

    <div class="project-text">
      <h3>Outcome & Skills</h3>

      <p><strong>Outcome:</strong> The final system successfully balanced a ping-pong ball along the beam and demonstrated stable closed-loop performance with minimal overshoot and fast settling time. The project highlighted the importance of the integration between mechanical design, sensing, and control, and provided hands-on experience in translating theoretical concepts into a functioning physical system.</p>

      <p><strong>Skills & Tools:</strong><br>
        SolidWorks · Mechanical Design · Kinematic Analysis · PID Control ·
        Computer Vision · 3D Printing · Laser Cutting · System Integration
      </p>
    </div>
  </div>
</div>
