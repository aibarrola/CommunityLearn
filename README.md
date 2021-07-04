# Spartan Swipe

Setting up Node - Using VSCode

1.) Download Node.js from https://nodejs.org/en/
2.) In VSCode, open up the terminal by clicking View -> Terminal
3.) In the terminal, check if node is correctly installed with the command "node -v"

Setting up Firebase Connection - I will need your gmail's 

1.) In the terminal, on Windows I typed the command "npm i firebase-tools -g"

  (If there is an error, you might have to stack overflow it, I had an error and it had me go into my PC User profile and delete some   file or something.)
   
   On Mac, I typed "sudo npm install -g firebase-tools"
2.) Next, type in the terminal "firebase login"
3.) [Allow Firebase to collect CLI usage and error reporting information? (Y/n)] : Press 'y' key and then the enter key
4.) THe terminal will now automatically generate a link and your web browser will open to connect to your gmail account
5.) Once connected, your Firebase CLI Login will be successful

Setting up Firebase Tools

1.) In the terminal, type "firebase init"
2.) [Are you ready to proceed? (Y/n)] : Press 'y' key and then the enter key
3.) [Which Firebase CLI features do you want to set up for this folder?...] : Scroll down by pressing the down key until you reach [Hosting: Configure files for Firebase Hosting and (optionally) set up Github Action deploys] : Press 'spacebar' key and then scroll down again until you reach [Emulators: Set up local emulators for Firebase products] : Press 'spacebar' key and then press the enter key

Setting up Project - Terminal

1.) [Please select an option:...] : Use an existing project
2.) [Select a default Firebase project for this directory:...] : spartanswipe-129a (SpartanSwipe) <-(This is what I named my project and file)

Setting up Hosting - Terminal

1.) [What do you want to use as your public directory?] : public
2.) [Configure as a single-page app (rewrite all urls to /index.html)?] : Yes
3.) [Set up automatic builds and deploys with Github?] : No
4.) [File public/index.html already exists. Overwrite?] : No

Setting up Emulator - Terminal

1.) [Which Firebase emulators do you want to set up? Press Space to select emulators, then Enter to confirm your choices...] : (Same thing as in Setting up Firebase Tools)-> Select "Function Emulator, Firestore Emulator, Hosting Emulator"
2.) [Which port do you want to use for the functions emulator?] : 5001  <-(Should be default number)
3.) [Which port do you want to use for the firestore emulator?] : 8080  <-(Should be default number)
4.) [Which port do you want to use for the hosting emulator?] : 5000    <-(Should be default number)
5.) [Would you like to enable the Emulator UI?] : Yes
6.) [Which port do you want to use for the Emulator UI (leave empty to use any available port)?] : Skip by just pressing the enter key
7.) [Would you like to download the emulators now?] : Yes
8.) To deploy the web app to the internet, type in the terminal "firebase deploy" 
  (I already deployed it and the website URL should be: https://spartanswipe-12d9a.web.app) (Works on mobile too)
