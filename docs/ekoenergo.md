# ekoenergo – Solar Water Heating Inverter

This inverter is specifically designed to optimize the use of photovoltaic (PV) panels for powering a standard electric heating element in a domestic hot water (DHW) storage tank (boiler). It converts direct current (DC) from PV panels into alternating current (AC) with a 50 Hz rectangular waveform and a variable duty cycle ranging from approximately **3% to 98%**.

In automatic mode, the inverter continuously measures **voltage and current** to calculate the output power of the PV panels. It dynamically adjusts the duty cycle to maintain the **Maximum Power Point Tracking (MPPT)**, ensuring optimal energy extraction.

Without this feature, a fixed full-duty load on the panels — especially in **low-light conditions** — would cause voltage to drop, resulting in minimal power output. Thanks to MPPT, the inverter excels even in weak or fluctuating sunlight, such as during **early mornings, evenings, cloudy skies, or partial shading**.

> **Example:**  
> If the duty cycle is manually set to 100% under weak sunlight, you might get only **300 W** from a nominal **750 W** PV system. With MPPT, the inverter adjusts the load to extract significantly more energy.

---

## Installation and Usage Guidelines

- Place the inverter as **close to the boiler** as possible.
- Connect **only resistive loads** to the output terminals (e.g., heating element, immersion heater, standard boiler **without** electronics or contactors).
- Do **not** connect the output to:
  - Ground
  - Other inverters
  - External voltage sources

---

## Technical Specifications

| Parameter                            | Value                                |
|--------------------------------------|--------------------------------------|
| **Max PV input voltage (open circuit)** | 400 V DC                            |
| **Continuous output current**         | 8–9 A                                |
| **Maximum output current**            | 10 A                                 |
| **Maximum output power**              | approx. 2800 W                       |
| **Recommended PV array**             | 8 panels, 260–280 Wp each            |
| **Recommended heating element**      | 2–3 kW / 230 V                       |
| **Minimum resistive load**           | approx. 15 Ω                         |


---


