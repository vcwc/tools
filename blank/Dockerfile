ARG  VCW_TAG=1.0.0
ARG  VCW_TAG_BASH=5.0.18
FROM vcwc/bash.wrapper:${VCW_TAG_BASH}

COPY _image/* /vcw/pwd/

LABEL co.vcweb.schema-version="1.0" \
      co.vcweb.label="vcwc/swarm Library" \
      co.vcweb.description="Blank placeholder image for blank templates." \
      co.vcweb.realm="vcwc" \
      co.vcweb.library="tools" \
      co.vcweb.image="blank" \
      co.vcweb.tag="${VCW_TAG}" \
      co.vcweb.maintainer="vcw@vcweb.co"
