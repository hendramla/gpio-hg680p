# gpio-hg680p
# Installation

opkg update && (cd /tmp && curl -sLko install https://raw.githubusercontent.com/hendramla/gpio-hg680p/main/install && bash install)

Add to Startup

sleep 20 && /usr/bin/inet-hg680p.sh -r
