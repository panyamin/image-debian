NAME =			debian
VERSION =		sid
VERSION_ALIASES =	unstable
TITLE =			Debian Sid/Unstable
DESCRIPTION =		Debian Sid/Unstable
SOURCE_URL =		https://github.com/scaleway/image-debian
VENDOR_URL =		https://wiki.debian.org/DebianUnstable

IMAGE_NAME =		Debian Sid/Unstable
IMAGE_BOOTSCRIPT =	latest
IMAGE_VOLUME_SIZE =	50G

## Image tools  (https://github.com/scaleway/image-tools)
all:    ../docker-rules.mk
../docker-rules.mk:
	$(MAKE) -C .. docker-rules.mk
-include ../docker-rules.mk
