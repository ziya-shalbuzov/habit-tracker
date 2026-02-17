# Habit Tracker

A simple, offline habit tracker with a full-year calendar and a GitHub-style activity heatmap.

## Overview

Habit Tracker is a no-nonsense tool for tracking daily habits. There are no accounts, no servers, and nothing to configure. You just open it and start marking days.

The app shows all 12 months of the year on one screen. Click a day when you’ve done your habit. Below that, a GitHub-style heatmap gives you a quick visual overview of how consistent you’ve been over the year.

## Features

### Full-Year Calendar
- All 12 months visible at once  
- Click any day to toggle it on or off  
- Clear visual feedback  
- Handles real dates correctly (including leap years)

### GitHub-Style Heatmap
- Yearly activity view  
- Automatically reflects the calendar  
- Easy way to spot streaks and gaps  
- Read-only summary for motivation

### Offline & Private
- Works without an internet connection  
- Runs entirely in your browser  
- Data is saved locally on your device  
- No accounts, tracking, or data collection

### Zero Dependencies
- Single HTML file  
- No frameworks or libraries  
- No build step  
- Just open and use

## Design Ideas

**You decide what counts**  
There’s no definition of “success” built in. A completed day means whatever you want it to mean.

**Generic on purpose**  
It’s not locked to fitness, productivity, or any specific habit. Use it for anything.

**Offline first**  
Your data never leaves your computer.

**Minimal and focused**  
No reminders, no gamification, no noise—just the habit and the calendar.

## Getting Started

1. Download `index.html`  
2. Open it in any modern browser  
3. Click days as you complete your habit  
4. Watch the heatmap fill up over time  

That’s all there is to it.

## Examples of Use

- 🏃‍♂️ Workouts  
- 📚 Studying or reading  
- 🧘‍♀️ Meditation  
- 💻 Coding or side projects  
- 🎨 Creative work  
- 💤 Good sleep nights  
- 🚭 Staying off a bad habit  
- ✅ Any daily goal you care about  

## Technical Notes

- Everything lives in one file (HTML, CSS, JS)  
- Uses `localStorage` to save progress  
- No backend, no server  
- Works on desktop and mobile  
- Written with modern JavaScript  
- Uses semantic HTML and readable contrast

## Browser Support

Works in all modern browsers:
- Chrome / Edge  
- Firefox  
- Safari  
- Mobile browsers (iOS and Android)

## Privacy

- No analytics  
- No cookies  
- No accounts  
- No network requests  
- Your data stays on your device

## How It Works

1. Click a day to mark it complete  
2. The state is saved in `localStorage`  
3. The heatmap updates automatically  
4. Each year is tracked separately  

## Core Principles

1. Keep it simple  
2. Manual input only  
3. Visual progress over numbers  
4. Offline by default  
5. Local data only  
6. No distractions  

## Contributing

Feel free to fork it, tweak it, or build on top of it. The code is intentionally small and easy to change.

## License

Free and open source. Use it however you want.

## Why This Exists

Most habit trackers try to do too much: cloud sync, social features, subscriptions, streak anxiety, and data collection.

This one doesn’t.

It gives you a calendar. You mark days. You see progress.

That’s the whole point.
