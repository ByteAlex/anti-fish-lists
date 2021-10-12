# anti-fish-lists

This project's purpose is to serve a publicly accessible whitelist for false posititves found via the [anti-fish-api serivce](https://anti-fish.bitflow.dev/).

## How it works
The contents of the `whitelist.txt` are being pulled from the API once every 60 minutes. The API parses this as "one entry per line" and makes sure none of
the listed entries are being returned as a match.

## Contributing
You can just add a line to the `whitelist.txt` and file a PR explaining why this domain should be whitelisted.

# The API
Please check out the [API](https://anti-fish.bitflow.dev/)
