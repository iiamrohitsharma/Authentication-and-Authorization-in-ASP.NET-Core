# Authentication and Authorization in ASP.NET-Core
Authentication and Authorization in ASP.NET Core

### JSON Web Token
JWTs are used as a secure way to authenticate users and share information. Typically, a private key, or secret, is used by the issuer to sign the JWT. The receiver of the JWT will verify the signature to ensure that the token hasn't been altered after it was signed by the issuer.

### OAuth
OAuth is a standard for users to delegate permissions to apps or websites to access their resources, for example when you allow some web app to post on your behalf to your Facebook feed. Various tokens are used in this process and they're very often JWT. OAuth2 adds authentication via OpenID Connect.

### OWIN
OWIN on the other hand is a standard for web servers which decouples IIS and ASP.NET with the aim of allowing ASP.NET to run on other web servers which implement OWIN and other frameworks generally to run on OWIN compatible servers if those frameworks are OWIN compatible.

### Auth0
Auth0 is an identity platform which can do OAuth and allows you to use JWTs, generally it handles your identity and SSO

### IdentityServer
IdentityServer is an authentication server that implements OpenID Connect (OIDC) and OAuth 2.0 standards for ASP.NET Core. It's designed to provide a common way to authenticate requests to all of your applications, whether they're web, native, mobile, or API endpoints

## Some alternatives

#### ASP.NET Core Identity
It is an API that supports user interface (UI) login functionality.
It is designed to be used together with Duende IdentityServer4.
Manages users, passwords, profile data, roles, claims, tokens, email confirmation, and more.

## Important Links

#### [ASP.NET Core Identity](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/identity?view=aspnetcore-6.0&tabs=visual-studio)
#### [Words of wisdom for Authentication](https://stackoverflow.com/questions/549/the-definitive-guide-to-form-based-website-authentication)



