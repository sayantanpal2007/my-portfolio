# 🚀 Sayantan Pal — Personal Portfolio Website
### B.Tech Computer Science & Engineering (Artificial Intelligence & Machine Learning)

A modern, responsive personal portfolio website crafted for **Sayantan Pal**, a 3rd-semester B.Tech Computer Science student specializing in Artificial Intelligence and Machine Learning.

Designed with a **dark navy & midnight black** color palette, glowing electric blue accents, responsive layouts, and interactive features without requiring any external frameworks or build dependencies.

---

## ✨ Features & Highlights

- **Aesthetic Dark Theme**: Tailored deep navy (`#06080e`, `#0b1120`) background with subtle sky-blue/cyan (`#38bdf8`) accents and glassmorphic cards.
- **Dynamic Typewriter Subtitle**: Animated role switcher highlighting student aspirations and skills.
- **100% Vanilla Tech Stack**: Pure HTML5, CSS3, and JavaScript — no Node.js, React, or complex build steps needed.
- **Mobile-First Responsive Design**: Flawlessly adapts across mobile phones, tablets, and desktop displays.
- **Personalized Sections**:
  - **Home (Hero)**: Academic badge (`3rd Semester • B.Tech CSE (AI & ML)`), Sayantan Pal intro, dynamic typing, social buttons, and AI-themed illustration.
  - **About Me**: Academic focus, background narrative, and current learning targets.
  - **Skills**: Categorized into *Programming Languages*, *AI & Machine Learning*, *Computer Science Foundations*, and *Developer Workflow*.
  - **Projects**: Clean, attractive project cards with honest student status badges (`Completed`, `In Progress`, `Upcoming Milestone`).
  - **Education**: Interactive vertical timeline detailing B.Tech degree, Class XII, and Class X.
  - **Achievements & Milestones**: Clean milestone cards prepared for academic advancement, certifications, and technical competitions.
  - **Contact**: Direct email with a one-click copy button, GitHub & LinkedIn buttons, location status, and a functioning interactive contact form.
- **Ready for GitHub Pages**: Free and instant 1-click deployment.

---

## 📁 Project Structure

```text
antigravity.new/
├── index.html            # Main website markup for Sayantan Pal
├── README.md             # Guide, setup, and customization instructions
├── css/
│   └── style.css         # Modern styling, responsive breakpoints & dark theme
├── js/
│   └── main.js           # Typewriter, scrollspy, mobile menu & form handling
└── assets/
    ├── favicon.svg       # Custom AI neural network browser icon
    └── avatar.svg        # Modern developer & AI visual illustration
```

---

## 🖥️ How to Preview the Website Locally

As a beginner, you have several quick ways to view your website on your computer:

### Option 1: Direct Browser Preview (Easiest & Fastest)
1. Open the project folder in your computer's Finder / File Explorer.
2. Double-click **`index.html`** (or right-click -> **Open With** -> **Google Chrome**, **Safari**, or **Edge**).
3. The portfolio will immediately open in your browser!

### Option 2: Using VS Code Live Server (Recommended for Editing)
1. Open this project folder in **Visual Studio Code**.
2. Go to the Extensions tab (`Ctrl+Shift+X` or `Cmd+Shift+X`) and install **Live Server** (by Ritwick Dey).
3. Right-click on `index.html` inside VS Code and click **"Open with Live Server"**.
4. Any changes you save in `index.html` or `css/style.css` will auto-refresh immediately.

### Option 3: Using Python's Built-in Server (Terminal)
If you have Python installed, run this command in your terminal inside this folder:
```bash
python3 -m http.server 8000
```
Then visit `http://localhost:8000` in your web browser.

---

## ✏️ How to Further Customize (When Needed)

All files have clear comments indicating where you can update any specific details:

### 1. Social & Contact Links
- **GitHub**: Search for `https://github.com/sayantanpal` in `index.html` to link your exact GitHub profile username.
- **LinkedIn**: Search for `https://linkedin.com/in/sayantanpal` in `index.html` to link your exact LinkedIn profile.
- **Email**: Update `sayantan.pal@example.com` in `index.html` (line 680) and `js/main.js` (line 199) with your real email address.

### 2. Education & Institution Details
- In the `<section id="education">` block in `index.html`, you can replace the placeholder names `B.Tech Engineering Institution`, `Higher Secondary School`, and `Secondary High School` with the exact names of your college and schools whenever you like.

### 3. Adding Your Own Photo (Optional)
If you want to use your real portrait instead of the modern vector avatar:
1. Place your picture (e.g., `profile.jpg`) into the `assets/` folder.
2. In `index.html`, find:
   ```html
   <img src="assets/avatar.svg" alt="Student Developer Avatar" class="avatar-img" ...>
   ```
3. Change `assets/avatar.svg` to `assets/profile.jpg`.

### 4. Adding Real Milestones & Hackathons
As you earn course certificates (Coursera, NPTEL, Kaggle) or participate in hackathons (SIH, college code fests), simply update the corresponding cards in the `<section id="achievements">` block!

---

## 🌐 How to Publish for Free to GitHub Pages

You can host this website completely free with a custom `https://<your-username>.github.io/<repo-name>` address:

1. **Create a GitHub Repository**:
   - Go to [GitHub](https://github.com/) and create a new public repository (e.g., `portfolio`).
2. **Push your code**:
   Open your terminal in this folder and run:
   ```bash
   git init
   git add .
   git commit -m "Personalize portfolio for Sayantan Pal"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo-name>.git
   git push -u origin main
   ```
3. **Enable GitHub Pages**:
   - Go to your repository on GitHub.
   - Click on **Settings** (gear icon) -> **Pages** (in the left sidebar).
   - Under **Build and deployment** > **Branch**, select `main` (and `/root` folder).
   - Click **Save**.
4. In 1–2 minutes, your website will be live worldwide! 🎉

---

## 📄 License
This portfolio is open-source under the MIT License.
