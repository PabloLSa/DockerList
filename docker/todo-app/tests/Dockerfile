FROM mjgargani/puppeteer:trybe1.0
EXPOSE 3000
WORKDIR /app
ADD node_modules.tar.gz .
COPY . .
ENTRYPOINT [ "npm" ]
CMD [ "test" ]

