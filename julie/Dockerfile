FROM quay.io/lyfe00011/test:beta

RUN git clone https://github.com/KingofCheuuthanSpidey/Criminal_v2 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN yarn install --no-audit
RUN git clone https://github.com/KingofCheuuthanSpidey/Nandhuttynew
RUN cp -R /root/Utils/* /root/WhatsAsenaDuplicated 
CMD ["node", "bot.js"]
