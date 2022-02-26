# hosts
Unblock various website

## USAGE
### Windows
- Drop into `C:\Windows\System32\drivers\etc`

### Linux
- Drop into `/system/etc/` or `/etc/` directory

### Android (ADB)
- NOTE: Some devices need root to copy and paste the hosts file to the device
- Drop into `/system/etc/` or `/etc/` directory using [ADB](https://developer.android.com/studio/releases/platform-tools)

### Android (alternative | no root access)
1. Download [Hosts Go](https://play.google.com/store/apps/details?id=dns.hosts.server.change&hl=en&gl=US)
2. Open app > Hosts Editor > 3-dot Menu > Download HOSTS file > paste https://raw.githubusercontent.com/ArnNied/hosts/master/hosts
