## Edit Workflow File

## Removed Afdian Verification

``
docker run -d --name ani-rss --hostname ani-rss -p 7789:7789/tcp -e PUID=0 -e PGID=0 -e UMASK=022 -e PORT=7789 -e CONFIG=/config -e TZ=Asia/Shanghai -v /opt/ani-rss/config:/config -v /mnt/sda1/bangumi:/downloads --restart always chat240515/ass:latest
