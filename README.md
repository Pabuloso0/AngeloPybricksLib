<div align="center">

<img src="docs/assets/banner.png" width="100%">

# 🤖 AngeloPybricksLib

### Advanced Motion Library for FIRST LEGO League Robots using Pybricks

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)]
[![Pybricks](https://img.shields.io/badge/Pybricks-Compatible-orange?style=for-the-badge)]
[![FLL](https://img.shields.io/badge/FLL-Competition_Ready-red?style=for-the-badge)]
[![MIT License](https://img.shields.io/badge/License-MIT-success?style=for-the-badge)]
[![Status](https://img.shields.io/badge/Status-Active_Development-brightgreen?style=for-the-badge)]

---

### 🚀 Precision • Speed • Reliability • Performance

Biblioteca avançada para desenvolvimento de robôs FLL utilizando Pybricks.

</div>

---

## 📊 Estatísticas da Biblioteca

<div align="center">

| Recurso                  | Status |
| ------------------------ | ------ |
| 🚗 Movimento Giroscópico | ✅     |
| 🔄 Curvas Proporcionais  | ✅     |
| 🎯 Controle PID          | 🚧     |
| ⚡ Motion Profiling      | 🚧     |
| 📍 Odometry              | 📅     |
| 🛣 Path Following        | 📅     |

</div>

---

## 🎥 Demonstração

<p align="center">
<img src="docs/assets/demo.gif" width="800">
</p>

---

## 🏗 Arquitetura da Biblioteca

```text
                AngeloPybricksLib
                        │
        ┌───────────────┼───────────────┐
        │               │               │
        ▼               ▼               ▼
  Movement.py      Turning.py     Attachments.py
        │               │               │
        └───────┬───────┴───────┬───────┘
                ▼               ▼
            PID.py          Menu.py
```
