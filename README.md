# Aqua App

> This is a microservice component, representing the reviews on a product detail page.

## Related Projects

  - https://github.com/Aqua-App/photos
  - https://github.com/Aqua-App/booking
  - https://github.com/Aqua-App/aquabnb-more-places-to-stay-proxy

## Table of Contents

1. [Requirements](#requirements)
1. [Development](#development)
1. [Usage](#Usage)



## Requirements
- Node 12+
- MongoDB server

An example config file is located at `config/dev.example.env`.  A mongoDB connection must be provided.


## Development
Run the following commands sequentially from the root of the project.


### Installing Dependencies

1. npm install
2. npm run seed
3. npm run build
4. npm run dev:client
5. npm run dev:server

## Usage

Visit `localhost:3010/` and you will be served the application.

From here, you can view the seeded component and filter reviews as needed.
