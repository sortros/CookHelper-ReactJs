# CookHelper-ReactJs

## Description
​
Cook-helper is an app that will make your life much easier by helping you organize your ingredients and meals by offering you lots of recipes from what you have in your fridge.
​
## USER STORIES (MVP)
​
**404** - As a user I want to see a nice 404 page when I go to a page that doesn’t exist so that I know it was my fault
​
**500** - As a user I want to see a nice error page when the super team screws it up so that I know that is not my fault
​
**Home page** - As a no-user I want to be able to access the landing page so that I see what the app is about.
​
**Sign up** - As a user I want to be able to create an account to use the app and save my tasks
​
**Login** - As a user I want to be able to log in on the webpage 
​
**Logout** - As a user I want to be able to log out from the webpage
​
**Profile** - As a user I want to be able to see my profile and edit it
​
**private route** - As a user you are alowed to create an account and have a profile and you can search many recipes as you want and booked as favourites in your profile
​
## BACKLOG
​
*Fully responsive*

​
​
## ROUTES backend
​
| Name            | Method | Endpoint                      | Description                                      | Body                                  |        |
| --------------- | ------ | ----------------------------- | ------------------------------------------------ | ------------------------------------- | --------------- |
| Home           | GET    | /home                            | See all my tasks                               |                                       |                 |
| Sign up    | POST   | /signup                        | Sign up a user with an account                          | { mail, username, password }                                   |              |
| Log in          | POST   | /login                        | Log in the user                                  | { mail, password }                      |            |
| Logout   | GET    | /logout                            | Logout a user                       |                                       |  |
​
## ROUTES Frontend
​
| Name            | Method | Endpoint                      | Description                                      | Body                                  |        |
| --------------- | ------ | ----------------------------- | ------------------------------------------------ | ------------------------------------- | --------------- |
| Homepage 
| Userpage
​

​
​
## MODELS
​
recipes model
​
```js
{
    title: String,
    description: String
}
```
​
 user model
​
```js
{
    username: String,
    email: String,
    hashedPassword: String,

}
```
​
## LINKS
​
### Github project
​
- [Frontend project]()
- [Backend project]()
​
### Deploy links
​
- [Frontend deploy]()

​
### Wireframes 
​
- [InVision with Wireframes]()
​
### Slides
​
- [Slides]()
