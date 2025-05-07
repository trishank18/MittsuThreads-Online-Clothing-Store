❖ Install NodeJs ( Ignore If Already Installed)
 1. Visit the official Node.js website i.e) https://nodejs.org/en/download/
 2. Download the Node.js installer
 3. Run the installer.
 4. Follow the prompts in the installer
 —First Run Backend then Frontend & Admin—
❖ StepsToSetup Backend Of The Project
 1. OpenProject Folder In VS Code
 2. OpenIntegrated Terminal
Right Click on ‘backend’ > Select “Open In Integrated Terminal”
 3. Type “npm install” and press Enter and Wait for Installation to be completed
 (requires Internet)
4. Setup Cloudinary for file storage.
 Create account and login to: https://cloudinary.com/
 The go to Dashboard
Copy and paste the Cloud Name, API Key, And Secret Key in the
 backend / .env file
 6. Setup The MongoDB
 a. Open this link- LINK
 b. After that Sign Up on the website
c. Click on New Project Option
 d. After Creating Project go to Database Section & Build a database
 e. Select M0 & Your Region & Create Database
f. Setup Username & Password & Create User
 Note: Do not use ‘@’ symbol in the password
 g. NowClick on Finish & Close
h.Whitelist IP0.0.0.0&ClickonAddEntry
 i. NowClickonConnect
 j. NowSelectCompassOption
 k. AndCopytheConnectionString
l.
 And Paste It in the backend / .env file and replace the <password> with
 the password you set previously in 4.F & save changes.
 ● Inmongodb uri don’t add ” / ” in the end
 7. Setup Stripe ( Optional )
a. create a stripe account from here
 b. After creating account get the Stripe Secret Key from dashboard
 c. Paste the Secret Key in backend / .env file and save file
 8. Setup Razorpay( Optional )
a. create a razorpay account from here
 b. After creating account get the Razorpay Secret Key & Razorpay Key ID from
 dashboard
 c. Paste the Secret Key in backend / .env file and save file
9. To Run Backend use npm run server command in Integrated Terminal
 >>> Before Running Frontend or Admin Projects make sure Backend is
 Running in the background terminal
 ❖ StepsToRunFrontend of The Project
 1. Right Click on ‘frontend’ folder > Select “Open In Integrated Terminal”
 2. Type “npm install” and press Enter and Wait for Installation to be completed
 (requires Internet)
 3. After that type “npm run dev” in terminal
 4. Nowyou will see the ‘http://localhost:5173’ link in that terminal. Open that link
 in the browser.
❖ StepsToRunAdminPanel of The Project
 1. Right Click on ‘admin’ folder > Select “Open In Integrated Terminal”
 2. Type “npm install” and press Enter and Wait for Installation to be
 completed (requires Internet)
 3. After that type “npm run dev” in terminal
 4. Nowyou will see the ‘http://localhost:5174’ link in that terminal. Open
 that link in the browser.
