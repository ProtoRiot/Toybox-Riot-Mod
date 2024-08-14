
# **Toybox-Riot-Mod**
**Step-by-Step Exploration of Modding the Toybox Alpha 3D Printer**

---

## **Introduction**

Welcome to the **Toybox-Riot-Mod** project. This repository is dedicated to documenting the step-by-step exploration of potential modifications for the Toybox Alpha 3D printer. Our focus is on understanding the various versions of the Toybox Alpha and implementing modifications that can enhance its capabilities.

This project combines hands-on 3D printing experience with AI-assisted programming to overcome challenges and bring creative ideas to life. We’re not making promises—just sharing our journey as it unfolds.

---

## **Versions of the Toybox Alpha**

The Toybox Alpha has three known versions, each with unique features:

1. **Version 1 (V1):**
   - Identifiable by a 3D printed cover over the SD and USB ports on the front of the frame.
   - Comes with a Pi V2 board and a motherboard labeled "Super."

2. **Version 2 (V2):**
   - Features a power button on the front of the unit.
   - Uses an ESP12 controller and an STM32F103 microcontroller.
   - Mechanically similar to V1, allowing most modifications to be compatible with both versions.

3. **Version 3 (V3):**
   - Does not have a power button on the front.
   - Mechanically the same as V1 and V2, but the electronics may be different.
   - The details of the V3 electronics are currently unknown as we only have access to V1 and V2.

---

## **Current Focus**

We are currently in the early stages of exploring:

- **Understanding the Limitations:** Identifying what can be improved or modified in each version of the Toybox Alpha.
- **Firmware Exploration:** Investigating options for replacing the firmware, focusing on the V2 electronics.
- **Mechanical Modifications:** Experimenting with small tweaks and seeing how they affect performance across different versions.

---

## **Subfolder Projects**

### **Pi Zero 2 Mount for Toybox Alpha V2**
- **Overview:** Replacing the ESP12 board in the Toybox Alpha V2 with a Pi Zero 2.
- **Details:** Includes steps for removing the display/internal cover, disconnecting the UART wiring, and printing a custom mount.
- **Link:** [PiZero2-Mount](https://github.com/ProtoRiot/Toybox-Riot-Mod/tree/main/PiZero2-Mount)

---

## **Getting Started**

### **Prerequisites**

To follow along with our journey, you may want:

- **Basic Tools:** Screwdrivers, pliers, and other small tools for disassembly and reassembly.
- **Software:** Access to CAD software (e.g., Fusion 360) and 3D printing software.
- **3D Printer Filament:** Ensure you have the appropriate filament for any tests.

### **Clone the Repository**

Start by cloning this repository:

```bash
git clone https://github.com/ProtoRiot/Toybox-Riot-Mod.git
```

### **Step-by-Step Updates**

As we make progress, we’ll update the repository with our findings, instructions, and any new ideas that emerge. Check back often to see what’s new!

---

## **Usage**

### **Current Exploration**

- **Testing Firmware:** We’re currently experimenting with alternative firmware for the V2 version. Details will be provided as we gather results.
- **Mechanical Tweaks:** Small adjustments are being tested to see their impact on print quality and speed across different versions.

---

## **Collaboration and AI Assistance**

This project is driven by a blend of practical experience and AI assistance, allowing us to tackle challenges that come up along the way. The AI plays a key role in helping to brainstorm, troubleshoot, and implement changes as we progress.

---

## **Contributing**

We welcome collaboration! If you’re interested in contributing ideas, testing, or offering feedback, feel free to fork the repository, submit pull requests, or open issues for discussion.

---

## **License**

This project is licensed under the GPL v3.0 License - see the `LICENSE.md` file for details.

---

## **Acknowledgments**

- **AI Assistance:** Thanks to AI for helping to navigate the exploration process and overcome technical challenges.
- **Community Support:** Gratitude to the 3D printing and maker communities for ongoing inspiration and support.
