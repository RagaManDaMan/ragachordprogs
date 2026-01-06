# 🎹 Raga Harmony & Progression Generator

A web-based music theory tool designed for students to explore the intersection of **Carnatic Ragas** and **Western Functional Harmony**. 

This app allows users to define any scale (Janya or Melakarta) by semitones and instantly generates a harmonic map, including secondary progressions for every degree of the scale.

## 🚀 Key Features

* **Key Transposition:** Shift the entire analysis to any of the 12 chromatic keys to match your instrument or vocal range.
* **Custom Scale Engine:** Define scales using scale degree numbers (1-12). Works for Pentatonic, Hexatonic, and Heptatonic ragas.
* **Dynamic Progression Builder:** Generate custom multi-chord sequences (like `3-6-2-5-1`) targeting every note in the scale.
* **Harmonic Mapping:** Automatically identifies triads and seventh chords based on the available notes in the user-defined scale.

## 📖 How to Use

1.  **Select a Key:** Use the dropdown to set your tonic (Adhara Shadjam).
2.  **Enter Scale Degrees:** In the "Define Scale" box, enter the semitones of your raga separated by commas.
    * *Example (Sankarabharanam):* `1, 3, 5, 6, 8, 10, 12`
    * *Example (Mohanam):* `1, 3, 5, 8, 10`
3.  **Set Progression:** Enter the functional degrees you want to see leading to the target.
    * *Example:* Entering `2-5-1` will show you the $ii$ and $V$ chords for every note in your raga.
4.  **Analyze:** The table updates in real-time as you type.

## 🛠 Installation

No installation is required. This is a standalone web application.

1.  Download the `index.html` file.
2.  Open it in any modern web browser (Chrome, Firefox, Safari, or Edge).
