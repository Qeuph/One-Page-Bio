# BioLink
https://biolinknuke.netlify.app

```markdown
# BioLink Pro

A completely free, serverless "Link-in-Bio" web application. It allows users to create a customizable profile, share links via QR codes, track profile views, and follow others.

## 🚀 Features

- **Authentication:** Secure Sign Up and Login system (Username & Password).
- **Customizable Profiles:** Edit name, bio, and social links.
- **Themes:** Switch between Light, Dark, and Neon modes instantly.
- **QR Code Generation:** Automatically creates a downloadable QR code for sharing.
- **Analytics:** Track total profile views.
- **Social Interactions:** Follow/Unfollow other users with real-time counters.
- **100% Free:** Built using JSONBin.io for the database and Netlify for hosting. No backend server costs.

## 🛠 Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **Database:** JSONBin.io (NoSQL JSON Storage)
- **Hosting:** Netlify (or any static file host)
- **QR API:** QRServer API

## 📦 Installation

### Prerequisites
1.  A JSONBin.io account (Free tier).
2.  A Netlify account (Free tier).

### Step 1: Setup Database
1.  Go to [JSONBin.io](https://jsonbin.io) and create a new Bin.
2.  Leave the content as `{}`.
3.  Create an API Key in your settings.
4.  **Important:** Copy your **API Key** and the **Bin ID**.

### Step 2: Configure Code
1.  Download `index.html`.
2.  Open the file in a text editor.
3.  Scroll to the `<script>` section (bottom of the file).
4.  Replace the placeholder values with your keys:
    ```javascript
    const API_KEY = 'YOUR_JSONBIN_API_KEY_HERE';
    const BIN_ID = 'YOUR_JSONBIN_BIN_ID_HERE';
    ```
5.  Save the file.

### Step 3: Deploy
1.  Go to [Netlify Drop](https://app.netlify.com/drop).
2.  Drag and drop the folder containing your `index.html` file.
3.  Your site is now live!

## 📖 Usage Guide

### For Users
1.  **Sign Up:** Create a username and password.
2.  **Edit Profile:** Add your bio and social links (Format: `Title | URL`).
3.  **Customize:** Select a visual theme (Light/Dark/Neon).
4.  **Share:** Go to the "QR & Share" tab to copy your link or download your QR code.
5.  **Social:** Visit other user profiles (e.g., `your-site.com/?user=username`) to follow them and see their stats.

### URL Structure
To share a profile, simply append the username to the URL:
`https://your-site.com/?user=john_doe`

## 🔧 Development

### Project Structure
```text
/
├── index.html       # Main application file (HTML, CSS, JS)
└── README.md        # This file
```

### Customization
- **Themes:** Edit the CSS variables in the `<style>` block to change brand colors.
- **Validation:** Passwords are currently stored in plain text within the JSONBin. For a production environment, implement hashing on a backend server.

## 📄 License
This project is open source and available for personal and educational use.

## 🤝 Contributing
Since this is a personal prototype, feel free to fork and modify it as you wish!
```
