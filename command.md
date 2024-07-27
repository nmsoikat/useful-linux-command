### OS
- `lsb_release -dc` Ubuntu version check
- `ps --no-headers -o comm 1` Check init system your platform
  - systemd (which uses the `systemctl` command)
  - System V init (which uses the `service` command)
- `find / -name "mongosh"` Find directory of command
