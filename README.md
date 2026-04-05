# 🌱 RadiusBoneMeal

**RadiusBoneMeal** is a lightweight and fully configurable Paper plugin that enhances bonemeal by applying it in a radius instead of just a single block.

Perfect for survival servers, farming setups, and quality-of-life improvements.

---

## ⚡ Features

- 🌿 Bonemeal affects multiple blocks in a radius
- 📏 Adjustable radius & vertical range
- 🌾 Works with configurable plant types
- ✨ Optional particle effects
- 🚀 Lightweight & optimized (no lag)
- 📦 Easy plug-and-play setup

---

## 🛠️ Configuration

All settings can be edited in the `config.yml`.

### Example Config

```yml id="cfg7721"
radius: 3
max-radius: 5
y-range: 1
growth-amount: 1

particles: true
particle-type: VILLAGER_HAPPY

allowed-plants:
  - WHEAT
  - CARROTS
  - POTATOES
  - BEETROOTS
  - NETHER_WART
  - COCOA
  - SWEET_BERRY_BUSH
