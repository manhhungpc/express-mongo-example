# Get started

```ssh
npm install
# Make a copy of file enviroment and update some config.
cp .env.example .env

# Run Application
npm run dev
```

Documentation available at: `/api/docs`

# Documentation

### Tech stack

-   NodeJS / ExpressJS / Javascript
-   MongoDB

### Project Structure

| Name                     | Description                                                                                        |
| ------------------------ | -------------------------------------------------------------------------------------------------- |
| **src/**                 | Source files                                                                                       |
| **src/config**           | The config directory, as the name implies, contains all of your application's configuration files. |
| **src/utils**            | Other utility functions to use in your app.                                                        |
| **src/api/controllers/** | REST API Controllers                                                                               |
| **src/api/exceptions/**  | (WIP) Custom HttpErrors like 404 NotFound                                                          |
| **src/api/models/**      | MongDB Models                                                                                      |
| **src/api/services/**    | Service layer                                                                                      |
| **.env.example**         | Environment configurations                                                                         |
| **jsconfig.json**        | Javascript config file                                                                             |
