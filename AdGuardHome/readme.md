## AdGuard Home

Copy the Quadlet file to `/etc/containers/systemd/`:

```bash
sudo cp adguardhome.container /etc/containers/systemd/
```

Reload systemd:

```bash
sudo systemctl daemon-reload
```

Start the container:

```bash
sudo systemctl start adguardhome
```

Check the status:

```bash
sudo systemctl status adguardhome
```

The container will be managed by systemd and automatically started after reboot.