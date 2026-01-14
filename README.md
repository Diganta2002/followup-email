# Follow‑Up Email Template

This folder contains a single HTML file (`followup_email.html`) that represents a premium email template.

## How to view the template locally

1. **Prerequisite**: You need a static web server. The easiest way on Windows is to use the Node.js `http-server` package, which we have installed globally.
   ```powershell
   npm install -g http-server
   ```
2. **Start the server**
   ```powershell
   cd "d:\DIGANTA 2002\Followup mail"
   http-server -p 8000
   ```
   This will serve the current directory on `http://localhost:8000`.
3. **Open the template**
   Open your browser and navigate to:
   ```
   http://localhost:8000/followup_email.html
   ```
   You should see the email rendered with the gradient header and CTA button.

## Stopping the server
Press `Ctrl + C` in the terminal where `http-server` is running.

## Alternative servers
- **Python** (if installed): `python -m http.server 8000`
- **PowerShell** built‑in: `Start-Process "powershell" -ArgumentList "-NoProfile -Command \"cd 'd:\DIGANTA 2002\Followup mail'; python -m http.server 8000\""`

## Customising the template
Replace the placeholder variables in `followup_email.html` with real values before sending:
- `{{RecipientName}}`
- `{{CTA_URL}}`
- `{{Year}}`

Feel free to edit the HTML file to match your branding.
