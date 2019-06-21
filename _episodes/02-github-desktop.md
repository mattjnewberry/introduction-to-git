---
title: "Github Desktop"
teaching: 0
exercises: 0
questions:
- "How can we use Git to make some simple changes?"
objectives:
- "Become familiar with Github Desktop"
- "Undestand how to make a Github commit and revert the commit"
keypoints:
- "Github deskop let's use use all the amazing functionality git has"
- "We can make commit to update the git version"
- "We can also revert commits incase we've made a mistake!"
---

Firstly, we need to download Github Desktop to start working with git.

Download Github Desktop from here: https://desktop.github.com/ (Mac and Windows)

Once it's downloaded, open up the zip file. You can do this by just double clicking on the download at the bottom of the chrome tab. From there, the zip file will unpack and install the application!

To open the application on Mac, `cmd + space` and Search for "Github Desktop"
To open the application on windows, click ont he windows icon in the bottom left and search for "Github Desktop".

---

Okay, brilliant! We know should see a login on page on the Github Desktop application! Hopefully, you already have a Github account and you can sign in, but if not, don't worr! Let's make one:

Go to: https://github.com/ and click `Sign Up` in the top right hand corner (It's free don't panic!). Fill out the details on the page and click continue. Please ask one of the teaching assistants if you get stuck or are unsure.

Once we've made a Github account, make sure to sign into your new account on Github Desktop to continue with the lesson!

---

Let's begin by creating out first repository!
(Repository just desribes a project and all it's files, it can have sub-directories etc.)

Click on `Create a local repository` - You can call your repository whatver you like, some suggestions might be "hello-world", "${INSERT_YOUR_NAME_HERE}-app", "my-first-project".
    - Enter a sensible desciption that will help you remember what the repository is for, maybe "This is my first Github repository".
    - Leave the local path as is
    - Tick the box that says `Initlize this repository with a README` (A README is just a text file that gives someone who's never seen your project before all the information they need about the project, such as who made it and why they made it etc;!)
    - Ignore "Git Ignore" and the "licences" sections
    - Click `Create repository`

Congratulations! You've now created your very own, first, github project!. But it looks a little the same as everyone else, so let's start changing it!

Okay, now remember, Github Desktop is just a tool that allows us to use git. So when it tells you you have "No Local Changes", that's correct! Even though in the repository there is the `README` file, that file was created with the repository. You have two version of your repository, the git version and the local version. We can add to the git version by doing what's called a "commit".

Let's change the  `README` file to be more personal. 

Click the button that says `Open in Visual Studio Code` (Visual Studio Code is just a text editor, you can use any text editor you like, even notepad!).

Type some text into the `README` file. Maybe we can add who's repository this is, for example `Made by Matt!`. Then save the file using `cmd + s` on mac or `ctrl + s` on windows.

Once it's saved, go back to Github Desktop. Now we can see the change we've made! So what this means is that we have made a local change to the file (That's a change that only exists on your laptop).

Git will now give us the option, in the bottom left, to write a message and `commit` this change to the git version of our repository. So let's do that. 

Give the `commit` message a sensible summary, something like `Add creator to README`. You can choose to give it a description if you want. Then click `commit to master` (Master is just the main git version, you can have other git versions too, we'll cover that later).

And it's done! We've made our first git commit! To see this commit, go to the `History` tab in the top left. 

Now for a challenge. Make another change to the `README` file, adding `Dina is a bad programmer`, and commit it!.

.
.
.
.
.
.
.
.
.
.
.
.
.
.

Uh oh! We've made a mistake, that last commit wasn't supposed to go to master! `Dina is a good programmer!`. So we need to `revert` this change!

Go to the history, and right click on the change we just added. Click on `Revert this commit`. This will return the git version back to before the previous commit. Check it out by viewing the `README` file.




