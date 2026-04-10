# node-starter

Node.js + TypeScript starter with sensible defaults and best practices — built on top of [NestJS](https://nestjs.com).

## Features

- TypeScript with strict mode
- NestJS for modular, testable backend structure
- Dockerfile for containerized deployments
- Jenkins CI pipeline scaffold
- Unit + e2e test harness out of the box
- Production-ready build and start scripts

## Getting Started

```bash
npm install
```

## Running

```bash
# development
npm run start

# watch mode
npm run start:dev

# production
npm run start:prod
```

## Testing

```bash
# unit tests
npm run test

# e2e tests
npm run test:e2e

# coverage
npm run test:cov
```

## Docker

```bash
docker build -t node-starter .
docker run -p 3000:3000 node-starter
```

## License

MIT
