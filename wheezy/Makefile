NAME =			debian
VERSION =		wheezy
VERSION_ALIASES =	7.9 7
TITLE =			Debian Wheezy
DESCRIPTION =		Debian Wheezy
SOURCE_URL =		https://github.com/scaleway/image-debian
VENDOR_URL =		https://www.debian.org

IMAGE_NAME =		Debian Wheezy (7.9)
IMAGE_BOOTSCRIPT =	stable
IMAGE_VOLUME_SIZE =	50G


## Image tools  (https://github.com/scaleway/image-tools)
all:    ../docker-rules.mk
../docker-rules.mk:
	$(MAKE) -C .. docker-rules.mk
-include ../docker-rules.mk
