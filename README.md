# Sample Okta widget integration in ReactJS application

In the project directory, you can run:

## To run the application

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## OKTA Setup

### Add an OpenID Connect Client in Okta

- Sign in to the Okta Developer Dashboard, and select Create New App
- Choose Single Page App (SPA) as the platform, then populate your new OpenID Connect application with appropriate values for your app. For example:
Setting | Value |
-------  -------

App Name | OpenID Connect App (must be unique)
Login redirect URIs | http://localhost:3000/login/callback
Logout redirect URIs | http://localhost:3000/
Allowed grant types | Authorization Code

Go to [OKTA Developer Website](https://developer.okta.com/code/react/okta_react/) for more information.
