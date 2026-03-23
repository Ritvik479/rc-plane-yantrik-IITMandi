# ✈️ Garuda 2.0 — RC Plane Design

> Fixed-wing RC aircraft designed for payload delivery, built by **Team Garuda** under the **Yantrik Club, IIT Mandi**.

---

## 📌 Overview

Garuda 2.0 is a high-wing monoplane with a conventional tail, designed for stability and payload delivery. The design philosophy prioritizes a balance between payload capacity and structural rigidity. The **CH-10 airfoil** was selected for its superior lift characteristics at low speeds, and the streamlined rectangular fuselage minimizes drag while housing a 250g cube payload internally.

Visit Official Webpage at : https://remandey.github.io/yantrik-rcplane

---

## 📐 Technical Specifications

### Dimensions

| Component | Parameter | Value |
|-----------|-----------|-------|
| **Wing** | Span | 1.18 m |
| **Wing** | Chord | 0.28 m |
| **Wing** | Dihedral | 3° |
| **Fuselage** | Length | 0.9 m |
| **Fuselage** | Width × Height | 0.13 m × 0.13 m |
| **Horizontal Tail** | Span | 0.52 m |
| **Horizontal Tail** | MAC | 0.1305 m |
| **Vertical Tail** | Height | 0.19 m |
| **Vertical Tail** | MAC | 0.0963 m |
| **All-Up Weight** | (without payload) | ~921 g |

### Propulsion System

| Component | Specification | Justification |
|-----------|---------------|---------------|
| Motor | 1500 KV BLDC | High torque for cargo lift |
| ESC | 40A Brushless | Reliable current handling for 3S |
| Battery | 3S LiPo, 2200 mAh (11.1V) | Optimal weight-to-energy ratio |
| Propeller | 1100 × 6 | Matched to motor KV and 3S voltage |

---

## 📊 Design Calculations

| Parameter | Value |
|-----------|-------|
| **Airfoil** | CH-10 |
| **Thrust-to-Weight Ratio** | 1.1 (with payload) / 0.9 (without payload) |
| **Wing Loading** | ~4.19 kg/m² (~41 N/m²) |
| **CG Position** | 25–30% of wing MAC (70–84 mm from LE) |
| **Static Margin** | ~10% (positive longitudinal stability) |

---

## 📦 Payload System

- **Payload:** 250g cube, housed in a balsa cage centered at the CG
- **Drop Mechanism:** RC-operated trap door driven by a high-torque 9g servo
- **Retention:** Push springs at the roof of the cage for smooth ejection

The payload bay is positioned exactly at the aircraft's CG to ensure flight stability is unaffected during and after the drop.

---

## 🧱 Materials & Construction

| Part | Material |
|------|----------|
| Fuselage skin | Depron foam |
| Wing ribs | Laser-cut Balsa |
| Wing main spar | Balsa wood (bending stiffness) |
| Wing mounting | Rubber bands (crash-repair friendly) |

---

## 🛠️ Tools & Software

| Tool | Purpose |
|------|---------|
| [SolidWorks](https://www.solidworks.com/) | 3D CAD modelling of airframe and components |
| [OpenVSP](http://openvsp.org/) | Aerodynamic geometry and performance analysis |
| [XFLR5](http://www.xflr5.tech/xflr5.htm) | Airfoil selection and wing aerodynamics |

---

## 📸 Construction Photos & CAD Files

📁 [Google Drive — Photos & CAD](https://drive.google.com/drive/folders/1Txp1gwdNweSBexzmWJwU87oO0N__N0AG?usp=sharing)

---

## 🤝 Acknowledgements

Developed under the **Yantrik Club** at **IIT Mandi** .

---

## 📄 License

This project is intended for academic and educational use.  
© Team Garuda — Yantrik Club, IIT Mandi
