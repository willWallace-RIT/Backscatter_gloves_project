🧤 Backscatter Gloves

A low-power wearable input device that uses RF backscatter instead of traditional radio transmission.

🚀 Concept

Instead of generating RF signals, this glove modulates and reflects existing RF energy (WiFi, ambient signals) to transmit data.

This enables:

- Ultra-low power operation
- Potential batteryless designs
- Minimal RF hardware

---

⚡ How It Works

1. A nearby RF source (WiFi router, transmitter) emits signals
2. The glove modulates its antenna impedance
3. This creates detectable changes in the reflected signal
4. A receiver decodes those changes into data

---

🧠 Features (Planned)

- Finger position sensing (flex sensors or contact points)
- Gesture encoding (binary / low bitrate)
- Backscatter modulation (OOK / simple switching)
- Optional hybrid mode (BLE fallback)

---

🛠️ Hardware

- Ultra-low-power MCU (ATtiny, nRF52, or similar)
- RF switch (transistor or RF switch IC)
- Antenna integrated into glove (conductive thread or PCB strip)
- Optional:
  - Supercapacitor
  - Energy harvesting (RF / solar)

---

📡 Communication

- Method: Backscatter (OOK modulation)
- Data rate: Very low (gestures, not streaming)
- Range: Experimental (depends on RF environment)

---

🧪 Goals

- Build a functional prototype
- Minimize power consumption
- Explore batteryless wearable input
- Enable spatial/gesture interaction systems

---

🔥 Future Ideas

- Multi-glove interaction mesh
- Passive VR/AR input system
- Environmental sensing via backscatter nodes

---

⚠️ Status

Early-stage experimental project.

---

📜 License

MIT (or TBD)
