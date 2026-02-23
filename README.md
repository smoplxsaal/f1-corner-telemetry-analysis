
This project investigates how two drivers execute Turn 10 at Bahrain and quantifies where time delta is created within the corner.
Rather than comparing total lap time, the corner is decomposed into braking, rotation (minimum speed), and exit phases.

Methodology:
Telemetry extracted using FastF1
Push laps selected
Distance-aligned interpolation applied
Cumulative time delta computed
Corner segmented into braking, rotation, and exit
Key Findings:

Turn 10 contributed ~0.161s of the 0.879s total lap delta (~18%).
Braking efficiency and exit acceleration were primary contributors.
Higher minimum speed did not guarantee faster corner time.

Engineering Implications
Setup must support braking stability and rear traction.
Exit-focused execution materially impacts lap outcome.
Driving style influences setup direction and tyre behavior.

Limitations
Single lap sample
Fuel load not normalized
ERS deployment not directly measured

Why This Matters:
Corner-level performance analysis helps identify how driving style and vehicle balance influence lap time. Heavy braking zones such as Turn 10 are sensitive to:
Brake stability
Rear rotation behavior
Traction on exit
Tyre temperature evolution
Quantifying time gain within a single corner enables engineers to determine whether performance differences stem from braking execution, mid-corner balance, or exit efficiency.

Visual Analysis
Speed Profile Comparison

<img width="989" height="590" alt="59068b63-cbf0-4e64-afa9-a40e91a7d772" src="https://github.com/user-attachments/assets/08887342-8650-4e0a-b96c-8e0a58def0ee" />

This illustrates braking approach, minimum speed, and exit acceleration differences between the two drivers.

Delta Time Evolution

<img width="989" height="590" alt="5e147eb3-287d-4cf5-b450-981185eddf2a" src="https://github.com/user-attachments/assets/860a7e67-29b9-4a89-a438-9a0edb5ed527" />


The delta curve quantifies where time is gained across the corner.
Turn 10 contributed ~0.161s (~18%) of total lap delta.
