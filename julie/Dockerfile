FROM fusuf/whatsasena:latest

RUN git clone https://github.com/ThesanduT/QueenCutie /root/QueenCutie
WORKDIR /root/QueenCutie/
ENV TZ=Asia/Colombo
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/Ttmodz/Queen-Cutie/plugins

CMD ["node", "bot.js"]
