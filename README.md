# Commands

## Extract tar.bz2 archive to the directory
```bash
tar -xjvf archive.tar.bz2 -C /target/directory
```
## Init-scripts management (System-V)

### Append Init-script to autostart
```bash
sudo update-rc.d <script> defaults
```
### Remove Init-script from autostart
```bash
sudo update-rc.d -f <script> remove
```
## Systemd-services management

### Append Systemd-service to autostart
```bash
sudo systemctl enable <name>.service
```

### Remove Systemd-service from autostart
```bash
sudo systemctl disable <name>.service
```
