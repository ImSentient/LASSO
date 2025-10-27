## Hello!

Table of Contents:

[Pulling](#Pulling)

[Committing / Pushing](Committing-/-Pushing)

[Obsidian](#Obsidian)


if you want to contribute to this project, there's a few steps you need to do first:
* Download [Github Desktop](https://desktop.github.com/download/) (or if you know CLI that works too)
* Download [Obsidian](https://obsidian.md/)

Awesome! Now that you've downloaded these necessary things, you'll need to sign into Github Desktop with your Github account (or create it if you don't have one already). 

We'll move onto adding, committing, and pulling (these are the primary things you'll be doing with git), then we'll finish up with Obsidian.
- - -
Workflow

First, let's clone this repo so you can have access to it locally on your own computer

![enter image description here](https://github.com/ImSentient/LASSO/blob/main/Pictures/2.png)

Go over to "Clone a repo from the internet" and click 

![enter image description here](https://github.com/ImSentient/LASSO/blob/main/Pictures/3.png)

Once your window looks like the screenshot above (except "local path", change that to wherever you want this repo stored. The desktop on Windows would be C:\Users\(username)\Desktop) and you've deleted the trailing #, click "Clone" and tada! You have the repo installed locally now. 

> Question: What does this do for me? Why arent we just uploading and downloading files off of Google Drive or something? 

Good question. The answer is because going to a cloud service and manually downloading changes each time can be cumbersome, and if two people edit the project overnight, one person's upload is going to erase the work the other person's upload had. Github handles this issue wonderfully. 

Anyways, back to the workflow:

## Pulling
Whenever you want to update your local repo to be most current, you'll have to "fetch" first. 

![enter image description here](https://github.com/ImSentient/LASSO/blob/main/Pictures/4.png)

If there aren't any new changes to the repository, then nothing will change. If there *are*, then you'll see something like this

![enter image description here](https://github.com/ImSentient/LASSO/blob/main/Pictures/5.png)

Go ahead and pull from main (origin) and you'll be current. If you go and take a look back inside the repository file, you'll see any new files that have been added and new content if you open it within obsidian.

## Committing / Pushing
If you make any changes and want to upload them, go back to the Github Desktop app and it'll look something like this:

![enter image description here](https://github.com/ImSentient/LASSO/blob/main/Pictures/6.png)

You can remove any files you don't want to push to main on the left sidebar, and you can optionally write a title with a brief description of the data you've added (for bookkeeping)


![enter image description here](https://github.com/ImSentient/LASSO/blob/main/Pictures/7.png)

After you're done, click "commit to main" and then "push origin"

![enter image description here](https://github.com/ImSentient/LASSO/blob/main/Pictures/8.png)

Done! everyone else should be able to pull your changes now.


## Obsidian
Open Obsidian and you should see something like the picture below

![enter image description here](https://github.com/ImSentient/LASSO/blob/main/Pictures/9.png)

Click "open folder as vault" and navigate to the repo we just created.

![enter image description here](https://github.com/ImSentient/LASSO/blob/main/Pictures/10.png)

Select the folder, and then you should have a view that looks like this

![enter image description here](https://github.com/ImSentient/LASSO/blob/main/Pictures/11.png)

From here you're able to navigate through our research and start contributing! Don't forget to push to main after you're done making changes! It doesn't matter too much if you forget to, but definitely push before citing your own research in the repository lol.

One last thing, we need to change your Obsidian to put your pasted pictures into dedicated folders within the project (for housekeeping). Go down to the cog wheel on the bottom right, click "files and links" on the left sidebar, and then navigate to "default location for new notes". Change it to "in the folder specified below" 

![enter image description here](https://github.com/ImSentient/LASSO/blob/main/Pictures/12.png)

and then insert "_screenshots" into the field below the setting.

![enter image description here](https://github.com/ImSentient/LASSO/blob/main/Pictures/13.png)

Done! You're all set!
