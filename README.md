# IB Grade Tracker

A professional IB (International Baccalaureate) grade tracking web application with weighted assessment support.

## Features

- 📊 **Dashboard**: Track up to 6 subjects with real-time grade predictions (0-42 total)
- ⚖️ **Optional Weighted Grading**: Organize assessments by category (Tests, Homework, etc.) with custom weights
- 📈 **Trends Chart**: Visualize grade progression over time
- 👤 **Profile Customization**: Add your name, grade level, and profile picture
- 📥 **Import/Export**: Backup and restore your data as JSON
- 💾 **Local Storage**: All data stored securely in your browser (no server required)

## How to Use

1. **Open** `index.html` in your web browser
2. **Add Subjects**: Click "+ Add Subject" and choose between SL or HL
3. **Add Assessments**: Click on a subject to add grades
4. **Enable Weighting** (Optional): Go to Settings → enable "Assessment Weighting" to organize by categories
5. **Track Trends**: View your grade progression in the Trends tab

## Weighting System

When enabled, instead of adding assessments directly:
1. Click "Setup Weights" to create categories (Tests: 80%, Homework: 20%, etc.)
2. Click into each category to add assessments
3. Grades are automatically weighted and calculated

Total weight must not exceed 100%.

## Profile Settings

- **Name**: Your full name (optional)
- **Grade**: Your current school year (optional)
- **Profile Picture**: Upload a custom image (optional)

If all fields are blank, no profile is displayed.

## Data Management

- **Export**: Download all your data as a JSON file for backup
- **Import**: Restore data from a previously exported JSON file
- **Clear All**: Delete everything (careful!)

All data is stored in your browser's localStorage and is not sent anywhere.

## Technical Details

- Pure HTML/CSS/JavaScript - no dependencies except Chart.js
- Works offline
- Responsive design (mobile & desktop)
- Cool IB tab icon

## Browser Compatibility

- Chrome/Edge: ✅ Full support
- Firefox: ✅ Full support
- Safari: ✅ Full support
- Mobile browsers: ✅ Full support

## Installation

No installation needed! Just download `index.html` and open it in your browser.

---
CREATED WITH PERPLEXITY AI
**Made with ❤️ for IB students**
