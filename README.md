<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/c3ef1c58-d932-441d-bf6f-6019c9e83c92" />Problem
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

## Visual Analysis

### Speed Profile Comparison
![Speed Comparison](images/combined_speed.png)

### Delta Time Evolution
![Delta Curve](images/delta_curve.png)
