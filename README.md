# 📵 Distraction Blocker Extension

> **"Excess of everything is always positioned."**  
> – A reminder that too much of anything eventually dominates your space.

## 🛡️ About the Project

This is a **browser extension** built to help users stay focused by **blocking distracting websites** . The extension promotes digital mindfulness and control over addictive content.

## 🚀 Features

- ✅ Easy to customize with your own blocked sites
- ⚙️ Lightweight and privacy-first
- 📂 100% Open Source

## 🛠️ How to Use

1. Clone or download this repository.
2. Go to your browser’s **Extensions** page.
3. Enable **Developer Mode**.
4. Click **Load Unpacked** and select the extension folder.
5. You're set! The extension will now block the configured sites.

## 🌐 Customize Blocked Sites

To block different websites, just edit the `matches` in `manifest.json`:

```json
"matches": [
    "*://*.example1.com/*",
    "*://*.example2.com/*"
]
```

Just Replace the example1.com and example1.com . 
If you want to add more than two website then you can add like this 

```json
"matches": [
    "*://*.example1.com/*",
    "*://*.example2.com/*",
    "*://*.example3.com/*",
    "*://*.example4.com/*",
              . 
              . 
              . 
]
```

>And Just remember one thing for the last website name do not give the `,`

## Your screen 

After finishing the all the setups . And go that website then you will find this . 
![Image](Src/image.png)