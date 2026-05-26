# Module 4 — Consistency Check Using Mie Scattering (Version 4.2)

## 4.1 Purpose of this module

Module 4 shows that the Hexaphoton notation system is **compatible with
established classical optics**. The test example is a real, well-studied
process: **Mie scattering by spherical particles.**

This module postulates no new physics; it checks whether the notation is
correct, free of contradictions, and applicable to real optical
phenomena.

> **Important classification — what this module is and is not.**
> This is a **consistency check**, not an *independent validation*. It
> shows that the Hexaphotone notation connects to Mie theory without
> contradiction. It does **not** show that the system derives scattering
> from its own resources — from F and superposition alone. A genuine
> independent validation is the subject of a later Module 5.

---

## 4.2 Starting point: the Hexafield

A Hexafield is a set of Hexaphotons:
\[
\mathcal{H} = \{ H_1, H_2, \dots, H_N \}, \qquad H_i = (f_i, P_i, d_i)
\]

The resulting wave is obtained by superposition:
\[
E(\vec{x},t) = \sum_{i=1}^{N} F(H_i)
\]

This is exactly the classical superposition of electromagnetic waves.

---

## 4.3 The effect of matter: applying T_M

A particle (e.g. a water droplet) acts on each Hexaphoton via the matter
operator:
\[
T_M(H_i) = (f_i', P_i', d_i')
\]

In linear optics, \( f_i' = f_i \), \( P_i' = M_P P_i \),
\( d_i' = M_d d_i \). Thus T_M is compatible with the classical
description of scattering.

---

## 4.4 Comparison with Mie theory

Mie theory describes angle-dependent intensity and polarization, phase
shifts, spectral dependence and changes of direction. In Hexaphotone
notation these quantities arise through:

1. transformation of the polarization: \( P' = M_P(\theta,\phi)\,P \)
2. transformation of the direction: \( d' = d'(\theta,\phi) \)
3. superposition of all scattered contributions:
   \( E_{\text{scat}} = \sum_i F(T_M(H_i)) \)

The notation thus represents the same quantities as Mie theory.

> **Honesty note.** That the notation represents the same quantities
> means: it is *compatible* with Mie. It does not mean it *replaces* Mie
> or reproduces it independently. The concrete numerical check is
> performed by the companion script (see 4.7).

---

## 4.5 Consistency criteria

The notation system is consistent if:

1. **frequency is preserved** — ✔ satisfied (correct for linear optics)
2. **polarization is transformed correctly** — ✔ satisfied (Jones/Mueller)
3. **changes of direction are represented correctly** — ✔ satisfied
4. **superposition is identical to classical wave optics** — ✔ satisfied
5. **no new physics is introduced** — ✔ satisfied (pure notation)

The Hexaphoton system is thus **conceptually consistent** with classical
Mie scattering.

---

## 4.6 What Module 4 does NOT do

- It introduces **no** new mechanisms.
- It tests **no** speculative hypotheses (H1–H7).
- It does **not** replace Mie theory.
- It does **not** serve to model nonlinearities.
- It provides **no** independent validation (see 4.1).

---

## 4.7 Numerical companion script

The concrete check is accompanied by an executable Python script
(`Module_4_ConsistencyCheck.py`). It computes the scattering by a sphere
along two paths (Mie reference and Hexaphotone notation) and compares
them for several sphere sizes.

The script confirms the **consistency** (contradiction-free connection).
As explained in 4.1, it is not an independent validation, since the
Hexaphotone path uses the same Mie kernel.

---

## 4.8 Extensibility

The system can be extended later: nonlinear scattering (via T\*_M),
spectral distributions, coherent vs. incoherent fields, time-dependent
fields. These extensions do not change the core.

---

## 4.9 Next step

The mapping F (Module 2) is conceptually complete — polarization vector,
amplitude and the transition to the modal basis are defined. This lays
the groundwork for **Module 5**: the independent validation, which
derives the scattering process from the modules themselves and checks it
against Mie theory.

---

## 4.10 Summary

Module 4 shows:

- The Hexaphoton system is **conceptually consistent** with classical
  optics.
- The notation represents real physical processes without contradiction.
- There are **no contradictions** with established measurements.

The Hexaphoton notation system (Modules 1–4) is thus **internally
coherent** at the notational level. An independent numerical validation
is still pending (Module 5).
