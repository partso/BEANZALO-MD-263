FROM quay.io/eypzgod/izumi:latest
RUN git clone https://github.com/partso/ROYAL-BOT-263 /root/bot/
WORKDIR /root/bot/
RUN yarn install --network-concurrency 1
CMD ["npm", "start"]
