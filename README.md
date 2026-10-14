# time-el

TIME/EL is a minimal, interactive exploration of time, daylight, and the moments in between, centered on Jakarta, Indonesia.

**Live site:** [time-el.pages.dev](https://time-el.pages.dev/)

## What it does

- Shows a live Jakarta clock (WIB, UTC+07:00), with an option to synchronize against an online time service.
- Visualizes Jakarta's sunrise, solar noon, sunset, and daylight duration.
- Tracks the elapsed portion of the current day and year.
- Offers short reflections that rotate automatically, with a button to browse them.
- Lets you write one personal note per Jakarta date and save it in your browser.
- Includes a focus mode for the clock and other visualizations.

## Run locally

No build step or package installation is required. Open `index.html` in a browser, or serve the project directory with any static web server.

## Data and privacy

The app uses the [WorldTime service](https://worldtime.timezone.io/api/timezone/Asia/Jakarta) to synchronize the clock and [Sunrise-Sunset.org](https://sunrise-sunset.org/) for solar data. An internet connection is needed for these live services; if time synchronization is unavailable, the clock uses your device's time.

Daily notes are saved in this browser's local storage on this device. The note text is not sent to the app's data providers. Clearing browser storage removes saved notes.
