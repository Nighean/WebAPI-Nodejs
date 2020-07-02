# WebAPI-Nodejs

WebAPI-Nodejs is an API middleware that manages some information regarding insurance policies and company clients.

## Getting Started

This API allows you to:

- Login with a user email -> You get a token that allows you to get all the requests as long as you are authorized with your role.
- Get user data filtered by user id -> Can be accessed by users with role "users" and "admin"
- Get user data filtered by user name -> Can be accessed by users with role "users" and "admin"
- Get the list of policies linked to a user name -> Can be accessed by users with role "admin"
- Get the user linked to a policy number -> Can be accessed by users with role "admin"

To start the app you need to install all the dependencies with the following command:

```bash
$ npm install
```

Then, run the app in development mode to start with this command:

```bash
$ npm run dev
```

In order to see and check all requests to the API, you can use swagger in the following path:
http://localhost:5000/api-docs/

Furthermore, there are some unit tests that can be executed by this command:

```bash
$ npm test
```

### Prerequisites

You need to have [Nodejs](https://nodejs.org/) already installed.

## Built With

- [Nodejs](https://nodejs.org/) - The javascript framework used

## Authors

- **Anna Alcaide** - _Initial work_ - [WebAPI-Nodejs](https://github.com/Nighean/WebAPI-Nodejs)
