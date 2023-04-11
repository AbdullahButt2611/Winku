<p align="center">
  <img src = "ExternalImages/logo.png" width="300">
</p>
<h1></h1>
<h3 align="center">
  Social Networking Site
</h3>


<br><br>

<p align="justify">
A social networking site built using Node.js and MongoDB would be a web application that allows users to create profiles, connect with friends, and share various forms of content such as photos, videos, and posts. The application would utilize Node.js on the server-side to handle incoming requests, process data, and communicate with the MongoDB database to store and retrieve user information and content. The database would store user profiles, connections between users, and all shared content. Users would be able to create accounts, customize their profiles, and connect with friends by sending friend requests. They would be able to share content on their profile page, create and join groups, and participate in various forms of social interaction such as commenting, liking, and sharing posts. The application would also have features for searching and discovering new users and content, as well as various privacy and security settings to ensure the safety and security of user data.<br>
Social networking site is a project developed in Node JS and Mongo DB. It has all the functionality that you need to build a social network for your local community. Node JS is becoming a rising programming language for backend servers, it is fast and easy to learn. If you know Javascript, you already knew Node JS.
On the other hand, Mongo DB is quickly becoming a standard for creating schema-less applications where the structure of your database is not important. It is widely being used in large systems with an intention to scale easily.
</p>

### Basic Version

<p align="justify">
This project has a basic version that allows you to download the code for free and set it up in your local system. In the source files, a file named “How to install.txt” will guide you on how you can set up the project in your system. But if you are still facing a problem, you can always contact me.
In the basic version, you will avail of the authentication functionality that includes login and registration of the user. Passwords are encrypted before storing in Mongo DB. The project uses JSON Web Token (JWT) for storing logged-in user’s information. JWT is used to transmit information securely between client and server. After logging in, the user will be able to update his profile picture and cover photo. Uploaded files are being stored in Node JS server using fs module which stands for File System and the path of the uploaded file is stored in Mongo DB.<br>
Now come to the most important part of any social networking site, POSTS. What makes a social network great is the number of posts, so you should allow users to create posts, update their status, what they are doing, etc. The basic version has the ability to create posts using text, images, or video. Post created by the user will only be viewed by his friends. When the post is created, the user will like the post, comment on a post, and reply to any comment. Posts can also be shared on your timeline, so you can pick any post you like and hit the “share” button, and will be displayed on your timeline as well.
When someone likes your post, comments on your post, or replied to your comment, a notification will be received on the left side of your home page. You can view a list of all notifications received and notification will be marked as read once opened. The basic version also has a search functionality where you can search people by their name, username, or email address. This is all we are offering in the basic version. Next, we will discuss its pro version.
</p>

### Pro Version

<p align="justify">
In terms of search functionality, in the basic version, you are able to search the people, but in the pro version, you will be able to search groups and pages as well by their name. This will create 3 tabs on the search page, first for users, second for pages, and third for groups.
In terms of authentication, you will be able to verify the user by his email address during registration. When someone registers, an email will be sent to him with an instruction to verify their email address. Users who have not verified their emails will not be able to log in. This will help you know that the users you have on your site are actual users, not robots. This pro version also comes with the functionality to reset the password. This gives users the ability to reset their passwords if they have forgotten. When someone types his email for resetting the password, the system will check if the email exists then it will send an email with a link to reset the password. When that link is opened then it will confirm that it is the valid link and show the field to enter a new password. <br>
You can create friends by searching people by their name, then send them a friend request. The other person will be able to respond to that request, he can either decline or accept the request. Once accepted, you both will be able to view each other’s posts in your timeline.<br>
You can create pages by entering the page name, cover photo, and a short description of the page. Then you will be able to add posts to that page as well. When someone searches for that page, he will be able to view all the posts on that page. Users will be able to like the page, once liked they will be able to view the page’s posts in their timeline as well.<br>
This pro version also allows you to create groups by entering the group’s name, cover photo, and a short description of the group. Once the group is created, people will be able to see it in their search results, they will send a request to join the group. Only you (admin) will be able to decline or accept the group request. Once accepted, the user will become a member of that group. Members are allowed to add posts in that group and all the other members will be able to view it in their timeline.<br>
One of the most demanding functions of a social network is chat. You make friends chat with them, in this version you will be able to have a real-time secure chat between 2 friends. We have used Sockets for real-time communication, all the messages are also being stored in Mongo DB.<br>
It also has a functionality where you can see a list of all people you have viewed your profile. When someone visits someone’s profile, we are storing his record in Mongo DB along with the current date and time. Then the other person will see a list of people who viewed his profile along with the time that person visited your profile recently.
Since you are creating posts, you must be able to edit and delete posts. You can edit your own created posts and you can also delete your created posts as well. Once the post is updated, it will be updated on all social networks. Although it is Mongo DB (non-relational) still manages to update the post’s document in all places. The same goes for delete, once the post is deleted, it will be deleted all over the social network. It also has a functionality that we call “load more”. It allows you to load more posts without having to reload the page. When the social network is opened, the first 30 posts will be fetched and displayed in the browser. When the user scrolls to the bottom, a button is displayed at the bottom of the page which when clicked will fetch the next 30 posts. You can change the number of posts as you wish.You can send images and videos in a chat with your friends. All attachments sent are being stored in the Node JS file system. You can also preview the files before sending them. Images and videos are not being compressed, so you can send high-quality images without having to worry that the system will reduce the quality of images, it will not reduce the quality of images or videos.<br>
You will be able to share posts in your timeline, pages you have created, and the groups you have joined.
You will be able to view a list of all people you have liked and shared your post. This is really helpful for a social network where you want to know who has liked and shared your post.
</p>

<br><br>
<!-- ................................................................................................................................. -->




### Requirements
Following are some of the things required to successfully run the project:

- [Node JS](https://nodejs.org/en/)
- [MongoDB](https://www.mongodb.com/download-center)
- [MongoDB Compass](https://www.mongodb.com/download-center/compass)


<br><br>
<!-- ................................................................................................................................. -->






### Features
<br>
Following are some of the new features and learning encountered while creating this amazing project:

- Message encryption.
- Customer support.
- Ban & delete the user.
- Filter bad or abusive words.
- Adult image validation.
- Ban the post.
- 24 hour stories
- Audio files
- Events
- YouTube links
- Advertisement (boost post)
- Emoji comments
- Like, dislike, and comments on stories
- People nearby
- Group chat


<br><br>
<!-- ................................................................................................................................. -->


### Resources
<br>
Follwing resources have been used in maintaining this project:

- [Wix](https://manage.wix.com/) to create logo of the project.
- [Remove.bg](https://www.remove.bg/upload) to remove the background of the images used.
- [Chatgpt](https://chat.openai.com/chat) to write some content for the website.


<br><br>
<!-- ................................................................................................................................. -->





### Developer

Muhammad Abdullah Butt <br>
abdullahbutt12292210@gmail.com <br>
> [Instagram](https://www.instagram.com/abdullah.butt.22/)<br>
> [FaceBook](https://www.facebook.com/profile.php?id=100076291614529)<br>
> [YouTube](https://www.youtube.com/channel/UCnuOFQyMywg-KuoN-lmav1Q)<br>
> [Portfolio](https://rebrand.ly/MuhammadAbdullahButt_MABCORP)<br>
> [Project Displayer]( https://rebrand.ly/ProjectDisplayer_MABCORP)
<br><br>
<!-- ................................................................................................................................. -->






<h1 align="center">Graphical User Interface</h1>
<br>

![GUI for this Project](https://adnan-tech.com/wp-content/uploads/2023/04/How-to-create-a-social-networking-site-in-Node-JS-and-Mongo-DB.jpg)
![GUI for this Project](https://adnan-tech.com/wp-content/uploads/2023/04/social-networking-site-nodejs-mongodb.png)



<br><br>
<!-- ................................................................................................................................. -->





