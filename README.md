# DM Airlines - MERN
This MERN final project is about a programm 


## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


## Description
This is an app 
## Functionality
Examples
- Dark and light theme
- Preview em tempo real
- Modo tela cheia
- Multiplataforma


## Components
Pages:

* HomePage
* LoginPage
* SignupPage
* Crew Schedule

Components:
* NavBar
* LoginPage
* SignupPage
* Crew
* 
## Service
* Auth Service

        authService:

            .login(user)

            .signUp(user)

            .logout()

            .validate()

- **User Service**

     `userService` :   

        `.updateCurrentUser(id, userData)`
        `.getCurrentUser()`       
## Routes
### ReactRouter Routes (React App)
| Path                         | Component            | Permissions                | Behavior                                                  |
| ---------------------------- | -------------------- | -------------------------- | --------------------------------------------------------- |
| `/login`                     | LoginPage            | anon only `<AnonRoute>`    | Login form, navigates to home page after login.           |
| `/signup`                    | SignupPage           | anon only  `<AnonRoute>`   | Signup form, navigates to home page after signup.         |
| `/`                          | HomePage             | public `<Route>`           | Home page.                                                |
| `/user`              | ProfilePage          | user only `<PrivateRoute>` | User and player profile for the current user.             |
| `/user/edit`         | EditProfilePage      | user only `<PrivateRoute>` | Edit user profile form.                                   |
| `/tournaments/add`           | CreateTournamentPage | user only `<PrivateRoute>` | Create new tournament form.                               |
| `/tournaments`               | TournamentListPage   | user only `<PrivateRoute>` | Tournaments list.                                         |
| `/tournaments/:tournamentId` | TournamentDetailPage | user only `<PrivateRoute>` | Tournament details. Shows players list and other details. |
| `/tournament/players/:id`    | PlayerDetailsPage    | user only `<PrivateRoute>` | Single player details.                                    |
| `/rankings/:tournamentId`    | RankingsPage         | user only `<PrivateRoute>` | Tournament rankings list.                                 |



## Server | Backend

## Models

User Models
```
{
  email: { type: String, required: true, unique: true },
  password: { type: String, required: true },
}
```
Crew model
```
{
  firstName: { type: String, required: true },
  lastName: { type: String, required: true },
  profileImage: { type: String },
}
```

User Models
```
{
  email: { type: String, required: true, unique: true },
  password: { type: String, required: true },
}
```




## Packages

```
git init

```
## Stack used

**Front-end:** React

**Back-end:** Node, Express, Mongo


## Links

[Client repository Link]()

[Server repository Link]()

[Deployed App Link]()

Slides

[Presentation](https://choosealicense.com/licenses/mit/)
## Authors
Daniel Rodrigues 

Mariana Carvalho




