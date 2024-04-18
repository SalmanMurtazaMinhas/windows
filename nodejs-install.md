# Installing Node.js on Windows
![image](https://portswigger.net/cms/images/70/79/895d-article-200624-nodejs-body-text.png)

Node.js is a popular JavaScript runtime environment that allows developers to execute JavaScript code server-side. Installing Node.js on Windows is a straightforward process. This guide will walk you through the steps to install Node.js on your Windows operating system.

## Step 1: Download Node.js Installer

1. Open your web browser and navigate to the official Node.js website at [https://nodejs.org](https://nodejs.org).
2. On the homepage click download in the navbar and it'll take you to the download page, you will see two versions available for download: LTS (Long-Term Support) and Current. For most users, it's recommended to download the LTS version as it provides stability and long-term support. Click on the "Download Node.js".
![image](https://github.com/SalmanMurtazaMinhas/windows/assets/139884020/9d1f301a-a28b-4dc2-8786-f0b1a59a157c)


## Step 2: Run the Installer

1. Once the installer file is downloaded, locate it in your downloads folder or wherever you saved it.
2. Double-click on the installer file to start the installation process.
3. You may see a User Account Control prompt asking for permission to make changes to your system. Click "Yes" to proceed.
4. The Node.js Setup Wizard will open. Click "Next" to begin the installation process.
5. Read and accept the terms in the License Agreement, then click "Next."
6. Choose the destination folder where you want to install Node.js, or leave the default setting, and click "Next."
7. Select the components you want to install. It's recommended to keep the default components selected, which include Node.js runtime, npm package manager, and Add to PATH. Then, click "Next."
8. Choose any additional tasks you want the installer to perform, such as automatically installing necessary tools or creating desktop shortcuts. Once selected, click "Next."
9. Finally, click "Install" to begin the installation process.

## Step 3: Verify the Installation

1. Once the installation is complete, you will see a "Completed" message in the installer window. Click "Finish" to exit the installer.
2. To verify that Node.js and npm (Node Package Manager) have been successfully installed, open a command prompt.
3. Type the following commands and press Enter after each to check the installed versions:

```bash
node -v
npm -v
```

If Node.js and npm are installed correctly, you will see their respective version numbers printed in the command prompt.

Congratulations! You have successfully installed Node.js on your Windows operating system. You are now ready to start developing applications using Node.js.
