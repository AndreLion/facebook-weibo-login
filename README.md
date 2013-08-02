Facebook and Weibo Login
====================
**a.k.a. FWL.** A combiniation of Facebook and [Weibo](http://open.weibo.com/widget/js#connect) javascript SDK with 3rd party login function.

This is a javascript component combined with Facebook SDK and Weibo SDK. Help you deploy 3rd party website login function to your own website.

Login with 3rd party website members will help you:

1. One click register, easily attract new users;
2. No need to mantain/store/encrypt user password in database;
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

Something you should prepare beforehand:

1. Your own website required a register/login function.
2. Create a Facebook app and write down  it's ID.
3. Create a Webio app and write down it's ID. [link](http://open.weibo.com/wiki/%E6%96%B0%E6%89%8B%E6%8C%87%E5%8D%97)
4. A user table in database used for storing 3rd party user informatin.
5. Skill of write backend language and rewrite CSS to adapt your own style.

How to use FWL:

1. Check the Demo and it's source code.
2. Copy the HTML code and paste them to the right place on your page.
3. Copy the Javascript code and paste them before the closing of body tag.
4. (Optional)Add the code in CSS file into your stylesheet, or write your own stylesheet to fit your website style.
5. (Optional)If you use Javascript module loader, package the Javascript code into a module.
6. (Optional)Optimize your code, make them graceful.

FAQs:

Q: How can I register as Weibo developer if I can't read Chinese?
A: Message me.

Q: How can I register as Facebook developer if I can't read English?
A: Ask your English teacher.

Q: I can't visit Facebook!
A: Ask Schoolmaster Fang.
