FROM alpine:3.18.5
WORKDIR /db
ADD customers.sql /db
ADD customers.table /db
RUN apk add --update sqlite
RUN mkdir /db/data
RUN sqlite3 /db/data/microservices.db < /db/customers.sql

ENTRYPOINT ["sqlite3"]
