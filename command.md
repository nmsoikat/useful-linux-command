### OS
- `lsb_release -dc` Ubuntu version check
- `ps --no-headers -o comm 1` Check init system your platform
  - systemd (which uses the `systemctl` command)
  - System V init (which uses the `service` command)
- `find / -name "mongosh"` Find directory of command
- `sudo lsof -iTCP -sTCP:LISTEN -n -P` List of tasks running on your machine

### Folder
- `mkdir -p mongodb-data/db1` Create nested directory if not exist (using -p)
- `rm -rf <folder-name>` Delete folder `-rf` means Recursive and Force
