FROM node:12.18.3-alpine3.12

# Basic dev tools
RUN apk add --no-cache --update \
  git \
  openssh \
  zsh \
  curl \
  && sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

