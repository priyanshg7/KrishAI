# Firebase Studio

This is a NextJS starter in Firebase Studio.

To get started, take a look at src/app/page.tsx.
✅ Prerequisites
Make sure you have the following installed:

Node.js (v16+ recommended)

npm or yarn

Firebase CLI:

bash
Copy
Edit
npm install -g firebase-tools
Firebase project is already set up (optional for local dev, needed for deploy)

🧭 Project Structure (Based on your git status)
Looks like your project includes:

pgsql
Copy
Edit
KrishAI4/
├── firebase.json
├── firestore.rules
├── functions/ (if using cloud functions)
├── public/
├── src/ or pages/
├── next.config.ts
├── tailwind.config.ts
├── package.json
🧪 Step-by-Step: Start the App Locally
1. Install Dependencies
bash
Copy
Edit
cd ~/Desktop/KrishAI4
npm install
This installs dependencies from package.json.

2. (Optional) Login to Firebase
bash
Copy
Edit
firebase login
3. Start Next.js Dev Server
If you’re not using Firebase Hosting locally and just want to test the UI:

bash
Copy
Edit
npm run dev
This runs Next.js at http://localhost:3000

npm run build
npm start 
