# Sandpoint, ID vs Tampa, FL — Live Weather Showdown

A one-page site that compares live weather comfort between **Sandpoint, North Idaho** and **Tampa, Florida**.
Lower humidity, comfortable "real feel," and less mugginess = higher score. Perfect = dry Idaho air. 🌲

**Live data** is pulled straight from the free [Open-Meteo](https://open-meteo.com/) API in your browser every time
the page loads — no API key, no server, no cost.

## How the score works (0–100, higher is better)

- **Humidity — 50%**: at or below 30% = perfect; worse as it climbs to 90%+.
- **Real feel — 30%**: apparent "feels like" temperature; comfortable ≈ 50–72°F.
- **Mugginess — 20%**: sunshine × humidity. Sunny + dry is fine; sunny + humid is punished hard.

Tweak the weights and thresholds in the `<script>` section of `index.html`.

## Run it locally

Just open `index.html` in any browser. That's it.

## Publish it live on GitHub Pages

1. Commit and push these files to the `main` branch of your GitHub repo.
2. On GitHub, go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Set branch to **`main`** and folder to **`/ (root)`**, then **Save**.
5. Wait ~1 minute. Your site goes live at:
   `https://DevEagle-KJD.github.io/IdahoVSTampa/`
