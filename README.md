<h1 style="
  color: #5b14c7; 
  font-weight: 1000;
">Nxt-Watch</h1>

In this project, I have developed the **Nxt-Watch**, an application that offers a user-friendly platform for job seekers. Users can log in and access a comprehensive list of Nxt-Watch opportunities with various features, including search functionality by job title and filtering options based on salary range and employment type.

### Link: https://nxtwatch7854.ccbp.tech/login

### Login Credentials

### Username: rahul

### Password: rahul@2021


The key components and functionalities of this project include:

- **User Interface**: I created distinct pages for Login, Home Details using React components. These components leverage React's capabilities for handling props, state management, event handling, and form inputs.
- **Authentication**: Users can log in by providing their username and password. The application then performs an HTTP API call for login authentication. Upon successful login, a JSON Web Token (JWT) is generated and stored in the client's storage. This token is subsequently included in the headers of API requests to authorize the user.
- **Routing**: To ensure a seamless user experience, I implemented routing using React Router components such as Route, Switch, and Link.
- **Security**: I established security measures by implementing protected routes. If a user attempts to access Home, Details routes without proper authentication, they are automatically redirected to the Login page.

**Technologies used**: React JS, JS, CSS, Routing, REST API Calls, Local Storage, Cookies, JWT Token, Authorization, Authentication
