# 🎛️ Smart Remote Scene Selector

[[![Import Blueprint into Home Assistant](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?url=https%3A%2F%2Fraw.githubusercontent.com%2Fkevinderonde%2FSmart-Remote-Scene-Selector%2Fmain%2Fblueprints%2Fautomation%2Fkevinderonde%2Fsmart_remote_scene_selector.yaml)](https://my.home-assistant.io/redirect/blueprint_import/?url=https://raw.githubusercontent.com/kevinderonde/Smart-Remote-Scene-Selector/main/blueprints/automation/kevinderonde/smart_remote_scene_selector.yaml
)

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

1. **Create a Counter Helper**  
   Go to *Settings → Devices & Services → Helpers → Create Helper → Counter* and set:
   - **Name:** `scenes afstandsbediening`
   - **Minimum value:** `1`
   - **Maximum value:** equal to your number of scenes  
   - **Initial value:** `1`

2. **Import this Blueprint**  
   👉 [Click here to import the blueprint into Home Assistant](https://my.home-assistant.io/redirect/blueprint_import/?url=https%3A%2F%2Fraw.githubusercontent.com%2Fkevinderonde%2FSmart-Remote-Scene-Selector%2Fmain%2Fblueprints%2Fautomation%2Fkevinderonde%2Fsmart_remote_scene_selector.yaml)

3. **Assign the Inputs**  
   - Select your **“+” button entity**  
   - Select your **“–” button entity**  
   - Choose up to **10 scenes**  

4. **Save and enjoy effortless scene switching** 🎬  

---

## 💡 Tips
- Only filled scene slots are used  
- Works great with **Zigbee**, **Z-Wave**, or **Matter** remotes  
- Keep it simple: short press = next scene, long press = previous scene  
- Ideal for bedside remotes, wall switches, or media room setups  

---

**Created by [Kevin de Ronde](https://github.com/kevinderonde)**  
For Home Assistant users who love simplicity and style ✨
