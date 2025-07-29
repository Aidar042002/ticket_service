FROM node:18

WORKDIR /app

RUN test -f package.json || npx create-react-app . --template cra-template --use-npm

CMD ["npm", "start"]
