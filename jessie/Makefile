DOCKER_NAMESPACE =	armbuild/
NAME =			scw-distrib-debian
VERSION =		jessie
VERSION_ALIASES =	8.2 8 latest
TITLE =			Debian
DESCRIPTION =		Debian Jessie
SOURCE_URL =		https://github.com/scaleway/image-debian
VENDOR_URL =		https://www.debian.org

IMAGE_NAME =		Debian Jessie (8.2 latest)
IMAGE_BOOTSCRIPT =	latest
IMAGE_VOLUME_SIZE =	50G

## Image tools  (https://github.com/scaleway/image-tools)
all:    ../docker-rules.mk
../docker-rules.mk:
	$(MAKE) -C .. docker-rules.mk
-include ../docker-rules.mk
