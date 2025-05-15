# Facebook Share Tool

An automated Facebook post sharing tool with a modern, sleek interface.

## Features

- Cookie-based authentication
- Cookie generator from username/password
- Persistent sharing process (continues even if browser is closed)
- Real-time progress tracking with statistics
- Dark theme UI with custom styling

## Deployment

This repository contains all necessary files for deploying to various platforms:

### Deploy to Render

1. Go to [Render](https://render.com) and sign up/login
2. Connect to this GitHub repository
3. Create a new Web Service with these settings:
   - **Build Command**: `pip install -r requirements.txt`
   - **Start Command**: `streamlit run app.py --server.port $PORT --server.address 0.0.0.0`

### Local Development

1. Clone this repository
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Run the application:
   ```
   streamlit run app.py
   ```

## Usage

1. Enter your Facebook cookie (or generate one with the built-in tool)
2. Paste the Facebook post URL you want to share
3. Set the desired number of shares and delay between operations
4. Click "Start Engine" to begin the sharing process

## Note

Use responsibly and only with accounts you own.
