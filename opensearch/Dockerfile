FROM opensearchproject/opensearch:1.1.0
RUN /usr/share/opensearch/bin/opensearch-plugin remove opensearch-security
COPY --chown=opensearch:opensearch custom-opensearch.yml /usr/share/opensearch/config/