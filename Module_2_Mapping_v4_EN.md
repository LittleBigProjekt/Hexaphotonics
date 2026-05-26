# Module 2 — The Mapping F (Version 4.1)

## 2.1 Purpose of the mapping

The mapping **F** describes how a single Hexaphoton
\[
H = (f, P, d)
\]
gives rise to a contribution to the classical electromagnetic wave.

F is **not a physical process**, but a **notation** that describes
classical wave optics in compact form.

---

## 2.2 The mapping F for a single Hexaphoton

F maps a Hexaphoton to a complex wave contribution — a plane wave:

\[
F(H) = A \; \vec{\varepsilon}\; e^{\,i(\vec{k}\cdot\vec{x} - \omega t)}
\]

with:

- \( \omega = 2\pi f \) — angular frequency, from the frequency
- \( \vec{k} = \dfrac{2\pi f}{c}\,\vec{d} \) — wave vector, from frequency and direction
- \( \vec{\varepsilon} \) — polarization vector, from \( P \) (see 2.3)
- \( A \) — amplitude, determined from the energy \( E \) (see 2.7)

> **Consistency with Module 1.** The wave vector \( \vec{k} \) is the
> momentum \( \vec{p} \) in wave notation (\( \vec{p} = \hbar\vec{k} \));
> Constraint C2 is thereby automatically satisfied.

**Important:** the phase arises **only within the Hexafield**, not in the
single Hexaphoton. For an isolated \( H \) it is set to zero by
convention. F is thus fully compatible with Module 1.

---

## 2.3 The polarization vector

The polarization \( P \) is a **Jones vector** — two complex numbers
\( (J_1, J_2) \). To turn it into a **real** oscillation vector
\( \vec{\varepsilon} \) in 3D space, two reference directions in the plane
perpendicular to \( \vec{d} \) are required.

**Convention B — co-moving reference pair.** The pair \( \hat{e}_1,
\hat{e}_2 \) is constructed from the direction \( \vec{d} \) itself; it
depends only on a Hexaphoton quantity. With a fixed auxiliary vector
\( \hat{z} \):

\[
\hat{e}_1 = \frac{\hat{z}\times\vec{d}}{\lVert\hat{z}\times\vec{d}\rVert},
\qquad
\hat{e}_2 = \vec{d}\times\hat{e}_1
\]

\( \hat{e}_1, \hat{e}_2, \vec{d} \) form a right-angled triad. The
polarization vector is:

\[
\vec{\varepsilon} = J_1\,\hat{e}_1 + J_2\,\hat{e}_2
\]

> **Special case.** If \( \vec{d} \) is parallel to \( \hat{z} \), the
> rule fails (\( \hat{z}\times\vec{d}=0 \)); an alternative auxiliary
> vector is then used. This is a known, unavoidable feature of any
> reference-pair construction (compare the meridians at the North Pole),
> not a defect.

Real \( J_1, J_2 \) give **linear** polarization, a 90° phase difference
gives **circular**, other values give **elliptical** polarization.
\( \vec{\varepsilon} \) is by construction always perpendicular to
\( \vec{d} \) — the transverse-wave condition is automatically satisfied.

---

## 2.4 The Hexafield as a sum of contributions

A Hexafield is a set of Hexaphotons:
\[
\mathcal{H} = \{ H_1, H_2, \dots, H_N \}
\]

The resulting wave is obtained by linear superposition of the wave
contributions:

\[
E(\vec{x},t) = \sum_{i=1}^{N} F(H_i)
\]

where each \( H_i \) is assigned its relative phase \( \Delta\phi_i \)
(Module 1). Only through this do the following arise:

- interference
- coherence
- phase relationships
- wave character

These properties are **not** contained in the single Hexaphoton; they
emerge only through the sum.

---

## 2.5 Linearity of the mapping

The mapping is **linear in the wave contributions**: the wave of a
Hexafield is the sum of the individual waves, and scaling a wave
contribution carries over directly:

\[
F\!\left(\sum_i H_i\right) = \sum_i F(H_i),
\qquad
A\cdot F(H) = F(H)\big|_{\text{amplitude } A}
\]

> **Clarification.** What is linear is the **superposition of the
> waves**, not an operation "number times Hexaphoton". An expression like
> \( aH \) is not defined — a Hexaphoton is the triple \( (f,P,d) \), not
> a vector-space element. Linearity concerns only the wave contributions
> \( F(H_i) \). This corresponds exactly to classical wave optics.

---

## 2.6 No new physics

F is a **reformulation** of the known Maxwell solution for plane waves
and their superposition. **No** new assumptions are introduced.

---

## 2.7 The amplitude constant

The amplitude \( A \) of a wave contribution and the energy \( E \) of
the Hexaphoton describe the **same property** — how strong the wave is —
in two measures. They are not independent quantities, but convertible
into one another.

Classical wave optics prescribes the relationship: the energy of a wave
is proportional to the **square** of the amplitude. Conversely:

\[
A = \sqrt{\frac{E}{k}}
\]

> **\( k \) is a fixed conversion constant with a fixed dimension**
> (energy per amplitude squared). It is set by the choice of units and
> is not freely selectable; it carries no physics of its own beyond this
> unit conversion. In particular, \( k \) does **not** depend on the
> photon count (that is the sum, Section 2.4), on the primary quantities
> \( f, P, d \) (since \( E = h f \) already contains the frequency, an
> \( f \)-dependence would be a double count), or on the polarization.
> \( k \) is the single-element conversion for *one* Hexaphoton, formed
> before any sum or interaction enters.

Thus \( A \) is fully determined by \( E \) — consistent with the
Constraints C1, C2 of Module 1: the Hexaphoton fully determines its wave,
with no open parameters.

---

## 2.8 Transition to the modal basis

Sections 2.2–2.5 describe light as **plane waves** — the natural
description for light in free space. For the connection to Mie scattering
theory (Module 4), however, it does not fit directly: a sphere scatters
light into **spherically outward-travelling** wavefronts. For this, a
different description is more practical — the **spherical modes**.

This section is the **bridge** between the two descriptions. It is the
*same* light wave, merely expressed in a coordinate system adapted to the
spherical shape.

> **Analogy.** A city can be described with a street grid or with rings
> and spokes around the centre. Both describe the same city; for a
> circular old town, rings are more practical.

**Nothing new is invented here.** The translation of plane waves into
spherical modes is established mathematical physics (the *plane-wave
expansion in spherical functions*; used by Mie in 1908). It connects at
two points: before applying a sphere-related operator \( T_M \), the wave
is translated into the spherical-mode representation; after scattering,
the result can be translated back.

The concrete formula is standard and is applied where calculation
actually takes place — in **Module 5**. For the conceptual completeness of
the mapping F it suffices that the change of representation is a known,
lossless translation, not an additional physical assumption.

---

## 2.9 Extension F\* (optional)

For later work, an extended mapping **F\*** can be defined that describes
nonlinear effects (frequency shifts such as Raman, generation of new
frequencies such as SHG, polarization changes beyond linear optics).

F\* is **not part** of the Hexaphoton core system, but an optional
extension.

---

## 2.10 Note on interpretation

- The Hexaphoton describes **discrete degrees of freedom**.
- F describes how these degrees of freedom contribute to the
  **classical wave**.
- The Hexafield is the **bridge** between the single element and the
  wave picture.

Speculative hypotheses (H1–H7) are **not** integrated into F.
