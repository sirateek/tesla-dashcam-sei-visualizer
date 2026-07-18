# Tesla Dashcam SEI Visualizer

A web-based tool to visualize and analyze Tesla dashcam video data along with vehicle telemetry information. Upload your Tesla dashcam videos and explore the data with interactive graphs and playback controls.

![Dashboard Overview](https://raw.githubusercontent.com/sirateek/tesla-dashcam-sei-visualizer/refs/heads/master/docs/imgs/Screenshot%202569-07-18%20at%2022.15.05.png)
![Video with Telemetry Graph](https://raw.githubusercontent.com/sirateek/tesla-dashcam-sei-visualizer/refs/heads/master/docs/imgs/Screenshot%202569-07-18%20at%2022.15.20.png)

![Detailed Metrics View](https://raw.githubusercontent.com/sirateek/tesla-dashcam-sei-visualizer/refs/heads/master/docs/imgs/Screenshot%202569-07-18%20at%2022.15.29.png)

## Features

- **Video Playback**: View your Tesla dashcam footage directly in the browser
- **Telemetry Visualization**: Display vehicle data (speed, acceleration, position, etc.) alongside video playback
- **Interactive Graphs**: Zoom, pan, and explore vehicle telemetry data with interactive charts
- **Easy to Use**: Simply paste or upload your Tesla dashcam video file
- **Privacy First**: All data processing happens locally on your device—no data is stored on any server or sent over the internet

## How to Use

1. Open the visualizer by visiting the hosted version or running locally
2. Upload or paste your Tesla dashcam video file
3. The application will display:
   - **Video Player**: Your dashcam footage
   - **Telemetry Graphs**: Vehicle data visualization with multiple metrics
4. Use the interactive controls to:
   - Play/pause the video
   - Sync playback with telemetry data
   - Zoom and explore specific time ranges
   - Inspect detailed vehicle metrics

## Privacy & Security

🔒 **Your data stays on your device**

- All video and telemetry processing is done locally in your browser
- No data is uploaded to any server
- No tracking or analytics
- No permanent storage—data is cleared when you close the browser

## Getting Started

### Online Version

Visit the hosted version directly in your browser—no installation needed.

### Local Development

```bash
# Clone the repository
git clone https://github.com/sirateek/tesla-dashcam-sei-visualizer.git

# Navigate to the directory
cd tesla-dashcam-sei-visualizer

# Open in your browser
open index.html
# or
open dashcam/index.html
```

## Technology Stack

- **Frontend**: HTML5, JavaScript
- **Video**: Native HTML5 video player
- **Data Processing**: Client-side JavaScript
- **Visualization**: Interactive charts and graphs

## License

[Add your license here]

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for any bugs or feature requests.

## Support

If you have questions or encounter issues, please open an issue on GitHub.
