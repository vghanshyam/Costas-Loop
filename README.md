# Costas-Loop
A Costas Loop is a special type of Phase-Locked Loop (PLL) used for carrier recovery in digital communication systems.
--
👉 It removes carrier frequency and phase offset from modulated signals such as:

- **BPSK**
- **QPSK**
- **QAM**
- # 🎯 Why Do We Need a Costas Loop?

When a signal is transmitted:
`s(t) = m(t) cos(2π f_c t)`

At the receiver, due to oscillator mismatch:
`r(t) = m(t) cos(2π (f_c + Δf) t + ϕ)`

---

## Where:

- `Δf` → Frequency offset  
- `ϕ`  → Phase offset  

---

## 🚨 Without Correction:

- Constellation rotates  
- Bit errors increase  
- Demodulation fails  

---

👉 The **Costas Loop** locks onto the carrier and removes this frequency and phase offset.
