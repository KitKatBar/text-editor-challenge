# Text Editor Challenge - Cache In Your Words!
  
## Description

The application that I have built this week is a text editor that runs in the browser. The app uses a single-page application that follows the PWA guidelines and criteria. Additionally, it incorporates a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application can also function offline.

I have also implemented methods for getting and storing data to an IndexedDB database. Included is a package called idb, which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla.
        
## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [How to Contribute](#how-to-contribute)
- [Questions](#questions)

        
## Installation

This code has been deployed to Render so that you can view it on your own device. To do so, please visit the following link: https://text-editor-challenge-c0we.onrender.com/

Additionally, you can install this application to your local computer and run it by double clicking on the icon.  Please refer to the following image on how to do so.

![image showing where the install button is](https://github.com/KitKatBar/text-editor-challenge/blob/main/images/text-editor-install.png?raw=true)

Once you have clicked on the 'Install' button, an alert should pop up asking if you want to install this application.  Click on 'Install' to download it and it should be saved on your desktop where you can open it.

![image showing the install alert when the button is clicked](https://github.com/KitKatBar/text-editor-challenge/blob/main/images/text-editor-install-alert.png?raw=true)

## Usage

Please refer to the following image showing the functionality of the application.  When the page is first loaded, you should see a header with an 'Install' button (already covered in the previous section), a header and an icon of the application.  There will also be some pre-filled text in the text editor area.

![image showing the layout of the application in the browser](https://github.com/KitKatBar/text-editor-challenge/blob/main/images/text-editor-browser.png?raw=true)

This image is the desktop version (note that the install button is missing because this is the downloaded version).

![image showing the layout of the application in the desktop version](https://github.com/KitKatBar/text-editor-challenge/blob/main/images/text-editor-desktop.png?raw=true)

Feel free to type anything you want in the text editor.  Everything should be saved to an indexedDB in the browser whenever you make any changes.  As such, reloading the page or closing it and coming back later should load all the text where you previously left off.  This also works if you have downloaded the desktop version.

![image showing some text being typed into the text editor](https://github.com/KitKatBar/text-editor-challenge/blob/main/images/text-editor-type.png?raw=true)

![image showing the indexedDB storing the key and value of the text](https://github.com/KitKatBar/text-editor-challenge/blob/main/images/indexed-db.png?raw=true)

Additionally, the following images shows the application's ```manifest.json``` file being run on the backend along with the application's registered service worker.

![image showing the manifest.json file](https://github.com/KitKatBar/text-editor-challenge/blob/main/images/manifest-json.png?raw=true)

![image showing the service worker](https://github.com/KitKatBar/text-editor-challenge/blob/main/images/service-worker.png?raw=true)
        
## Credits

Render Setup Guide: https://coding-boot-camp.github.io/full-stack/render/render-deployment-guide

Our instructor Drew Hoang for introducing us to Progress Web Applications (PWA) this week. These applications provide many benefits like implementing native mobile device features, can operate offline and can run through multiple platforms from a single codebase (just to name a few).  He provides good metaphors for how to do exercises and also makes speed-run videos that are very insightful for providing information and for reviewing class material.

Our TA Kyle Vance for his continued guidance during class and taking the time to explain new concepts. He continues to provide direction for students and is straight to the point in his explainations.

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
This project was built using the MIT License. Please refer to the LICENSE in the repo for more information.
          
## How to Contribute

You can contribute to this project by providing suggestions or helping implement some additional functionalities to improve the text editor!

## Questions

This project was created by KitKatBar.
    
Click on [this link](https://github.com/KitKatBar) to see more of my other works!

Have additional questions about this project?  You can reach out to me with any inquiries at: katriel_chiu@msn.com