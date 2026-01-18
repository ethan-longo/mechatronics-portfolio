---
title: Autonomous Tennis Training Robot
excerpt: Autonomous robot for randomized tennis ball training sessions
layout: project
header:
  overlay_image: /assets/images/tennis_robot/full.png
  overlay_filter: 0.4
---

<div class="project-flow">

  <!-- Row 1: Overview -->
  <div class="project-row">
    <div class="project-image">
      <img src="{{ '/assets/images/tennis_robot/full.png' | relative_url }}"
           alt="Tennis training robot prototype">
    </div>

    <div class="project-text">
      <h3>Autonomous Tennis Training Robot</h3>
      <p>
        This project involved the design and construction of a mobile robotic
        system intended as a low-cost alternative to commercial tennis ball
        machines and private coaching sessions.
      </p>
      <p>
        The robot autonomously collects Tetrix balls, navigates to a set
        court position, and launches balls at randomized angles to support
        customizable user training sessions.
      </p>
    </div>
  </div>

  <!-- Row 2: Role (reversed) -->
  <div class="project-row reverse">
    <div class="project-image">
      <img src="{{ '/assets/images/tennis_robot/Shooting flow chart.png' | relative_url }}"
           alt="Tennis training robot flow chart">
    </div>

    <div class="project-text">
      <h3>My Role</h3>
      <ul>
        <li>Co-designed and assembled mechanical systems including conveyor intake, launcher, and drivetrain</li>
        <li>Programmed RobotC functions for intake, navigation, and shooting</li>
        <li>Implemented randomized firing logic and user-configurable rounds</li>
        <li>Integrated colour and gyro sensors for ball detection and orientation</li>
        <li>Contributed to troubleshooting, testing, and iteration</li>
      </ul>
    </div>
  </div>

  <!-- Row 3: Technical Focus -->
  <div class="project-row">
    <div class="project-image">
      <img src="{{ '/assets/images/tennis_robot/intake.png' | relative_url }}"
           alt="Tennis training robot intake">
    </div>

    <div class="project-text">
      <h3>Technical Focus</h3>
      <ul>
        <li>
          <strong>Mechanical Design:</strong> Conveyor belt intake, dual flywheel
          launcher with two-stage gearing (1300+ rpm), and mobile drivetrain
        </li>
        <li>
          <strong>Software:</strong> Modular RobotC functions for navigation,
          intake sequencing, and randomized shot execution
        </li>
        <li>
          <strong>Sensing:</strong> Colour sensor for ball detection and gyro for
          accurate rotational control
        </li>
        <li>
          <strong>Testing & Iteration:</strong> Reduced drift and conveyor jamming
          through drive tuning, tray redesign, and motor upgrades
        </li>
      </ul>
    </div>
  </div>

  <!-- Row 4: Outcome (text-focused) -->
  <div class="project-row reverse">
    <div class="project-image">
      <img src="{{ '/assets/images/tennis_robot/final.png' | relative_url }}"
           alt="Tennis training robot final">
    </div>

    <div class="project-text">
      <h3>Outcome</h3>
      <p>
        The final system delivered automated, multi-round tennis training with
        randomized ball launches and user-configurable shot parameters. While
        some constraints limited full autonomy, the prototype demonstrated strong
        feasibility as a customizable and affordable training aid.
      </p>
      <p>
        The project highlighted the importance of coordinated mechanical design,
        sensing, and software logic in achieving reliable real-world robotic
        behavior.
      </p>

      <p>
        <strong>Skills & Tools:</strong>
        LEGO EV3 Mindstorms, RobotC, mechanical prototyping, sensor integration,
        testing and debugging, team collaboration, project planning
      </p>
    </div>
  </div>

</div>
