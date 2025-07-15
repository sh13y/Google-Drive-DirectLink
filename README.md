# 🚀 Google Drive Direct Link Generator

Welcome, fellow code explorer! 👋

Ever tried to share a Google Drive file and ended up with a link longer than your last Netflix binge? Or maybe you just want a direct download link—no more “Request Access” drama, no more clicking through Google’s labyrinthine UI. Well, you’re in luck! This project is here to save your day (and your sanity).

## 🎯 What is this?
A super-slick, beginner-friendly web app that:
- Converts your Google Drive share links into direct download links
- Generates a QR code for your link (because typing URLs is so 2010)
- Looks great on your phone, tablet, or desktop (responsive design FTW!)
- Is so easy, even your grandma could use it (but please, teach her about internet safety first)

## 🧑‍💻 Who is this for?
- IT students learning web basics
- Anyone who wants to share files from Google Drive without the hassle
- People who love QR codes (we see you, techies)
- You, if you like fun, simple, and effective tools!

## 🛠️ How do I use it?
1. **Clone or download this repo** (or just open the `index.html` file in your browser—no server needed!)
2. Paste your Google Drive share link into the input box.
3. Click the big, shiny “Generate Direct Link” button.
4. Copy your new direct download link, or scan/download the QR code.
5. Share it with your friends, your boss, or your pet goldfish. (We don’t judge.)

## ✨ Features
- **Direct Link Magic:** Turns those clunky Google links into instant downloads.
- **QR Code Wizardry:** Instantly get a QR code for your link—great for posters, slides, or impressing your classmates.
- **Copy & Test:** Copy the link with one click, or test it in a new tab.
- **Mobile-First:** Works beautifully on phones, tablets, and desktops. Try resizing your browser. Go on, we dare you!
- **Toasts:** Get friendly notifications for your actions. (No, not the breakfast kind.)

## 🤔 How does it work?
- It extracts the file ID from your Google Drive link using a sprinkle of JavaScript regex magic.
- It builds a direct download URL for you.
- It uses the legendary [QRCode.js](https://github.com/davidshimjs/qrcodejs) library to make QR codes.
- All in your browser. No data leaves your computer. (Your secrets are safe!)

## 📝 Example
```
Share Link: https://drive.google.com/file/d/1A2B3C4D5E6F7G8H9I0J1K2L3M4N5O6P7/view?usp=sharing
Direct Link: https://drive.usercontent.google.com/download?id=1A2B3C4D5E6F7G8H9I0J1K2L3M4N5O6P7&export=download&confirm=t
```

## 🧑‍🎓 For Curious Students
- Want to know how the regex works? Check out the `extractFileId` function in the code!
- Want to style it your way? Tweak the Tailwind CSS classes or add your own flair.
- Want to break it? (Please don’t, but if you do, you’ll learn a lot!)

## 🐞 Troubleshooting
- **QR code not showing?** Make sure you’re online (the app loads QRCode.js from a CDN).
- **Link not working?** Double-check your Google Drive permissions. If it’s private, only you can download it!
- **Still stuck?** Ask your favorite teacher, or open an issue on GitHub.

## 👨‍🍳 Credits
- Made with Vue 3, Tailwind CSS, and a dash of Ceylonese love by [sh13y](https://github.com/sh13y)
- QR codes powered by [QRCode.js](https://github.com/davidshimjs/qrcodejs)

## 📢 License
WTFPL – Do What The F*ck You Want To Public License. Seriously, do whatever you want with this code. Copy it, remix it, sell it, print it out and make paper airplanes—just have fun!

Full license in the LICENSE file.

---

Happy sharing, and may your links be ever direct! 🥳 