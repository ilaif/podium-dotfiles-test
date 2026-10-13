ARG PODIUM_BASE_IMAGE
FROM ${PODIUM_BASE_IMAGE}
USER root
RUN apt-get update && apt-get install -y --no-install-recommends cowsay && rm -rf /var/lib/apt/lists/*
COPY .podium/marker /etc/podium-custom-image-marker
