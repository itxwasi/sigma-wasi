FROM quay.io/maherzubair/sigma-md:beta
RUN git clone https://github.com/itxwasi/wasi-md/root/itxwasi/wasi-md
WORKDIR /root/https:/itxwasi/wasi-md/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]


 
 
