# 📖 Surah Al-Baqarah - Comprehensive Tafseer Study Table

An interactive, modern web application for comprehensive Quranic learning with 12 different study methods built in.

## ✨ Features

- **📊 Interactive Table** - All 13 sections of Surah Al-Baqarah with expandable content
- **🔍 Search Functionality** - Find sections by ayat, title, or keyword
- **📋 Progress Tracking** - Toggle status (In Progress ⏳ / Completed ✓ / Not Started ❌)
- **🎨 Beautiful UI** - Modern, responsive design that works on all devices
- **💾 Local Storage** - Your progress is saved automatically
- **📱 Mobile Friendly** - Optimized for phones, tablets, and desktops
- **🖨️ Print Ready** - Print your study notes directly
- **⚡ Fast & Lightweight** - Pure HTML/CSS/JavaScript, no dependencies

## 🎯 Study Methods Included

1. **Ayat Range** - Verse references
2. **Tafseer Summary** - Classical interpretation
3. **Key Arabic Terms** - Language learning
4. **Quranic Parallels** - Cross-references
5. **Hadith References** - Prophetic tradition
6. **Fiqh Rulings** - Islamic law
7. **Historical Context** - Background & Occasion
8. **Spiritual Lesson** - Heart connection
9. **Personal Reflection** - YOUR application
10. **Discussion Points** - Questions to ponder
11. **Status Tracking** - Progress monitoring

## 🚀 Quick Start

### Local Development
```bash
# Using Python 3
python -m http.server 3000

# Or using Node.js (if you have it)
npm run dev
```

Then visit `http://localhost:3000`

### Deploy to Vercel

#### Option 1: Using Vercel CLI
```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

#### Option 2: Using GitHub + Vercel Web Interface
1. Push code to GitHub:
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/surah-baqarah.git
git push -u origin main
```

2. Go to [https://vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your GitHub repository
5. Click "Deploy"

#### Option 3: Using Vercel Web Upload
1. Visit [https://vercel.com/new](https://vercel.com/new)
2. Select "Other" (for HTML)
3. Upload the project files
4. Click "Deploy"

## 📁 File Structure

```
.
├── index.html          # Main application
├── vercel.json         # Vercel configuration
├── package.json        # Project metadata
└── README.md          # This file
```

## 🎨 Customization

### Change Colors
Edit the CSS variables in `<style>` section:
```css
:root {
    --primary: #203864;
    --secondary: #4472C4;
    /* ... more colors ... */
}
```

### Add More Sections
Edit the `sections` array in the `<script>` section:
```javascript
{
    ayat: '1–5',
    title: 'Section Title',
    tafseer: 'Tafseer content...',
    // ... more fields ...
}
```

### Modify Learning Methods
Update the table headers in `<table>` to match your needs.

## 💡 Usage Tips

1. **Search**: Use the search box to find specific topics
2. **Click Cells**: Click any cell to see full content
3. **Track Progress**: Click status emoji to cycle through states
4. **Filter**: Use filter buttons to view specific sections
5. **Print**: Press Ctrl+P to print your notes

## 🔗 Special Ayat to Focus On

- **Ayat 255 (Al-Kursi)** - The Throne Verse - Memorize it
- **Ayat 282 (Al-Mudayanah)** - Longest ayah in Quran
- **Ayat 286** - Contains 5 powerful duas

## 📚 Recommended Resources

- **Ibn Kathir Tafseer** - [Quran.com](https://quran.com)
- **Fi Zilal al-Quran** - Sayyid Qutb
- **Tafseer As-Sa'di** - Clear & concise
- **Maariful Quran** - For Fiqh understanding

## 🌐 Deployment Status

- ✅ Vercel: [Your Deployed URL]
- ✅ GitHub: [Your GitHub URL]
- ✅ Local: Works with any HTTP server

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables
- **Vanilla JavaScript** - No frameworks, pure JS

## 📄 License

MIT License - Feel free to use and modify

## 🤝 Contributing

Found a typo or want to improve something? 
1. Fork the repository
2. Create a branch: `git checkout -b feature/improvement`
3. Commit: `git commit -m 'Add improvement'`
4. Push: `git push origin feature/improvement`
5. Open a Pull Request

## 💬 Support

For questions or suggestions, open an issue on GitHub or reach out via email.

## 🙏 Acknowledgments

- Quranic content based on classical tafseer
- Hadith references from Sahih al-Bukhari, Muslim, and other authentic sources
- Inspired by modern digital learning platforms

---

**Made with ❤️ for Quranic learning**

May Allah grant us understanding of His book and wisdom to apply it in our lives. 🤲

*Last Updated: April 2026*
