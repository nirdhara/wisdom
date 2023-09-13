# Setting Up

## Prerequisites

Before you begin, ensure that you have the following software installed on your system:

1. [Git](https://git-scm.com/downloads)
2. [Node.js](https://nodejs.org/) (version 18.x)
3. [Yarn](https://yarnpkg.com/) (version 3.x)

Please check the instructions to install prerequisites [here](https://github.com/nirdhara/wisdom/blob/main/technology/prerequisite.md).

## Clone the Repository

1. Open your terminal(Command prompt).
2. Navigate to the directory where you want to create your project or choose an existing directory.
3. Clone the repository by running the following command:

   ```bash
   git clone https://github.com/nirdhara/nirdhara
   ```

   This will create a folder named "nirdhara" with the project files.

4. Change your working directory to the newly created "nirdhara" folder:

   ```bash
   cd nirdhara
   ```

## Install Dependencies

1. Once you're inside the "nirdhara" folder, install project dependencies using Yarn. Yarn will read the `package.json` files from the workspace and download the necessary packages:

   ```bash
   yarn
   ```

   This will install all the project dependencies specified in all the `package.json` files present in the workspace.

## Start the Composer API (Development Mode)

1. To run the Composer API in development mode, navigate to the "composer-api" folder:

   ```bash
   cd apps/composer-api
   ```

2. Start the Composer API:

   ```bash
   yarn start
   ```

   This will launch the Composer API in development mode.

## Start the Composer UI (Development Mode)

1. Open a new terminal tab or window to keep the Composer API running.

2. Navigate to the "composer-ui" folder from the root project directory:

   ```bash
   cd apps/composer-ui
   ```

3. Start the Composer UI in development mode:

   ```bash
   yarn dev
   ```

   This will launch the Composer UI in development mode in a separate tab or window.

---

You have now successfully set up and started the Node.js project with Composer API and UI in development mode. You can access the Composer UI in your web browser. Make sure to keep the Composer API running in one terminal tab while working on the Composer UI in another tab.