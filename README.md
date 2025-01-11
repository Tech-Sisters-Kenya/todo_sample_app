# todo_sample_app

This is a simple todo app

This project is in html, js and http as the server

## How to clone and set your remotes properly

Learn more abote github remotes [here]()

Assuming your github username is `sistech` here are the steps to set proper remotes:

1. Fork the repository. Then locally on your terminal do the following:
2. Clone it : git clone https://github.com/sistech/todo_sample_app then navigate to the sample app folder `$ cd todo_sample_app`
3. Add the Tech sister repo as your upstream reomte -- `$ git remote add upstream https://github.com/Tech-Sisters-Kenya/todo_sample_app`

## Essentials when branching and syncing branches

- When working on a new task always work on a feature branch
- Always pull from upsream main `git pull upstream main`
- Use interactive rebase on your feature branch
- Push your feature branch to yor fork and make a pull request form there.

https://github.com/Tech-Sisters-Kenya/todo_sample_app

## Installation Steps

Before running the app locally, you need to have Node.js installed.

### How to Install Node.js

Download Node.js: Go to the [Node.js download page](https://nodejs.org/en), and download the latest stable version for Windows.

Install Node.js: Run the installer and follow the prompts. It will install both Node.js and npm (Node Package Manager).

Verify Installation: After installation, open your terminal (Command Prompt or PowerShell) and verify the installation by running: `node -v` and `npm -v`

## To run this app locally after cloning do

1. Install dependencies: `$ npm install`

2. Start the HTTP server: `$ npx http-server`

3. You should be able to view the app on http://127.0.0.1:8080 or localhost:8080 from your browser

## MIT License

MIT License

Copyright (c) 2025 Tech Sisters Kenya

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
