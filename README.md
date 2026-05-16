# ⏰ Study Clock

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0.0-pink?style=for-the-badge&logo=clock">
  <img src="https://img.shields.io/badge/Platform-Windows-blue?style=for-the-badge&logo=windows">
  <img src="https://img.shields.io/badge/License-Free-green?style=for-the-badge">
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=30&color=FF6B9D&center=true&vCenter=true&width=400&lines=A+Cute+Study+Companion+App" alt="Study Clock">
</p>

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🍅 **Pomodoro Timer** | Focus timer with customizable work/break durations |
| ⏱️ **Stopwatch** | Precise stopwatch with lap recording |
| 🔔 **Pop-up Notifications** | Desktop notifications when timers complete |
| 🎨 **Cute Theme** | Soft pink & lavender design with smooth animations |
| ⚙️ **Settings** | Fully customizable timer durations |
| 🔽 **System Tray** | Minimize to tray for quick access |

---

## 📸 Screenshots

### Pomodoro Timer
<img width="801" height="767" alt="image" src="https://github.com/user-attachments/assets/e05d6253-987a-48bf-b5eb-30d398fe47da" />


### Stopwatch
<img width="800" height="767" alt="image" src="https://github.com/user-attachments/assets/5c3f95d2-daa6-487e-a50b-2e825aa8b920" />


## 🚀 Guide

### Installation~

```bash
# Navigate to the Here.md
download the archive from the given link in that.

# Extract the Archieve
you can use winrar, 7zip, etc.

# Run the executable
dist\Essential Clock v1\study-clock.exe
```

---

## 📖 How to Use

### 🍅 Pomodoro Timer

1. **Start** - Click the Start button to begin focusing
2. **Pause** - Click again to pause the timer
3. **Reset** - Click Reset to start over
4. **Sessions** - Complete 4 focus sessions to get a long break

> 💡 **Tip:** The timer automatically cycles: Focus → Short Break → Focus → Short Break → Focus → Focus → Focus → Long Break

### ⏱️ Stopwatch

1. **Start** - Begin tracking time
2. **Lap** - Record split times during activity
3. **Stop** - Pause the stopwatch
4. **Reset** - Clear all time and laps

### ⚙️ Settings

Navigate to the **Settings** tab to customize:

| Setting | Default | Range |
|---------|---------|-------|
| Focus Duration | 25 min | 1-60 min |
| Short Break | 5 min | 1-30 min |
| Long Break | 15 min | 1-60 min |
| Sessions before Long Break | 4 | 1-10 |
| Sound | ✅ On | - |
| Pop-up Notifications | ✅ On | - |
| Auto-start Next Session | ❌ Off | - |

---

## ⌨️ Keyboard Shortcuts

| Action | Shortcut |
|--------|----------|
| Start/Pause Timer | `Space` |
| Reset | `R` |
| Navigate: Pomodoro | `1` |
| Navigate: Stopwatch | `2` |
| Navigate: Settings | `3` |

---

## 🔧 Technology Stack

```
Electron 42.x
├── HTML5
├── CSS3 (Custom Properties, Animations)
└── Vanilla JavaScript
```

---

## 📁 Project Structure

```
study-clock/
├── index.html      # Main UI
├── main.js         # Electron main process
├── preload.js      # IPC bridge
├── package.json    # Dependencies
├── SPEC.md         # Design specification
└── dist/
    └── Essential Clock v1/
        └── study-clock.exe  # Executable
```

---

## 🐛 Troubleshooting

### App doesn't start?
- Make sure you're in the `study-clock` folder
- Run as Administrator if needed

### Notifications not working?
- Check Windows notification settings
- Enable in app Settings tab

### Timer not accurate?
- Close other apps that may affect timing

---

## 🙌 Credits

<p align="center">
  Made with 💖 for students everywhere
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=yourgithub&label=Views&color=ff6b9d&style=flat" alt="Profile views">
</p>

---

## 📜 License

MIT License - Feel free to use and modify!

---

<p align="center">
  <strong>Made with ❤️ | Study Smart! 📚</strong>
</p>
