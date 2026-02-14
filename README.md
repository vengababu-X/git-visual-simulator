<div align="center">

<!-- TITLE SVG -->
<svg width="100%" height="180" viewBox="0 0 800 180" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="g1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00f3ff">
        <animate attributeName="offset" values="0;1;0" dur="4s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#ffb800"/>
    </linearGradient>
  </defs>

  <rect width="100%" height="100%" fill="#020204"/>

  <text x="50%" y="60%" text-anchor="middle"
        font-size="48"
        font-family="monospace"
        fill="url(#g1)">
    git-visual-simulator
  </text>

  <text x="50%" y="78%" text-anchor="middle"
        font-size="16"
        font-family="monospace"
        fill="#888">
    Learn Git by seeing it, not memorizing it
  </text>
</svg>

</div>

---

## 🧠 What is this?

**git-visual-simulator** is an **interactive, gamified Git learning simulator** designed for beginners.

It teaches Git by:
- Visualizing Git internals
- Simulating real command flow
- Allowing safe mistakes
- Reinforcing concepts with animation and feedback

No backend.  
No setup.  
No fear.

---

## ⚙️ Animated Git Flow

<div align="center">

<svg width="100%" height="220" viewBox="0 0 800 220" xmlns="http://www.w3.org/2000/svg">
  <rect width="100%" height="100%" fill="#000"/>

  <!-- Nodes -->
  <g font-family="monospace" font-size="14" fill="#fff">
    <rect x="60" y="80" width="120" height="50" rx="6" stroke="#00f3ff" fill="none"/>
    <text x="120" y="110" text-anchor="middle">WORKING</text>

    <rect x="250" y="80" width="120" height="50" rx="6" stroke="#ffb800" fill="none"/>
    <text x="310" y="110" text-anchor="middle">STAGING</text>

    <rect x="440" y="80" width="120" height="50" rx="6" stroke="#00ff9d" fill="none"/>
    <text x="500" y="110" text-anchor="middle">REPO</text>

    <rect x="630" y="80" width="120" height="50" rx="6" stroke="#bc13fe" fill="none"/>
    <text x="690" y="110" text-anchor="middle">REMOTE</text>
  </g>

  <!-- Animated Path -->
  <circle r="6" fill="#00f3ff">
    <animateMotion dur="4s" repeatCount="indefinite"
      path="M120 140 L310 140 L500 140 L690 140"/>
  </circle>
</svg>

</div>

---

## 🎮 Features

- 📦 Visual Git zones (Working, Stage, Repo, Remote)
- ⌨️ Real Git commands simulation
- 🧭 Guided learning path (13 missions)
- ⚔️ Error-based feedback system
- 📜 Built-in manual and flowcharts
- 🎨 Cyberpunk UI, zero dependencies

---

## 🧪 Commands Covered

```bash
git init
git status
git add .
git commit -m "message"
git log
git branch
git checkout
git stash
git stash pop
git reset
git merge
git remote add
git push

```
---

🚀 How to Run

git clone https://github.com/your-username/git-visual-simulator
cd git-visual-simulator
open index.html

That’s it.
No install. No build. No nonsense.


---

🎯 Who is this for?

Git beginners

Students & workshops

Visual learners

Anyone tired of breaking repos


Not for Git veterans rewriting history at 3am. They already suffer enough.


---

🏆 Goal

Help users understand how Git actually works before touching real repositories.

Fearless Git > Memorized Git.


---

📜 License

MIT License.
Learn freely. Break nothing.



----

<div align="center"><svg width="100%" height="100" viewBox="0 0 800 100" xmlns="http://www.w3.org/2000/svg">
  <rect width="100%" height="100%" fill="#020204"/>
  <text x="50%" y="60%" text-anchor="middle"
        font-size="14"
        font-family="monospace"
        fill="#666">
    Built to teach. Not to intimidate.
  </text>
</svg></div>

