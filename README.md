# Madlibs Activity
For this activity, you will use what you've learned about git to work collaboratively as a classroom to fill out a couple Madlibs stories.

## How To Setup This Activity

1) Join a breakout group. One person will work on the code and the others
   will help them now screw it up. 😜

2) Accept the Github Classroom invite from the teacher. One the one person
   who will be coding needs to do this. Its not a problem if you all do it.

3) The person coding should log into Cloud9. You can find the login information
   in your class dashboard.

4) Clone the repo created by GitHub Classroom.

5) Open the `index.html` file to see the app working on your computer.

5) Create new stories, verbs, nouns, adjectives, and adverbs! Or, just one of them---whatever you want. Checkout a new branch with a good name before you do your work. This will be a command like
    ```
    git checkout -b kyle-new-verbs
    ```
    Here, I named my branch "kyle-new-verbs". You should name yours something different, no spaces.

6) Take a look around at the files. Familiarize yourself where everything lives. 

7) Create a new file. You can also edit existing files, but that will make our merging harder! If you want to make a new file of verbs, you might make a file at
`/js/verbs/my-new-file.js` and in that file, add new verbs.

    You should choose a name other than "my-new-file.js". You can use the command `nano` to create and edit files, or use the Cloud9 editor.  You may also use the cloud9 editor, or a local text editor you have installed, like [atom](https://atom.io/) or [vscode](https://code.visualstudio.com/) (my favorite).   

8) Check your code works. Did you break the app? No? Great!

9) Commit your changes and share them

    First, take a look at the status of your work

    ```
    git status
    ```

    It should show what files are new and what files are changed. Now, you want
    to add the new files, try the `git add` command. You'll need to supply a file name.

    Once you've added your changes to the "staging area", you want to make a commit. This
    is a command like

    ```
    git commit -m "Added some verbs for class"
    ```

    Now, push your changes up to GitHub.

    ```
    git push origin BRANCHNAME
    ```

    where `BRANCHNAME` is the name of your branch.

10) Go to GitHub, find your fork and the new branch, then make a pull request

    Pull requests let you tell others about changes you've pushed to a repository on GitHub. Once a pull request is sent, interested parties can review the set of changes, discuss potential modifications, and even push follow-up commits if necessary.

    Click on the logo at right to get started.
    ![Starting the pull request](https://github.com/yale-cpsc-113/CPSC113-madlibs/blob/master/images/pull.png).
    Then, once you get to another page, click the blue link.
    ![Continuing the pull request](https://github.com/yale-cpsc-113/CPSC113-madlibs/blob/master/images/pull2.png)

    Finally, click the create button to checkout the commit.
    ![Finishing the pull request](https://github.com/yale-cpsc-113/CPSC113-madlibs/blob/master/images/pull3.png)
    If you need extra help, check this out [https://help.github.com/articles/using-pull-requests/](https://help.github.com/articles/using-pull-requests/) or just come see a TA.

11) The instructor will merge in everybody's work. 
