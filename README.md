# Pi-doh 

Pi-doh is a script which installs and configures PiHole and Cloudflared to be your Pi-hole's DNS server, enabling DNS-Over-HTTPS functionality.

## What if I already have PiHole installed? ##
You will be prompted during the script to either install PiHole *and* Cloudflared (option 1), or to just install Cloudflared along with required configuration (option 2).

## How to run ##
___
Run the following command on your Pi to download the script:

`wget -O pi-doh.sh https://raw.githubusercontent.com/meulk/doh/main/pi-doh.sh && chmod +x pi-doh.sh`

`sudo ./pi-doh.sh`
