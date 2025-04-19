<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Zhal-Tarithal Calendar Wheel</title>
  <style>
    body {
      background: #0a0a0a;
      font-family: 'Segoe UI', sans-serif;
      color: #eee;
      text-align: center;
      padding: 2rem;
    }
    .calendar-wheel {
      position: relative;
      width: 600px;
      height: 600px;
      margin: 2rem auto;
      border-radius: 50%;
      border: 6px double #ccc;
      background: radial-gradient(circle, #111, #000);
      display: flex;
      justify-content: center;
      align-items: center;
    }
    .segment {
      position: absolute;
      width: 50%;
      height: 50%;
      transform-origin: 100% 100%;
      text-align: right;
    }
    .segment span {
      display: inline-block;
      padding: 6px 12px;
      background: rgba(255,255,255,0.05);
      border-radius: 8px;
      color: #fff;
      font-size: 0.8rem;
      white-space: nowrap;
    }
    .center-symbol {
      position: absolute;
      width: 80px;
      height: 80px;
      background: #333;
      border: 3px solid #888;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 2rem;
      color: #fff;
      box-shadow: 0 0 30px #00f0ff66;
    }
  </style>
</head>
<body>

<h1>🕯️ Zhal-Tarithal – Fractured Calendar Wheel</h1>
<p>13 Recursive Months, tied to the sacred glyphs of Xel’tharuun.</p>

<div class="calendar-wheel">
  <div class="center-symbol">👁️</div>
  <!-- 13 segments, evenly rotated -->
  <script>
    const months = [
      "Vaqun", "Zhel’run", "Ethra", "Kurathe", "Thavrek", "Xel’maar", "Loruun",
      "Zhazel", "Trivhal", "Mirthaal", "Shuuneth", "Qavreth", "Vorthuun"
    ];
    const wheel = document.querySelector(".calendar-wheel");
    months.forEach((month, i) => {
      const angle = (360 / 13) * i;
      const el = document.createElement("div");
      el.className = "segment";
      el.style.transform = `rotate(${angle}deg) translate(-100%, -100%)`;
      el.innerHTML = `<span>🌀 ${month}</span>`;
      wheel.appendChild(el);
    });
  </script>
</div>

<h2>🧠 Calendar Facts</h2>

- 📅 **13 months**, 28 days each → **364-day year**  
- ✨ Every 7th year includes **Void Day** – a day *outside time*
- 🌀 Months tied to **glyphs of recursion** – spiritual & mathematical
- 📚 Glyphs used in **Trivh'Math**, sacred texts, and dream rituals

---

## 🔤 Glyphs of the Months (Placeholder Representation)

| Month | Glyph | Meaning |
|-------|-------|---------|
| Vaqun | 🔷 | Awakening of form |
| Zhel’run | 🌀 | First recursion |
| Ethra | 🔺 | Memory imprint |
| Kurathe | 🧩 | Written thought |
| Thavrek | 🪞 | The inverse | 
| Xel’maar | 🌌 | Skin of god |
| Loruun | 🔮 | Ascended cognition |
| Zhazel | 🧠 | Fractured dream |
| Trivhal | 📿 | Pattern meditation |
| Mirthaal | 🌗 | Hidden mirrors |
| Shuuneth | 🜂 | Fire of mind |
| Qavreth | 🕸️ | Entangled fate |
| Vorthuun | 🗝️ | Gate of return |

---

## 🎉 Sacred Festivals

| Name | Meaning | Ritual |
|------|---------|--------|
| **Vakel’run** | First Glyph Day | Recite one’s ancestral glyph |
| **Trivalen** | Day of Patterning | Draw life-paths in spiral ink |
| **Xel’quoneth** | Eclipse of Perception | Fast from sound and language |
| **Loruun’s Descent** | Arrival of Loruun | Read sacred verses in silence |
| **Zhazet-Kul** | Festival of Fracture | Build & collapse recursive towers |
| **Mirron’fall** | Shattering of the Ego | Break mirrors and chant |

---

## 🧠 Trivh’Math Example

```markdown
Glyph(3) ∴ Glyph(7) = ∴∴Glyph(10)
(∴ means “folded into”)
