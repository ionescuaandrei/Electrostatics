# ⚡ Electrostatics Simulation Project (QuickField)

This project presents a detailed numerical analysis of an electrostatic system using **QuickField**, focusing on the influence of **charges**, **mesh density**, and **dielectric permittivity** on electric potential and field distribution.

---

## 📌 Project Overview

The model consists of:
- A **star-shaped geometry** inside a square domain
- **Three point charges**:
  - `q1` – central positive charge
  - `q2`, `q3` – negative charges placed asymmetrically
- Two **floating conductors (armatures)** dividing the star
- Two dielectric regions:
  - **Dielectric 1 (εr1)**
  - **Dielectric 2 (εr2)**

The goal is to study how physical parameters influence:
- Electric potential (V)
- Electric field intensity (E)

---

## 🧪 Tests Performed

### 1️⃣ Mesh Test
- Compared multiple mesh densities
- Selected **Mesh 3** for highest accuracy
- Observed smoother field lines and stable numerical values

---

### 2️⃣ Charge Tests

We performed **3 charge configurations**, analyzing:

- Scaling of charges (`10⁻⁶ → 1 C`)
- Sign variation (positive vs negative)
- Symmetry breaking

📊 Observations:
- Field magnitude scales linearly with charge
- Highest values occur near charge locations
- Field direction depends on charge polarity

---

### 3️⃣ Permittivity Tests

We designed **3 different dielectric scenarios**:

#### 🔹 Symmetric variation
- εr1 = εr2 = 1 → 10 → 100  
→ Field remains symmetric, magnitude decreases

#### 🔹 Dielectric 1 dominant
- εr1 increases while εr2 stays small  
→ Field shifts toward upper region

#### 🔹 Dielectric 2 dominant
- εr2 increases while εr1 stays small  
→ Field shifts toward lower region

📊 Observations:
- Higher permittivity attracts electric field lines
- Field intensity decreases inside high-ε materials
- Symmetry breaks when εr1 ≠ εr2

---

## 📍 Computation Points

Electric potential and field intensity were evaluated at:
- 13 predefined points (P1 – P13)
- Covering:
  - Center region
  - Near charges
  - Outer domain

---

## 🖼️ Results

The project includes:
- Electric potential contour plots
- Electric field vector maps
- Comparative tables for all tests

---

## 🧠 Key Conclusions

- Mesh density affects **numerical accuracy**
- Charges control **field intensity and direction**
- Permittivity controls **field distribution**

👉 The interaction between geometry, materials, and charges plays a crucial role in electrostatic behavior.

---

## 🛠️ Technologies Used

- **QuickField** – electrostatic simulation
- **Microsoft Word** – report & tables
- **VBA (optional)** – automated data extraction
- **Wine (Whisky on macOS)** – running QuickField


---

## 🚀 Future Improvements

- Automate data extraction using Python instead of VBA
- Improve visualization (interactive plots)
- Extend to 3D simulations

---

## 👤 Author

**Ionescu Andrei**  
- GitHub: https://github.com/ionescuaandrei  
- LinkedIn: https://www.linkedin.com/in/ionescuaandrei/

---

## ⭐ Notes

This project was developed as part of an academic study in **Electrostatics**, combining numerical simulation with physical interpretation.
