FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Afx-Spidy/Spidy_ser /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/Afx-Spidy/Spidy-media

CMD ["node", "bot.js"]
