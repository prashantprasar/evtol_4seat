# 4-Pax VTOL Designed in CATIA

## Wing Aerodynamic Parameters

| Parameter | Value |
|------------|--------|
| Airfoil | MH 114 |
| Wingspan | 11000 mm |
| Root Chord | 1720 mm |
| Tip Chord | 860 mm |
| Taper Ratio | 0.50 |
| Dihedral Angle | 0° |
| Wing Incidence | 2° |
| Geometric Twist (Washout) | 0° |

### Wing Notes

- MH 114 airfoil selected for efficient low-Reynolds-number cruise performance.
- Straight, untwisted wing simplifies manufacturing and structural design.
- Zero dihedral is adopted due to the inherent stability provided by the distributed lift propulsion system and flight control computers.
- A moderate taper ratio of 0.70 provides a good balance between structural efficiency and aerodynamic performance.

---

## Cruise Propeller

| Parameter | Value |
|------------|--------|
| Diameter | 2500 mm |
| Number of Blades | 5 |
| Hub Diameter | 350 mm |
| Root Blade Pitch | 32° |
| Tip Blade Pitch | 12° |
| Total Blade Twist | 20° |
| Estimated Cruise RPM | 1500–1800 rpm |

---


## Vertical Lift Propellers

| Parameter | Value |
|------------|--------|
| Quantity | 8 |
| Diameter | 2550 mm |
| Radius | 1275 mm |
| Number of Blades | 3 |
| Hub Diameter | 300 mm |
| Root Blade Pitch | 28° |
| Tip Blade Pitch | 10° |
| Total Blade Twist | 18° |
| Estimated Hover RPM | 900–1200 rpm |
| Disk Area (Each Rotor) | 5.11 m² |
| Total Rotor Disk Area | 40.85 m² |
| Disk Loading | 58.8 kg/m² (576.4 N/m²) |

### Lift Rotor Arrangement

- Four lift rotors mounted on each wing.
- Adjacent rotors rotate in opposite directions to minimize net torque.
- Large-diameter rotors reduce disk loading, improving hover efficiency and reducing acoustic noise.

### Lift Rotor Arrangement

- Four lift rotors mounted on each wing.
- Adjacent rotors rotate in opposite directions to minimize net torque.
- Fixed-pitch rotors driven by independent electric motors.

## Stabilizer Design

**Location**

- Y-location: 2800 mm from wing leading edge (LE)

### Horizontal Stabilizer

| Parameter | Value |
|------------|--------|
| Span | 2400 mm |
| Chord | 500 mm |

### Vertical Stabilizer

| Parameter | Value |
|------------|--------|
| Span | 1000 mm |
| Root Chord | 500 mm |
| Tip Chord | 300 mm |

## Fuselage Sizing

| Parameter | Value |
|------------|--------|
| Cross Section | 1800 mm (height) × 1400 mm (width) 2.5m long with this crosssection tapered on front and rear. |
| Overall Length | 6100 mm |

## Propulsion and Power System

### Energy Storage
- Main Battery Pack Volume: **0.96 m³**
- Battery integrated within the fuselage floor section to maintain a low center of gravity and improve stability.

### Cruise Propulsion
- Configuration: **Single Cruise Propeller**
- Diameter: **2500 mm**
- Function: Provides efficient forward thrust during cruise flight, reducing power consumption compared to lift rotors.

### Vertical Lift System
- Configuration: **8 Lift Propellers**
- Diameter: **1500 mm each**
- Total Lift Rotor Disk Area:

  \[
  A_{total} = 8 \times \pi \left(\frac{1.5}{2}\right)^2
  = 14.14\;m^2
  \]

- Function: Generates vertical thrust for takeoff, landing, and hover operations.

### Propulsion Architecture
- Type: **Lift + Cruise eVTOL**
- Lift Rotors: Dedicated vertical takeoff and landing
- Cruise Propeller: Dedicated forward flight propulsion
- Advantages:
  - Simpler control system than tilt-rotor configurations
  - Higher cruise efficiency
  - Reduced mechanical complexity
  - Improved safety through propulsion redundancy

| Parameter | Value |
|------------|--------|
| Battery Volume | 0.96 m³ |
| Cruise Propeller Diameter | 2500 mm |
| Number of Lift Propellers | 8 |
| Lift Propeller Diameter | 1500 mm |
| Total Lift Disk Area | 14.14 m² |
| Configuration | Lift + Cruise eVTOL |
---



## CATIA Rendering

### Isometric View

![Isometric View](render/iso.jpg)

### Three-Views Configuration
![Side View](render/side.jpg)
![Front View](render/front.jpg)
![Top View](render/top.jpg)


> **Note:** Conceptual 4-passenger eVTOL configuration developed and modeled in CATIA for preliminary design studies.