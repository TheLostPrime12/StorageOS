# StorageOS Hugo Fullsstack

This is the production fullstack for StorageOS. 
Any commits / accepted pull requests will be pushed to the Netlify site:
https://storageos.netlify.app

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)

---

### Contributing

Contributions regarding code errors, docs typos, and security policies will be taken into consideration.
They should be submitted as issues or pull requests.
DO NOT commit without making an issue first.

---

### How to Contribute

It aims to simplify and guide the way beginners make their first contribution. If you are looking to make your first contribution, follow the steps below.

**If you don't have git on your machine, [install it](https://docs.github.com/en/get-started/quickstart/set-up-git).**

**1. Fork this repository**

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

**2. Clone the repository**

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

For example:

```
git clone https://github.com/this-is-you/StorageOS.git
```

where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

**3. Create a branch**

Change to the repository directory on your computer (if you are not already there or if it is required):

```
cd StorageOS
```

Now create a branch using the `git switch` command:

```
git switch -c your-new-branch-name
```

**4. Make necessary changes and commit those changes**

Add those changes to the branch you just created using the `git add` command:

```
git add .
```
Now commit those changes using the `git commit` command:

```
git commit -m "Describe"
```

replacing `Describe` with what you have added or changed.

**5. Push changes to GitHub**

Push your changes using the command `git push`:

```
git push -u origin your-branch-name
```

replacing `your-branch-name` with the name of the branch you created earlier.

**6. Submit your changes for review**

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

Now submit the pull request.

Soon I'll be merging all your changes into the main branch of this project. You will get a notification email once the changes have been merged.

---

### License

This project is licensed under the **MIT license**.


