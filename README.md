# Music Player App

## Overview

The **Music Player App** is a sleek web-based application that provides users with an elegant interface for playing and managing their music collection. The app features a beautiful pink-purple theme inspired by Yae Miko, with smooth animations and visual effects that enhance the user experience.

## Features

### Player Controls

- **Play/Pause**: Start or pause the current song with a smooth transition
- **Previous**: Skip to the previous song in the playlist
- **Next**: Skip to the next song in the playlist
- **Shuffle**: Randomly reorder the playlist for variety

### Visual Experience

- **Dynamic Album Art**: Album cover changes with each song and features subtle hover effects
- **Responsive Design**: Automatically adjusts layout for mobile and desktop screens
- **Animated Elements**: Visual feedback for interactions with hover effects and transitions

### Playlist Management

- **Song Selection**: Click any song in the playlist to play it immediately
- **Delete Songs**: Remove unwanted songs from your collection with a single click
- **Reset Playlist**: Restore the default playlist if you remove too many songs
- **Auto-sort**: Songs are automatically sorted alphabetically by title

## Technical Details

### Technologies Used

- **HTML5**: Semantic structure for better accessibility
- **CSS3**: Advanced styling with variables, gradients, and animations
- **JavaScript**: Dynamic functionality for player controls and playlist management
- **Web Audio API**: Handles audio playback with event tracking

### Code Structure

The application is organized into three main files:

1. **index.html**: Contains the structure of the player and playlist
2. **styles.css**: Implements the Yae Miko-inspired theme with responsive design
3. **script.js**: Handles all player functionality and user interactions

## Usage Instructions

### Playing Music

1. Click on any song in the playlist to begin playback
2. Use the control buttons to navigate between songs:
   - Play/Pause: Toggle playback of the current song
   - Previous: Go back to the previous song
   - Next: Skip to the next song
   - Shuffle: Randomize the playlist order

### Managing Your Playlist

- **Playing a Song**: Click on the song title/info in the playlist
- **Removing a Song**: Click the delete button (✕) next to any song
- **Restoring Songs**: If your playlist becomes empty, a "Reset Playlist" button will appear

## Customization

You can easily customize the playlist by modifying the `allSongs` array in `script.js`:

```javascript
const allSongs = [
  {
    id: 0,
    title: "Your Song Title",
    artist: "Artist Name",
    duration: "3:30",
    src: "./path/to/your/song.mp3",
    img: "./path/to/album-cover.jpg"
  },
  // Add more songs as needed
];
```

## Responsive Design

The Music Player adapts to different screen sizes:

- **Desktop**: Full-width layout with horizontal arrangement of album art and controls
- **Mobile**: Compact vertical layout with optimized spacing and touch-friendly controls

## Visual Theme

The app features a custom "Yae Miko" theme with:

- Pink-purple color palette with gradient backgrounds
- Subtle glow effects on interactive elements
- Custom hover animations for buttons and controls
- Decorative elements like the flower symbols and parallel lines

## Browser Compatibility

The Music Player works in all modern browsers including:
- Chrome, Firefox, Safari, Edge
- Mobile browsers on iOS and Android

## License

This project is available for use under the MIT License.
