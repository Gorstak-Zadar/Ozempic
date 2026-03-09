# 🧹 Ozempic

> Batch script — **Windows Update / SoftwareDistribution cleanup** — stops wuauserv/BITS, deletes SoftwareDistribution, DISM component cleanup, ResetBase.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🛑 **Stop Services** | wuauserv, BITS |
| 🗑️ **SoftwareDistribution** | Deletes `%windir%\SoftwareDistribution` |
| 📦 **DISM** | StartComponentCleanup, ResetBase |
| ⚙️ **Auto-Elevation** | UAC via fsutil/vbs |

---

## 📋 Requirements

| Requirement | Details |
|-------------|---------|
| **OS** | Windows 10/11 |
| **Privileges** | Administrator |

---

## 🚀 Usage

```cmd
:: Run as Administrator
Ozempic.bat
```

---

<p align="center">
  <sub>🧹 Gorstak System Cleanup</sub>
</p>
