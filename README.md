# Auto updater

Update raspberry pi and send a notification via telegram

1. pull file

2. `chmod +x auto-updater`

3. `sudo mv auto-updater /usr/bin/`

---

# Execution

`auto-updater`

To run this command every first day of the month. Follow these steps:
1. sudo crontab -u root -e 
2. `0 0 1 * * auto-updater >/dev/null 2>&1`
