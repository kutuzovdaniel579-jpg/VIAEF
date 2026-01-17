# VIÆF — Powered by FoL
*A modern multilingual vocabulary platform built on structure, clarity, and Latin roots.*

**VIÆF** (pronounced *VIAE*, using the classical **Æ** ligature) is an open, modular learning platform focused primarily on **Latin**, with structured support for **English, French, Dutch, and Russian**.  
The project is developed under **FoL — OpenFluxLab**, emphasizing clean data design, consistency, and developer-friendly formats.

---
## 🌐 Overview
VIÆ provides a lightweight JSON-based vocabulary engine designed for:

- language learners  
- developers building language tools  
- educational platforms  
- automated quiz or lookup systems  

Every vocabulary entry follows a strict, unified schema, making the dataset predictable, scalable, and easy to integrate.

---

## 📚 Supported Languages
**For Learning:**
- Latin
- Greek

**Website Languages:**
- Dutch


**Comming Soon:**
```
- English
- French
- Dutch
- Russian
```
---

## 🧩 Data Structure

This is the json structure we use and may change in the future
```json
{
  "word": {
    "NL": "Dutch meaning",
    "LA": "Latin form",
    "Gen": "Genitive / grammar info",
    "Tel": "Roman numeral (optional)"
  }
}
```

---
## 📰 Version Structure

The Version structure is as followed
```
1.22.333.444.555
```
- 1 stands for VIÆF 1
- 2 stands for mayor updates
- 3 stands for small updates
- 4 stands for mayor bug fixes
- 5 stands for small bug fixes
