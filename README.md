# Custom-STM32-PCB
This project implements a reference STM32 microcontroller design on a custom PCB from Phil's Lab.

Key design goals:

Gain familiarity with professional PCB design workflows in Altium.

Apply schematic capture, layout, and design rule checking (DRC).

Practice power distribution, decoupling, and trace routing strategies used in real-world hardware.

Schematic Capture: Imported and adapted STM32 reference design in Altium.

PCB Layout:

Routed power and signal traces with attention to noise reduction.

Separated analog and digital grounds where appropriate.

Used Altium’s DRC (Design Rule Check) to validate design before prototyping.
<img width="1228" height="762" alt="image" src="https://github.com/user-attachments/assets/612376ce-c72f-44d5-a136-acd85887280e" />
<img width="723" height="718" alt="image" src="https://github.com/user-attachments/assets/14a7b25a-9fb2-4aae-bf8a-6f9d9e05e07c" />
<img width="764" height="729" alt="image" src="https://github.com/user-attachments/assets/5e890204-151b-44c5-8d9c-b79d1be004cb" />
<img width="717" height="713" alt="image" src="https://github.com/user-attachments/assets/faa00c5d-63ea-4331-b82d-d07797be6e75" />

# What?
- The goal was to design and fabricate a custom PCB featuring the STM32F4 microcontroller, both to learn PCB workflows and to create a platform for future embedded projects.
# How?
- Recreated the STM32 schematic in Altium Designer following industry reference designs.
- Routed power and differential signal traces with proper grounding strategies to reduce EMI.
- Applied Design Rule Checks (DRC) to ensure the board was manufacturable.
# Results
- Gained hands-on experience with schematic hierarchy, net labeling, and Altium layout best practices.
- Learned about EMI shielding using vias, and how via stitching and via holes improve current return paths and strengthen layer-to-layer connectivity.
