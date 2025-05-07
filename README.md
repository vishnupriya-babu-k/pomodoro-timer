# Pomodoro Timer

A pomodora timer web application for effective study sessions with time tracking and statistics.

## Features

- **Custom Pomodoro Cycle**: 50-minute work periods followed by 5-minute breaks
- **Timer Controls**: Start, pause, and reset functionality
- **Visual Progress**: Color-coded interface and progress bar
- **Audio Features**:
  - Background music (soft jazz during work, upbeat during breaks)
  - Sound alerts at the end of each period
  - Toggle controls for both audio options
- **Statistics Tracking**:
  - Monthly study time summaries
  - Most productive day identification
  - Most productive time of day analysis
  - Focus sessions counter
  - Calendar heatmap visualization
  - Month-to-month navigation
- **Data Persistence**: All study data saved to localStorage
- **Celebratory Elements**: Confetti animation when completing sessions
- **Responsive Design**: Works on desktop and mobile devices

## Usage

1. Open the HTML file in any modern browser
2. Click "Start" to begin a work session
3. When the 50-minute work period ends, confirm to start your break
4. After the 5-minute break, confirm to begin another work session
5. Use the monthly summary section to track your progress over time

## Technical Details

- Pure HTML, CSS, and JavaScript - no dependencies
- Uses browser localStorage for data persistence
- Audio elements use CDN-hosted placeholder sounds
- Mobile-friendly responsive design

## Browser Compatibility

Works in all modern browsers (Chrome, Firefox, Safari, Edge) that support:
- localStorage API
- Audio elements
- CSS Grid and Flexbox

## Privacy

All data is stored locally in your browser - no data is sent to any server.
