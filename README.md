# HabitMinder: Open Source Habit Tracking App :iphone:

This is a habit tracking app that allows users to login/sign up using Firebase Authentication and keep track of their habits using Firestore, a cloud database. Users can add new habits, mark them as complete or incomplete, and track their progress over time.

# Design Mockups

<table>
    <tr> <td align="center" colspan=2>Phone Mockup</td></tr>
    <tr>
        <td align="center" colspan=2><img src="https://github.com/ashgozli/HabitMinder/blob/main/assets/Group%201%20(1).png" width="600px;" alt="Image 1"/></td>
    </tr>
    <tr> 
        <td align="center">Overview Page</td>
        <td align="center">Habit Hub</td>
    </tr>
    <tr>
        <td align="center"><img src="https://github.com/ashgozli/HabitMinder/blob/main/assets/IMG_5603%20(2).png" width="300px;" alt="Image 1"/></td>
        <td align="center"><img src="https://github.com/ashgozli/HabitMinder/blob/main/assets/IMG_5932%20(1).png" width="300px;" alt="Image 1"/></td>
    </tr>
    <tr> 
        <td align="center">Add Habits</td>
        <td align="center">Profile</td>
    </tr>
    <tr>
        <td align="center"><img src="https://github.com/ashgozli/HabitMinder/blob/main/assets/IMG_5933%20(2).png" width="300px;" alt="Image 1"/></td>
        <td align="center"><img src="https://github.com/ashgozli/HabitMinder/blob/main/assets/IMG_5973.png" width="300px;" alt="Image 1"/></td>
    </tr>
</table>
    
# About the Project  

This project has been developed for educational purposes and is intended to be used as part of the Project Workshop for the Google Developer's Student Club at the University of British Columbia, Vancouver. To fully leverage the potential of this repository, we recommend referring to the Branches section and reviewing the branches in a sequential order to gain a comprehensive understanding of the app development process.

# Features :sparkles:

- User authentication with Firebase Authentication
- Add, update, and delete habits
- Mark habits as complete or incomplete
- View a calendar to track habit completion over time


# Getting Started 💻

## 0. Install Node Version: 16.13.2:

### **Windows:**

1. Install NVM for Windows by downloading the installer (setup.exe) from the following link:

**[https://github.com/coreybutler/nvm-windows/releases/latest](https://github.com/coreybutler/nvm-windows/releases/latest)**

2. Run the installer and follow the prompts to install NVM on your system.

3. Open a new Command Prompt window or restart the current one to load the new environment variables.

4. Verify that NVM is installed correctly by running the following command:

```
node -v
```

5. This should display the version number of NVM installed on your system.

```
nvm --version
```

5. Install Node.js version 16.13.2 by running the following command:

```
nvm install 16.13.2
```

This will download and install Node.js version 16.13.2 on your system.

### **macOS:**

1. Open a Terminal window.
2. Install NVM by running the following command:

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```

1. Follow the prompts to complete the installation. Note that you may need to restart your terminal session or run the **`source ~/.bash_profile`** command for the installation to take effect.

2. Install Node.js version 16.13.2 by running the following command:

```
nvm install 16.13.2
```

This will download and install Node.js version 16.13.2 on your system.

3. Verify that Node.js version 16.13.2 is installed by running the following command:

```
node -v
```

This should display the version number of Node.js installed on your system.

## 1. Fork or Clone Repository

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY\
```

More information on cloning and forking repositories here:

**https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository**

## 2. Install Dependencies

1. Install the npm node modules folder by running:

```
npm intsall
```

2. Before we start, you'll need to make sure you have the following software installed on your computer:

```
npm install -g expo-cli
```

## 3. Start the app

1. Start the app by writing the following script in your command prompt:

```
expo start
```

2. Download the Expo App from Appstore or Google Store on your mobile device.

3. Scan the QR Code provided in your command prompt to have the app running on your phone.

# Technologies Used

- React Native Libraries
- Firebase Authentication
- Google Cloud Firestore

# Contributing

"If you would like to contribute to this project, please fork the repository and submit a pull request. Bug reports and feature requests are also welcome through the GitHub Issues page" (UBC GDSC Tech Team 22-23)

# License

This project is licensed under the MIT License - see the LICENSE file for details.
