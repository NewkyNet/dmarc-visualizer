FROM python:3.7-alpine

# RUN apk add build-base libxml2-dev libxslt-dev \
# && pip3 install -U parsedmarc

RUN apk add build-base libxml2-dev libxslt-dev libffi-dev \
    && pip install parsedmarc


# RUN apk add --update --no-cache libxml2-dev libxslt-dev
# RUN apk add --update --no-cache --virtual .build_deps build-base libffi-dev \
#     && pip install parsedmarc \
#     && apk del .build_deps

COPY parsedmarc.ini /
#COPY GeoLite2-Country.mmdb /usr/share/GeoIP/GeoLite2-Country.mmdb
