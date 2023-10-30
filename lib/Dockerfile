FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/MADAM-MASK-OFFICIAL/MADAM-MASK-MD-V2 /root/MADAM-MASK-OFFICIAL
WORKDIR /root/MADAM-MASK-OFFICIAL/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
