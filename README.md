# 555 Timer LED Blinker PCB Project

---

## 📌 Project Title

**555 Timer LED Blinker** – Compact PCB Design using KiCad

---

## 📄 Description

This project is a simple and classic implementation of an **astable multivibrator circuit** using the NE555 timer IC. It periodically blinks an LED with a defined frequency, controlled by external resistors and a capacitor.

The main aim of this project is to:

* Practice schematic creation in KiCad.
* Design and route a compact single-sided PCB.
* Generate 3D visualization.
* Export files ready for fabrication.

---

## 🧠 Concepts Covered

* NE555 timer in astable mode.
* RC timing calculations.
* Schematic to PCB layout flow.
* Manual routing + curved board edges.
* 3D board design and silkscreen text.

---

## 🧰 Tools & Software

* **KiCad 7.0**
* OS: Windows 11
* PCB Render Tool: KiCad 3D Viewer

---

## 🧾 Bill of Materials (BOM)

| Quantity | Component                | Value | Footprint          |
| -------- | ------------------------ | ----- | ------------------ |
| 1        | NE555 Timer IC           | U1    | DIP-8              |
| 1        | Resistor                 | 1 kΩ  | R\_Axial           |
| 1        | Resistor                 | 10 kΩ | R\_Axial           |
| 1        | Capacitor (Electrolytic) | 10 µF | C\_Elec\_Polarized |
| 1        | Resistor                 | 330 Ω | R3 (LED resistor)  |
| 1        | LED (Green)              | D1    | LED\_THT (5mm)     |
| 1        | Power Supply             | 5V DC | Header 2-pin       |

---

## 🖼️ Project Structure

```
555-Blinker-PCB/
|├──555_Blinker.kicad_pro
|├──555_Blinker.kicad_sch
|├──555_Blinker.kicad_pcb
|├──Images/
|   └──render_3D.png
|├──Production/
|   └──Gerbers, BOM, Pick&Place files
|└──Docs/
    ├──README.md
    └──Schematic.pdf
```

---

## 🖥️ Getting Started

1. Open `555_Blinker.kicad_pro` in KiCad.
2. Navigate to the schematic editor and review the design.
3. From the schematic editor, click **"Update PCB from Schematic"** to sync changes.
4. In PCB Editor:

   * Arrange components
   * Draw board outline (with rounded corners)
   * Route manually (or autoroute)
5. Go to 3D Viewer to preview your board.

---

## 🛠️ Fabrication Prep

* Export Gerber files using **File > Plot**.
* Export Drill Files from **File > Fabrication Outputs > Drill Files**.
* Optionally generate:

  * BOM
  * Pick and Place files

---

## 🎨 Visual Preview

> ![3D View](./Images/render_3D.png)

---

## 🧑‍💻 Author Info

**Designed by:** Animesh Tripathi
**GitHub:** [github.com/animeshtripathi779](https://github.com/animeshtripathi779)

---

## 📄 License

MIT License

---

## 🌟 Future Enhancements

* Add multiple LEDs with sequencing.
* Integrate button to toggle blinking.
* Build a wearable version.

---

**Happy Hacking! ✨**

