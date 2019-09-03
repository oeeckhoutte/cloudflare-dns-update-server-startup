# cloudflare-dns-update-server-startup

## Description

This image updates a Cloudflare DNS Record with your actual IP address

## Usage

```
docker run --rm -e CF_API_KEY='0000000000000000000000000000000000000' -e CF_API_EMAIL='your.email@domain.com' -e DNS_TO_UPDATE='your_dns_or_subdns' -it cloudflare-dns
```
