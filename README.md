# UCLFS_Performance

This repository if for the files used by the UCL Formula Student performance sub-team.

## How to use GitHub

I am not a git expert and some of the steps I talk about here I have never done myself as I have only used git for personal projects and not collaborative projects. If you get some cryptic error then I will likely not be able to help, and I also do not know how to use git through the console.

Step 1. Install visual studio.
Step 2. Install git. On Windows there are a bunch of options when installing it and you should actually pay attention to those settings, message on the chat if you are unsure.
Step 3. Set your git credentials. Look up how to do this, it involves two terminal commands to set your email and your username.
Step 4. Copy and the link to this repository (https://github.com/HenryGinn/UCLFS_Performance/), go to visual studio, click "clone repository", and enter the link.
Step 5. Save it somewhere sensible.

This has created a local copy of the repository on your device, any changes you make will only affect that local copy. Once you have made some changes and you want to submit them, you go to the source control tab (there are five tabs arranged vertically on the top left in visual studio, source control is the third one), and click commit. You will then need to write a small message describing what you have done. The limit is 72 characters, and this is what appears in the version history. If you want to include more details then you can use the other lines. Try not to change loads of stuff in each commit, if this is happening then you are not committing often enough. Save the commit message (it is a text file that is uploaded along with everything else) and click the tick in the upper right. You should now see the changes on GitHub after a minute.

Following the steps in the above paragraph are what you do when you are submitting to the main branch. If you have multiple people working on a topic at once or you want to split the project in two to test a direction then you will branch the repository. These branches can be merged later on. If the part that was edited on one branch has not been changed on the main branch then everything will work fine, but if the main branch has been updated since then there will be a merge conflict. Here someone needs to go through and decide which parts to keep, or what edits need to be made to get it to work. This is a pain and we will try to avoid this, should be easy enough with three people. To make a branch go to the bottom left and click "main" and select new branch. It will say which branch you are committing to in the bottom left. If you do not feel comfortable with branches then just work with main and we will deal with it later.

Suppose someone else has updated the repository and your local version is now out of date. To update this you need to go to the source control tab and click the three dots in the top right of the source control window. Click "pull", and this will take the current version on GitHib and use it to update your local area. If you have uncommitted changes then it will complain as it does not know what to do with them. To solve this you can commit to a new branch and then merge the branch with the most recent version. Then you can go back to the branch you were on, pull to update your local area, and delete the new branch you had just made.

Other notes:
- Fatal error likely means you are not connected to the internet
- This README document is written in markdown. If you do not know what that means then ignore this
- The repository is public. This is not amazingly relevant for us, but make sure you do not upload API keys to GitHub (they may be in caches as well)
- If you cannot access this then it is probably because I have fucked up and not added you as a collaborator properly

Test line