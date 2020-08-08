## FAQs 
#### What is Hacktoberfest?
Hacktoberfest is a monthlong celebration of open source software run by DigitalOcean.

#### Hacktoberfest is open to everyone in our global community!
Four quality pull requests must be submitted to public GitHub repositories.
You can sign up anytime between October 1 and October 31.
What is open source?
Open source refers to source code that is publicly accessible and allows anyone to inspect, modify or learn from it. Open source projects encourage collaboration and the freedom to use the software for any purpose you wish.

#### What is a pull request?
Pull requests are proposed code changes you can submit to a branch in a repository on GitHub. Once submitted, a project maintainer will review and discuss the changes before they become final.

#### How do I get started?
Enter your email above to receive updates on this year’s program.

#### Do I get a prize for participating?
Aside from the knowledge you’ll gain (and the fun you’ll have), you’ll also receive a limited edition Hacktoberfest T-shirt for submitting 4 valid pull requests.


## What to Do
<img align="right" width="300" src="assets/fork.png" alt="fork this repository" />

If you don't have git on your machine, [install it]( https://help.github.com/articles/set-up-git/).

#### Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

#### Clone the repository

<img align="right" width="300" src="assets/clone.png" alt="clone this repository" />

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the clone button and then click the *copy to clipboard* icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```
where "url-you-just-copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<img align="right" width="300" src="assets/copy-to-clipboard.png" alt="copy URL to clipboard" />

For example:
```
git clone https://github.com/this-is-you/first-contributions.git
```
where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd first-contributions
```
Now create a branch using the `git checkout` command:
```
git checkout -b <add-your-new-branch-name>
```

For example:
```
git checkout -b add-alonzo-church
```
(The name of the branch does not need to have the word *add* in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)

#### Make necessary changes and commit those changes

Now open `Contributors.md` file in a text editor, add your name to it, with your Github profile link. Now, save the file.

<img align="right" width="450" src="assets/git-status.png" alt="git status" />


If you go to the project directory and execute the command `git status`, you'll see there are changes.


Add those changes to the branch you just created using the `git add` command:

```
git add Contributors.md
```

Now commit those changes using the `git commit` command:
```
git commit -m "Add <your-name> to Contributors list"
```
replacing `<your-name>` with your name.

#### Push changes to GitHub

Push your changes using the command `git push`:
```
git push origin <add-your-branch-name>
```
replacing `<add-your-branch-name>` with the name of the branch you created earlier.

#### Submit your changes for review

If you go to your repository on GitHub, you'll see a  `Compare & pull request` button. Click on that button.

<img style="float: right;" src="assets/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="assets/submit-pull-request.png" alt="submit pull request" />

Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.
