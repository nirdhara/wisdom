# Prerequisite

## Git

### macOS

Git comes pre-installed on MacOS, so you don't need to do anything special to get started with version control.

## Node.js (Latest LTS Version)

1. Go to the [Node.js download page](https://nodejs.org/en/download).

2. Download the latest LTS (Long Term Support) version of Node.js that matches your operating system (e.g., Windows, macOS, Linux).

3. Follow the installation instructions for your specific operating system.

## Yarn

1. The preferred way to manage Yarn is by-project and through Corepack, a tool shipped by default with Node.js. Modern releases of Yarn aren't meant to be installed globally, or from npm.

2. To enable Corepack, open your terminal and run the following command:

   ```bash
   corepack enable
   ```

3. After enabling Corepack, you can check the Yarn version by running the following command, and it should be version 3.x:

   ```bash
   yarn --version
   ```