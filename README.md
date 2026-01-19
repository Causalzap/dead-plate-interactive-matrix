<div align="center">

  <img src="https://deadplate.net/favicon.svg" alt="Dead Plate Toolkit Logo" width="100" height="100" />

  # Dead Plate Interactive Matrix & Wiki

  <p>
    <strong>The definitive open-source data collection and decision logic for the indie horror game "Dead Plate".</strong>
  </p>

  <p>
    <a href="https://deadplate.net">
      <img src="https://img.shields.io/badge/Live_Simulator-FF0000?style=for-the-badge&logo=rss&logoColor=white" alt="Live Demo" />
    </a>
    <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" alt="Status" />
    <img src="https://img.shields.io/badge/Game_Version-v1.0-blue?style=for-the-badge" alt="Version" />
    <img src="https://img.shields.io/badge/Focus-Data_Analysis-orange?style=for-the-badge" alt="Focus" />
  </p>

  <p>
    <a href="#features">Features</a> •
    <a href="#data-structure">Data Structure</a> •
    <a href="https://deadplate.net/games/dead-plate/">🚀 Launch Simulator</a>
  </p>

</div>

---

## 📖 About The Project

This repository serves as the knowledge base and logic core for **HorrorHub**, a fan-made initiative to document mechanic-heavy indie horror games.

We have reverse-engineered the relationship mechanics of **Dead Plate** to provide exact calculations for unlocking all 4 endings.

**🌟 Main Project URL:** [https://deadplate.net](https://deadplate.net)

## ✨ Features

Here is what you can find in the live toolkit:

- 🧮 **Ending Calculator:** Input your choices (dialogue, items) to see Rody's fate in real-time.
- 📂 **Character Archives:** Detailed JSON-structured profiles for Rody, Vincent, and Manon.
- 🔍 **Lore Database:** Hidden secrets and plot analysis (e.g., The "Best Served Hot" ending requirements).
- 📱 **Mobile Optimized:** Built with Astro for lightning-fast performance.

## 🛠️ Data Structure (Example)

We strictly map the game's decision tree. Here is a snippet of the ending logic:

```json
{
  "ending_type": "True Ending",
  "requirements": {
    "suspicion_level": "High (>70)",
    "key_items": ["Matches", "Freezer Key"],
    "affinity": "Variable"
  },
  "outcome": "Rody burns down the bistro."
}
