# Room for Improvement

A pocket think tank for making the world better — inspired by Ellen MacArthur, who
sailed the world solo and then spent her life carrying one big idea between places:
waste nothing, circulate everything.

The whole app is a single file, `index.html`, with no build step and no server.
Open it in any browser, on any phone.

## What it does

- **Ideas** — a commons of world-improving ideas. Browse ideas seeded from real
  initiatives around the world (repair cafés, food rescue, tool libraries, community
  solar, nature prescriptions…), back the ones you believe in, and post your own with
  a concrete first step.
- **Act** — for people who just want to get actionable. Pick a cause and how much
  time you honestly have (10 minutes, an hour, ongoing) and get real step-by-step
  actions, with a personal tally of what you've completed.
- **Guide** — an AI co-navigator. Works fully offline with a built-in coach that
  helps you find where to start, match spare time to actions, and sharpen an idea
  before posting. Optionally, paste a Claude API key in settings (gear icon) to power
  it with live AI — the key is stored only on your device.

Ideas, backings, and completed actions are saved in your browser's local storage.

## Run it

- Open `index.html` directly in a browser, or
- Serve it: `python3 -m http.server` and visit `http://localhost:8000`, or
- Enable GitHub Pages for this repo (Settings → Pages → deploy from branch) and open
  the URL on your phone.
