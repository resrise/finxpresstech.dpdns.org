# Deployment Instructions for FinXpress Website

## 1. Local Deployment

1. **Clone your repository:**
   ```sh
   git clone https://github.com/resrise/finxpresstech.dpdns.org.git
   cd finxpresstech.dpdns.org
   ```

2. **Add your logo and screenshots (recommended):**
   - Place `logo.png` in the root directory.
   - Place screenshots in `screenshots/finxpress-features-1.png` and `screenshots/finxpress-features-2.png`.

3. **View locally:**
   - Open `index.html` in your web browser.
   - No server required for static preview.

---

## 2. Deploy on GitHub Pages

1. **Push all files to your main branch** (already done).

2. **Enable GitHub Pages:**
   - Go to your repo on GitHub.
   - Click **Settings** > **Pages**.
   - Under **Source**, select the `main` branch and `/ (root)` folder.
   - Click **Save**.
   - Your site will be available at:  
     `https://resrise.github.io/finxpresstech.dpdns.org/`  
     (Check for the actual URL after saving.)

---

## 3. Deploy on Netlify

1. Go to [Netlify](https://www.netlify.com/) and sign in.
2. Click **Add new site** > **Import an existing project**.
3. Connect your GitHub repository.
4. Set build command as `N/A` (static site) and publish directory as root.
5. Click **Deploy**.
6. After deploy, you can set a custom domain in Netlify settings.

---

## 4. Deploy on Vercel

1. Go to [Vercel](https://vercel.com/) and sign in.
2. Click **Import Project** > **Import Git Repository**.
3. Select your repository.
4. Set framework as **Other** (since it’s HTML/CSS only).
5. Click **Deploy**.

---

## 5. Custom Domain

- For GitHub Pages:  
  In **Settings > Pages**, add your custom domain and follow instructions for DNS setup.
- For Netlify/Vercel:  
  Go to domain settings after deployment and follow their instructions.

---

## 6. Updating Your Site

- Make changes to your files locally.
- Commit and push to your main branch:
    ```sh
    git add .
    git commit -m "Update website"
    git push
    ```
- Your deployed site will update automatically (may take a few minutes).

---

## Need Help?

Open an issue in your GitHub repository or contact your web administrator.