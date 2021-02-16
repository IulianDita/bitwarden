# Not tested!

## How to set up on a new machine
- Set up VM/VPS with fixed IP and a proper hostname/dns (FQDN).
- Clone repository.
- Check the nginx config file AND the init script and adjust FQDN where needed.
- Create network `docker network create bitwarden`.
- Run `init-letsencrypt.sh` (only on the first run, right after cloning).
- Profit.
