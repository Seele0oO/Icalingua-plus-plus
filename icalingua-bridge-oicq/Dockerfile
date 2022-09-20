FROM node
WORKDIR /usr/src/oicq
COPY . .
RUN npm install -g pnpm
RUN pnpm install
WORKDIR /usr/src/oicq/icalingua-bridge-oicq

RUN  pnpm compile
CMD [ "ls -la" ]