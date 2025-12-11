# Data Wrapped 💕

A Spotify Wrapped-style analyzer for your Hinge dating data! Upload your Hinge export and get a fun, shareable summary of your dating life.

## 🚀 Quick Deploy

### Option 1: GitHub Pages (Recommended)

1. **Create a GitHub account** at [github.com](https://github.com) (if you don't have one)

2. **Create a new repository**
   - Click the "+" icon → "New repository"
   - Name: `data-wrapped` (or any name you like)
   - Make it **Public**
   - Check "Add a README file"
   - Click "Create repository"

3. **Upload the file**
   - Click "Add file" → "Upload files"
   - Drag and drop the `index.html` file
   - Click "Commit changes"

4. **Enable GitHub Pages**
   - Go to Settings → Pages (left sidebar)
   - Under "Source", select "Deploy from a branch"
   - Branch: `main`, Folder: `/ (root)`
   - Click "Save"
   - Wait 1-2 minutes, then refresh the page

5. **Your site is live!** 🎉
   - URL will be: `https://[your-username].github.io/data-wrapped/`
   - Share this link with friends!

### Option 2: Netlify Drop (Easiest)

1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag the `index.html` file into the browser
3. Done! You'll get an instant URL like `https://random-name-12345.netlify.app`

### Option 3: Vercel

1. Go to [vercel.com](https://vercel.com)
2. Sign up with GitHub
3. Import your repository
4. Deploy!

## 📱 How to Use

1. **Get your Hinge data**
   - Open Hinge app → Settings → "Download My Data"
   - Wait for the email (can take a few days)
   - Download and extract the JSON file

2. **Upload to Data Wrapped**
   - Visit your deployed site
   - Click "Upload Your Data"
   - Select your Hinge JSON file
   - Wait for the magic! ✨

3. **Share your results**
   - Navigate through slides with Previous/Next buttons
   - Screenshot your favorite slides
   - Share on Instagram/Twitter with #HingeWrapped #DataWrapped

## 🎨 What You'll Get

- 📊 Total likes sent
- 💯 Match rate percentage
- 💬 Conversation statistics
- ⏰ Peak activity times
- 🔥 Flirt score (1-10)
- 💭 Your texting style
- ✨ Your go-to line
- 👤 Your personality traits
- 💚 Dateability score (with roast!)

## 🔒 Privacy

- **All data is processed in your browser**
- Nothing is uploaded to any server
- Your data never leaves your device
- The only external call is to Claude's API for AI analysis
- 100% private and secure

## 🛠️ Customization

Want to customize the look? Edit the `index.html` file:

- **Colors**: Change gradient colors in the `bg` property (e.g., `from-purple-600 to-pink-600`)
- **Quips**: Modify the `getQuip()` function to add your own jokes
- **Slides**: Add/remove slides in the `slides` array
- **Meta tags**: Update Open Graph tags for better social sharing

## 📤 Sharing Tips

### Make it shareable:
- Take screenshots of each slide
- Post to Instagram Stories with #HingeWrapped
- Create a collage of your top stats
- Compare results with friends

### Custom domain (optional):
- Buy a domain from Namecheap/GoDaddy ($12/year)
- Point it to your GitHub Pages or Netlify site
- Now it's `datawrapped.com` instead of `username.github.io`

## 🐛 Troubleshooting

**"Error processing file"**
- Make sure you uploaded a valid Hinge JSON export
- Check the browser console (F12) for error details

**"Time showing Unknown"**
- Your Hinge export might not have timestamp data
- This is normal for older exports

**AI analysis not working**
- Check your internet connection
- The Claude API needs to be accessible
- Try refreshing and uploading again

## 🙏 Credits

Built with:
- React 18
- Tailwind CSS
- Claude 4 API (Anthropic)
- Love and chaos 💕

## 📜 License

MIT License - Feel free to fork, modify, and share!

---

**Made with 💕 for everyone who's survived the dating apps**

Share your wrapped: #HingeWrapped #DataWrapped
