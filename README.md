<div align="center">
  <br />
  <a href="/litAmor_main/assest/Screenshot 2025-06-20 at 21-41-33 SoloSpark.png" target="_blank">
  </a>
  <br />

  <h3 align="center">✨ Solo Sparks - Emotional Growth Tracker</h3>

  <div align="center">
    Explore emotional intelligence with a gamified experience and unlock your hidden potential. Built with love 💖 and logic ✨.
  </div>
</div>

---

## 📋 Table of Contents

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🌟 [Key Features](#key-features)
4. 🎯 [Quick Start](#quick-start)
5. 🧩 [Hidden Tab Logic](#hidden-tab)
6. 📸 [Preview Screenshots](#screenshots)
7. 🚀 [More](#more)

---

## 🤖 Introduction

**Solo Sparks** is a self-discovery platform designed to help users grow emotionally through personal quests. The app offers a journey of reflection, growth, and awareness.

Whether you're struggling with self-awareness or looking to boost your emotional skills—Solo Sparks gives you a space to evolve.

---

## ⚙️ Tech Stack

- HTML5
- Tailwind CSS
- Vanilla JavaScript
- LocalStorage (for user progress)
- Custom Animations

---

## 🌟 Key Features

- 🧠 Emotion-based user journeys
- 🔒 Hidden content that unlocks after quest completion
- 🌈 Aesthetic neon visuals
- 🕹️ Interactive user experience
- 🎯 Personalized quest tasks
- 💡 Mood tracker and habit-forming tasks

---

## 🎯 Quick Start

```bash
# Clone this repository
git clonehttps://github.com/Mus-1kan/Solo--Spark
cd solo-sparks

# Open in browser
just open index.html in your browser
```

## 🎯 Hidden Tab
🧩 <a name="hidden-tab">How Hidden Tab Works</a>
 <img src="/litAmor_main/assest/Screenshot 2025-06-20 at 21-42-21 SoloSpark.png" alt="Reflection Task" width="100%" /> 

  🔐 Important: The "How It Works" section in Solo Sparks remains hidden by default.

To unlock it:

    Complete all required reflection tasks on the landing page

    The app uses localStorage to check for completion status

    Once done, the "How It Works" section becomes visible with animation

```bash

#If you're a developer, you’ll find the conditional logic inside the file:

if (localStorage.getItem("tasksCompleted") === "true") {
  document.querySelector("#howItWorks").classList.remove("hidden");
}
```
## 📌 This ensures users engage meaningfully before jumping into explanations.
📸 Preview Screenshots <a name="screenshots"></a>
<p align="center"> <img src="/litAmor_main/assest/Screenshot 2025-06-20 at 21-41-33 SoloSpark.png" alt="Home Page" width="100%" /> <br><br> <img src="/litAmor_main/assest/Screenshot 2025-06-20 at 21-42-21 SoloSpark.png" alt="Reflection Task" width="100%" /> <br><br> <img src="/litAmor_main/assest/Screenshot 2025-06-20 at 21-42-33 SoloSpark.png" alt="How It Works Section" width="100%" /> </p>

##🚀 More

Want to add personalized journeys or emotion-matching AI? Join us in v2 soon! For now, enjoy the neon vibes and introspective sparkle ✨

© 2025 Solo Sparks by Muskan Tripathi. All rights reserved.


---

### ✅ Next Steps:

1. Save this content in `README.md` inside your root folder.
2. Push it to GitHub:
```bash
git add README.md
git commit -m "Add Solo Sparks README"
git push origin main

Want me to include dynamic badges for commits, stars, or live site too?
