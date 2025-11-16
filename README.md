# MAGNETIC BOUNDARY CONDITIONS:

## Introduction

Magnetic boundary conditions describe how magnetic fields behave at the interface of two different materials. The key conditions are that the normal component of magnetic flux density is continuous across the boundary, while the tangential component of magnetic field intensity is discontinuous if there is a surface current present. If no surface current exists, the tangential component of magnetic field intensity is also continuous. 

<img width="529" height="485" alt="boundary-conditions" src="https://github.com/user-attachments/assets/f30a4da0-2f97-405f-9a1d-a108262bdaaa" />


## 1. Tangential Magnetic Field Boundary Condition
### Condition

(H2 − H1) (tangential) = K

### Special Case (No Surface Current)

H1 (tangential) = H2 (tangential)

### Meaning

The tangential (parallel) component of the magnetic field is continuous unless a surface current exists at the boundary.

### Real-Life Examples

### i) Induction Cooktop:
Strong AC surface currents produce tangential magnetic fields that heat the pan.

<img width="1350" height="1440" alt="Induction cooktop (stove)" src="https://github.com/user-attachments/assets/5409f1f3-bfd8-4e0b-a670-cda10835495a" />

### ii) PCB Microstrip Lines:
High-frequency signals cause surface currents that influence tangential H and signal integrity.

## 2. Normal Magnetic Flux Boundary Condition
### Condition

B1 (normal) = B2 (normal)

### Meaning

Normal magnetic flux density is continuous because magnetic monopoles do not exist.

### Real-Life Examples

### i) Magnetic fields passing from air into a transformer core 
Flux moves smoothly from air into the steel core; normal B remains continuous.


### ii) Loudspeaker Magnet: Magnetic field enters metal parts without breaking, focusing flux onto the coil.

### iii) Earth’s Magnetic Field: Magnetic lines pass from atmosphere into ground continuously.

## 3. Magnetic Boundary Conditions for a Perfect Conductor
### Conditions

H (tangential) = 0
B (normal) = 0

### Meaning

A perfect conductor expels magnetic fields.
Real conductors behave similarly at high frequencies due to skin effect.

### Real-Life Examples

### i) Microwave Oven Shielding: Metal walls block magnetic fields.

### ii)Copper Shields in Cables: Prevent magnetic noise from entering.

### iii) High-Frequency AC Wires: Magnetic fields stay only near the surface (skin effect).

## 4. Summary Table
# Boundary Condition	Formula	Meaning	Real-Life Example
Tangential H continuity	(H2 − H1) (tangential) = K	Jump due to surface current	Copper wire
Tangential H (no current)	H1 (tangential) = H2 (tangential)	Continuous	Dielectric interfaces
Normal B continuity	B1 (normal) = B2 (normal)	Flux continuous	Transformer
Tangential H at perfect conductor	H (tangential) = 0	No field inside	Microwave shield
Normal B at perfect conductor
