# SkySet Generator Web Interface

A simple HTML interface for the SkySet Generator API. This web page allows users to generate SkySet files for SkySafari by entering natural language prompts.

## Features

- Clean, minimalist UI
- Simple text input for natural language prompts
- Automatic file download when generation is complete
- Error handling for API communication issues

## Usage

1. Enter a prompt describing the celestial view you want (e.g., "Show me the Moon, Dec 1st, 2023, Toronto, ON, 22:22, 1.0 FOV")
2. Click "Generate"
3. Wait for the SkySet file to be generated
4. The file will automatically download when ready

## Backend Connection

This frontend connects to the SkySet Generator API hosted at:
`https://skysafari-ai-mcp-docker.onrender.com/`
