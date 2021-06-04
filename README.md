# Tiny weather station based on TTGO T5 V2.3.1 (ESP32 with 2.13" e-ink display)

Original code by piotr-kubica

Needed to make changes to make it play nice with PlatformIO and customise what's shown on the display. The main purpose is the provide a quick overview of the prediction for the current day, so I can dress my son appropiately before dropping him off at the daycare. It hangs next to a weatherstation display that shows the current weather.

Differences with original weather display:
- only 1 location
- No air quality (nearest station is too far from our place)
- No pressure (no use for it)
- No battery indication (USB powered)

TODOs
- Better spacing of hours to cover day
- Temperature per hour instead of hi/lo
- Smaller time/date font
- Remove wind?
