# Daily Weather Summary (Make.com Automation)

This Make.com scenario retrieves a daily weather forecast and sends a formatted summary email via Gmail.

## What it does

- Fetches daily weather forecast data
- Aggregates per-day minimum, maximum, and average temperatures
- Formats the output with clear separation between days
- Sends the summary via Gmail

## Tools / Services Used

- Make.com
- Weather module (daily forecast)
- Text Aggregator
- Gmail (Send an Email)

## Files

- `blueprint.json` – Exported Make.com scenario blueprint

## How to use

1. Open Make.com
2. Create a new scenario
3. Import `blueprint.json`
4. Reconnect required services (Weather, Gmail)
5. Run or schedule the scenario

## Notes

- Email formatting uses HTML (`<br>` and `<hr>`) for clarity
- Blueprint is provided for reference and reuse

## Disclaimer

This repository contains a Make.com scenario blueprint provided for educational and demonstration purposes.

To use this automation:
- You must have an active Make.com account
- The `blueprint.json` file must be manually imported into Make
- All API connections, credentials, and email settings must be configured by the user

No API keys, credentials, or personal data are included in this repository.
