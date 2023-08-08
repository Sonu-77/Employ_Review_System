# Employee review system

The Employee Review web application enables employees to provide feedback on each other's performance. Users are assigned either an "employee" or "admin" role, and the application displays different dashboard pages based on their role. Admin users have the ability to assign employees to participate in reviews of their peers, while employees can only submit feedback for the assigned reviews. The application is developed using Node.js, Express.js, MongoDB, EJS, and JavaScript.

### 🔗 Hosted link: [Employee review system](https://ers-project-0yl0.onrender.com)



## ⚙️ Functionality

### Admin's functions

- Add employee
- Delete employee
- Update employee details
- Assign review to employee
- Update review of employee

### Employee's functions

- Submit reviews assigned to it
- View reviews given by others

## 🧑‍💻 Getting started

- Fork the project
- Clone the forked repository in your local system
- Create .env file in the root directory and add the following:-
  - PORT="Your port number"
  - MONGODB_URL="Your MongoDB URL"
  - SESSION_SECRET_KEY="Your secret session key"
- Install all required packages

```bash
npm install
```

- Run project

```bash
npm start
```

The project is running on the port number provided by you.

## 🛠️ Tools Used

- NodeJS
- MongoDB
- ExpressJS
- EJS
- Bootstrap


