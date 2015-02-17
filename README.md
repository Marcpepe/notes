# notes

## Rebuild your vagrant (sogé)

1. vagrant up
2. ssh-keygen -f "/home/marcpp/.ssh/known_hosts" -R dev-mothership.pepinie.re
3. type yes (x2)
4. (pepiniere-gaia-mock): make provision-development
5. (pepiniere-sgdir): make provision-development
6. (pepiniere-sgdir-api): make provision-development
7. ssh to vagrant
8. `cd /var/www/gaia-mock/current/client && npm install`
9. `cd ../server && npm install && npm run update-db`
10. `cd /var/www/sgdir-api/current && npm install`
11. `cd /var/www/sgdir/current && npm install`
