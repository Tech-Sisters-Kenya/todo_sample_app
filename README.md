# Todo Sample App

Welcome to the **Todo Sample App**! This is a simple application designed with **HTML**, **JavaScript**, and **HTTP (using a lightweight server)**. It serves as a **playground to help beginners and contributors** learn how to collaborate on GitHub effectively for Open Source.

In this guide, we'll walk you through everything from cloning the repo to making a pull request. Think of this as a "for beginners" guide—step by step

---

## What You'll Learn:
- Setting up the project on your local machine.
- Understanding GitHub remotes and branches.
- How to contribute to the project by making pull requests.
- Using this app as a sandbox to practice collaboration skills.

---

## 1. **Getting Started: Cloning and Setting Up Remotes**

First things first, let’s get this project onto your computer. Here’s how:

### Step 1: Fork the Repository
1. Navigate to the [Tech Sisters' Todo Sample App Repo](https://github.com/Tech-Sisters-Kenya/todo_sample_app).
2. Click on the **Fork** button at the top-right corner of the page. This creates your own copy of the project under your GitHub account.

### Step 2: Clone Your Fork
1. Find a directory to fork the repo in your local
2. Assuming your GitHub username is `sistech`:

 Open your terminal and run the following:

   ```bash
   git clone https://github.com/sistech/todo_sample_app

  ```
### Step 3: Set Up Remotes
- Add the original repository (Tech Sisters Kenya) as an upstream remote:

``` bash
git remote add upstream https://github.com/Tech-Sisters-Kenya/todo_sample_app
```
- Check your remotes to ensure they’re set correctly:

``` bash
git remote -v
``` 
- You should see something like:

``` bash
origin   https://github.com/sistech/todo_sample_app.git (fetch)
origin   https://github.com/sistech/todo_sample_app.git (push)
upstream https://github.com/Tech-Sisters-Kenya/todo_sample_app.git (fetch)
upstream https://github.com/Tech-Sisters-Kenya/todo_sample_app.git (push)
``` 
## 2. Essentials for Working with Branches
### Step 1: Always Pull Latest Changes
Before starting any new task, ensure your local main branch is up-to-date:

``` bash
git pull upstream main
```

### Step 2: Create a Feature Branch
Never work directly on the main branch. Instead, create a new branch for every feature or task:don't worry about having many  branches you can aways delete these later.

``` bash
git checkout -b feature/your-feature-name
```
### Step 3: Commit Your Changes
Once you've made changes, save your work:

```bash
git add .
git commit -m "Brief description of the changes"
``` 
### Step 4: Push Your Branch to Your Fork
Send your feature branch to GitHub:

``` bash
git push origin feature/your-feature-name
```

### Step 5: Make a Pull Request
Go to your forked repository on GitHub.
You’ll see a prompt to "Compare & pull request." Click it.
Provide a clear title and description of your changes.
Submit the pull request for review.

## 3. Using Rebase to Keep a Clean History
Before opening a pull request, it’s a good idea to rebase your branch on top of the latest main:

``` bash

git pull --rebase upstream main
``` 
## 4. Running the App Locally
Before you can run the app, make sure you’ve installed Node.js. Here's how:

Installing Node.js
Download Node.js:
Head over to the [Node.js official site](https://nodejs.org/en) for steps on how to install node in your PC

Install Node.js:
Run the installer and follow the prompts. This will install both Node.js and npm (Node Package Manager).

Verify Installation:
Open your terminal and run:

```bash
node -v
npm -v
``` 
You should see version numbers if everything is installed correctly.

## 5. Running the App
After cloning and setting everything up:

Install the dependencies:
``` bash
npm install
```
Start the HTTP server:

``` bash
npx http-server
```
Open your browser and visit http://localhost:8080 to see the app in action!

## 6. Contributing to the Project
We encourage you to contribute! Here’s a simple checklist to guide you:

- Fork the repo.
- Clone it to your machine.
- Set up remotes.
- Create a new branch for your feature.
- Make your changes and commit them.
- Push your branch and open a pull request.

Need help? Don't hesitate to reach out on our [Issues Page](https://github.com/Tech-Sisters-Kenya/todo_sample_app/issues).

## 7. Next Steps
Use this app as your GitHub sandbox:

- Practice making commits.
- Experiment with branches.
- Get comfortable submitting pull requests.


We’re excited to see your contributions! Happy coding! 🚀

