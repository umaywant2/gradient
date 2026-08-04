# **Attunement Template — Gradient Layer**

**Gradient → Attunement → RTT/1**

Attunement is the *pre‑engine harmonization step* that prepares an idea for entry into the RTT lineage.  
It aligns the idea across the three Gradient modes:

- **S‑mode (Structure)**  
- **R‑mode (Resonance)**  
- **E‑mode (Energy)**  

and produces a stable **Attunement Profile**.

---

## **1. Attunement Declaration**

```
rtt: 1
coherence: declared
drift: bounded
paradox: structural
mode: <S | R | E>
```

Choose one mode depending on the idea’s initial character:

- **S‑mode** → structural footing  
- **R‑mode** → resonance mapping  
- **E‑mode** → activation energy  

---

## **2. Idea Input**

```
idea:
  title: <your idea title>
  summary: <1–3 sentence description>
  intent: <what the idea wants to achieve>
```

---

## **3. Mode Alignment**

### **S‑mode (Structure)**  
```
structure:
  frame: <core structural frame>
  boundaries: <explicit limits>
  invariants: <what must remain true>
```

### **R‑mode (Resonance)**  
```
resonance:
  frequency: <dominant conceptual frequency>
  harmonics: <secondary patterns>
  dissonance: <where resonance breaks>
```

### **E‑mode (Energy)**  
```
energy:
  activation: <what energizes the idea>
  flow: <how energy moves through the concept>
  decay: <where energy dissipates>
```

---

## **4. Drift Envelope (bounded)**

```
drift:
  allowed: <what drift is permitted>
  disallowed: <what drift is not permitted>
  threshold: <maximum drift before re-attunement>
```

---

## **5. Coherence Vector (declared)**

```
coherence:
  primary: <main coherence axis>
  secondary: <supporting coherence axes>
  risks: <where coherence may fail>
```

---

## **6. Paradox Frame (structural)**

```
paradox:
  core: <the structural paradox at the heart of the idea>
  tension: <what forces create the paradox>
  resolution: <how the paradox stabilizes>
```

---

## **7. Attunement Output → RTT/1**

This is the JSON block handed off to **Lumen (RTT/1)**.

```
attunement_profile:
  rtt: 1
  mode: <S | R | E>
  coherence: declared
  drift: bounded
  paradox: structural
  idea: <normalized idea object>
```

---

## **8. Next Step**

Send the **attunement_profile** to:

**RTT/1 — Lumen**  
[https://lumen.rtt1.online](https://lumen.rtt1.online)
