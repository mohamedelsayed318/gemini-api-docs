# Project Setup Guide

This guide will help you set up the project on your local machine.

## Prerequisites

- Ensure you have **Node.js** installed on your machine.

## Steps

### 1. Download Node.js

Download and install Node.js from the official website: [Node.js](https://nodejs.org/).

### 2. Verify Node.js Installation

Open your terminal or command prompt and run the following commands to verify that Node.js and npm (Node Package Manager) are installed correctly:

```sh
node -v
npm -v
```
You should see the version numbers of Node.js and npm printed on the terminal like this: 
![image](https://github.com/user-attachments/assets/b329becd-730d-4e63-875d-3fb9af2eb9b0)


### 3. Install Project Packages
Navigate to the project directory and install the required packages by running:
npm install

### 4. Update API Key
Locate the configuration file (e.g., .env, config.js, or similar) and replace the placeholder API key with your own API key. For example:

![code-snapshot](https://github.com/user-attachments/assets/085bbb68-a55a-425e-8543-3e49b8f2fb7f)

### 5. make sure you put the products.xlsx in the folder in main root like this:
![image](https://github.com/user-attachments/assets/d4c824be-9806-4205-b3fd-69bca21ea3bc)


### 6. Run the Project
To start the project in development mode, run the following command:
```
npm run dev
```
### 7. After finish you should have output.xlsx like this:
![image](https://github.com/user-attachments/assets/49e67515-3bd9-49ed-8aec-bb3e2a51ee60)



you can modify the code base on your excel file like this:
<br /> 
![code-snapshot2](https://github.com/user-attachments/assets/35bf0e1d-cc7e-4661-b10b-bce542e2bfa4)

here i use the last file that have the "product_name" and "prompt" only if you need to send to the ai the product name, Description and prompt just uncomment the first line by remove the "//" and comment the second line by add the "//" in the first of the line 

### Don't Forget to save the file after make any change by using "ctrl + s"





