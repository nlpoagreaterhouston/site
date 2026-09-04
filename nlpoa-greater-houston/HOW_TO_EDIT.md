# 📘 How to Easily Edit the NLPOA Greater Houston Website

Welcome! Your website has been designed so that you can easily edit text, photos, events, and board members on your own without needing advanced web development experience.

---

## 🌟 Method 1: The Built-In Visual Editor (Easiest — No Coding!)

You can edit the entire website visually right in your web browser:

1. **Open the Website**:
   - Double-click [`index.html`](file:///C:/Users/gonhe/.gemini/antigravity/scratch/nlpoa-greater-houston/index.html) to open it in Chrome, Edge, or any browser.
2. **Turn On Edit Mode**:
   - Look at the bottom-left corner of the screen.
   - Click the gold button that says **`Edit Mode: OFF`**. It will turn into **`Edit Mode: ON`** with a gold active glow.
3. **Swap Any Photo**:
   - Click on **any image** on the site (Hero photo, board officers, event galleries, programs, or social feed images).
   - Your computer's file explorer will open. Select any image file from your PC — it will instantly replace that photo!
4. **Edit Any Text or Button**:
   - Click directly on any button (e.g. *Apply for 2027 Scholarship*), headline, officer name, agency, event date, phone number, or paragraph and start typing. In Edit Mode, clicking a button lets you edit its text instead of opening a modal or link!
5. **Publish New Social Media Posts**:
   - Click **`Add Post`** in the bottom-left dock to upload a new event photo with a custom caption and hashtags into the live Facebook/Instagram stream.
6. **Save & Export**:
   - All edits automatically auto-save to your browser.
   - Click **`Export HTML`** in the bottom dock anytime to download a fresh, updated `index.html` file ready for publishing!

---

## 📝 Method 2: Editing Text in Notepad or Any Code Editor

All the website files are located in this folder:
📂 `C:\Users\gonhe\.gemini\antigravity\scratch\nlpoa-greater-houston\`

### 1. [`index.html`](file:///C:/Users/gonhe/.gemini/antigravity/scratch/nlpoa-greater-houston/index.html) — Text & Layout
Right-click `index.html` and choose **Open With > Notepad** (or VS Code). You can use **Ctrl + F** to find:
- **Phone Number & Email**: Search for `(832) 755-9860` or `nlpoahouston@gmail.com`.
- **Board Members**: Search for `Executive Board` to change officer names, ranks, and police departments.
- **Programs & Scholarships**: Search for `Annual Scholarship Golf Classic` or `Scholarship Fund` to update dates and requirements.
- **Events Calendar**: Search for `Upcoming Schedule` to update dates, locations, and times.

### 2. [`styles.css`](file:///C:/Users/gonhe/.gemini/antigravity/scratch/nlpoa-greater-houston/styles.css) — Colors & Styling
- Open `styles.css` to adjust colors:
  - `--navy-800: #0B1B3D` (Houston Navy)
  - `--gold-500: #D4AF37` (Prestige Gold)
  - `--white: #FFFFFF` (Clean White)

### 3. [`app.js`](file:///C:/Users/gonhe/.gemini/antigravity/scratch/nlpoa-greater-houston/app.js) — Social Feed & Features
- Open `app.js` and look at the `SOCIAL_POSTS` array at the top to add, remove, or modify Instagram/Facebook posts, captions, and like counts.

---

## 🔒 Members-Only Portal Login

The password-protected member area is pre-configured with the following demo access:
- **Email / Username**: `member@nlpoa.org`
- **Password**: `Houston2026!`
- *(Or click the "1-Click Demo Login" helper button inside the login window).*

---

## 🌐 How to Publish to the Internet (Free & Easy)

When you're ready to put this website online at your domain (like `nlpoagreaterhouston.com`):

### Option A: Free Drag-and-Drop Hosting (Netlify / Vercel)
1. Go to [Netlify.com](https://www.netlify.com/) or [Vercel.com](https://vercel.com/) (both offer free hosting).
2. Simply drag and drop the `nlpoa-greater-houston` folder into the Netlify dashboard.
3. Your website will be live on the web in seconds with free SSL and lightning speed!
4. Connect your custom domain `nlpoagreaterhouston.com` in Netlify's domain settings.

### Option B: Traditional Web Hosting (cPanel / GoDaddy / Bluehost)
1. Log into your hosting cPanel File Manager.
2. Upload the files (`index.html`, `styles.css`, `app.js`, and `assets/` folder) into the `public_html` directory.
