# Funzy Land 

A playful web portal featuring three categories of interactive games: Puzzle, Action, and Funny Fill-in stories.

## Features

### Game Categories
1. **Puzzle Games** - Brain-teasing challenges
   - Matching games
   - Picture puzzles
   - Code cracking
   - Logic challenges

2. **Action Games** - Fast-paced adventures
   - Animal-themed sports
   - Quick reflex challenges
   - Arcade-style games

3. **Funny Fill-in** - Creative storytelling
   - Mad-lib style word games
   - Customizable stories
   - Shareable results

## Technical Details

### File Structure
```
funzy-land/
├── assets/
│ ├── css/
│ │ └── styles.css
│ ├── img/
│ │ └── logo.jpg
│ └── shared/
│ ├── action.php
│ ├── fill.php
│ └── puzzle.php
├── index.php
└── README.md
```


### Requirements
- PHP 7.0+
- Web server (Apache/Nginx)
- Modern web browser

### Installation
1. Clone repository to your web server
2. Ensure PHP is properly configured
3. Access via web browser

## Game Content Sources
All games are embedded from trusted educational sources including:
- National Geographic Kids
- Edge Digital Media
- Educational game providers

## How to Use
1. Select a game category from the main navigation
2. Choose a specific game from the displayed cards
3. Games load in responsive iframes
4. Use fullscreen mode for best experience

## Customization
Edit these files to modify:
- `styles.css` - Visual styling
- `shared/*.php` - Game listings
- `index.php` - Main layout

## Troubleshooting
If games don't load:
1. Verify PHP is running
2. Check file permissions
3. Ensure all files are in correct locations
4. Test with browser console for errors
