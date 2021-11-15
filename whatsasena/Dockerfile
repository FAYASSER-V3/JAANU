FROM fusuf/whatsasena:latest

RUN git clone https://github.com/FAYASSER-V3/JAANU /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
