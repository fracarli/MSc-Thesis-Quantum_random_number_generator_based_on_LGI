# Quantum Random Number Generators and Implementations based on Leggett–Garg Inequalities

This repository contains the Master's thesis in Physics titled **"Quantum Random Number Generators and implementations based on Leggett–Garg inequalities"**, defended at the University of Genoa (School of M.F.N. Sciences, Master's Degree in Physics).

## 📋 Project Overview
Quantum Random Number Generators (QRNGs) are essential tools for cryptography, numerical simulations, and metrology. Traditionally, the certification of randomness in these devices relies on the violation of Bell's inequalities. However, this approach requires complex experimental conditions, such as spatial entanglement and the strict spatial separation of detectors.

This work explores a promising alternative: utilizing **Leggett–Garg inequalities (LGIs)** to certify non-classicity and generate quantum random numbers via temporal scenarios (repeated measurements over time on a single system). This drastically reduces experimental complexity, paving the way for more compact implementations that are easier to integrate on a micro- and nanotechnological scale.

---

## 🏗️ Thesis and Repository Structure

The thesis is divided into the following main chapters:

*   **Chapter 1: Foundations of Quantum Mechanics**
    *   Review of two-level system (qubit) kinematics, Hilbert space formalism, and the density matrix.
    *   Analysis of the mixture state, Bloch sphere representation, and environmental decoherence.
    *   The measurement problem through the double-slit experiment and the concept of *which-way* information.
*   **Chapter 2: From EPR to Macrorealism**
    *   From the EPR paradox and Bell's local realism to the Leggett–Garg framework (1985).
    *   Postulates of macrorealism per se ($MR_{ps}$) and non-invasive measurability (NIM), utilizing ideal negative measurements (INM).
    *   Fine's Theorem and the classification of macrorealism forms: **Weak** ($MR_{weak}$), **Intermediate** ($MR_{int}$), and **Strong** ($MR_{strong}$).
*   **Chapter 3: Randomness Generation: From Classical to Quantum**
    *   Distinction between epistemological randomness (classical/pseudo-randomness) and ontological randomness (quantum).
    *   The device-independent paradigm and the crucial role of **min-entropy** for the quantitative estimation of unpredictability.
*   **Chapter 4: Predictability and Randomness**
    *   Theoretical derivation of LGIs starting from No-Signaling-in-Time (NSIT) conditions and predictability.
    *   Analytical optimization for min-entropy certification as a function of LGI violations in a single-system architecture.
*   **Chapter 5: Quantitative Characterization and Min-Entropy Analysis (Original Contribution)**
    *   Definition of novel geometric distance metrics ($d_{weak}$, $d_{int}$, $d_{strong}$) to quantify deviations from macrorealistic regimes.
    *   Implementation of a Python simulation framework to analyze the evolution of mixed and pure states under the effect of Pauli operators.
    *   Discussion on the decoupling between non-classicity and statistical randomness.

---

## 🛠️ Appendices Overview
The work also includes supporting technical and analytical appendices:
*   **Appendix A:** Analytical results.
*   **Appendix B:** Detailed predictability analysis.
*   **Appendix C:** Statistical uncertainties and error propagation.
*   **Appendix D:** Device-independent certification.
*   **Appendix E:** Predictability and Non-Signaling within three-time operational frameworks.


---

## ✒️ Author and Contacts
*   **Candidate:** Francesco Carli
*   **Advisor:** Prof. Paolo Solinas
*   **Co-advisor:** Prof. Dario Ferraro
*   **University of Genoa**# MSc-Thesis-Quantum_random_number_generator_based_on_LGI
