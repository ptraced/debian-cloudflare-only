# debian-cloudflare-only
Debian 12 cloudflare only using nft tables

```
sudo apt update
sudo apt install -y nftables
sudo systemctl enable nftables
sudo systemctl start nftables
sudo nft -f /etc/nftables.conf
sudo nft list ruleset
sudo systemctl enable nftables
```
