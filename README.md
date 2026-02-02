📌 **Project Overview**
This project demonstrates the **local setup of Strapi CMS**, creation of a **sample content type**, and pushing the setup to **GitHub**.  
It also includes a **Loom video walkthrough** for easier understanding.

**Technologies Used:**
- Node.js
- Strapi
- Git & GitHub

- ## 📑 Table of Contents
1. [Clone Repository](#clone-repository)
2. [Install Dependencies](#install-dependencies)
3. [Run Strapi Locally](#run-strapi-locally)
4. [Start Admin Panel & Create Admin User](#start-admin-panel--create-admin-user)
5. [Create Sample Content Type](#create-sample-content-type)
6. [Push Setup to GitHub](#push-setup-to-github)
7. [Loom Video Walkthrough](#loom-video-walkthrough)
8. [Submission](#submission)

1️⃣ Clone Repository
'''bash
git clone https://github.com/strapi/strapi.git
cd strapi '''

2️⃣ Install Dependencies
npm run develop

"
Strapi server: http://localhost:1337
Admin Panel: http://localhost:1337/admin
"

4️⃣ Start Admin Panel & Create Admin User
1. Open http://localhost:1337/admin in your browser
2. Create a new admin account:
    Email
    Password
    Display Name
3. Log in to access the dashboard

5️⃣ Create Sample Content Type
1. Go to Content-Types Builder in Admin Panel
2. Click Create new collection type → Name: Blog
3. Add fields:
    Title (Text)
    Author (Text)
    Content (Rich Text)
    Published (Boolean)
4. Save the content type
5. Restart server if prompted

6️⃣ Push Setup to GitHub

"
git init
git add .
git commit -m "Initial Strapi setup with Blog content type"
git branch -M main
git remote add origin <YOUR_REPO_URL>
git push -u origin main
"

Loom Vedio : https://www.loom.com/share/10f7fd5ffa2f46adbe64d32db75ed461
