FROM node:18.13.0-alpine

# create destination directory
WORKDIR /service/frontend

# update and install dependency
RUN apk update && apk upgrade
RUN apk add git


# set app serving to permissive / assigned
ENV NUXT_HOST=0.0.0.0
# set app port
ENV NUXT_PORT=3000
