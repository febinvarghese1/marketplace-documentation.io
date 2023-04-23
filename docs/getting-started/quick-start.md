---
layout: default
title: Quick Start
parent: Getting Started
nav_order: 1
---

# **Quick Start**

### You can build Sparrow apps that will automate most of your development tasks by using the following steps.

#### 1. [Initial Requirements](#inital-requirements)

#### 2. [Install Sparrow CLI](#install-the-sparrow-cli)
#### 3. [Develop an App](#develop-an-app)
#### 4. [Test the App]()
#### 5. [Validate and Pack]()

---

## **Inital requirements**

### &emsp; **Install NVM**:

&emsp;&emsp; NVM (Node Version Manager) is a tool that allows you to easily manage multiple versions of Node.js on your system. Here are the steps to install NVM
 
 - On a Mac or Linux, follow the installation instructions provided on the NVM GitHub page.

- On Windows, download the nvm-setup.zip file from the NVM release channel, extract the files, and run the installer.

- To verify that NVM is installed correctly, open a terminal window and run the following commands

```bash 
nvm --version
```

### &emsp; **Install Node:**

- To install Node.js, follow the given steps.

```bash 
nvm install 18
```

- To verify that the node is installed correctly, run the following commands

```bash 
node –version
```

## **Install the sparrow CLI**

- To install the latest CLI version, run the following command.

```bash
npm install https://cdn.sparrow.io/ssdk/latest.tgz -g
```
- Run the following command to verify the CLI installation.

 ```bash
 ssdk version
 ```
 
## **Develop an App:**

&emsp; You can use the following steps to create an app that displays a sample text in the ‘app & integration’ section of setting page.

- From the command line, navigate to the empty directory in which you want to create an app.

- Run the following command:
```bash
 ssdk create
```
- Select your_first_app. A new app is created based on the your_first_app template.