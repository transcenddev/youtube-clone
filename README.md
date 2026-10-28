# YouTube Clone (HTML & CSS)

## Overview
This project is a simple YouTube clone built using only HTML and CSS. The goal is to replicate the layout and styling of YouTube's homepage, including the navigation bar, sidebar, video thumbnails, and responsive design.

## Features
- Responsive YouTube-like layout
- Sticky navigation bar
- Sidebar with navigation categories
- Grid-based video section

## Technologies Used
- HTML5
- CSS3 (Flexbox, Grid, Media Queries)

## Project Structure
```
youtube-clone/
├── index.html              # Main HTML file
├── styles/
│   ├── general.css         # Base styles, body padding, font
│   ├── header.css          # Fixed top navigation bar
│   ├── sidebar.css         # Left sidebar navigation
│   └── video.css           # Video grid and thumbnails
├── thumbnails/             # Video thumbnail images (WebP)
├── channel-pictures/       # Channel avatars and user picture
├── icons/                  # SVG icons
└── README.md               # Project documentation
```

## Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/transcenddev/youtube-clone.git
   ```

2. Navigate to the project folder:
   ```
   cd youtube-clone
   ```

3. Open index.html in your browser.

## Responsive Design
This project uses CSS media queries to adapt the layout across different screen sizes:

- **Up to 750px**: 2-column video grid, collapsed sidebar (72px)
- **751px - 999px**: 3-column video grid, collapsed sidebar (72px)
- **1000px - 1199px**: 4-column video grid, collapsed sidebar (72px)
- **1200px and above**: 4-column video grid, expanded sidebar (250px)

## Future Improvements
- Add JavaScript for video functionality
- Implement a dark mode toggle
- Enhance UI with animations and transitions

## License
This project is open-source and free to use under the MIT License.

## Contributing
Feel free to contribute or suggest improvements.