# API Documentation

This repository contains API documentation hosted on GitHub Pages using Swagger UI.

## Setup Instructions

1. Fork this repository
2. Go to your repository's Settings
3. Navigate to "Pages" in the left sidebar
4. Under "Source", select "main" branch
5. Click "Save"

Your documentation will be available at: `https://<your-username>.github.io/<repository-name>/`

## Local Development

To view the documentation locally:

1. Clone this repository
2. Open `index.html` in your web browser
3. Or use a local server:
   ```bash
   python -m http.server 8000
   ```
   Then visit `http://localhost:8000`

## Customizing the Documentation

1. Edit `swagger.json` to update your API documentation
2. The documentation will automatically update when you push changes to the main branch

## License

MIT License 