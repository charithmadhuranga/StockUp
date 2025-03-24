# StockedUp | [Live Demo]


[**StockedUp**] is a complete Inventory Management System
that focuses on managing distributed stock for large organizations.

## Quick Start
If you want to start using StockedUp, I host fully fledged [live demo].
For simplicity's sake, you can also create
[a demo account] and skip the registration process.

You can also setup local instance on your machine or deploy this project to a cloud. For instructions please reefer to the [setup guide](SETUP.md).

## About

StockedUp is an easy-to-use service that allows for managing vast amounts of inventory data
for logistical companies. The design philosophy is to separate product definitions from
actual stock data. This allows for separation between global changes of product details
(such as price or description) and stock values.

The general ideas used in StockedUp are:

- **Organization** - You can think of an organization as your company.
- **Product Definition** - Information about a product. Its name, price, description, SKU.
- **Warehouse** - Representation of the physical location where your company stores products, like a warehouse or a store.
- **Inventory** - A product inside a warehouse with quantity and its location.

## Tech Stack

- [Nest.js](https://nestjs.com) - Nest.js, a TypeScript-based Node.js framework, is used as the main backend.
- [React](https://react.dev) - React.js alongside Tailwind CSS and other client-side libraries is used as the frontend library.
- [Amazon AWS](https://aws.amazon.com) - AWS is used as the primary hosting provider that handles server hosting with [EC2](https://aws.amazon.com/ec2/) and image hosting with [S3](https://aws.amazon.com/s3/).
- [MongoDB](https://www.mongodb.com) - MongoDB (with [Mongoose ODM](https://mongoosejs.com)) is the primary database used to optimize access to vast amounts of organizational data.
- [Redis](https://redis.io) - Redis is used as a secondary database for sessions and caching.

