# Shadow Warrior Training System 🗡️

A gamified workout tracker inspired by Solo Leveling, designed to help you build strength through a structured 3-month calisthenics program.

## Features

- **Progressive Training Program**: 3-month structured workout plan
- **Gamification**: Level up, gain power, earn achievements
- **Track Progress**: Monitor workouts, streaks, and stats
- **Responsive Design**: Works on mobile and desktop
- **Local Storage**: All your progress is saved locally

## How to Deploy to Vercel

Since this is a static HTML site, you need to:

1. Add these files to your repository:
   - `package.json`
   - `vercel.json`

2. Commit and push:
   ```bash
   git add .
   git commit -m "Add Vercel config files"
   git push origin master
   ```

3. Deploy:
   ```bash
   vercel --prod
   ```

## Running Locally

Simply open `index.html` in your browser, or use a local server:

```bash
# Python 3
python3 -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (if you have http-server installed)
npx http-server
```

Then open `http://localhost:8000` in your browser.

## Program Overview

### Month 1: Foundation
- 3 workouts per week
- Full body training
- 12 total workouts

### Month 2: Intensity
- 4 workouts per week
- Split routines (Upper/Lower)
- Skill work introduction
- 16 total workouts

### Month 3: Mastery
- 4-5 workouts per week
- Advanced skills
- Peak performance
- 16 total workouts

## Technologies Used

- HTML5
- CSS3 (with custom properties and animations)
- Vanilla JavaScript
- LocalStorage API
- Google Fonts (Cinzel & Rajdhani)

## License

MIT