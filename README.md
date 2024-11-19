# my-dns

1. git clone.
2. `docker pull ubuntu/bind9`
3. change dns name at named.conf.local if you need.
4. change ip for dns name at db.my.domain.
5. ```shell
   sudo systemctl stop systemd-resolved
   sudo systemctl disable systemd-resolved
   ```
6. docker compose up -d
