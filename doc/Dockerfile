FROM node:18-alpine

WORKDIR /app

COPY package.json package-lock.json ./
RUN npm install -g pnpm
RUN pnpm install
RUN pnpm run build

COPY . .

CMD ["pnpm", "serve"]