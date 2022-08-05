FROM quay.io/lyfe00011/test:beta

RUN git clone https://github.com/Bashir12340/b4sh.ir /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN yarn install --no-audit
RUN git clone https://github.com/Bashir12340/media
RUN cp -R /root/Utils/* /root/WhatsAsenaDuplicated 
CMD ["node", "bot.js"]
