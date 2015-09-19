NAME =			debian
VERSION =		testing
VERSION_ALIASES =	9 testing
TITLE =			Debian Testing
DESCRIPTION =		Debian Testing
SOURCE_URL =		https://github.com/scaleway/image-debian
VENDOR_URL =		https://www.debian.org

IMAGE_NAME =		Debian Testing (9 testing)
IMAGE_BOOTSCRIPT =	latest
IMAGE_VOLUME_SIZE =	50G

## Image tools  (https://github.com/scaleway/image-tools)
all:    ../docker-rules.mk
../docker-rules.mk:
	$(MAKE) -C .. docker-rules.mk
-include ../docker-rules.mk
