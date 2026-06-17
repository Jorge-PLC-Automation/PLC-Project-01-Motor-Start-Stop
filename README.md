# PLC-Project-01-Motor-Start-Stop
IEC 61131-3 Ladder Logic - Motor Start/Stop Seal-In Circuit using OpenPLC Editor
# PLC Project 01 — Motor Start/Stop Seal-In Circuit

**Language:** Ladder Diagram (LD) | IEC 61131-3  
**Tool:** OpenPLC Editor  
**Status:** ✅ Complete & Simulated  
**Difficulty:** ⭐☆☆☆☆ Beginner  

---

## 📋 Project Overview

The "Hello World" of PLC programming. This project implements the 
classic industrial motor control circuit — the **seal-in (latching) 
circuit** — found in every factory, pump station, and conveyor system 
on earth.

### Behavior
- Press **START** → Motor turns ON and locks itself on
- Press **STOP** → Motor turns OFF
- **Power loss** → Motor stays OFF (fail-safe)

---

## 🔌 I/O Variable Map

| Variable | Class | Type | Description |
|----------|-------|------|-------------|
| `Start` | Input | BOOL | Normally Open start pushbutton |
| `Stop` | Input | BOOL | Normally Closed stop pushbutton |
| `Motor` | Output | BOOL | Motor contactor output |

---

## 📐 Ladder Logic Structure
## 🧠 Key Concepts Learned

- **Normally Open (NO) contact** `[ ]` — passes power when TRUE
- **Normally Closed (NC) contact** `[/]` — passes power when FALSE  
- **Output Coil** `( )` — energizes when rung is TRUE
- **Seal-in contact** — parallel Motor contact that latches output ON
- **Variable declaration** — Input/Output BOOL types in OpenPLC
- **Simulation & debug** — live rung power-flow visualization

---

## 🏭 Real-World Applications

This exact circuit controls:
- Industrial conveyor belts
- Water pump stations  
- HVAC fan motors
- Oil field pump jacks
- Manufacturing assembly lines

---

## 🛠️ Tools Used

- **OpenPLC Editor** — IEC 61131-3 programming environment
- **OpenPLC Simulator** — built-in logic simulation & debug

---

## 📸 Screenshots

*Simulation screenshot — ladder logic with live power flow*

> Screenshots folder coming soon

---

## 👤 Author

**Jorge Gonzalez** — PLC & Automation Self-Study Lab  
github.com/Jorge-PLC-Automation
