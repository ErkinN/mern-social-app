# FullStack Social Media App

Complete React MERN Full Stack Social Media App

REST Api conventions
//AUTH
Register a new user => POST/auth/register
Login a user => POST/auth/login

//POSTS

Get all posts => GET/posts/
getUserPosts => GET/posts/:userId/posts
Like a post => PATCH/:id/like

//USERS
Get a User => GET/users/:id
Get User Friends => GET/users/:id/friends
Add Remove & Friend => GET/users/:id/:friendId
