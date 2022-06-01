FROM busybox

RUN mkdir import

COPY import/keycloak-themes/ import/themes
COPY import/realm-config/dev/catenax-central/ import/catenax-central/realms
COPY import/realm-config/dev/catenax-shared/ import/catenax-shared/realms
