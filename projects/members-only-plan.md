# 🎯 _Feature List_

- [x] Users should be able to register and login.
 
- [ ] A user should be able to create messages that have a **title, a time stamp and some text.**  
- [ ] The database should be able to **keep track** of who created the message.  
- [ ] The sign up form should contain proper validation.  
- [ ] Users should be able to log in.  
- [ ] Give the users an option to join membership if they know the secret password.  
- [ ] Allow **only** logged in users to create a new message.  
- [ ] Display all messages from other club members on the homepage -- those who are members.  
- [ ] Add an option to make a user admin.  
- [ ] Admin should be able to delete a message from the database. 
<hr>


# Database Structure
## What data do we need to store?
1. username and password to let them login and sign up on our website. -- A userInformation table.

2. A message table to store title, timestamp, message and author of the message (author is same as the username).

3. A membership table to store information about the users who are the members of the club.

4. An admin table that stores information about which users are admins.


# what is the MVP?
- A user will be able to sign up and log in using their credentials. The user then join the membership to see the messages in the club and **only** able to create a message if the user is in the club. After the message is created it will show it in the message page and homepage with the message details. The details will be gathered from the database that stored the message details. The author name will be gathered from the user who created the message.