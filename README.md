# 🌸 Resha Handcraft Crochet — Website

A beautiful, fully responsive e-commerce website for **Resha Handcraft Crochet** — handmade crochet items including decorative flowers, hair accessories, keychains and custom orders.

---

## 🚀 Deploy to GitHub Pages (Step-by-Step)

### Step 1 — Create a GitHub Repository
1. Go to [github.com](https://github.com) and sign in (or create a free account)
2. Click the **+** button → **New repository**
3. Name it: `resha-crochet` (or any name you like)
4. Set it to **Public**
5. Click **Create repository**

### Step 2 — Upload the Files
1. On the repository page, click **Add file → Upload files**
2. Upload **all files and folders** from this ZIP:
   - `index.html`
   - `images/` folder (with all product photos and logo)
3. Click **Commit changes**

### Step 3 — Enable GitHub Pages
1. Go to your repository → **Settings** tab
2. Scroll down to **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Choose **main** branch, **/ (root)** folder
5. Click **Save**
6. Wait ~1 minute, then your site is live at:
   ```
   https://YOUR-USERNAME.github.io/resha-crochet/
   ```

---

## 📧 Set Up Email for Forms (Formspree — Free)

The website has 2 forms — Order Form and Contact Form. To receive these as emails:

### Step 1 — Create Formspree Account
1. Go to [formspree.io](https://formspree.io) and sign up for free
2. Create **2 new forms** (one for Orders, one for Contact)
3. Copy the **Form ID** from each (looks like `xabcdefg`)

### Step 2 — Update index.html
Open `index.html` and find these two lines (around line 450):
```javascript
sendFormspree('https://formspree.io/f/YOUR_ORDER_FORM_ID', {
...
sendFormspree('https://formspree.io/f/YOUR_CONTACT_FORM_ID', {
```
Replace `YOUR_ORDER_FORM_ID` and `YOUR_CONTACT_FORM_ID` with your actual Formspree IDs.

### Step 3 — Set Your Email in Formspree
In Formspree dashboard, set the notification email to your inbox.  
All order and contact form submissions will arrive there instantly.

---

## 📲 Add Your UPI QR Code

1. Generate your UPI QR code from Google Pay / PhonePe / Paytm
2. Save it as `images/upi_qr.png`
3. In `index.html`, find the `qr-placeholder` div and replace it with:
```html
<img src="images/upi_qr.png" alt="UPI QR Code" style="width:160px;margin-top:.5rem;border-radius:10px;" />
```

---

## 📁 File Structure
```
resha-crochet/
├── index.html          ← Main website (single file)
├── README.md           ← This guide
└── images/
    ├── logo.png
    ├── hibiscus_vase.jpg
    ├── hibiscus_vase2.jpg
    ├── hibiscus_stem.jpg
    ├── tulip_pot1.jpg
    ├── tulip_pot2.jpg
    ├── sunflowers.jpg
    ├── sunflower_stem.jpg
    ├── hair_accessories.jpg
    ├── hair_clips.jpg
    ├── hair_ties.jpg
    ├── bows_3colors.jpg
    ├── pink_bow.jpg
    ├── teal_bow.jpg
    ├── purple_bow.jpg
    ├── keychain.jpg
    └── mixed_bouquet.jpg
```

---

## 🎨 Website Sections

| Section | Description |
|---|---|
| **Hero** | Full-screen intro with product photo grid |
| **About** | Brand story with product photos |
| **Shop** | Product catalogue with filter tabs |
| **Process** | 4-step how-it-works flow |
| **Order** | Order form with Cash / UPI / Bank payment options |
| **Gallery** | Masonry photo gallery with lightbox |
| **Contact** | Message form that emails you directly |
| **Footer** | Links + Instagram & Facebook icons |

---

## ✏️ Customise

- **Your social handles**: Search for `@ReshaHandcraftCrochet` in `index.html` and update to your actual handle
- **WhatsApp link**: Add `href="https://wa.me/91XXXXXXXXXX"` to the WhatsApp contact item
- **Prices**: Update product prices in the product cards
- **Email**: Set your email in Formspree dashboard

---

Made with 🧶 by Resha Handcraft Crochet · Est. 2026
