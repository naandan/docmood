FROM node:18-alpine

WORKDIR /app

COPY . .
RUN npm install -g pnpm
RUN pnpm install
RUN pnpm run build

CMD ["pnpm", "serve"]