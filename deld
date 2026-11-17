# DELD Capstone Project
# Traffic Light Controller Using MOD-N Counter

## 1. Introduction
A Traffic Light Controller is a digital electronic system used to manage traffic at road intersections. It controls Red, Yellow and Green lights in a fixed sequence.

This project combines a Finite State Machine (FSM) with a MOD-N counter to control the timing of traffic signals.

## 2. Objectives
- To design a digital traffic light controller.
- To understand the working of a MOD-N counter.
- To implement sequential logic circuits.
- To understand state transitions.
- To control traffic lights using digital logic.

## 3. Components Required
- IC 555 Timer (clock pulse generation)
- IC 7476 (JK Flip-Flop)
- IC 7490 (Decade Counter) or equivalent counter implementation
- Logic gates (AND, OR, NOT)
- Red LED
- Yellow LED
- Green LED
- Resistors
- Breadboard
- Connecting wires
- Power supply

## 4. Block Diagram

Clock Generator → MOD-N Counter → State Controller (FSM) → Traffic Lights

## 5. Working Principle

The traffic light controller operates in four states:

| State | North-South Signal | East-West Signal |
|---|---|---|
| S0 | Green | Red |
| S1 | Yellow | Red |
| S2 | Red | Green |
| S3 | Red | Yellow |

The controller changes its state after a predefined time interval.

The MOD-N counter counts clock pulses and generates a signal when the required count is reached. This signal triggers the next state transition.

## 6. State Transition Sequence

S0 → S1 → S2 → S3 → S0

The sequence repeats continuously.

## 7. MOD-N Counter

A MOD-N counter counts from 0 to N−1 and then resets to 0.

For example, a MOD-10 counter counts:

0 → 1 → 2 → 3 → 4 → 5 → 6 → 7 → 8 → 9 → 0

The counter provides timing intervals for the traffic light controller.

## 8. Truth Table

| State | Q1 | Q0 | NS | EW |
|---|---|---|---|---|
| S0 | 0 | 0 | Green | Red |
| S1 | 0 | 1 | Yellow | Red |
| S2 | 1 | 0 | Red | Green |
| S3 | 1 | 1 | Red | Yellow |

## 9. Applications
- Road traffic management.
- Traffic signal automation.
- Digital control systems.
- Embedded system learning.
- Sequential circuit applications.

## 10. Advantages
- Automatic operation.
- Reduces manual traffic control.
- Demonstrates sequential logic.
- Easy to understand and implement as a laboratory prototype.

## 11. Conclusion

The Traffic Light Controller using a MOD-N Counter demonstrates the application of digital electronics and sequential circuits. The project combines counters, flip-flops, logic gates and finite state machines to control traffic signals automatically.

**Note:** This is an educational prototype design, not a certified road traffic control system.

## 12. Future Scope
- Add pedestrian crossing signals.
- Add vehicle detection sensors.
- Implement emergency vehicle priority.
- Use microcontrollers for advanced control.
