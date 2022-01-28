# [Full-Stack Soft Dashboard PRO](https://appseed.us/product/full-stack/react-soft-dashboard)

Made of hundred of elements, designed blocks, and fully coded pages, Soft UI Dashboard PRO is ready to help you create stunning websites and web apps. The product comes with a simple JWT authentication flow: **login/register/logout** powered by a [Node JS API Server](https://github.com/app-generator/api-server-nodejs-pro) (PRO version). 

<br />

> Features

- Premium Material UI design - Crafted by [Creative-Tim](https://bit.ly/3fKQZaL/)
- React, Redux, Redux-persist
- Authentication: JWT Login/Register/Logout
- [Node JS API server](https://github.com/app-generator/api-server-nodejs-pro) for a complete full-stack experience 

<br />

> Links

- [Full-stack Soft Dashboard PRO](https://appseed.us/product/full-stack/react-soft-dashboard) - product page
- [Full-stack Soft Dashboard PRO](https://fullstack-react-soft-dashboard.appseed-srv1.com/) - LIVE Demo
- [Node JS API Server](https://github.com/app-generator/api-server-nodejs-pro) (PRO version) - the backend server 
- Support via **Github** (issues tracker) and [Discord](https://appseed.us/support) - LIVE Assistance 

<br />

> Tested with:

| NodeJS | NPM | YARN | Status | 
| --- | --- | --- | --- | 
| `v16.13.0` | `v8.1.0`   | `v1.22.5` | ✔️ | 
| `v14.15.0` | `v6.14.8`  | `v1.22.5` | ✔️ |
| `v12.22.0` | `v6.14.11` | `v1.22.5` | ✔️ |

<br />

![Full-stack Soft Dashboard PRO - Full-stack product built in React and Node JS by AppSeed and Creative-Tim](https://user-images.githubusercontent.com/51070104/138590484-794474cc-c709-458e-8340-695743bc9788.gif)

<br />

## How to use it

To use the product Node JS (>= 12.x) is required and GIT to clone/download the project from the public repository.

> **Step #1** - Clone the project

```bash
$ git clone https://github.com/app-generator/priv-react-soft-ui-dashboard-pro.git
$ cd priv-react-soft-ui-dashboard-pro
```

<br >

> **Step #2** - Install dependencies via NPM or yarn

```bash
$ npm i
// OR
$ yarn
```

<br />

> **Step #3** - Start in development mode

```bash
$ npm run start 
// OR
$ yarn start
```

<br />

## Backend Integration

> The backend API server address is saved in `src/config/constant.js`.

```javascript
export const API_SERVER = "http://localhost:5000/api/";
```

<br />

> Frontend api has been created at `src/api/auth.js`.

```javascript
const axios = Axios.create({
    baseURL: `${baseURL}/api`,
    headers: { "Content-Type": "application/json" },
});
```    

<br />

> Register implementation:

- Frontend method with call to backend
- Form validation
- Error handling

<br />

> Login implementation:

- Frontend method with call to backend
- Form validation
- Error handling

<br />

> Logout implementation:

- Frontend method with call to backend

<br />

> User Context:

- The user account is now saved both to the React.Context wrapper and localStorage

<br />

> Protected routes:
 
- The user cannot access protected routes like /admin, /rtl without being logged in.
- Example of 3 different routes:

```javascript
    <ProtectedRoute path="/admin" component={AdminLayout} />
    <ProtectedRoute path="/rtl" component={RtlLayout} />
    <Route path="/auth" component={AuthLayout} />
```

<br />

> **API Server Descriptor** - POSTMAN Collection

The API Server definition is provided by the [Nodejs API Server](https://github.com/app-generator/api-server-nodejs)

- [API POSTMAN Collection](https://github.com/app-generator/api-server-nodejs/blob/master/media/api.postman_collection.json) - can be used to mock (simulate) the backend server or code a new one in your preferred framework. 

<br />

## Node JS API Server

The product is also open-source and cis already configured to work with Berry Dashboard Template - product features:

- Nodejs / Express server
- JWT authentication (`passport-jwt` strategy)
- Persistence: MongoDB 

> Links

- [Node JS API](https://github.com/app-generator/api-server-nodejs) - source code
- [Node JS API](https://appseed.us/boilerplate-code) - product page

<br />

![Node JS API - Open-source API server built on top of Express Nodejs Framework.](https://user-images.githubusercontent.com/51070104/124934824-c210a700-e00d-11eb-9d01-e05bd8bfb608.png)

<br />

---
[Full-stack Soft Dashboard PRO](https://appseed.us/product/full-stack/react-soft-dashboard) - Provided by [Creative-Tim](https://bit.ly/3fKQZaL/) and **AppSeed [App Generator](https://appseed.us/app-generator)**. 
