# 🛵 Gothenburg Courier Zones

A free, single-page web guide for **Wolt and Uber Eats moped couriers in Gothenburg**. It shows where to wait between orders, when demand peaks, and how to get more deliveries with less idle time.

**Live demo:** https://github.com/Hasnain17/gothenburg-courier-guider/

## Features

- **Zone map:** a schematic map of Gothenburg with a highlighted core zone and eight waiting spots. Tap a spot to see why it works, the best times, where to stand, and a "Go there" button that opens Google Maps.
- **Right now card:** suggests the two best spots for the current time of day. It updates automatically every 15 seconds and when you return to the tab.
- **Peak times:** an hour-by-hour demand chart for weekdays, Friday–Saturday, and Sunday.
- **Guidance:** practical tips for running both apps at once, judging offers, handling quiet hours, and riding safely.
- **Light and dark mode:** follows your device setting.
- **Mobile friendly:** built for use on a phone.

## Run it locally

No install or build step. Download `index.html` and open it in any browser.

## Deploy on GitHub Pages

1. Put `index.html` in the root of a public repository.
2. Open **Settings → Pages**.
3. Set **Source** to *Deploy from a branch*, choose the `main` branch and the `/ (root)` folder, then save.
4. After a minute or two your site is live at `https://YOUR-USERNAME.github.io/REPO-NAME/`.

## Customize

Everything is plain HTML, CSS and JavaScript in one file, with no dependencies.

- **Spots:** edit the `L` array in the script. Each spot has a name, map position (`x`, `y`), a rating (`s`, 1–5), time weights (`w`), best times, a reason, a waiting tip, and a Google Maps search query.
- **Peak hours:** edit the `D` object. Each day type has 24 values, one per hour, from 0 to 100.
- **Colors:** change the CSS variables at the top of the `<style>` block.

## Disclaimer

The map is a schematic layout, not to scale. Spot ratings and peak hours are general patterns for a city like Gothenburg, **not live data** from Wolt or Uber Eats. When the apps' own busy-area hints disagree with this page, trust the apps. Track your own orders per hour at each spot and keep what works for you.

## Author

Developed by **Muhammad Hasnain Altaf**

- LinkedIn: https://linkedin.com/in/muhammad-hasnain-altaf
- GitHub: https://github.com/Hasnain17
