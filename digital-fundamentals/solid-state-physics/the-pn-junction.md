# The PN Junction
**Source:** ChipVerify - Digital Fundamentals

**Status:** Completed

---

## Learning Objectives

- [ ] How does the depletion region and built-in field form when p-type meets n-type
- [ ] What does forward bias and reverse bias do to the depletion region and the current
- [ ] How does doping and voltage set the depletion width and junction capacitance
- [ ] Where do p-n junctions hide inside every CMOS standard cell


---

## My Answers

### 1. How does the depletion region and built-in field form when p-type meets n-type?

My Answer:

When p-type and n-type semiconductors meet, electrons diffuse from the n-type to the p-type region, while holes diffuse in the opposite direction. Electrons and holes recombine near the junction, leaving behind fixed positive ions on the n-side and negative ions on the p-side. This creates a depletion region with very few mobile charge carriers. The fixed ions produce a built-in electric field pointing from the n-side to the p-side, which opposes further diffusion.

### 2. What does forward bias and reverse bias do to the depletion region and the current?

My Answer:

Forward bias makes the depletion region narrower, allowing more current to flow through the P-N junction. Reverse bias makes the depletion region wider, preventing most current from flowing, except for a small leakage current.

### 3. How does doping and voltage set the depletion width and junction capacitance?

My Answer:

Higher doping levels make the depletion region narrower, increasing junction capacitance. Lower doping levels make the depletion region wider, decreasing capacitance. Increasing reverse-bias voltage also widens the depletion region, decreasing junction capacitance.

### 4. Where do p-n junctions hide inside every CMOS standard cell?

My Answer: 

P-N junctions are found where the source and drain regions meet the transistor's body. In an NMOS, the N-type source and drain form P-N junctions with the P-type body. In a PMOS, the P-type source and drain form P-N junctions with the N-type well.

---

## Practice Exercise

### An NMOS transistor has its source at 0 V and its drain at 1.0 V. Because a well tap was missed, its p-type body is not tied to ground, and substrate noise pushes the body up to +0.8 V.

#### 1. For the source-to-body junction and the drain-to-body junction, state whether each is forward or reverse biased.

*My Answer:*

Source-to-body:  p-side (body) = 0.8 V, n-side (source) = 0 V
                 p is 0.8 V above n  -> FORWARD biased (above ~0.6 V)

Drain-to-body:   p-side (body) = 0.8 V, n-side (drain) = 1.0 V
                 n is 0.2 V above p  -> REVERSE biased (normal)
#### 2. What current flows as a result, and why is it a problem?

*My Answer:*

the source junction conducts strongly, injecting electrons
into the body. This wastes current, disturbs neighbouring devices,
and can trigger latch-up. Correct well-tap placement keeps the body
at 0 V so every junction stays reverse biased.

---

## Summary

- At a p-n boundary, carriers diffuse across and recombine, leaving a depletion region with no free carriers

- Exposed fixed ions in the depletion region create a built-in field that stops further diffusion

- Forward bias shrinks the depletion region; current rises steeply above about 0.6-0.7 V, roughly 10× per 60 mV

- Reverse bias widens the depletion region and blocks current, apart from a small temperature-sensitive leakage

- Heavier doping narrows the depletion region; more reverse bias widens it and lowers junction capacitance

- Every MOSFET contains p-n junctions that must stay reverse biased, which is why well taps exist

---

## Chapter Review

**Can I explain these concepts without looking?**

- [ ] Yes, I understand everything.
- [x] I need to review some concepts.

**Date Completed:** 10/26/2026