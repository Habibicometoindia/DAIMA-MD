FROM quay.io/eypzgod/izumi:latest
RUN git clone https://github.com/henrygokugt99/DAIMA-MD /root/bot/
WORKDIR /root/bot/
RUN yarn install --network-concurrency 1
CMD ["npm", "start"]
