FROM fusuf/whatsasena:latest
RUN git clone https://github.com/Meenutty/Xbroz.git /xasena
WORKDIR /xasena
RUN yarn install --network-concurrency 1
CMD ["node", "bot.js"] 
