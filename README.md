# FITNESS.TECH Mobile App

A Progressive Web App (PWA) version of the FITNESS.TECH Planner that can be installed on mobile devices as a native app.

## 📱 Installation Instructions

### For iOS (iPhone/iPad)

1. **Transfer the files to your phone:**
   - Send `fitness-tech.html`, `manifest.json`, and `icon-192.png` to your phone via AirDrop, iCloud, or email
   - Place all files in the same folder

2. **Open the HTML file:**
   - Tap on `fitness-tech.html` to open it in Safari

3. **Add to Home Screen:**
   - Tap the **Share** button (square with arrow pointing up) at the bottom of Safari
   - Scroll down and tap **Add to Home Screen**
   - Confirm by tapping **Add** in the top-right corner

4. **Launch the app:**
   - The FITNESS.TECH icon will appear on your home screen
   - Tap it to open as a native app (no Safari toolbar)

### For Android (Chrome)

**Option A - Direct Installation (Simplest):**
1. Transfer all files (`fitness-tech.html`, `manifest.json`, `icon-192.png`) to your phone
2. Open `fitness-tech.html` in Chrome
3. Tap the **three dots** menu in the top-right
4. Tap **Install app** or **Add to Home screen**
5. Confirm installation

**Option B - Hosting (Better Experience):**
1. Upload all files to a web host (GitHub Pages, Netlify, Vercel, or any hosting service)
2. Open the URL on your Android device
3. Chrome will automatically detect the PWA
4. Tap **Install app** from the browser menu
5. The app will be installed with its own icon

### For Desktop Testing

1. Open `fitness-tech.html` in any modern browser
2. The app will work exactly like the mobile version
3. Data is saved to localStorage (persists between sessions)

## ✨ Features

- 📅 **Interactive Calendar** - View and navigate through months
- 💪 **Today's Workout** - See today's scheduled workout at a glance
- 🔥 **Streak Tracking** - Keep track of consecutive workout days
- ⚙️ **Customizable Routines** - Configure your workout cycle
- ✅ **Log Progress** - Mark workouts as complete or missed
- 📝 **Notes** - Add notes to each workout session
- 🌈 **Cyber Theme** - Beautiful animated background with neon styling
- 💾 **Local Storage** - All data saved locally on your device

## 🎨 Customization

1. Tap the **gear icon** in the top-right corner
2. Reorder modules using the **up/down arrows**
3. Edit module names, types, muscle groups, and colors
4. Add new modules with **ADD_MODULE**
5. Save changes with **SAVE_CONFIG**

## 💾 Data Persistence

All workout logs and custom routines are saved to your device's localStorage. This means:
- ✅ Data persists even after closing the app
- ✅ Works offline (no internet needed)
- ⚠️ Data is NOT synced across devices
- ⚠️ Clearing browser cache will delete all data

## 🔧 Troubleshooting

**"Add to Home Screen" option not appearing:**
- Make sure you're using Safari (iOS) or Chrome (Android)
- Try reloading the page first
- Ensure the page is fully loaded before tapping Share

**Data not saving:**
- Check if browser storage is enabled
- Try a different browser
- Ensure you're not in private/incognito mode

**App opens in browser instead of fullscreen:**
- Make sure you've properly added to home screen
- Try re-installing (remove old icon first)
- Verify `manifest.json` is in the same folder as the HTML file

## 📦 Hosting Your PWA

For the best mobile experience, consider hosting your PWA online:

**Free Options:**
- **GitHub Pages** - Push to a GitHub repo and enable Pages
- **Netlify** - Drag and drop the folder
- **Vercel** - Connect your repo
- **Firebase Hosting** - Free hosting for static sites

**Benefits of hosting:**
- Easy sharing with others
- Updates can be deployed remotely
- Better PWA installation experience
- Works offline with service worker caching

## 🎯 Tips

- Log workouts immediately after completing them
- Use the streak tracker as motivation
- Customize your routines to match your actual workout plan
- Add detailed notes to track progress over time

---

**Enjoy your FITNESS.TECH app! 💪🔥**
