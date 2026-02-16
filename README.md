# 🎂 Anime Birthday Website

An interactive, multi-page birthday celebration website with an anime theme! Features animations, interactive elements, and special birthday messages.

## 🌟 Features

- **Home Page**: Animated landing page with navigation to all sections
- **Birthday Wishes**: Heartfelt messages with anime-themed inspiration
- **Memory Gallery**: Nostalgic moments and memories
- **Anime Quiz**: Test your anime knowledge with an interactive quiz
- **Birthday Countdown**: Real-time countdown to the next birthday

## 🎨 Design Highlights

- Stunning gradient animations and particle effects
- Sakura petals and floating hearts
- Interactive hover effects
- Responsive design for all devices
- Custom fonts and color scheme
- Smooth page transitions

## 🚀 How to Deploy on GitHub Pages

### Method 1: Using GitHub Web Interface

1. **Create a new repository**
   - Go to [GitHub](https://github.com) and sign in
   - Click the "+" icon in the top right and select "New repository"
   - Name it something like `anime-birthday` or `birthday-website`
   - Make it public
   - Click "Create repository"

2. **Upload files**
   - Click "uploading an existing file"
   - Drag and drop all the HTML files (index.html, wishes.html, memories.html, quiz.html, countdown.html)
   - Commit the files

3. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll down to "Pages" section (in the left sidebar)
   - Under "Source", select "main" branch
   - Click "Save"
   - Your site will be published at: `https://[your-username].github.io/[repository-name]/`

### Method 2: Using Git Command Line

```bash
# Initialize git in your project folder
git init

# Add all files
git add .

# Commit the files
git commit -m "Initial commit - Anime birthday website"

# Add your GitHub repository as remote
git remote add origin https://github.com/[your-username]/[repository-name].git

# Push to GitHub
git branch -M main
git push -u origin main
```

Then enable GitHub Pages in repository settings as described in Method 1.

## 📝 Customization

To personalize this website:

1. **Change Birthday Messages** (wishes.html):
   - Edit the messages in the `.wish-card` sections
   - Add or remove wish cards as needed

2. **Update Quiz Questions** (quiz.html):
   - Modify the `quizData` array in the JavaScript section
   - Change questions, answers, or add new ones

3. **Customize Colors**:
   - All colors are defined in CSS variables at the top of each file
   - Modify the `:root` section to change the color scheme

4. **Add Your Own Content**:
   - Replace placeholder emojis with actual images
   - Add more pages by creating new HTML files
   - Update navigation links in index.html

## 🎮 How to Use

1. **Home Page**: Click on any of the four cards to navigate
2. **Wishes Page**: Read through heartfelt birthday messages
3. **Memories**: Browse through nostalgic moments
4. **Quiz**: Answer 5 anime-related questions and see your score
5. **Countdown**: Enter a birthday date to see the real-time countdown

## 📱 Browser Compatibility

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## 🎉 Live Demo

Once deployed, share the GitHub Pages URL with the birthday person!

## 📄 License

Feel free to use this template for personal birthday celebrations!

---

Made with 💖 for anime fans everywhere!
