# TikTok Clone

A React-based video streaming platform that mimics the TikTok user experience.

## Features Implemented

1. **Core Video Player**
   - Vertical swipe navigation (up/down)
   - Auto-play when in view
   - Pause when out of view
   - Video title overlay

2. **UI Components**
   - Like, comment, and share buttons
   - Responsive design for mobile and desktop
   - Touch swipe support for mobile devices
   - Keyboard navigation for desktop testing

3. **User Experience**
   - Random video shuffle on reload
   - Smooth transitions between videos
   - Intuitive navigation controls

## Technology Stack

- React.js
- Tailwind CSS
- JavaScript (ES6+)

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Add your videos:
   - Place your .mp4 video files in the `public/videos` folder
   - Update the `src/videos.json` file with the correct paths and titles

3. Start the development server:
   ```bash
   npm start
   ```

4. Build for production:
   ```bash
   npm run build
   ```

## How to Use

### Mobile
- Swipe up to go to the next video
- Swipe down to go to the previous video

### Desktop
- Use the arrow keys (up/down) to navigate between videos
- Use the navigation buttons at the bottom of the screen

## Project Structure

```
tiktok-clone/
├── public/
│   ├── videos/
│   │   ├── video1.mp4
│   │   ├── video2.mp4
│   │   └── video3.mp4
│   └── index.html
├── src/
│   ├── App.js
│   ├── index.js
│   ├── index.css
│   └── videos.json
├── package.json
├── tailwind.config.js
└── postcss.config.js
```

## Customization

- To change the videos, edit `src/videos.json`
- To modify the UI, edit `src/App.js`
- To change the styling, modify the Tailwind CSS classes or add custom styles in `src/index.css`

## Future Enhancements

- Add user authentication
- Implement video upload functionality
- Add real-time engagement features (likes, comments)
- Connect to a backend for video management
- Add progress bar for video duration
- Implement more advanced animations with Framer Motion