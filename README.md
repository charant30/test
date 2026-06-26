# Hello Page

A minimal static HTML page that greets the user with "Hi there!"

## Requirements

- Python 3 (for the built-in HTTP server), or any static file server of your choice

## Run locally

From this directory, start a simple HTTP server:

```bash
python -m http.server 8080
```

Then open [http://localhost:8080](http://localhost:8080) in your browser.

You can use any available port by changing `8080` to another number (for example, `3000` or `5500`).

## Project structure

```
.
├── index.html   # Single-page greeting
└── README.md
```

## Stop the server

Press `Ctrl+C` in the terminal where the server is running.
