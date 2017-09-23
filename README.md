# intro-to-git

This guide is meant to give you a quick introduction to the four steps of saving your work and pushing it up into your GitHub repo.  The four git commands we'll be covering are:

1. git status
2. git add .
3. git commit -m " "
4. git push

## git status

You would start with a *git status* this command shows us what files were changed in red and if it is already added, then the color of the text will be green.

![ScreenShot](https://raw.githubusercontent.com/junior-devleague/intro-to-git/master/assets/Screen%20Shot%202017-09-22%20at%203.05.45%20PM.png)

**If you have changes, this is what it should look like:**

![Screenshot](https://raw.githubusercontent.com/junior-devleague/intro-to-git/master/assets/Screen%20Shot%202017-09-22%20at%203.08.24%20PM.png)

## git add .
If your git status looks like that, then awesome! That means there's something we can add.

The next step is *git add .* remember the space in between the add and . this command will prepare our work to be committed.

It should look like this:

![Screenshot](https://raw.githubusercontent.com/junior-devleague/intro-to-git/master/assets/Screen%20Shot%202017-09-22%20at%203.12.40%20PM.png)

Hit *enter* and you shouldn't receieve a response.  However, if you hit **git status** again, you'll see that the text is now green!

![Screenshot](https://raw.githubusercontent.com/junior-devleague/intro-to-git/master/assets/Screen%20Shot%202017-09-22%20at%203.14.50%20PM.png)

## git commit -m " "

Once you have it added, we are now going to *commit* our work, this basically means that we are saving the work we made in our own personal repo.  *Remember when we cloned our project off of GitHub? we made a copy of that project in our computer that we edit and then copy it in GitHub*

After git add, we use the command *git commit -m " "* This command saves our updated work.  When we save it to GitHub, we can give it a message with *-m " "* that can help remind us or other people what we have changed in our files.  Keep it short, sweet, and clear!

Here's what it looks like:

![Screenshot](https://raw.githubusercontent.com/junior-devleague/intro-to-git/master/assets/Screen%20Shot%202017-09-22%20at%203.38.49%20PM.png)

Once you hit enter, you should get a response from your computer telling you what's been changed.  If there are no errors then you should be good to go!

![Screenshot](https://raw.githubusercontent.com/junior-devleague/intro-to-git/master/assets/Screen%20Shot%202017-09-22%20at%203.41.53%20PM.png)


## git push 

Lastly, is the command *git push* this command is what we use to "push" up our work to GitHub, this will update up our work between what we have done on our own computers and what we have saved on GitHub.

It should look like this:

![Screenshot](https://raw.githubusercontent.com/junior-devleague/intro-to-git/master/assets/Screen%20Shot%202017-09-22%20at%203.45.55%20PM.png)

And after you hit *enter*, this is the response you should get and this tells you that you're good to go! After pushing, you can go back to your github project and you'll see all of your changes saved!

![Screenshot](https://raw.githubusercontent.com/junior-devleague/intro-to-git/master/assets/Screen%20Shot%202017-09-22%20at%203.48.32%20PM.png)

## Reminder

Remember that you _must_ be inside of the correct project/folder inside of your terminal/bash.  If you want to update a project, remember that your terminal _must_ say mingw64~/desktop/webdev/*name of your project* and we can do this by using the command *cd* and then the name of where you want to go!
