FROM fedora:31
LABEL maintainer "Pris Nasrat <pnasrat@fedoraproject.org>"

RUN dnf -y update && dnf -y install \
	stress-ng \
	&& dnf clean all

ENTRYPOINT [ "stress-ng" ]
