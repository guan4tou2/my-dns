# my-dns

1. git clone.
2. change dns name at named.conf.local if you need.
3. change ip for dns name at db.my.domain.
4. ```shell
   sudo systemctl stop systemd-resolved
   sudo systemctl disable systemd-resolved
   ```
5. docker compose up -d
