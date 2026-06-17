# cassLabsWebsite
## codebase for Cass Labs LLC website 
###### A simple website for my consulting business.

## Testing locally

- Open files directly: double-click `index.html` or open `pages/research.html` in your browser. Save CSS changes and reload the page.
- Serve with a simple HTTP server (recommended):

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000 and navigate to `/pages/research.html`. Save `styles/main.css` and refresh to see changes.

- Use VS Code Live Server for live reload (optional): install the Live Server extension, then right-click `index.html` or `pages/research.html` → "Open with Live Server".

- If styles don't update: perform a hard reload (Cmd+Shift+R), open DevTools → Network → check "Disable cache", and verify `styles/main.css` is being loaded.
