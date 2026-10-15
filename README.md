# byeClicker
A browser extension for Chrome, Brave, Edge, Firefox, and Zen that automatically answers iClicker poll questions for you so that you don't have to worry about attendance anymore.

## Features
- Automatically answers iClicker poll questions for attendance.
- Can join the class automatically and start answering once the instructor starts the session.
- Works in the background; so you can complete any other work peacefully (or sleep 😴).
- Can answer randomly.
- Automatically stops once the instructor ends the session.

## How to use
- Click on the **Auto Join** button and **Start** byeClicker to automatically join the class and start answering.
- **MAKE SURE YOU'VE JOINED THE CLASS IF NOT USING AUTOJOIN!**
- Click on the extension and a popup will open. You'll be able to see a **Start** button and a **Random** checkbox.
- Clicking the **Start** button will start byeClicker.
- If you want byeClicker to choose random answers, check the **Random** checkbox.
- If you want to stop byeClicker from answering, click on the **Stop** button that you'll only see after starting.
- byeClicker will automatically stop once the instructor ends the session.

## How to Install (Chrome/Brave/Edge)
- Download the folder from the download link.
- Open the Extensions page from the browser's menu.
- You'll see an option to turn on Developer mode. Turn it on.
- Click on Load Unpacked.
- Select the downloaded folder.
- Enjoy! 😉

## How to Install (Firefox/Zen)
- Download the folder from the download link.
- From the project folder, create the package with `mkdir -p dist && zip -r dist/byeclicker.xpi manifest.json background.js content.js popup.html popup.js style.css README.md assets`.
- Open `about:debugging#/runtime/this-firefox` in Firefox or Zen.
- Click **Load Temporary Add-on**.
- Select `dist/byeclicker.xpi`. On macOS, loading `manifest.json` directly can grant the browser access to only that file, causing extension pages such as `popup.html` to appear missing.
- Keep the browser open while using the temporary extension. Firefox and Zen remove temporary add-ons when the browser closes; a signed `.xpi` is required for permanent installation.
- Enjoy! 😉

## How to Install (Safari - a very lengthy process)
- Download the folder from the download link.
- Download Xcode from the App Store. Open Xcode and let it download additional programs.
- Open the terminal and run this command `sudo xcode-select -s /Application/Xcode.app`
- Accept Xcode's licenses by running this command `sudo xcodebuild -license accept`
- Then copy the path of the downloaded folder. Run this command `xcrun safari-web-extension-converter paste-the-copied-path-here`
- It will open an Xcode window. You will see a triangle (Run button) on the left panel in the top right. Press it. It will add the extension to Safari.
- Go to Safari's preferences -> Go to Advanced tab -> Check the `Show Develop menu in menu bar`
- Go to Develop menu in Safari's top menu -> Click on `Allow Unsigned Extensions`
- Enjoy! 😉

## Download Link
[Download the whole folder](https://drive.google.com/drive/folders/11aEZxcQcAxA3u0twSWbRTV3_NRRHvfpb?usp=sharing)

## Download from the Chrome Web Store
[Download here](https://chrome.google.com/webstore/detail/byeclicker/kmnlnlkcacgjkngggifcnalkldgpflic)
