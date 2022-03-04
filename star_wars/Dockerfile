FROM alpine:latest

LABEL MAINTAINER="Brent Salisbury <brent.salisbury@gmail.com>"

RUN apk add --no-cache busybox-extras

# Bored with "Hello World" for a test container run?
# Spruce up your Docker terminal with an ASCII version
# of Star Wars. Enjoy the show! :p

# Usage: docker run -it --rm networkstatic/star_wars
####################################################
#       A long time ago in a galaxy far,
#        far away....
#
#          8888888888  888    88888
#         88     88   88 88   88  88
#          8888  88  88   88  88888
#             88 88 888888888 88   88
#      88888888  88 88     88 88    888888
#
#      88  88  88   888    88888    888888
#      88  88  88  88 88   88  88  88
#      88 8888 88 88   88  88888    8888
#       888  888 888888888 88   88     88
#        88  88  88     88 88    8888888
####################################################
# Credits:
# Original Work   : Simon Jansen ( http://www.asciimation.co.nz/ )
# Telnetification : Sten Spans ( http://blinkenlights.nl/ )
# Terminal Tricks : Mike Edwards (pf-asciimation@mirkwood.net)
####################################################
ENTRYPOINT ["/usr/bin/telnet", "towel.blinkenlights.nl"]
