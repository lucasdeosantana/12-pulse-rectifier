# Three-Phase 12-Pulse Rectifiers

Rectifiers are devices that convert **alternating current (AC)** into **direct current (DC)**. There are several types, such as:

- Half-wave rectifiers  
- Full-wave rectifiers  
- Three-phase half-wave rectifiers  
- Three-phase full-wave rectifiers (*six-pulse*)  
- Complementary three-phase full-wave rectifiers (*twelve-pulse*)  

Currently, rectifiers used in railway traction systems (such as metro and train lines) are typically **12-pulse rectifiers**. Since this is a less commonly understood system with very interesting behavior, this document describes its operation.

---

## Notes

All waveforms and equations presented here consider:

- Ideal diode rectifiers  
- Purely resistive loads  

Although real systems do not meet these conditions, this simplification allows for clearer understanding.

---

## Three-Phase Systems with Phase Shift

Three-phase systems use three conductors with voltages phase-shifted by **120°** relative to each other.

To create a **12-pulse rectifier**, a second transformer secondary winding is added, introducing a **30° phase shift** relative to the first.

As a result:

- Two groups of three-phase voltages are created  
- Each group has **120° phase displacement internally**  
- The groups are shifted by **30° relative to each other**  

This produces a total of **six waveforms**, enabling 12-pulse operation.

---

## Six-Pulse vs Twelve-Pulse Rectifiers

By analyzing the diode connections, only the **maximum instantaneous voltages** are conducted.

### Key differences:

- The **12-pulse system** produces a waveform with a **larger effective area**  
- This leads to **higher efficiency**  
- The **RMS voltage** is directly related to the waveform area  
---

## Average DC Voltage

The average DC voltage can be understood as:

1. Calculate the area under the rectified waveform  
2. Transform this area into an equivalent rectangle over time  
3. The height of this rectangle represents the **average DC voltage**

---

## Ripple in DC Output

The main advantage of a **12-pulse rectifier** over a **6-pulse rectifier** is the reduction of ripple.

### Observations:

- In a single cycle, ripple differences are already visible  
- Over longer time periods, the difference becomes more evident  

### Results:

- Smoother DC output  
- Higher ripple frequency  
- Lower ripple amplitude  
---

## Advantages of 12-Pulse Rectifiers

- Reduced harmonic distortion  
- Improved power quality  
- Lower filtering requirements  
- Better performance in high-power applications  
---

## Applications

- Railway traction systems (metro and trains)  
- High-power industrial drives  
- HVDC systems  
- Heavy industry (mining, steel plants)  

---

## Summary

A **12-pulse rectifier** improves significantly over a 6-pulse design by:

- Combining two phase-shifted three-phase systems  
- Increasing output quality  
- Reducing ripple and harmonics  

This makes it ideal for **high-power and high-performance electrical systems**.

See my article in: ![https://www.linkedin.com/pulse/rectificadores-trif%25C3%25A1sicos-de-12-pulsos-lucas-de-oliveira-santana-03smf/?trackingId=3ufZTKNESlyrVgeb3Bzd7Q%3D%3Dhttps://www.linkedin.com/pulse/rectificadores-trif%25C3%25A1sicos-de-12-pulsos-lucas-de-oliveira-santana-03smf/?trackingId=3ufZTKNESlyrVgeb3Bzd7Q%3D%3D]
