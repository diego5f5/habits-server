# Habits

> The Habits project is a full-stack application created for the purpose of studying and applying some technologies in the JavaScript environment, with its main functionalities being the creation and tracking of daily habits.

The project is divided into 3 repositories:

💻 [Web](https://github.com/diego5f5/habits-web)

📱 [Mobile](https://github.com/diego5f5/habits-mobile)

⚙️ [Server](https://github.com/diego5f5/habits-server)

## Getting Started

The following instructions will provide you information to get the project up and running on your local machine for development purposes.

#### Prerequisites

- Node.js min version 18.x | npm

#### Technologies

This project uses mainly the following libraries and frameworks:

- [Fastify](https://www.fastify.io/)
- [Prisma](https://www.prisma.io/)
- [dayjs](https://day.js.org/)
- [zod](https://zod.dev/)

## Installing dependencies

```
npm install
```

## Setting up the local database

```
npx prisma migrate dev
```

#### Injecting preconfigured data from seed(optional)

```
npx prisma db seed
```

## Running

```
npm run dev
```
