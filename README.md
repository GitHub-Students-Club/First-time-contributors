### First-time-contributors

If you don't have git in your machine, download it from [here](https://git-scm.com/downloads). 

Follow the steps to make your first contribution. 

### Fork this repository 
Creating a fork is producing a personal copy of someone else's project. 

Forks act as a sort of bridge between the original repository and your personal copy. 

Fork this repository by clicking the fork button on top of this page. 

<img alt="PIC" src="fork_button.jpg" width="600"/> <br>

### Clone the repository 

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

For example:

```
git clone https://github.com/GitHub-Students-Club/First-time-contributors.git
```

where `GitHub-Students-Club` should be replaced with your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

### Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd first-time-contributors
```

Now create a branch using the `git checkout` command:

```
git checkout -b your-new-branch-name
```

For example:

```
git checkout -b add-alonzo-church
```

(The name of the branch does not need to have the word _add_ in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)


### Make necessary changes and commit those changes

Now open `Contributors.md` file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file. Also choose your favourite language folder and add a program that prints `Hello my name is John.` and save it.  

If you go to the project directory on your cli and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```
git add .
```

Now commit those changes using the `git commit` command:

```
git commit -m "Added <your-name> to Contributors list"
```

replacing `<your-name>` with your name.

### Push changes to GitHub

Push your changes using the command `git push`:

```
git push origin <add-your-branch-name>
```

replacing `<add-your-branch-name>` with the name of the branch you created earlier.

### Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

Now submit the pull request.

Soon the maintainers be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.

### Where to go from here?

Congrats! You just completed the standard _fork -> clone -> edit -> pull request_ workflow that you'll encounter often as a contributor!

Celebrate your contribution and share it with your friends and followers and explore your horizons and persue your interests. 













