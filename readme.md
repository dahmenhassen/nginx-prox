docker-compose run certbot   certonly --webroot --webroot-path /var/www/certbot/   -d  it.dahmene.com --email dahmen.com@gmail.com --agree-tos







 docker-compose run --rm  certbot certonly --webroot --webroot-path /var/www/certbot/ --dry-run -d  it.dahmene.com

./etc/crontab:
# m h  dom mon dow   command
0 5  * * *  /root/matomo/cron_job.sh


docker compose run --rm certbot renew

 docker-compose -f /test/nginx-net/docker-compose.yaml  run --rm certbot renew

01 00 14 */1 * root    docker-compose -f /test/nginx-net/docker-compose.yaml  run --rm certbot renew

