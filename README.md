# Onshape 3D CAD Models Collection

A collection of 3D CAD models and 2D sketches designed in [Onshape](https://www.onshape.com/) — a cloud-based, browser-accessible CAD platform. This repository documents all models from beginner components to complex mechanical parts.

---

## 📋 Table of Contents

- [About](#about)
- [Models Overview](#models-overview)
- [Model Details](#model-details)
- [Getting Started](#getting-started)
- [Tools Used](#tools-used)
- [License](#license)

---

## About

This repository contains a series of 3D CAD models created in Onshape, ranging from simple electronic components to complex mechanical assemblies. The models progress from basic shapes to more advanced designs, making this a great reference for CAD learners and engineers alike.

---

## Models Overview

| # | Model | Type | Complexity |
|---|-------|------|------------|
| 1 | EEE154 | SMD Electronic Component | ⭐ Basic |
| 2 | dasdahd | Flat Test/Practice Slab | ⭐ Basic |
| 3 | Flat Mounting Plate | Mechanical Base Plate | ⭐⭐ Intermediate |
| 4 | Rectangular Box | Electronic Enclosure | ⭐⭐ Intermediate |
| 5 | Two-Layer Box | Stacked Enclosure / Lid | ⭐⭐ Intermediate |
| 6 | Octagon Sketch | 2D Profile Sketch | ⭐ Basic |
| 7 | Circle Sketch | 2D Circle with Radius Lines | ⭐ Basic |
| 8 | Dice | Game Die with Pips | ⭐⭐ Intermediate |
| 9 | LEGO Brick (NSU) | LEGO-style Stud Brick | ⭐⭐ Intermediate |
| 10 | Wine Glass | Curved Revolve/Loft Part | ⭐⭐⭐ Advanced |

---

## Model Details

### 1. 🔲 EEE154 — SMD Electronic Component
A compact rectangular SMD component resembling a buzzer or crystal oscillator. Displayed with all three standard Onshape reference planes (Front, Top, Right).

- **Shape:** Small boxy enclosure
- **Features:** Side port/hole, part label "EEE154"
- **Use Case:** Electronic component reference model

---

### 2. 🟦 dasdahd — Flat Practice Slab
A flat rectangular slab with a single mounting hole on top. Likely a beginner practice or test model.

- **Shape:** Thin flat rectangle
- **Features:** Single top hole
- **Use Case:** CAD learning / test model

---

### 3. 🔩 Flat Mounting Plate
A large thin rectangular plate with 9 holes — 1 countersunk center hole and 8 surrounding through-holes arranged in a pattern.

- **Shape:** Large thin flat plate
- **Features:** 1 countersunk hole + 8 through-holes
- **Hole Pattern:**
```
        O       O
    O               O
        O   ⊙   O
    O               O
        O       O
```
- **Use Case:** Mounting base, fixture plate, enclosure floor

---

### 4. 📦 Rectangular Box — Enclosure
A solid rectangular box/housing with a single circular port on the front face. Resembles an electronics enclosure or project box.

- **Shape:** Large solid rectangle
- **Features:** 1 front-facing circular port
- **Use Case:** Device housing, project box, enclosure shell

---

### 5. 🗃️ Two-Layer Box — Stacked Enclosure
A two-part stacked box showing two distinct layers with different shading — representing a lid and base or a stepped housing. Includes a T-shaped part thumbnail visible in the Onshape UI.

- **Shape:** Two stacked rectangular layers
- **Features:** Dual-color layers, front port, T-shaped thumbnail
- **Use Case:** Lidded enclosure, two-section mechanical body

---

### 6. ✏️ Octagon Sketch — 2D Profile
A 2D sketch (not yet extruded) of a rounded octagonal/oval shape lying on the Top plane, with a construction circle used as a guide.

- **Shape:** Rounded octagon / truncated ellipse (2D)
- **Features:** Construction circle, constraint points, center origin
- **Status:** Sketch only — not extruded
- **Potential Part:** Flange, gasket, lens bezel, cover plate

---

### 7. ⭕ Circle Sketch — 2D with Radius Lines
A 2D circular sketch with two radial construction lines from the center to the edge, typically used to define the radius dimension.

- **Shape:** Circle (2D)
- **Features:** Center point, radial dimension lines
- **Status:** Sketch only — not extruded
- **Potential Part:** Cylinder, disc, washer, gear blank

---

### 8. 🎲 Dice — Game Die
A fully modeled 6-sided dice with recessed circular dot indentations (pips) on each face. One of the more detailed models in this collection.

- **Shape:** Cube with pip holes
- **Features:** Pips on top, front, and right faces
- **Technique:** Extrude + circular pocket cuts
- **Use Case:** Game piece, CAD practice model

---

### 9. 🧱 LEGO Brick (NSU) — Stud Brick
A LEGO-style brick with 6 raised circular studs on top arranged in a 2×3 pattern. Associated with **NSU** (university/organization). Created by **Mohan Dev Roy**.

- **Shape:** Flat rectangular brick with studs
- **Features:** 6 studs (2×3 pattern)
- **Technique:** Extrude + patterned cylinders
- **Use Case:** LEGO-compatible part, CAD learning exercise

---

### 10. 🍷 Wine Glass — Advanced Revolve Model
The most complex model in this collection — a wine glass featuring a hollow spherical bowl, cylindrical stem, and disc-shaped base. Uses two custom construction planes (Plane 1 & Plane 2).

- **Shape:** Bowl + stem + base disc
- **Features:** Hollow bowl, custom Plane 1 & Plane 2, smooth curved surfaces
- **Technique:** Revolve / Loft
- **Use Case:** Advanced CAD practice, demonstration of curved geometry

---

## 🚀 Getting Started

### View Models in Onshape

1. Open [Onshape](https://www.onshape.com/) and sign in (free account available)
2. Open the shared document links *(add your links here)*
3. Use the toolbar to rotate, pan, and inspect each model

### Navigation Controls

| Action | Control |
|--------|---------|
| Rotate | Right-click + drag |
| Pan | Middle-click + drag |
| Zoom | Scroll wheel |
| Reset view | Press `Home` or click the 🏠 icon |
| Switch view | Click Top / Front / Right on the axis cube |

---

## 📁 Repository Structure

```
├── README.md            # This file
├── screenshots/
│   ├── 01_eee154.png
│   ├── 02_dasdahd.png
│   ├── 03_mounting_plate.png
│   ├── 04_rectangular_box.png
│   ├── 05_two_layer_box.png
│   ├── 06_octagon_sketch.png
│   ├── 07_circle_sketch.png
│   ├── 08_dice.png
│   ├── 09_lego_nsu.png
│   └── 10_wine_glass.png
└── drawings/            # (Optional) 2D engineering drawings / DXF exports
```

---

## 🛠️ Tools Used

- **[Onshape](https://www.onshape.com/)** — Cloud-based CAD (no installation required)

---

## 👤 Author

- **Mohan Dev Roy**

---

## 📄 License

This project is open for personal and educational use. See [LICENSE](LICENSE) for details.

---

## 🙋 Contributing

Pull requests and suggestions are welcome! If you have improvements to any model or want to add new ones, feel free to open an issue or submit a PR.

---

> ⭐ If you found this helpful, consider starring the repository!
