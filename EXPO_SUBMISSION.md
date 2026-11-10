# Nomination — 10th Pakistan Industrial Expo 2026 (14–16 Nov, Expo Centre Lahore)

**Submitted by:** [Name, Designation] · [Department] · COMSATS University Islamabad, [Campus]
**Contact:** [email] · [phone]

---

## 1. Product / prototype name and brief description

**VoltLink Digital Twin: Smart EV Telematics & Battery Diagnostic Platform**

VoltLink is a real-time digital twin and diagnostics platform for electric two-wheelers (e-scooters and e-motorcycles). It mirrors a live vehicle as an interactive schematic showing the battery pack, BMS, motor controller and hub motor. It streams per-cell voltage and temperature for a 16-cell (16S, 60 V) lithium-ion pack, and it shows speed, current, pack voltage, state of charge, motor RPM and a range prediction based on the current discharge rate.

An AI health engine estimates battery State of Health (SOH), Remaining Useful Life (RUL) and an anomaly score. A rule-based safety layer reacts to faults automatically:

- **Thermal-runaway precursor:** when a cell passes 60 °C, the platform cuts the motor, opens the HV contactor, and alerts the rider and fleet operator.
- **Cell imbalance or weak cell:** the platform derates power to a limp mode, raises a maintenance ticket and recommends a service window.

Every event is written to a timestamped diagnostic log that can be exported.

**Value proposition:** it helps prevent battery fires, gives early warning of pack degradation and enables predictive maintenance. That lowers warranty and fleet operating costs for EV two-wheeler manufacturers, battery assemblers and delivery or ride-hailing fleets. The platform is designed to work alongside Chinese BMS and controller suppliers over standard CAN-bus telematics.

**Expo demo:** a live, interactive dashboard that runs offline on a laptop or large screen. One click switches between three scenarios: Normal Drive, Thermal Risk (cell 7 reaches 65 °C and the motor is cut off) and Cell Imbalance (cell 4 drops to 2.8 V and maintenance is advised).

## 2. Technology readiness and commercialization status

| Item | Status |
|---|---|
| **Technology Readiness Level** | **TRL 4**: the digital twin, diagnostics logic, safety-response rules and dashboard have been built and validated in a laboratory/simulated environment, using simulated BMS/CAN telemetry. |
| **Next milestone** | TRL 5–6: connect to a physical BMS and CAN bus on a test e-scooter, then run a pilot on a small fleet. |
| **IP status** | [e.g. none filed / invention disclosure planned / patent application no. ___] |
| **Commercialization status** | Pre-commercial prototype. We are looking for: (a) OEM pilot partners (EV two-wheeler and battery-pack manufacturers), (b) technology transfer or joint development with Chinese BMS/telematics companies, and (c) seed investment for hardware integration and field trials. |
| **Target market** | Pakistan's growing EV two-wheeler sector (NEV policy), battery-swap operators, and delivery and ride-hailing fleets. |
| **Business model** | Per-vehicle telematics licence (SaaS) plus an OEM integration fee. Optional hardware: a T-BOX/BMS gateway module. |

## 3. Relevant photographs

The `photos/` folder contains screenshots of the working prototype dashboard:

1. `photos/1-normal-drive.png`: live vehicle run with all indicators green and energy flowing from battery to motor
2. `photos/2-thermal-risk.png`: thermal-risk scenario, where cell C07 reaches 65 °C, a critical alert is raised and the motor cut-off safety protocol engages
3. `photos/3-cell-imbalance.png`: cell-imbalance scenario, where cell C04 drops to 2.80 V, limp mode engages and maintenance is advised

*(Add a photo of the team or a hardware test bench if available.)*

---

### Email text (ready to paste)

**Subject:** Nomination for 10th Pakistan Industrial Expo 2026: VoltLink Digital Twin (EV Battery Diagnostics)

Dear Sir/Madam,

In response to the call for nominations for the 10th Pakistan Industrial Expo 2026 (14–16 November, Expo Centre Lahore), please find our submission below.

**1. Product name and description:** VoltLink Digital Twin: Smart EV Telematics & Battery Diagnostic Platform. VoltLink is a real-time digital twin for electric two-wheelers. It monitors all 16 battery cells (voltage and temperature), drivetrain telemetry and predicted range. An AI health engine estimates battery State of Health and Remaining Useful Life. A safety layer automatically cuts the motor when it detects thermal-runaway risk, and it flags weak or imbalanced cells for maintenance. These functions help prevent battery fires and reduce fleet maintenance costs.

**2. Technology readiness and commercialization status:** TRL 4, validated in a laboratory/simulated environment. The next step is integration with a physical BMS/CAN bus and a fleet pilot (TRL 5–6). The product is a pre-commercial prototype. We are looking for OEM pilot partners, technology transfer or joint development with Chinese EV/BMS manufacturers, and investment.

**3. Photographs:** three screenshots of the working prototype are attached (normal drive, thermal-risk safety cut-off, and cell-imbalance diagnosis).

We will showcase a live interactive demonstration at the CUI stall.

Regards,
[Name]
[Designation, Department]
COMSATS University Islamabad, [Campus]
[Phone] · [Email]
