# ⚔️ Shadow Warrior Training System

A Solo Leveling-inspired calisthenics training app that gamifies your 3-month workout journey with RPG-style progression, leveling system, and achievements.

## 🎯 Features

### Core Functionality
- **Complete 3-Month Program**: Structured progression from beginner to advanced
- **RPG Progression System**: Level up, gain power, and unlock achievements
- **Progress Tracking**: Track completed workouts, exercises, and stats
- **Streak System**: Maintain workout streaks to build consistency
- **Achievement System**: Unlock 8 different achievements throughout your journey
- **Persistent Storage**: All progress saved locally in your browser

### Training Structure
- **Month 1 (Foundation)**: 12 full-body workouts (3x per week)
- **Month 2 (Intensity)**: 16 split routine workouts (4x per week) with skill training
- **Month 3 (Mastery)**: 16 advanced workouts (4-5x per week) with skill mastery

### Stats & Analytics
- Total workouts completed
- Total exercises performed
- Estimated calories burned
- Training time tracked
- Completion percentage
- Training history

## 📱 Installation Instructions

### Option 1: Use as Web App (Recommended for All Devices)

#### iOS (iPhone/iPad)
1. Open Safari and load the `calisthenics-leveling-app.html` file
2. Tap the **Share** button (square with arrow pointing up)
3. Scroll down and tap **"Add to Home Screen"**
4. Name it "Shadow Warrior" and tap **Add**
5. The app icon will appear on your home screen like a native app

#### Android
1. Open Chrome and load the `calisthenics-leveling-app.html` file
2. Tap the **menu** (three dots in top-right)
3. Select **"Add to Home screen"**
4. Name it "Shadow Warrior" and tap **Add**
5. The app will be accessible from your app drawer

#### Desktop (Windows/Mac/Linux)
1. Open the `calisthenics-leveling-app.html` file in any modern browser
2. Bookmark it for easy access
3. **Chrome/Edge**: You can also click the install icon in the address bar to install as a PWA

### Option 2: Host Online

#### Using GitHub Pages (Free)
1. Create a new repository on GitHub
2. Upload the `calisthenics-leveling-app.html` file
3. Rename it to `index.html`
4. Go to Settings → Pages
5. Enable GitHub Pages
6. Access your app at `https://yourusername.github.io/repo-name`

#### Using Netlify (Free)
1. Drag and drop the file to [Netlify Drop](https://app.netlify.com/drop)
2. Get instant deployment with a custom URL
3. Share the URL across all your devices

#### Using Vercel (Free)
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the file's directory
3. Follow prompts to deploy

### Option 3: Local Server (For Development)

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx http-server

# Then open http://localhost:8000 in your browser
```

## 🎮 How to Use

### Getting Started
1. **Open the app** - Launch from home screen or browser
2. **View your stats** - Check your level, power, and progress at the top
3. **Start training** - Tap any workout to begin

### Completing Workouts
1. Tap on a workout card to open it
2. Check off each exercise as you complete it
3. Tap **"Complete Workout"** when all exercises are done
4. Gain 25 EXP and 5 Power points
5. Watch for level-up animations!

### Navigation
- **Training Tab**: View and complete workouts organized by month
- **Stats Tab**: View detailed statistics and training history
- **Achievements Tab**: Track unlocked and locked achievements

### Progression System
- **EXP**: Gain 25 EXP per workout completed
- **Levels**: Each level requires (Level × 100) EXP
- **Power**: Gain 5 power per workout + 10 per level up
- **Streaks**: Workout on consecutive days to build streaks
- **Unlocks**: Complete Month 1 to unlock Month 2, etc.

## 🏆 Achievements

| Achievement | Icon | Requirement |
|-------------|------|-------------|
| First Steps | 🎯 | Complete your first workout |
| Week Warrior | ⚔️ | Complete all workouts in a week |
| Month Master | 👑 | Complete Month 1 |
| Consistency King | 🔥 | Maintain a 7-day streak |
| Halfway Hero | 💎 | Complete 50% of the program |
| Shadow Monarch | 👹 | Complete the entire 3-month program |
| Power Surge | ⚡ | Reach 100 Power |
| Rising Star | 🌟 | Reach Level 10 |

## 💡 Pro Tips

1. **Consistency is Key**: Try to workout at the same time each day
2. **Track Progress**: Check your stats regularly to stay motivated
3. **Don't Skip Rest Days**: Recovery is crucial for muscle growth
4. **Proper Form**: Focus on quality over quantity
5. **Stay Hydrated**: Drink water before, during, and after workouts
6. **Warm Up**: Never skip the warm-up to prevent injuries
7. **Cool Down**: Stretching helps with recovery and flexibility

## 🔧 Technical Details

### Browser Compatibility
- **Chrome**: ✅ Fully supported
- **Safari**: ✅ Fully supported
- **Firefox**: ✅ Fully supported
- **Edge**: ✅ Fully supported

### Storage
- Uses `localStorage` to persist all progress
- Data stays on your device (no cloud sync)
- To backup: Export browser data or use developer tools
- To reset: Clear browser data for the app

### Offline Support
- Works 100% offline once loaded
- No internet connection required
- All data stored locally

### Privacy
- No data collection
- No analytics
- No external API calls
- Everything stays on your device

## 🎨 Design Philosophy

Inspired by Solo Leveling's aesthetic, the app features:
- **Dark Theme**: Easy on the eyes during early morning or late night workouts
- **Cinzel Font**: Epic, warrior-style headers
- **Rajdhani Font**: Clean, modern body text
- **Blue/Purple Gradients**: Power and energy
- **Gold Accents**: Achievement and mastery
- **Smooth Animations**: Level-ups feel rewarding

## 📊 Workout Program Summary

### Month 1: Building Foundation (Weeks 1-4)
- **Frequency**: 3 times per week
- **Focus**: Full body workouts
- **Total Workouts**: 12
- **Key Exercises**: Push-ups, Pull-ups, Dips, Squats, Lunges, Plank

### Month 2: Increasing Intensity (Weeks 5-8)
- **Frequency**: 4 times per week  
- **Focus**: Split routines (Upper/Lower) + Skill training
- **Total Workouts**: 16
- **New Skills**: Handstands, L-Sits
- **Key Exercises**: Pike Push-ups, Glute Bridges, Hanging Leg Raises

### Month 3: Skill Focus & Advanced (Weeks 9-12)
- **Frequency**: 4-5 times per week
- **Focus**: Advanced movements + Skill mastery
- **Total Workouts**: 16
- **Advanced Skills**: Free-standing Handstands, L-Sit Holds, Muscle-Ups
- **Key Exercises**: Decline Push-ups, Archer Push-ups, Pistol Squats, Bulgarian Split Squats

## 🛠️ Troubleshooting

### Progress Not Saving
- Ensure browser allows localStorage
- Check if in incognito/private mode (doesn't save)
- Try clearing cache and reloading

### App Not Loading
- Check console for errors (F12 in most browsers)
- Ensure JavaScript is enabled
- Try a different browser

### Reset Progress
1. Open browser developer tools (F12)
2. Go to Console tab
3. Type: `localStorage.removeItem('shadowWarriorState')`
4. Refresh the page

## 📝 Additional Notes

- **Equipment Needed**: Pull-up bar, parallel bars/bench (optional: resistance bands)
- **Duration**: Each workout takes approximately 45 minutes
- **Modifications**: Adjust reps and sets based on your fitness level
- **Rest**: Take at least one rest day between workouts
- **Nutrition**: Maintain adequate protein intake (1.6-2.2g per kg bodyweight)

## 🌟 Future Enhancements (Optional)

Potential features you could add:
- Exercise video tutorials
- Timer functionality for exercises
- Custom workout creation
- Export progress as PDF
- Social sharing of achievements
- Dark/light theme toggle
- More achievement categories
- Workout reminders/notifications

## 📄 License

This project is open source and available for personal use. Feel free to modify and enhance it for your own needs!

---

**Remember**: The journey of a thousand miles begins with a single workout. Become the Shadow Warrior you were meant to be! ⚔️💪

Start your transformation today!