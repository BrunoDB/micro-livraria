FROM brunobasso/micro_livraria:1.0

ENV NO_UPDATE_NOTIFIER=1

EXPOSE 3000
EXPOSE 5000

WORKDIR /app

ADD . .
RUN npm install --silent --loglevel=error

CMD ["npm", "run", "exec"]
