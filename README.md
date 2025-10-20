# Projects

This section outlines key hardware and software projects completed during my bachelor's degree studies.

---

## Honours Thesis: Effective Hardware Block Design Modifications: Impact on Neural Network Performance (2024)

* Researched and implemented on-FPGA neural network optimization by transitioning a Binarized Neural Network (BNN) to a Ternary Neural Network (TNN) via a weight randomization technique.
* Achieved a **12.5% model accuracy improvement** (from 73% to 82.1%) by implementing 10% weight randomization in the **Brevitas** framework.
* Validated the hardware cost of the optimization using the **FINN** framework for High-Level Synthesis (HLS), confirming the performance gain was achieved with only a minor increase in hardware resources (**7.1% in LUTs and 4.325% in FFs**).
* Utilized **PyTorch**, **Brevitas**, and **FINN** to bridge software simulations with hardware synthesis estimates.

---

## Jacaranda Flame Consulting: Squealing Pig Model Project (Nov 2023 – Feb 2024)

* Collaborated in a multidisciplinary team of 5 engineers to develop an interactive pig model simulating realistic responses for veterinary training.
* **Led the hardware implementation** of the mobility system by adapting and modifying components (motors, steering, chassis) from a children’s ride-on car, achieving stable remote-controlled movement.
* Designed and integrated a pressure-sensitive squealing mechanism using **Arduino**, thin-film pressure sensors, and **Bluetooth** connectivity to an Android app for interactive auditory feedback.
* Constructed and refined hardware prototypes, including custom platform design and component mounting (e.g., thread inserts for the pig model, embedded motor mounts), ensuring robustness and ease of maintenance.
* Managed component selection, circuit assembly, and cable management within budget and project constraints.

---

## SDR 2.0: Low-Cost WSPR Receiver Design (ELEC3607 Project, 2023)

* Designed and simulated the analog signal chain for a Software Defined Radio (SDR) receiver targeting the 7.04MHz WSPR (Weak Signal Propagation Reporter) band.
* Engineered the **Tayloe detector (mixer)** stage to successfully down-convert the 7.0401 MHz carrier frequency to the 1.4 kHz - 1.6 kHz audio range required for digital processing.
* Redesigned the **audio amplifier** stage using an active low-pass filter configuration to boost the output voltage (from 0.7V) to meet the input requirements of the selected ADC.
* Performed **overall circuit simulation using LTspice**, validating that the analog front-end achieved the target frequency range and an output level of 0.957 Vrms.
* Contributed to the 4-layer PCB design by creating the **schematic capture and layout** for the mixer and audio amplifier sections using **KiCAD**.

---

## Water Quality Monitoring Solution with Community Engagement (ENGG3851 Project, 2022)

* Contributed to a proposed solution for the Illawarra Local Aboriginal Land Council (ILALC) to monitor creek water quality using a three-tiered approach: hardware (data loggers), software (app/visualization), and community engagement (tours).
* Involved in the **hardware design concept**, including the selection of professional-grade sensors (**HOBO MX2001** for water level, **HOBO MX2501** for pH/temp) and the **CAD design** of a buoyant, waterproof acrylic casing to house them.
* Conducted a **hardware feasibility study** using Newtonian mechanics and fluid dynamics to analyze the forces (drag, buoyancy, friction) acting on the submerged data logger and its cement block anchor, determining optimal dimensions (0.095m x 0.095m x 0.762m block) for stability in worst-case flow conditions (2.5 m/s).
* Assisted in defining the system architecture for data transmission from sensors via **Bluetooth/Internet** to a private cloud database and subsequent visualization using **Python (Pandas/Matplotlib)**.

---

## Microsoft & USYD Digital Campus Transformation Project (ICPU1158 Project, 2024)

* Provided **key engineering analysis** within a 6-person team (Synergy Squad) evaluating the feasibility and implementation limitations of advanced AI technologies (like Microsoft Copilot) for the University of Sydney's digital campus transformation.
* Applied **design thinking methodologies** to identify stakeholder (students, staff) pain points related to AI adoption, infrastructure limitations, and the need for flexible learning.
* Co-developed potential solutions integrating AI tools, such as proposing a **Copilot-driven summarization bot** to help students catch up on missed content and recommending an **"opt-out" policy** for AI usage to foster autonomy.
* Contributed engineering perspectives to the final strategy report advising the university on navigating digital transformation, AI integration, and evolving learning trends.
