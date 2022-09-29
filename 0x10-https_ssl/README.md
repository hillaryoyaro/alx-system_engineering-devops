0. **World wide web** - Configure your domain zone so that the subdomain `www` points to your load-balancer IP (lb-01). Write a Bash script that will display information about subdomains
1. **HAproxy SSL termination** - Create a certificate using `certbot` and configure `HAproxy` to accept encrypted traffic for your subdomain `www.`
2. **No loophole in your website traffic** - A good habit is to enforce HTTPS traffic so that no unencrypted traffic is possible. Configure HAproxy to automatically redirect HTTP traffic to HTTPS
