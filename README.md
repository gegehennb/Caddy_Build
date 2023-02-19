## Download amd64

```bash
wget -P /usr/local/bin/ https://github.com/gegehennb/CN_Build/releases/download/main/caddy-linux-amd64.tar.gz
tar -zxvf /usr/local/bin/caddy-linux-amd64.tar.gz -C /usr/local/bin/ && rm -rf /usr/local/bin/caddy-linux-amd64.tar.gz
chgrp -R root /usr/local/bin/caddy && chown -R root /usr/local/bin/caddy
```

## Download arm64

```bash
wget -P /usr/local/bin/ https://github.com/gegehennb/CN_Build/releases/download/main/caddy-linux-arm64.tar.gz
tar -zxvf /usr/local/bin/caddy-linux-arm64.tar.gz -C /usr/local/bin/ && rm -rf /usr/local/bin/caddy-linux-arm64.tar.gz
chgrp -R root /usr/local/bin/caddy && chown -R root /usr/local/bin/caddy
```
