FROM node:9-alpine

RUN set -ex; \
    yarn global add js-beautify@1.11.0; \
    yarn cache clean

ENTRYPOINT ["js-beautify"]
CMD ["-i"]
