<h1 align="center">📘 Data Representation and Number Systems</h1>

<p align="center">
  <em>A comprehensive guide to number systems and data representation in modern computing</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen" alt="Status">
  <img src="https://img.shields.io/badge/Topic-Number%20Systems-blue" alt="Topic">
  <img src="https://img.shields.io/badge/License-Educational-orange" alt="License">
</p>

---

## 📋 Quick Copy — Full README

<button onclick="copyREADME()" style="background:#2ea44f;color:white;border:none;padding:10px 20px;border-radius:6px;cursor:pointer;font-size:14px;">📋 Copy Full README</button>

<script>
function copyREADME() {
  const text = `# 📘 Data Representation and Number Systems

A comprehensive guide to understanding number systems and data representation in modern computing.

## 👥 Group Members
| Name | Registration Number |
|------|---------------------|
| AMANYA AARON | M26B13/006 B36757 |
| WADEJE AARON DAVID | M26B13/042 B36791 |
| NOKUKUNDAKWE MARTHA | M26B13/035 B36784 |
| KABATETSI SHILLA | M26B13/020 B36769 |
| KAINEYESU MELISSA | M26B13/021 B36770 |
| WAIHE SAMUEL | M26BB13/050 B38041 |

## 🔢 Number Systems
- Decimal (Base 10)
- Binary (Base 2)
- Octal (Base 8)
- Hexadecimal (Base 16)

## 🌍 Applications
- Mobile Phones
- Computer Memory & Storage
- Internet Communication
- Digital Images
- Audio & Video Systems

## 📚 References
- Computer Systems: A Programmer's Perspective — Bryant and O'Halloran
- Chapter 10: Computer Organisation Architecture (Page 357)`;
  
  navigator.clipboard.writeText(text).then(() => {
    alert('✅ README copied to clipboard!');
  }).catch(err => {
    alert('❌ Failed to copy: ' + err);
  });
}
</script>

---

## 👥 Group Members

| Name | Registration Number |
|------|---------------------|
| AMANYA AARON | M26B13/006 B36757 |
| WADEJE AARON DAVID | M26B13/042 B36791 |
| NOKUKUNDAKWE MARTHA | M26B13/035 B36784 |
| KABATETSI SHILLA | M26B13/020 B36769 |
| KAINEYESU MELISSA | M26B13/021 B36770 |
| WAIHE SAMUEL | M26BB13/050 B38041 |

---

## 📖 Overview

This project explores **how computers represent, process, store, and transmit data** using different number systems. It covers the four main number systems used in computing, their importance, conversion techniques, and real-world applications.

---

## 🔢 Number Systems Covered

### 1. Decimal Number System (Base 10)
- **Digits:** 0 – 9
- **Importance:** Used by humans, easier calculations, converted to binary for processing

### 2. Binary Number System (Base 2)
- **Digits:** 0 and 1
- **Importance:** Core of all computer processing, stores data & instructions
- **Why binary?** Electronic devices have two states — **ON (1)** and **OFF (0)**

### 3. Octal Number System (Base 8)
- **Digits:** 0 – 7
- **Importance:** Shortens long binary numbers, easier for programmers

### 4. Hexadecimal Number System (Base 16)
- **Digits:** 0 – 9 and A – F (A=10, B=11, C=12, D=13, E=14, F=15)
- **Importance:** Shorter binary representation, used in programming, web design, memory addresses

---

## 🔄 Conversion Examples

<button onclick="copyCode('conv')" style="background:#0366d6;color:white;border:none;padding:6px 14px;border-radius:6px;cursor:pointer;font-size:13px;">📋 Copy Conversion Table</button>

<pre id="conv">
Binary → Decimal:    10110₂ = 22₁₀
Decimal → Binary:    37₁₀ = 100101₂
Decimal → Octal:     145₁₀ = 221₈
Decimal → Hex:       350₁₀ = 15E₁₆
Hex → Decimal:       3F₁₆ = 63₁₀
Binary → Octal:      101111₂ = 57₈
Binary → Hex:        1111000₂ = F2₁₆
</pre>

<script>
function copyCode(id) {
  const el = document.getElementById(id);
  const text = el.innerText;
  navigator.clipboard.writeText(text).then(() => {
    alert('✅ Copied!');
  });
}
</script>

---

## 🌍 Real-World Applications

| Application | Description |
|-------------|-------------|
| 📱 Mobile Phones | Binary runs apps, calls, messages, photos |
| 💾 Memory & Storage | Bits and bytes store all data |
| 🌐 Internet | Data transmitted in binary packets |
| 🖼️ Digital Images | Binary values represent colors & pixels |
| 🎵 Audio & Video | Converted to binary for storage & playback |

---

## 💡 Practical Demo: Traffic Light System

| Red | Yellow | Green | Binary |
|-----|--------|-------|--------|
| ON | OFF | OFF | 1, 0, 0 |
| OFF | ON | OFF | 0, 1, 0 |
| OFF | OFF | ON | 0, 0, 1 |

---

## ❓ Key Questions Addressed

**1. Why is hexadecimal preferred over long binary numbers?**
> Shorter, easier to read, reduces errors in networking and programming.

**2. What challenges if computers used decimal internally?**
> Hardware would become more complicated, slower, and less reliable.

**3. How does understanding number systems help IT professionals?**
> Essential for networking, memory systems, programming, cybersecurity, and troubleshooting.

---

## 📚 References

- *Computer Systems: A Programmer's Perspective* — Bryant and O'Halloran
- Chapter 10: Computer Organisation Architecture (Page 357)

---

## 🛠️ Tools Used

- Microsoft PowerPoint
- Microsoft Word
- GitHub

---

## 📌 How to Use

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
