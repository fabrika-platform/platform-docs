# Drivesfrom pathlib import Path

markdown_content = """# 📺 Displays  
## Overview

**Product number designation:**  
Každý produkt má svoje označenie pozostávajúce z častí podľa tejto štruktúry:

---

### 🧠 Processor Type

| Kód  | Typ procesora   |
|------|------------------|
| `32`  | ESP32-S3         |
| `32P` | ESP32-P4         |
| `32S` | STM32            |
| `CM`  | Compute Module   |

---

### 🖥️ Screen Size

| Kód    | Uhlopriečka |
|--------|-------------|
| `.3`   | 3,5"        |
| `.4`   | 4,3"        |
| `.5`   | 5"          |
| `.7`   | 7"          |
| `.10`  | 10"         |
| `.15`  | 15"         |
| `.21`  | 21"         |

> **Poznámka:**  
> - `stepHMI 32` ➝ max. veľkosť 7"  
> - `stepHMI CM` ➝ max. veľkosť 21"

---

### 🧱 Assembly (montáž)

| Kód   | Umiestnenie     |
|-------|------------------|
| `.1`  | na panel         |
| `.2`  | do panelu        |
| `.3`  | na stenu         |
| `.4`  | do steny         |
| `.5`  | vreckové/pocket  |

---

### ⚡ Power Supply

| Kód   | Typ napájania |
|-------|----------------|
| `.1`  | +24V DC        |
| `.2`  | 230V AC        |
| `.3`  | PoE            |

---

### 🌐 Ethernet

| Kód   | Typ rozhrania |
|-------|----------------|
| `.0`  | bez            |
| `.1`  | W5500          |
| `.2`  | LAN78xx        |

---

### 🔌 Serial Interface

| Kód | Typ sériového rozhrania |
|-----|--------------------------|
| `0` | bez                      |
| `1` | RS232                    |
| `2` | RS485                    |
| `3` | RS232/RS485              |

---

### 🚌 CAN

| Kód | Podpora |
|-----|---------|
| `0` | bez     |
| `1` | áno     |

---

### 📡 GSM

| Kód | Podpora |
|-----|---------|
| `0` | bez     |

---

### 📍 GPS

| Kód | Podpora |
|-----|---------|
| `0` | bez     |

---

### 📶 LoRa

| Kód | Podpora |
|-----|---------|
| `0` | bez     |

---

### 🧩 Extension

| Kód    | Rozšírenie |
|--------|-------------|
| `.000` | bez         |
| `.001` | (nešpec.)   |
| `.002` | (nešpec.)   |
| `.003` | (nešpec.)   |
| `.004` | SSR         |

---

### 🔖 Version

| Kód   | Verzia |
|-------|--------|
| `.10` | v1.0   |
| `.11` | v1.1   |
| `.12` | v1.2   |
| `.13` | v1.3   |

---

## 📦 Príklady označenia produktov

```text
stepHMI 32.5.2.1.000001.000.10
stepHMI CM5.7.2.1.001.000.10
stepHMI CM5.10.2.1.001.000.10
