FROM postgres:alpine

ENV POSTGRES_USER=kodilla
ENV POSTGRES_PASSWORD=kodilla
ENV POSTGRES_DB=kodilla-quotes

COPY dump.sql /docker-entrypoint-initdb.d/

EXPOSE 5432