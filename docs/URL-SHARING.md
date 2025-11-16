# URL Sharing Feature

## Overview
Each day in the advent calendar now has its own unique URL that can be shared directly.

## URL Format
To link to a specific day, use the following URL format:
```
index.html#day-N
```

Where `N` is the day number (1-25).

## Examples
- Day 1 (Welcome): `index.html#day-1`
- Day 2 (Code of Conduct): `index.html#day-2`
- Day 3 (Balancing Openness and Security): `index.html#day-3`
- Day 4 (InnerSource Ambassadors): `index.html#day-4`
- ...and so on

## Features
1. **Direct Links**: Share a specific day by copying the URL from your browser
2. **Auto-Open**: When someone clicks a day-specific link, that day automatically opens
3. **Browser Navigation**: The browser's back/forward buttons work as expected
4. **Shareable**: Perfect for social media, emails, or documentation

## Usage

### For Users
1. Click on any active day in the calendar
2. The URL will automatically update to include `#day-N`
3. Copy and share that URL with others
4. When they visit the URL, that specific day will open automatically

### For Developers/Marketers
Create direct links to specific days:
```html
<a href="index.html#day-1">Check out Day 1!</a>
<a href="index.html#day-5">See Day 5</a>
```

## Technical Details
- Uses URL hash fragments (`#day-N`)
- Works with static hosting (GitHub Pages, etc.)
- No server-side configuration required
- Maintains single-file architecture
- Supports browser history (back/forward buttons)
