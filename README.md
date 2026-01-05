# Joshua-Watson-Lab
# 🚀 HP Pavilion RAM Upgrade: 8GB to 16GB

This repository documents the memory expansion of my HP Pavilion. The goal was to double the capacity while maintaining the original system frequency to ensure 100% stability and compatibility with the HP BIOS.

## 💻 System Specs & Upgrade Logic
* **Model:** HP Pavilion
* **Upgrade Path:** 8GB (Single Channel) → 16GB (Dual Channel)
* **Frequency:** 2400 MT/s (Kept stock to avoid BIOS compatibility issues)

### 📊 Performance Impact
| Metric | Pre-Upgrade (8GB) | Post-Upgrade (16GB) |
| :--- | :--- | :--- |
| **Capacity** | 8 GB | 16 GB |
| **Memory Mode** | Single Channel | Dual Channel (2x8GB) |
| **Multitasking** | Occasional Swap/Lag | Smooth / No Swap |

---

## 🛠 Installation Steps
1.  **Preparation:** Unplug power and (if laptop) disconnect internal battery.
2.  **Seating:** Insert the new 8GB stick into the empty slot.
    * *Note: Ensure the notch aligns with the key in the slot.*
3.  **Verification:** Boot into Windows and check **Task Manager > Performance > Memory**.
    * Verify "Slots used: 2 of 2".
    * Verify "Speed: [Your Frequency] MHz".



## 📂 Repository Contents
* `benchmarks/`: Before and after logs (e.g., Chrome tab stress tests).
* `specs/`: Screenshots of CPU-Z 'Memory' and 'SPD' tabs to verify dual-channel mode.

