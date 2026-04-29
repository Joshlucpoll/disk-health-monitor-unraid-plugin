# Disk Health Monitor — Unraid Plugin

A real-time disk health dashboard that embeds directly into the Unraid **Main** page. Displays SMART data, temperatures, health scores, and pool/array usage for all HDDs, SSDs, and NVMe drives.

## Features

- Health score (0–100) with OK / Warning / Critical status for every drive
- SMART attribute monitoring (reallocated sectors, pending sectors, uncorrectable errors, command timeouts, NVMe critical warning)
- Temperature monitoring with configurable alert thresholds
- Pool and array capacity / usage display
- Drives grouped by Array, Pool, Flash, and Unassigned
- Filter pills to focus on healthy, warning, or critical drives
- Automatic theme adaptation — works with all Unraid dark and light themes
- No configuration required

## Requirements

- Unraid 6.9 or later
- `smartmontools` (installed automatically if not present)

## Installation

### Via Community Applications (recommended)

Search for **Disk Health Monitor** in the Community Applications plugin and click Install.

### Manual

1. Navigate to **Plugins → Install Plugin** in the Unraid web UI.
2. Paste the following URL and click Install:

```
https://raw.githubusercontent.com/Joshlucpoll/disk-health-monitor-unraid-plugin/main/disk-health-monitor.plg
```

## Usage

After installation, open the **Main** page in the Unraid web UI. The Disk Health Monitor panel appears at the top of the page. Click **Refresh** to reload data on demand.

## Support / Issues

Open an issue on [GitHub](https://github.com/Joshlucpoll/disk-health-monitor-unraid-plugin/issues).

## License

MIT — see [LICENSE](LICENSE).
