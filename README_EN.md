# Hexaphotonics — A Notation System for Light as an Information Carrier

### A compact, classical description of light through six quantities
**Author:** Manuel Julin
**License:** CC-BY-SA 4.0
**Status:** Notation system (Modules 1–4) conceptually complete — work in progress

---

## 📘 Overview

This repository develops **Hexaphotonics** — a *notation system* that
describes light through a compact, modular representation.

Important for context: Hexaphotonics is **not a new physical theory**. It
is a **reformulation of established classical wave optics** (Maxwell,
Fourier optics, Mie/T-matrix scattering theory) in its own intuitive
notation. The measure of success is not "is it true?" — the underlying
physics is known and correct — but "is it consistent, unambiguous, and
useful?".

Speculative ideas that go beyond established physics are kept **strictly
separate** in their own hypothesis collection (see file list). They are
**not part** of the notation system.

---

## 🔭 Core idea: two levels

The system strictly separates two levels — mixing them was the central
flaw of earlier drafts.

| Level | Symbol | Meaning |
|-------|--------|---------|
| **Hexaphoton** | `H` | A single light element — an idealized mode. |
| **Hexafield** | `{Hᵢ}` | An ensemble of many Hexaphotons — a source or an image. |

A single Hexaphoton is *positionless*: it carries a **direction**, but no
point of origin. Shape, image, interference, phase and the spatial
position of a source are **exclusively Hexafield properties**.

---

## 🧩 The Hexaphoton vector

A Hexaphoton is traditionally named through six quantities:

```
H = ( E , f , P , φ , p⃗ , d⃗ )
```

These six quantities are **not of the same kind**. They fall into three
classes:

| Class | Quantities | Character |
|-------|------------|-----------|
| **Primary** | `f` (frequency), `P` (polarization), `d⃗` (direction) | The three independent degrees of freedom of a single Hexaphoton. |
| **Derived** | `E` (energy), `p⃗` (momentum) | Follow from the primary quantities via fixed constraints. |
| **Relation** | `φ` (phase) | Not a property of a single `H`. Defined only as a relation *between* Hexaphotons in the Hexafield. |

A single Hexaphoton thus has **3 independent degrees of freedom**. The
name "Hexa" (six) is a memorable label for the six quantity types — **not
a law of nature**.

### Constraint equations

```
C1   E  = h · f                    (energy from frequency)
C2   p⃗  = (h · f / c) · d⃗          (momentum from frequency and direction)
```

---

## 🗂️ The four modules

The system is organized into four modules that build on one another:

| Module | Content |
|--------|---------|
| **1 — The Hexaphoton** | Definition of Hexaphoton, Hexafield, the three quantity classes and the constraints. |
| **2 — The Mapping F** | Translation of a Hexaphoton/Hexafield into a concrete light wave. Includes the polarization vector, the amplitude relation and the transition to the modal basis. |
| **3 — The Operator T_M** | Interaction with matter: redirecting, selecting, absorbing; emission (thermal radiation, spectral lines). |
| **4 — Consistency Check** | A check using Mie scattering: the notation connects to established optics without contradiction. |

---

## 📄 Contents of this repository

| File | Content | Status |
|------|---------|--------|
| `README.md` | This overview. | current |
| `Module_1_Hexaphoton_v4_EN.md` | Module 1 — definitions. | current (v4.1) |
| `Module_2_Mapping_v4_EN.md` | Module 2 — the Mapping F. | current (v4.1) |
| `Module_3_Operator_v4_EN.md` | Module 3 — the operator T_M. | current (v4.2) |
| `Module_4_ConsistencyCheck_v4_EN.md` | Module 4 — consistency check. | current (v4.2) |
| `Hexaphotonics_Modules_1-4.pdf` | The four modules as a single PDF document. | current |
| `LICENSE` | License text (CC-BY-SA 4.0). | current |

---

## 🗺️ Roadmap

- [x] **Module 1 — Definitions.** *(complete, v4.1)*
- [x] **Module 2 — The Mapping F.** *(complete, v4.1)*
- [x] **Module 3 — The Operator T_M.** *(complete, v4.2)*
- [x] **Module 4 — Consistency Check.** *(complete, v4.2)*
- [ ] **Module 5 — Independent Validation.** Derive the scattering
      process from the modules themselves and check it numerically
      against Mie theory.
- [ ] **Open question (later phase):** Can an independent prediction be
      formulated that goes beyond classical optics?

---

## ⚠️ What Hexaphotonics is (still) NOT

Honesty requires stating clearly what the system does *not* yet do:

- It is **not a quantum model.** It does not quantize the field and makes
  no claims about single-photon quantum effects.
- It makes **no prediction** that does not also follow directly from
  Maxwell/Mie.
- It is **not yet independently validated.** Module 4 so far shows only
  *consistency* (contradiction-free connection to Mie), not an
  independent derivation. The genuine validation is Module 5.
- The **hypothesis collection** is explicitly speculative and not part of
  the verified notation system.

---

## 📜 License

This project is released under the **Creative Commons CC-BY-SA 4.0**
license: anyone may use and build upon the work; the author must be
credited; derivative works must remain free under the same license.

Full license text: https://creativecommons.org/licenses/by-sa/4.0/

---

## 📚 Suggested citation

Manuel Julin (2026). *Hexaphotonics — A Notation System for Light as an
Information Carrier.* Working version, Modules 1–4. CC-BY-SA 4.0.

---

## 🤝 Contributions

Discussions, ideas and extensions are welcome.
Pull requests and issues can be opened at any time.
