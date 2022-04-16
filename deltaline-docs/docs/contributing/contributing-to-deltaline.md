---
title: Contributing to Deltaline
sidebar_position: 3
---

Welcome ! Feel free to contribute to Deltaline if you want. We are usually very lenient and relaxed with the submissions of PRs, and Issues reports. But there are some stuff that you need to know before contributing.

## Dependencies

To get started, make sure you have these things installed:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) (Comes bundled with Node.js)
- [NVM (Node Version Manager)](https://github.com/nvm-sh/nvm) (Optional. but highly recommended. If working on Windows, install NVM-Windows instead)
- An IDE like VS Code or WebStorm

## Installation

### Windows 

1. Fork the repo, and then clone it
    
    ```sh
    git clone https://github.com/[username]/Deltaline.git && cd nextjs-deltaline
    ```

2. Install all dependencies

    ```sh
    npm install
    ```

3. To run the dev server, just run the command below:

    ```sh
    npm run dev
    ```

### MacOS

1. Fork the repo, and then clone it
    
    ```sh
    git clone https://github.com/[username]/Deltaline.git && cd nextjs-deltaline
    ```

2. Install all dependencies

    ```sh
    npm install
    ```

3. To run the dev server, just run the command below:

    ```sh
    npm run dev
    ```

### Ubuntu

1. Set up nvm. This is optional, but highly recommended

2. Install any dependencies that you may need

    ```sh
    sudo apt-get install git
    ```

3. Fork the repo, and then clone it
    
    ```sh
    git clone https://github.com/[username]/Deltaline.git && cd nextjs-deltaline
    ```

4. Install all dependencies

    ```sh
    npm install
    ```

5. To run the dev server, just run the command below:

    ```sh
    npm run dev
    ```

### Fedora

1. Set up nvm. This is optional, but highly recommended

2. Install any dependencies that you may need

    ```sh
    sudo dnf install git
    ```

3. Fork the repo, and then clone it
    
    ```sh
    git clone https://github.com/[username]/Deltaline.git && cd nextjs-deltaline
    ```

4. Install all dependencies

    ```sh
    npm install
    ```

5. To run the dev server, just run the command below:

    ```sh
    npm run dev
    ```

### OpenSUSE

1. Set up nvm. This is optional, but highly recommended

2. Install any dependencies that you may need

    ```sh
    sudo zypper install git
    ```

3. Fork the repo, and then clone it
    
    ```sh
    git clone https://github.com/[username]/Deltaline.git && cd nextjs-deltaline
    ```

4. Install all dependencies

    ```sh
    npm install
    ```

5. To run the dev server, just run the command below:

    ```sh
    npm run dev
    ```

## Style Guidelines

Before you commit, there is a pre-commit hook that runs. This will format all of the code using Prettier. This is done automatically before each commit, so there is no need to pull the latest changes automatically. Linting is done on Codacy, so make sure to watch that to make sure that you aren't breaking any linting rules. By default, Next.js uses ESLint, so you can also lint your code locally by running `npm run lint`.

## Git Commit Guidelines

- When making changes to other files like README.md or the contributing.md, make sure to use `[skip ci]` to prevent the CI servers from running
