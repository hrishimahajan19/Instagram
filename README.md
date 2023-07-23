# Instagram
## Frameworks and Language used
Spring Boot Framework
Java language
## Data Flow
UserController
saveUser( )
getUser( )
deleteUser( )
updateUser( )
PostController
savePost( )
getPost( )
deletePost( )
updatePost( )
UserService
saveUser( ) - saves a new user to the tbl_user table
getUser( ) - gets users list if the request parameter is null
deleteUser( ) - deletes user and all the posts posted by him
updateUser( ) - updates user info
PostService
savePost( ) - saves a new post to the tbl_post table
getPost( ) - gets posts list by a perticular user and if postId is not specified, it will get all the posts
deletePost( ) - deletes a particular post
updatePost( ) - updates a post whose postId will be given
Repository
findAll( )
findById( )
deleteById( )
save( )
## Database Used
MySQL Database : instagram_db
## Project Summary
In this project we have created 2 models namely;User and Post. We have provided some endpoints and also in this section below we have given our API. Using this API we can perform the CRUD operations accordingly.

http://localhost:8080

End Points:

/user
for creating and getting user

/user/{userId}
for updating and deleteing user

/post
for creating and getting post

/post/{postId}
for updating and deleting post
