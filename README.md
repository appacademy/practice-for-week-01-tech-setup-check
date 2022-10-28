# Tech Setup Check

This exercise will allow you to confirm that you have all of your tech set up
and ready for week 1. In this exercise, you will:

1. Create a remote repository on GitHub
2. Clone the repository and open it in VS Code
3. Create and save a JavaScript file
4. Stage, commit, and push your changes to the remote repository
5. Confirm that your Git, GitHub, and VS Code workflows are working

_Note: You will not need to use the "Download Project" or "Submit Project"
buttons at the bottom of this page._

## Phase 1: Create a remote repository on GitHub

[Log in to GitHub] and click on the "+" icon in the navigation bar at the top of
the page. Click on "New repository".

Fill out the "Create a new repository" form with the following details:

- Repository name: "tech-setup-check"
- Description: "Checking Git, GitHub, and VS Code workflows"
- Click "Private" so that this practice activity will NOT be visible to the
  public.

Click the green "Create Repository" button to create the new repository.


## Phase 2: Clone the repository and open it in VS Code

Next, open your terminal and navigate to the directory where you keep your
coding projects (for example, `cd aa-projects`).

> If you do not already have a projects directory, you can create one and then
> navigate into it:
>
> `mkdir aa-projects`
>
> `cd aa-projects`

Now, you are ready to clone your repository and start working on it in VSCode.
To clone the repository, you will need to copy the HTTPS link right underneath
"Quick setup" on GitHub, and use that within the `git clone` command you learned
in the GitHub Overview lesson. Type the following command into the terminal,
making sure that `<YOUR-GITHUB-USERNAME>` is replaced with your username from
the HTTPS link that you copied to your clipboard from GitHub:

`git clone https://github.com/<YOUR-GITHUB_USERNAME>/tech-setup-check.git`

This will clone your (currently empty) repository into a new __tech-setup-check__
directory within your __aa-projects__ directory. You may be prompted to enter
your GitHub PAT to complete GitHub authentication.

> _Note: The instructions above assume that you have configured GitHub using a
> PAT. If you are using SSH, then make sure you are copying the SSH link from
> GitHub, and enter your SSH key when prompted. See this resource for [help with
> SSH]._


Open up the project in VS Code using the `code` command with the new
project directory name:

`code tech-setup-check`

## Phase 3: Create and save a JavaScript file

Create a new JavaScript file in the __tech-setup-check__ directory and name it
__tech-setup-check.js__. Make sure you are inside the __tech-setup-check__
directory when you create this file.

`touch tech-setup-check.js`

You should see the new file appear in the left sidebar of VS Code.

Open the file, and add the following contents:

```js
// This is a single-line comment in JavaScript. It starts with //.

/*
This is a
multi-line comment
in JavaScript.
*/

console.log("Hello World!")
// console.log is used to print messages or values to the console.
```

Save your file. You can save in VS Code by using `command-s` (Mac) or
`control-s` (Windows).

Next, check to make sure your Node installation is working. In the terminal, run
your JavaScript file using the command below:

```shell
node tech-setup-check.js
```

If successful, you should see the message inside your `console.log()` function
printed out: "Hello World!".


## Phase 4: Stage, commit, and push your changes to the remote repository

Now that you have completed this exercise, it is time to stage, commit, and push
the updates to the remote repository on GitHub. Use the following commands in
your terminal:

`git status`

Make sure that only the file you want to add is listed.  You can easily get into
trouble by accidentally committing something you didn't intend to if you don't
always check first!

`git add .` ...to stage the changes

`git commit -m "completed tech-setup-check practice"` ...to commit the changes

`git push origin main` ...to push the changes up to the remote repository

Enter your PAT or SSH if prompted.

## Phase 5: Confirm that your Git, GitHub, and VS Code workflows are working

Check the `<Code>` tab on the repository page in GitHub, and you should see your
JavaScript file, as well as you commit message "completed tech-setup-check
practice". You may need to refresh the page to see the file and message.

Now click on your GitHub profile, and you should start to see your commits show
up as green boxes in your "green garden" grid.

__If you can see your file, commit message, and green square on your profile:__

  - Congratulations! Your tech is set up properly and is ready to go for week 1.
    Send your instructor a quick message that says "Tech setup success!!!"

__If you got stuck in any of the phases above:__

  - Your instructors are here to help! Raise your hand in Progress Tracker to
    let them know that you were not able to complete the tech setup check. Be
    ready to share this information:
    - Your operating system (Windows or Mac)
    - Which phase you got stuck at (1-5)
    - Any details you have about what didn't work (error messages, etc)

## What you've learned

In this exercise, you set up a remote repository on GitHub and cloned a project
to your local machine. You created and saved a JavaScript file, and then staged,
committed, and pushed the changes to the remote repository on GitHub.

If you were able to complete this workflow successfully, you're ready for the
week! If not, communicate with your instructors to make sure your tech is setup
properly so you can hit the ground running in the first week.

[Log in to GitHub]: https://github.com/login
[help with SSH]: https://hackmd.io/@AgDXdHgSSPKsJIhCxlaTuA/BJtNu88fF