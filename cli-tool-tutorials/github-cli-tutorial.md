[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[<img align="right" width="150" src="https://firstcontributions.github.io/assets/gui-tool-tutorials/github-desktop-tutorial/join-slack-team.png">](https://join.slack.com/t/firstcontributors/shared_invite/enQtNjkxNzQwNzA2MTMwLTVhMWJjNjg2ODRlNWZhNjIzYjgwNDIyZWYwZjhjYTQ4OTBjMWM0MmFhZDUxNzBiYzczMGNiYzcxNjkzZDZlMDM)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Open Source Helpers](https://www.codetriage.com/roshanjossey/first-contributions/badges/users.svg)](https://www.codetriage.com/roshanjossey/first-contributions)


# First Contributions

| <img alt="GitHub Desktop" src="https://cdn.icon-icons.com/icons2/2157/PNG/512/github_git_hub_logo_icon_132878.png" width="200"> | GitHub Command Line Interface (CLI) |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------|

This is a guide for us the terminal nerds who wants to do everything in the terminal, and thanks to the [Github-CLI](https://cli.github.com/) we can achieve it, remember your first contribution should be fun, rewarding and a motivator just to keep going!

This guide is a bit more challenging since we are not using any graphical interface at all, but still it's really fun and you can totally follow it!

The first requisite is to have:
- Git installed (how to install [git](https://git-scm.com/downloads))
- Github account

Now we need to install the github-cli tool in our system by following the [official documentation](https://github.com/cli/cli#installation)

After that, we need to login in the CLI so enter this command: 
```bash 
gh auth login
```

Follow the instructions and we are ready!

# Fork this repository
It's just as easy as running this command:

```bash
gh repo fork firstcontributions/first-contributions
```
**Important: It will prompt you if you want to clone it as well, select the "yes" option**

# Create your branch
We will do this step with git, so we enter this command replacing the name with your name, for example:
```bash 
git switch -c add-john-doe
```

# Make necessary changes and commit those changes 
Now you can open `Contributors.md` file in a text editor, add your name to it. Put your name anywhere between the beginning and the end, now save the file.

In the project directory execute `git status` and you will see the changes.
![image-git](https://camo.githubusercontent.com/a35c4722d7aab337eefc655d1488f7b4dc038508e6adaf5e88e2e052a976f010/68747470733a2f2f6669727374636f6e747269627574696f6e732e6769746875622e696f2f6173736574732f526561646d652f6769742d7374617475732e706e67)

Add those changes to the branch you just created using the `git add` command:
`git add Contributors.md`

Now commit those changes using the `git commit` command:
`git commit -m "Add your-name to Contributors list`
replacing `your-name` with your name.

# Push changes to github 
Push your changes using the command `git push`:

```
git push origin -u your-branch-name
```

replacing `your-branch-name` with the name of the branch you created earlier.

<details>
<summary> <strong>If you get any errors while pushing, click here:</strong> </summary>

- ### Authentication Error
     <pre>remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.
  remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.
  fatal: Authentication failed for 'https://github.com/<your-username>/first-contributions.git/'</pre>
  Go to [GitHub's tutorial](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account) on generating and configuring an SSH key to your account.

</details>

# Submit your changes for review
Now running this command in our repo's directory will let us create a pull request for review:

```bash 
gh pr create --repo firstcontributions/first-contributions
```

After that submit the pull request.

You can use the command `gh status` to see your mentioned pull request in action.

## Where to go from here?

Congrats! You just completed the standard _fork -> clone -> edit -> pull request_ workflow that you'll often encounter as a contributor!

Celebrate your contribution and share it with your friends and followers by going to [web app](https://firstcontributions.github.io/#social-share).

You could join our slack team if you need any help or have any questions. [Join slack team](https://join.slack.com/t/firstcontributors/shared_invite/zt-vchl8cde-S0KstI_jyCcGEEj7rSTQiA).

Now let's get you started with contributing to other projects. We've compiled a list of projects with easy issues you can get started on. Check out [the list of projects in the web app](https://firstcontributions.github.io/#project-list).

### [Additional material](additional-material/git_workflow_scenarios/additional-material.md)

## Tutorials Using Other Tools

[Back to main page](https://github.com/firstcontributions/first-contributions#tutorials-using-other-tools)
