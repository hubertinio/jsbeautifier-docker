FROM node:9-stretch

RUN set -ex; \
    yarn global add js-beautify@1.11.0; \
    yarn cache clean

ENTRYPOINT ["js-beautify"]
CMD ["-i"]
