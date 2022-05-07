## Requirements
- [ ] Your application must be deployed and accessible to the public internet
- [ ] Your code must be made available to instructors for grading (via the submission link at the end of this section)
- [x] Your application must use a front-end, back-end, and database
- [x] The database should contain at least two entities, a User and a Post, in a one to many relationship, as shown in the ERD below
- [x] You should style your application in order to lay out components in a sensible way
- [ ] You should use the following stories to build out the functionality of your app

## Stories
1. As a blogger I want to be able to create an account so that I can create blogs.
- [x] The user credentials must be salted and hashed before being stored.
2. As a blogger I want to be able to log into my account so that I can see all the blogs that I have created.
- [x] After logging in, the blogger should be redirected to all of their blog posts.
3. As a blogger I want to be able to create a new post so that I can share my insights with the world.
- [x] After the post is created, the blogger should be redirected to all of their blog posts.
- [x] A post displays title, content, and creation date.
4. As a blogger I want to be able to see all of the posts I have created so that I can track my progress.
- [x] The blog posts should only display the first 100 characters with “...” at the end if they are longer than 100 characters.
5. As a blogger I want to be able to see any individual post I have made.
- [x] The full post should be displayed.
6. As a blogger I want to be able to edit a post so that I can fix any mistakes I made creating it.
- [x] When the user toggles edit mode, the page remains the same and the fields become editable.
7. As a blogger I want to be able to delete a post so that I can remove any unwanted content.
- [x] When the user deletes the blog they should be redirected to all of their blog posts.
8. As a visitor I want to be able to view all posts created by all users so that I can consume content.
- [x] Unauthenticated users should be able to view all posts, and any single post.
- [x] The posts should only display the first 100 characters with “...” at the end if they are longer than 100 characters.
9. As a visitor I want to be able to view a specific post created by all users so that I can consume content.
- [x] Unauthenticated users should be able to view all posts, and any single post.
10. As a blogger I want to be able to view all posts created by all users so that I can see other people’s content.
- [x] Unauthenticated users should be able to view all posts, and any single post.