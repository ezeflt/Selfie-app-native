🔼 ATTENTION Node js 🔼
If Node.js is not installed on your computer, 
please download and install Node.js from the official website https://nodejs.org/en/download before proceeding with the backend installation.
Once Node.js is installed, you can continue with the backend installation steps by following the instructions provided in the terminal.

🔼 ATTENTION Expo App 🔼
if Expo Go is not installed on your phone,
please download and install Expo Go from google play store or app store 

step 1/2 START BACKEND
-> terminal command

1) cd backend
2) yarn install
3) nodemon
✅ backend started

step 1/2 START FRONTEND
-> terminal command

1) cd frontend
2) yarn install
3) yarn start
4)After running yarn start, 
there will be a QR code displayed with the message 
"Metro waiting on exp://<your IP address>". 
Copy the IP address after "exp://". 
Go to frontend/screens/SnapScreen.tsx and on line 13
replace the backend address with the IP address you just copied. 
Paste the IP address and change the number after the colon to :3000.
It should look like this:
const BACKEND_ADDRESS = 'http://<your IP address>:3000';

5)Press r in your terminal to restart the application.
6)Take your phone, use your camera to scan the QR code.
✅ frontend started




