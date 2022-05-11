# docker-mssql-fts

This is a MSSQL docker image with free text search builtin.

Motivation: since there is no such image on [Microsoft SQL Server dockerhub](https://hub.docker.com/_/microsoft-mssql-server), we create our image of MSSQL with free text search.

This image is based on original MSSQL Linux Ubuntu docker image from Microsoft, with free text search installed.

We used [Dockerfile](https://github.com/microsoft/mssql-docker/blob/master/linux/preview/examples/mssql-polybase-fts-tools/Dockerfile) as reference.

## To Do

- Update Base OS when Microsoft releases a new one.
