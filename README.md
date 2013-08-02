Facebook and Weibo Login
====================
**a.k.a. FWL**

This is a javascript component combined with Facebook SDK and Weibo SDK. Help you deploy 3rd party website login function to your own website.

Login with 3rd party website members will help you:

1. One click register, easily attract new users;
2. No need to mantaining/store/encrypt user password in database;
3. Get social connetions information from users, also you can send notification via 3rd party website.

There are also some potential risk may harm your webiste:

1. 3rd party website shutdown
2. Banned by 3rd party website
3. 3rd party website network fail or javascript SDK bug.

Features of FWL:

1. **Covered the most netizens in the world.**
Facebook is the largest social website in the world (1.11 billion users as of May 2, 2013). Unfortunately, it's blocked in China, the country has most netizens in the world. And Weibo is the most widely used social service in China. So Facebook + Weibo ~= Global netizens.
2. **Asynchronously load javascript files, avoid slow down your page speed.**
Facebook has already changed their ways of loading javascript SDK to aysnc. But Weibo has not. FWL makes Weibo SDK load asynchronously so that it will not block the rendering of your page in any connection situation.
3. **Easily deploy and custom style.**
All you have to do is paste a snippet javascript and css code into your website, and then a little extra backend work such as read/write from database.

