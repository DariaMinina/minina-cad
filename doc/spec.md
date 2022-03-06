# Contents
1. Project objective 
2. Blog description
3. Estimated technology stack
4. Design Requirements


# 1. Project objective 

The goal of the project is to develop a blog for people interested in CAD-systems (next - Blog). Users with different access types can post and comment on posts.

# 2. Blog description

## The blog consists of the following use cases:
  1) Registration, authentication and authorization
  2) Functionality for the author
  3) Functionality for the author with the ability to comment
  4) Guest functionality
  
## 2.1 User types

The system provides for two types of system users: author and guest. The author will have the opportunity to post posts, and also, possibly, leave comments. The guest has the right to view all content.

## 2.2 Registration, authentication and authorization

Registering process bloggers must be implemented in the interfaces of the Blog. When registering a blogger, the following fields must be requested:

  1) email is a required field
  2) first and last name is a required field
  3) phone - optional field

After sending the subscriber registration form, he receives an email with the first code by which he can enter. Authentication will be based on one-time codes sent to email. 

Authorization process must be implemented in the interfaces of the Blog. When registering a blogger, the following fields must be requested:

  1) email is a required field
  2) first and last name is a required field

## 2.3 Functionality for the author 

After authorization, the author enters the Blog.
Available functionality: 

  1) сreating a new post 
  2) post editing
  3) profile editing
    a. It should be possible to change the password by confirming your old password
    b. The author has the ability to edit his profile data - email, delete or edit posts, social media, links, language
  5) creating a block with useful links and editing it
  6) choosing a post language 

## 2.4 Functionality for the author with the ability to comment

**2.3** + the ability to leave comments

## 2.5 Guest functionality

  1) view posts
  2) comment on posts
  3) evaluate the post with different reactions
 
# 2.6 Content

The content published by the author can be formatted text with the ability, as a minimum, to make the text bold, italic, underlined, strikethrough. Perhaps we should add the ability to create headings of different sizes to structure long text content.
It should be possible to add lists and images to the content of the post, as well as the ability to attach files.
Every post should have a title.
It should be possible to create a teaser post - a cover and description text about what is in this post. This teaser will be visible to guests and other authors.


# 3. Estimated technology stack

To implement the system, the following stack of technologies is proposed:
1) Backend:
 a. Go
 b. ...
2) Frontend
 a. HTML/CSS
 b. Javascript

# 4. Design Requirements
