<p align="center">
    <a href="https://dsc-iem.github.io/">
        <img height=185 src="assets/images/banner.jpg">
    </a>
</p>

# DSC IEM DEVELOPERS

- A repository on flutter application development for members to contribute and prepare for upcoming Hacktoberfest 2020. This application is available in dark mode too.
- In this repository each contributor will be adding their peice of information(an about kinda section) and get hands on experience with creating PRs.

---

# Table of Contents

1. [Softwares Required](#Softwares-Required)
2. [Start Contributing](#Start-Contributing)
3. [Screenshots](#Screenshots)

***

## Softwares-Required:

1.  Flutter Sdk
2.  Android Studio/VS Code

Visit [here](https://flutter.dev/) to know how to install the mentioned requirements. It is flutter team's official docs over the installation. Also, you can check [here](https://github.com/imKashyap/VSCode4Flutter) for more info.

---

## Start-Contributing:

### Step 1: Fork this repository

- A fork would place a copy of this project in your GitHub Account

![Fork](Screenshots/Fork.png "Fork the repo")

### Step 2: Clone the repository

- Cloning the repository will place a local copy of project on your own machine
- Copy the URL from the copy to clipboard icon

  ![Copy To Clipboard](Screenshots/Click-Copy-Icon.png)
- Open a terminal and run the following git command :

`git clone https://github.com/<your-user-name>/AppDev-Hacktoberfest.git`

### Step 3: Create a branch

- A branch is a way to keep your changes separate from the main part of the project called `Master`. For example if things go wrong and you are not happy with your changes you can simply delete the branch and the main project won't be affected.

Change to the repository directory on your computer (if you are not already there):

`cd AppDev-Hacktoberfest`

Now create a branch using the `git checkout` command:

`git checkout -b <your-name-profile-card>`

(While the branch name can be anything we suggest you to keep it the way we mentioned.)

### Step 4: Make necessary changes and commit

1. Open the project in _Android Studio_ or
   _VS Code_. Make sure you are not on _master_ branch.

2. Look for `assets/profiles` folder and drop your profile picture over there. It would be better if you can keep the name of your image file as
   yourname.fileformat

3. Look for `lib/data/all_members.dart`. Make a copy of the form as the one created below. Comments are added over there to help you get it done. Make use of and modify the file with your details.

| Parameters  | Info                                         |
| ----------- | -------------------------------------------- |
| name        | Your Full name                               |
| year        | Your college year                            |
| department  | Your Stream of graduation                    |
| profilePath | The path where you stored your profile photo |
| aboutMe     | A brief description about yourself           |
| fbUrl       | Your Facebook account url                    |
| githubUrl   | Your Github account url                      |
| linkedInUrl | Your LinkedIn account url                    |
| status      | A 2-3 words current status                   |

---

![Card-Template](Screenshots/Card-Template.png)

4. Copy the exact portion of a member object given in the screenshot and paste it. Maintain a gap of 2-3 lines between the profile cards. Indentation should be kept in mind.

5. Check whether your profile has been successfully added in the application or not. Connect your android device and run the application.
   You must have USB Debugging enabled on your phone. Make sure your info is visible under _members_ table.

6. Modify the profile card with your information. If you execute the command `git status`, you'll see there are changes.

7. Add those changes to the branch you just created using the `git add` command:

`git add .`

Now commit those changes using the `git commit` command:

`git commit -m "<your-name> Profile Card Added"`

### Step 5: Push Changes

Push your changes using the command `git push origin <your-branch-name>`

### Step 6: Make a Pull Request

Go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on it.

![Compare & Pull Request](Screenshots/Compare-Pull-Request.png)

Now submit the pull request

![Pull Request](Screenshots/Pull-Request.png)

Congrats! You have made your first contribution!

---

## Screenshots:

| Welcome Screen                                                 | Members Overview Screen                                                 | Member Detail Screen                                                 |
| -------------------------------------------------------------- | ----------------------------------------------------------------------- | -------------------------------------------------------------------- |
| <img src="Screenshots/ss1.png" width=200 alt="Welcome Screen"> | <img src="Screenshots/ss3.png" width=200 alt="Members Overview Screen"> | <img src="Screenshots/ss2.png" width=200 alt="Member Detail Screen"> |
