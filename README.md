# Roblox ESP + Aimbot Base  
**Offline Development Tool (Studio Only)**

![Roblox ESP Example](https://i.imgur.com/ROBLOX_ESP.png)  
*Red boxes on players — perfect for testing AI or debugging!*

---

## What Is This?

A **super simple, safe tool** that:
- Draws **red boxes** around players in **your own Roblox game**
- Lets you **aim at heads** by holding **Left Mouse Button**
- Works **only in Roblox Studio** or **local server**

> **100% Legal & Safe** — **No bans** — because it's **your game**.

---

## Why Use This?

Perfect for:
- Learning how game hacks work
- Testing AI bots in your game
- Debugging player positions
- Making cool dev tools

---

## Features (Super Easy)

| Feature        | Hotkey       | What It Does |
|----------------|--------------|-------------|
| **Toggle All** | `Insert`     | Turn tool ON/OFF |
| **ESP Boxes**  | `Home`       | Toggle red boxes |
| **Aimbot**     | `End` + LMB  | Hold LMB → aim at head |

---

## How to Use (Step-by-Step)

### Step 1: Open Roblox Studio
1. Open **Roblox Studio**
2. Create or open **your own game**
3. Click **Play Solo** (or **Start Server + Play**)

### Step 2: Build the Tool
1. Open this folder
2. **Double-click `BUILD.bat`**
   - Wait 10 seconds → `RobloxDevTool.exe` appears

### Step 3: Run the Tool
1. **Right-click `RobloxDevTool.exe` → Run as Administrator**
2. Console says “Waiting for Roblox...”
3. Once Studio is detected → **you’re in!**

### Step 4: Use Hotkeys
- Press `Insert` → tool turns on
- Press `Home` → red boxes appear
- Press `End` + **hold LMB** → aimbot works

---

## It Stopped Working? (Offsets Changed)

Roblox updates → tool breaks.

**Fix in 2 minutes:**

1. Open **Cheat Engine**
2. Attach to `RobloxPlayerBeta.exe`
3. Find your **health** (float) or **position** (3 floats)
4. Update numbers in `src/main.cpp`
5. Double-click `BUILD.bat`

**See `AUTO_UPDATE_GUIDE.txt` for pictures!**

---

## Is This Safe?

| Question | Answer |
|--------|--------|
| Will I get **banned**? | **NO** — it’s your game |
| Can I use in **public games**? | **NEVER** — don’t even try |
| Is this **legal**? | **YES** — for your own games |

---

## Want to Learn More?

- Open `src/main.cpp` — it’s **simple C++**
- Change `smooth = 0.5f` → slower/faster aim
- Change `fov = 90.0f` → bigger aim range

---

## Credits

- Built with love by **Dotty**
- Auto-finds `DataModel` from logs
- GDI+ overlay (safe & external)

---

**Happy developing!**  
*Never use in public games. Stay safe. Build cool stuff.*
