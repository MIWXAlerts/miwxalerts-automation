## 🌩️ Supported NWS Alerts (Michigan)

MIWXAlerts-Github tracks **severe** and **winter weather** alerts, including:

### Severe Weather
- 🟥 Severe Thunderstorm Warning
- 🌪️ Tornado Warning  
  - Includes **PDS** and **Tornado Emergency**
- 🟨 Severe Thunderstorm Watch
- 🟧 Tornado Watch

### Winter Weather
- ❄️ Winter Storm Warning
- ❄️ Winter Weather Advisory
- ❄️ Blizzard Warning
- ❄️ Ice Storm Warning
- ❄️ Freezing Rain Advisory
- ❄️ Snow Squall Warnings


## ⚙️ How It Works

- Runs automatically via **GitHub Actions** every **5 minutes** (We have to be API friendly)
- Pulls live alert data from the **NWS API** (`api.weather.gov`)
- Filters qualifying Michigan alerts
- Tracks alert state using official **NWS Alert IDs**
- Synchronizes alert lifecycle with GitHub Issues

## 🏷️ Automatic Labeling

Each issue is automatically labeled based on alert type.

### Core Label
- `nws-alert` — Applied to all alerts

### Severe Weather Labels
- `tornado-warning`
- `tornado-watch`
- `severe-warning`
- `severe-watch`
- `pds`
- `tornado-emergency`

### Winter Weather Labels
- `winter-warning`
- `winter-advisory`
- `blizzard-warning`
- `ice-storm-warning`
- `snow-squall-warning`
