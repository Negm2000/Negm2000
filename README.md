<img src="assets/header.svg" alt="Hello, world. I'm Karim. C# for industrial hardware, robotics, embedded systems, computer vision, neural networks." width="100%">

<p align="center">
<a href="projects/beko-connector-inspection.md"><img src="assets/projects/beko.gif" width="270" alt="Beko connector check. Finds missing cables on Beko oven control boards. Caught 21 of 25 real defects, passed 98.2% of good connectors. PyTorch - team of 4, I built the per-connector anomaly detection - drawing (photos under NDA). Picture: Drawing of a control board with four connectors; the scan marks the one with no cable."></a>
<a href="https://github.com/Negm2000/CADBOARD"><img src="assets/projects/cadboard.gif" width="270" alt="CADBOARD. A camera checks a part against its CAD drawing and marks what&#x27;s wrong. Python, OpenCV - team of 2. Picture: A CAD drawing fitted onto a camera image of a cardboard part, with the creases checked."></a>
<a href="https://github.com/Negm2000/ros2-mecanum-bot"><img src="assets/projects/robot.png" width="270" alt="Tour-guide robot. A robot that can drive in any direction. I wrote the motor interface, the odometry and the visitor screen. C++, ROS 2 - B.Sc. graduation project (A+), team of 5. Picture: Drive base of the tour-guide robot on four mecanum wheels."></a>
<a href="https://github.com/Negm2000/Seesaw"><img src="assets/projects/seesaw.gif" width="270" alt="Seesaw balancing. A cart keeps a seesaw level that would tip over on its own, on real lab hardware. MATLAB, Simulink - team of 4, I designed one controller and the test protocol. Picture: A cart driving back and forth on a seesaw to keep it level."></a>
<a href="https://github.com/Negm2000/Xonix-x86-assembly"><img src="assets/projects/xonix.gif" width="270" alt="Xonix. Two-player arcade game written by hand in assembly, about 4,800 lines. x86 assembly, runs in DOS. Picture: Two-player Xonix running in DOSBox."></a>
<a href="https://github.com/Negm2000/RNN-pirate-pain-classification"><img src="assets/projects/pain.png" width="270" alt="Pain from motion. Estimates pain level from motion-capture recordings. 0.960 F1 on Kaggle. PyTorch - team of 4, I built the model. Picture: Joint movement over time for three pain levels."></a>
<a href="https://github.com/Negm2000/cancer-histopathology"><img src="assets/projects/cancer.png" width="270" alt="Cancer subtypes. Tells breast-cancer subtypes apart from microscope images; the heat map shows where the model looked. 4th of 196. PyTorch - team of 4. Picture: Tissue sample next to a heat map of where the model looked."></a>
<a href="https://github.com/Negm2000/ATmega32-Star-Framework"><img src="assets/projects/drivers.gif" width="270" alt="Driver framework. Drivers for a microcontroller&#x27;s timer, serial port and display, written from the datasheet. C, ATmega32. Picture: A clock ticking on a character display driven by a simulated microcontroller."></a>
<a href="https://github.com/Negm2000/Tram-DC-Drive-Simulink"><img src="assets/projects/tram.png" width="270" alt="Tram drive. Speed control for the motor of a 25-tonne tram, in simulation. Simulink. Picture: Plot of a tram&#x27;s measured speed following the requested speed."></a>
<a href="https://github.com/Negm2000/AVR-Traffic-Light"><img src="assets/projects/traffic.gif" width="270" alt="Traffic light. Traffic light with a pedestrian button, running on a bare microcontroller. C, ATmega32 - my own timer and interrupt drivers. Picture: Simulated traffic-light circuit reacting to the pedestrian button."></a>
<a href="https://github.com/Negm2000/exam-autograder"><img src="assets/projects/exam.png" width="270" alt="Exam auto-grader. Grades multiple-choice exam sheets from phone photos. Python, OpenCV - led a team of 4, wrote the bubble-sheet reader. Picture: Photo of an exam sheet and the same sheet with the chosen answers marked."></a>
<a href="https://github.com/Negm2000/snakes-and-ladders-cpp"><img src="assets/projects/snakes.png" width="270" alt="Snakes &amp; Ladders. Four-player game with Monopoly-style cards and a board editor. C++ - team of 4, I wrote the play-mode actions and save/load. Picture: Snakes and Ladders board with ladders, snakes and cards."></a>
</p>

- **Now:** R&D Software Engineer at Danfoss, working on the PC software used to commission and diagnose servo drives (C#, .NET, WPF/MVVM), tested on real drives over EtherCAT, PROFINET and POWERLINK. That code is closed source, so what's here is university and personal work.
- **Studying:** M.Sc. Automation and Control Engineering at Politecnico di Milano. B.Sc. Mechatronics, Cairo University.

<img src="assets/now.svg" alt="Pixel art: PC software sending commands to a servo drive that spins a motor" width="100%">

<details>
<summary><b>All projects, with the technical details</b></summary>

| Project | What it is | Stack |
|---|---|---|
| [CADBOARD](https://github.com/Negm2000/CADBOARD) | Checks a part against its DXF drawing through an industrial camera and flags four defect types; homography alignment to 3-5 px error. | Python, OpenCV |
| [PCB connector inspection for Beko Europe](projects/beko-connector-inspection.md) (code private, client data under NDA) | Industrial project with Beko's oven plant: per-connector EfficientAD anomaly detection for missing cables. In the team's two-stage pipeline it caught 21 of 25 real defects while passing 98.2% of good connectors. | PyTorch, OpenCV |
| [RNN-pirate-pain-classification](https://github.com/Negm2000/RNN-pirate-pain-classification) | Pain-level classification from motion-capture time series with heavy class imbalance, 0.960 F1 on Kaggle. | PyTorch |
| [IACV](https://github.com/Negm2000/IACV) | Camera calibration and a metric 3D reconstruction of a church vault from a single uncalibrated photo. | MATLAB |
| [exam-autograder](https://github.com/Negm2000/exam-autograder) | Grades multiple-choice bubble sheets from phone photos with classical image processing. Team project; I wrote the bubble-sheet pipeline. | Python, OpenCV |
| [Xonix-x86-assembly](https://github.com/Negm2000/Xonix-x86-assembly) | Two-player arcade game written by hand in 16-bit x86 assembly for DOS, about 4,800 lines (2022). | x86 assembly |
| [ros2-mecanum-bot](https://github.com/Negm2000/ros2-mecanum-bot) | `ros2_control` hardware interface over serial and wheel odometry for a mecanum tour-guide robot. B.Sc. graduation project (A+). | C++, ROS 2 |
| [ATmega32-Star-Framework](https://github.com/Negm2000/ATmega32-Star-Framework) | Bare-metal GPIO, timer, UART and LCD drivers for the ATmega32, written from the datasheet. | C |
| [AVR-Traffic-Light](https://github.com/Negm2000/AVR-Traffic-Light) | Traffic light with a pedestrian button on an ATmega32, driven by a timer and an external interrupt. Udacity EgFWD Embedded Systems track. | C |
| [Terminal-Payment-Simulator](https://github.com/Negm2000/Terminal-Payment-Simulator) | Card, terminal and server modules of a payment flow in C, with Luhn and expiry checks. Udacity EgFWD Embedded Systems track. | C |
| [Seesaw](https://github.com/Negm2000/Seesaw) | Balancing an open-loop-unstable cart and seesaw on real Quanser hardware. I designed the pole-placement controller and observer and wrote the test protocol used to compare all controllers. | MATLAB, Simulink |
| [Tram-DC-Drive-Simulink](https://github.com/Negm2000/Tram-DC-Drive-Simulink) | DC traction drive for a 25 t tram with cascaded current/speed control and field weakening. | Simulink |
| [Networked-Control](https://github.com/Negm2000/Networked-Control) | Centralized vs. decentralized vs. distributed LMI control of coupled pendula. | MATLAB, YALMIP |
| [cancer-histopathology](https://github.com/Negm2000/cancer-histopathology) | Team entry that placed 4th of 196 in breast-cancer subtype classification. | PyTorch |
| [Danfoss-Challenge](https://github.com/Negm2000/Danfoss-Challenge) | Log parser that turns messy, multi-line log files into JSON, streaming line by line so memory stays flat on very large files. | C# |
| [snakes-and-ladders-cpp](https://github.com/Negm2000/snakes-and-ladders-cpp) | Four-player Snakes & Ladders with Monopoly-style cards, power-ups and a board editor. Team course project; I wrote the play-mode actions and save/load. | C++ |

</details>

<p align="center">
<a href="https://www.linkedin.com/in/karim-y-negm/"><img src="assets/btn_linkedin.svg" alt="LinkedIn" height="60"></a>
<a href="mailto:karim.y.negm@gmail.com"><img src="assets/btn_email.svg" alt="karim.y.negm@gmail.com" height="60"></a>
</p>

<img src="assets/footer.svg" alt="Pixel art: a yellow tram passing the Milan skyline at night" width="100%">
