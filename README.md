# 🎛️ Smart Remote Scene Selector

[![Import Blueprint into Home Assistant](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?url=https%3A%2F%2Fraw.githubusercontent.com%2Fkevindaronde%2FSmart-Remote-Scene-Selector%2Fmain%2Fblueprints%2Fautomation%2Fkevinderonde%2Fsmart_remote_scene_selector.yaml)

Easily control up to **10 Home Assistant scenes** using any remote or two button entities.  
Each press increases or decreases a counter that switches between scenes — simple, fast, and elegant.

---

## ⚙️ Features
- Control up to **10 scenes** with a single remote  
- Works with **any button or switch entity**  
- **Cycle through scenes** forward (+) or backward (–)  
- No complex setup or coding required  
- Includes visual names and emoji icons for clarity  

---

## 🧩 Installation

1. Create a counter helper named:
**Settings:**  
- Min value: `1`  
- Max value: equal to your number of scenes  
- Initial value: `1`

2. Import this blueprint in Home Assistant:  
👉 [Click here to import](https://github.com/<YOUR_USERNAME>/<YOUR_REPOSITORY>/blob/main/blueprints/automation/<YOUR_FOLDER>/smart_remote_scene_selector.yaml)

3. Assign:
- A **+ button entity**  
- A **– button entity**  
- Up to **10 scenes**

4. Save and enjoy effortless scene switching with your remote 🎬

---

## 💡 Tips
- Only filled scene slots are used  
- Works great with Zigbee or Z-Wave remotes  
- Keep it simple: short press = next scene, long press = previous scene  

---

**Created for Home Assistant users who love simplicity and style.**
