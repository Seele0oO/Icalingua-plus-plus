FROM node
WORKDIR /usr/src/oicq
COPY . .
RUN npm install -g pnpm
RUN pnpm install
RUN cd icalingua-bridge-oicq && pnpm compile
CMD [ "ls -la" ]