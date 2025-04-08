install docker and docker compose

    apt install docker.io docker-compose-v2



stop and disable resolvectl

    systemctl stop systemd-resolved
    systemctl disable systemd-resolved




run proxy

    docker compose up (-d for detached mode)




set dns resolver to localhost

    add (nameserver 127.0.0.1) in /etc/resolv.conf