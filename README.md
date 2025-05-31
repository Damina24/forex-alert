# Forex Alert for Termux

## 📦 Installation
```bash
pkg update && pkg install wget dpkg -y
wget https://github.com/Damina24/forex-alert/releases/download/v1.0/forex-alert_1.0_all.deb
dpkg -i forex-alert_1.0_all.deb
```

## 🚀 Usage
```bash
forex-alert
```
- Select pair (XAUUSD or USDJPY)
- Set level (20 or 80)
- Script runs every 1 minute and triggers a notification + vibration when level is crossed

## 📄 Notes
- Your TwelveData API key is stored once and reused
- Alerts stop the script automatically
