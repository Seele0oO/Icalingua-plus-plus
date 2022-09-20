FROM node
WORKDIR /usr/src/oicq
COPY . .
RUN npm install -g pnpm
RUN pnpm install
RUN  [ "ls -la" ]
RUN cd icalingua-bridge-oicq && pnpm compile
CMD [ "ls -la" ]