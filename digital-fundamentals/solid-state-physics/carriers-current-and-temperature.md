# Carriers, Current & Temperature
**Source:** ChipVerify - Digital Fundamentals

**Status:** Completed

---

## Learning Objectives

- [ ] How electrons and holes both contribute to current, through drift and diffusion
- [ ] Why higher temperature produces more carriers and more leakage
- [ ] Why higher temperature also slows carriers down, and how the two effects compete
- [ ] How temperature shows up in chip power budgets and timing sign-off

---

## My Answers

### 1. How do electrons and holes both contribute to current, through drift and diffusion?

My Answer:

Electrons and holes both contribute to current in semiconductors through drift and diffusion. Drift occurs when an electric field causes electrons and holes to move in opposite directions. Diffusion occurs when electrons and holes move from areas of high concentration to low concentration. Both processes allow electrical current to flow through a semiconductor.

### 2. Why does higher temperature produces more carriers and more leakage?

My Answer:

Higher temperatures give electrons more thermal energy, allowing more of them to move from the valence band to the conduction band, creating additional electron-hole pairs. These extra carriers increase leakage current because more electrons and holes can flow through a semiconductor even when a transistor is supposed to be off.

### 3. Why does higher temperature also slows carriers down, and how the two effects compete?

My Answer:

Higher temperatures cause atoms in a semiconductor to vibrate more, increasing collisions with electrons and holes, which reduces their mobility and slows them down. However, higher temperatures also generate more charge carriers. These effects compete because more carriers increase conductivity, while lower mobility reduces conductivity. The dominant effect depends on the semiconductor's doping and temperature.

### 4. How temperature shows up in chip power budgets and timing sign-off?

My Answer: 

Temperature affects both power consumption and timing in chips. Higher temperatures increase transistor leakage current, causing more static power consumption and heat. They can also reduce carrier mobility, slowing transistor switching and increasing propagation delay. During timing sign-off, engineers test chips under different temperature, voltage, and manufacturing conditions (PVT corners) to ensure the chip meets timing requirements and stays within its power budget.

---

## Practice Exercise

### A block leaks 10 mW at 25 °C. Assume a planning rule that leakage doubles for every 15 °C rise, and estimate its leakage at:

### 55 °C (a phone in a pocket)
**My Solution:** 
40 mW of leakage
### 85 °C (a busy laptop processor)
**My Solution:** 
160 mW of leakage
### 115 °C (a hot-corner sign-off temperature)
**My Solution:**
640 mW of leakage

---

## Summary

- Electrons and holes both carry current; they move in opposite directions but their currents add

- Drift is carrier motion driven by a field; diffusion is motion from crowded to sparse regions

- Electrons are about 3× more mobile than holes, which sets NMOS/PMOS sizing

- Higher temperature generates far more carriers, so leakage rises exponentially - doubling every 10 to 25 °C depending on process and mechanism

- Higher temperature also lowers mobility, so strongly ON transistors usually get slower

- At low supply voltages, temperature inversion can make the cold corner the slowest

- Power budgets and timing sign-off must be checked across the full temperature range

---

## Chapter Review

**Can I explain these concepts without looking?**

- [ ] Yes, I understand everything.
- [x] I need to review some concepts.

**Date Completed:** 11/09/2026