# Taha Gamal Alieldin — Portfolio

Single-page portfolio site for a mechatronics engineer working across automation, robotics, and machine learning.

**Live:** https://tahajralieldin-ship-it.github.io/taha-alieldin-portfolio/

## Selected work

| Project | Stack |
|---|---|
| AI-Enhanced Autonomous Surveying Swarm — graduation project, ASRT-funded | ROS 2 Humble, Nav2, Gazebo, Voronoi coverage, CycloneDDS |
| Automated Production Line | Siemens S7-1200, TIA Portal, Factory I/O, SIMATIC HMI |
| Pneumatic Humanoid Arm (3-DOF) | Pneumatics, Arduino, Automation Studio |
| Real-Time Human Behavior Recognition | CNN-LSTM, OpenCV |
| Furuta Pendulum Control System | MATLAB/Simulink, LQR, SimMechanics, hardware-in-the-loop |
| Mobile-Robot Chassis Plate | FEA, CalculiX/MATLAB, Inventor |

Every project links to its full technical report in `reports/`.

## Built with

Static HTML, CSS, and vanilla JavaScript — no build step, no dependencies. The hero background is a Voronoi animation drawn on `<canvas>`. Type is Space Grotesk, Inter, and IBM Plex Mono. The entire colour theme runs off CSS variables at the top of `index.html` (`--bg`, `--accent`, `--text`), so the whole site re-themes from a few lines.

## Structure

```
├── index.html                    # the entire site
├── Taha_Gamal_Alieldin_CV.pdf    # CV served by the download button
├── images/                       # project photos
└── reports/                      # project reports (PDF)
```

## Deployment

GitHub Pages, deployed from `main` at root. Any commit to `main` goes live in about a minute.

## Contact

- tahajralieldin@gmail.com
- [LinkedIn](https://www.linkedin.com/in/taha-alieldin-479b0918b/)
- Cairo, Egypt
