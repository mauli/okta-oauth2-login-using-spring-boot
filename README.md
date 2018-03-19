# Okta Oauth2 login using Spring Boot

Simple Okta OAuth 2 authentication application with Login and Logout. This app can be intigrated with any Java, Spring or backend framework. You can extend this as per your needs.   

## Spring Boot, OAuth2 Authentication, Okta API


## Requirements

1.  Java - 1.8.x

2.  Maven - 3.x.x

3.  Spring 5, Spring Boot

4.  Okta developer App


## Steps to Setup

** 1. Clone the application repo **

** 2. Change application.yml file  **
 Change file with your clientId and clientSecret.

** 3. Build and run the backend app using maven**

```bash
mvn spring-boot:run
```
The application will start at <http://localhost:8080>.

## Snapshots

```
Landing page
```
<img src="src/main/resources/static/images/login.png" width="60%" >

```

```
API authentication on Okta
```
<img src="src/main/resources/static/images/Okta_app_authentication.png" width="80%" >

```
Callback to base URL after successful authentication
```
<img src="src/main/resources/static/images/callback_successful_login.png" width="60%" >

Feel free to use the code.
