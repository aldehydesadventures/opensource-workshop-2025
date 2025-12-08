# <img src="Images and vids\wrench.gif" alt="Alt text" width="22 " height="22"> Setting up Git

Cool, now that you've installed Git let's move on to setting it up for use.

First we'll get ourselves acquainted with some common terms used in Git.

## <img src="Images and vids\folder.gif" alt="Alt text" width="18 " height="18"> Repository

A repository (repo) is a centralized storage space where a project’s files, folders, and complete version history are kept. It acts as the main workspace for a project, allowing you to track changes, collaborate with others, and manage different versions of the code. Repositories can exist locally on your computer or remotely on platforms like GitHub. In easier words, its basically the main folder of your project.

Now they can be tracked or not tracked by Git.

Let's first create one in which we'll be testing all the commands which we'll learn in this workshop.

1. Go to any preferred location in your ``File Explorer``.

2. Create a folder giving it a name of your choice.

3. Open VS Code, then click on ``File`` (Top left corner) and open the folder which you just created. This folder will act as your repository.

## <img src="Images and vids\buffering.png" alt="Alt text" width="18 " height="18"> Status

To check which files are tracked in your repo, ``git status`` command is used.

1. Run GitBash.

2. Write ``pwd`` in the terminal and press *Enter*. It'll show the current working location.

3. If the location is not of the folder which you created then:

    * Go to the location of your folder and right click on it.

    * Press ``CTRL + Shift + C`` to copy the path of the folder.

    * Return to GitBash terminal and type ``cd '...'`` where ... represents the copied location. **(Be mindful to give the ' ')**

4. Run the command ``git status``. It'll show an error based output as Git has not been initialised in your directory yet.

That brings us to the initialisation of our directory in Git.

## <img src="Images and vids\start-button.png" alt="Alt text" width="18 " height="18"> Initialisation

The main repository which we want to track using Git must be initialised at first. It is analogous to importing packages to use them during programming.

1. Run ``pwd`` once again to make sure our current directory is our folder.

2. If it is then type ``git init`` and press *Enter*.

    It'll show an output saying ``Initialized empty Git repository in ...``.

3. Now again type ``git status`` and press *Enter*. It'll show us our branch and if there is anything to commit yet (you'll learn about commits in the next part).

## <img src="Images and vids\greentick.png" alt="Alt text" width="18" height="18"> Configuration

Remember the GitHub account which you made earlier? Now we're going to add those credentials to Git so that it knows that you're the one making changes and later display to other developers that those changes were made by you.

1. In your GitBash terminal, type ``git config --global user.email "your-email@example.com"`` and press *Enter* (It is preferable to use the email-id used in GitHub).

2. Also type ``git config --global user.name "Your Name"`` and press *Enter* (you can use your username or your actual name).

Again **be mindful about " " in the commands**.



***Congratulations!!!*** After all of these, you're ready to start using Git.
