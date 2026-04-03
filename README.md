# IP Checker

A lightweight, single-page tool that displays your public and local network information in real time. Perfect for quick network diagnostics, geolocation lookups, and system profiling.

## Features

- **Public IP Information**: Instantly retrieves your public IPv4 and IPv6 addresses
- **Network Details**: Shows CIDR block, ISP/org, ASN, and connection type
- **Geolocation Data**: Displays country, city, timezone, and coordinates based on your IP
- **Browser & System Info**: Captures browser type, OS, device classification, screen resolution, color scheme, and CPU thread count
- **Reverse DNS Lookup**: Fetches hostname (PTR record) for your connection
- **One-Click Refresh**: Easy button to re-fetch all data
- **Minimal Design**: Fast, clean interface with no bloat

## Use Cases

- Diagnose network connectivity issues
- Verify public IP before VPN testing
- Check geolocation accuracy
- Profile system specs quickly
- Network troubleshooting in broadcast/IT environments

## Tech Stack

- Vanilla JavaScript (no dependencies)
- Responsive HTML/CSS design
- Real-time API calls to three data sources:
  - **ipapi.co** for comprehensive geolocation and network data
  - **ipify.org** for IPv4/IPv6 verification
  - **Google DNS** for reverse PTR lookups

## API Sources

- [ipapi.co](https://ipapi.co) — Geolocation, ISP, ASN, timezone, coordinates
- [ipify.org](https://www.ipify.org) — IPv4 and IPv6 address detection
- [Google Public DNS](https://developers.google.com/speed/public-dns/docs/doh) — Reverse DNS (PTR) lookups

All services are free and require no authentication.

## Local Setup

1. Clone the repository
2. Open `index.html` in a web browser, or serve it via HTTP
3. Click "Refresh" to fetch current network data

No build process, no install, no configuration needed.

## Browser Support

Works on any modern browser (Chrome, Firefox, Safari, Edge). Tested on desktop and mobile.

## Privacy

- No data is stored or logged by this tool
- All requests are made directly from your browser to the third-party APIs listed above
- Review their privacy policies if concerned about data collection

## License

© 2026 The Tyler Woodward Project. All rights reserved.

## Author

Built by Tyler Woodward. Part of the [tools.tylerwoodward.me](https://tools.tylerwoodward.me) suite.

---

**Feedback or Issues?** Open an issue or contact the author directly.
