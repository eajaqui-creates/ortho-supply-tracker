# Ortho Supply Tracker — GitHub Pages Setup

A supply management app for your orthodontic office. Runs entirely in the browser with localStorage — no database, no backend, no monthly fees.

## Deploy in 5 Minutes

### Step 1: Create a GitHub Account (skip if you have one)
1. Go to [github.com](https://github.com) and sign up (free)

### Step 2: Create a Repository
1. Click the **+** button (top right) → **New repository**
2. Name it: `ortho-supply-tracker`
3. Set it to **Public** (required for free GitHub Pages)
4. Check **"Add a README file"**
5. Click **Create repository**

### Step 3: Upload the File
1. In your new repo, click **Add file** → **Upload files**
2. Drag and drop the `index.html` file
3. Scroll down and click **Commit changes**

### Step 4: Enable GitHub Pages
1. Go to your repo's **Settings** tab
2. In the left sidebar, click **Pages**
3. Under "Source", select **Deploy from a branch**
4. Branch: **main**, Folder: **/ (root)**
5. Click **Save**
6. Wait 1-2 minutes, then refresh the page
7. You'll see a link like: `https://yourusername.github.io/ortho-supply-tracker/`

### Step 5: Bookmark It
Open that URL on your office computer and bookmark it. That's your app!

---

## How Data Works

- All data is saved in **localStorage** on the browser you use
- Data survives closing the browser, restarting the computer, updates, etc.
- Data is only deleted if you manually clear browser data or uninstall the browser

### Backup Habit (recommended)
Once a week, go to **Settings → Export JSON** to download a backup file. Keep it in a Google Drive folder. If anything ever happens, use **Import JSON** to restore.

---

## Features
- Dashboard with reorder alerts and quick stats
- Clinical Supplies (14 categories) and Office Supplies (5 categories)
- Editable items — name, category, unit, cost, stock, threshold
- Last order info on each item — date, quantity, price, vendor, estimated days left
- Order History with inline editing, status changes (Ordered/Received/Returned/Incomplete/Wrong)
- Log Order with vendor selection (add new vendors on the fly), tax, shipping, discount
- Monthly Spending charts — clinical vs office breakdown
- Vendor management in Settings
- Export: JSON backup + CSV for inventory and orders
- Import: restore from JSON backup
- Location switcher: Suwanee / Tucker / All

---

## Updating the App
If you need changes later, just upload a new `index.html` to the same repo (it will replace the old one). Your data stays safe in localStorage — it's separate from the app file.
