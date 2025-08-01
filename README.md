# 🌐 How to Publish a Google Site from GitHub

This guide explains the steps I follow to publish my Google Site using GitHub Pages.

---

## 📁 Step 1: Locate Your Website Folder

- Open **Google Drive** and find the folder containing your Google Site (e.g., `my_website`).
- Or directly open [Google Sites](https://sites.google.com) and look for your site (e.g., `Ravi_site`).

## ✏️ Step 2: Make Changes to Your Site

- Edit your Google Site as needed using the Google Sites editor.

## 📦 Step 3: Export Your Site Using Google Takeout

1. Go to [Google Takeout](https://takeout.google.com/).
2. Click **"Deselect all"**.
3. Scroll down and **select only "Drive"**.
4. Click on **"All Drive data included"** → Uncheck **"Include all files and folders in Drive"**.
5. Click **"Deselect all"** again.
6. Now select only your site folder (e.g., `my_website`) and click **"OK"**.
7. Scroll down and click **"Next step"**.
8. Click **"Create export"**.
9. Wait for the export to finish. You will receive an email with the download link.

## 📥 Step 4: Download and Extract

- Download the ZIP file from your email.
- Extract it (Right-click → **Extract All** or **Extract Here**).
- Navigate inside the extracted folder until you reach the final folder named **`DRAFT`**.

## 📝 Step 5: Create `index.html`

- Inside the `DRAFT` folder, make a **copy of `Home.html`**.
- Rename the copied file to **`index.html`**.  
  > GitHub Pages looks for `index.html` as the default entry file.

## 🚀 Step 6: Push to GitHub

- Replace the previous content in your GitHub repository with the contents of the `DRAFT` folder (including the new `index.html`).
- Commit and push the changes to GitHub.

Your Google Site is now live through GitHub Pages! 😊

---

