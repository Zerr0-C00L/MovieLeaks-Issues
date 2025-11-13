# Movie Leaks - Bug Reports & Feature Requests

This is the public issue tracker for the **Movie Leaks Stremio Addon**.

## 🐛 Report a Bug

Found a bug? Help us improve!

1. Click the **"Issues"** tab above
2. Click **"New Issue"**
3. Choose **"Bug Report"** template
4. Fill out the details and submit

## ✨ Request a Feature  

Have an idea for a new feature?

1. Click the **"Issues"** tab above
2. Click **"New Issue"**
3. Choose **"Feature Request"** template
4. Describe your idea and submit

---

## 📖 About the Addon

**Movie Leaks** is a Stremio addon that catalogs leaked and upcoming movies from r/movieleaks subreddit, bringing them directly to your Stremio library.

### 🎬 Features

- **Leaked Movies** - Automatically scraped from r/movieleaks
- **Auto-updating Catalog** - New movies added weekly
- **Multiple Sort Options** - New, Hot, Top, Rising
- **Rich Metadata** - Movie info, posters, ratings via Cinemeta
- **RPDB Integration** - Optional custom posters with RT scores (supporters only)
- **Two-Tier System**:
  - 🆓 **Free Tier**: 100 movies, no signup required
  - 💎 **Supporter Tier**: All movies + RPDB support

### 📦 Installation

**Free Tier (100 movies):**
```
https://movie-leaks.vercel.app/manifest.json
```

1. Open **Stremio**
2. Click the **puzzle icon** (Add-ons)
3. Click **"Community Add-ons"** at the bottom
4. Paste the URL above and click **Install**
5. Browse the **"Movie Leaks"** catalog

**Supporter Tier (movies):**

1. Subscribe on Ko-fi: https://ko-fi.com/zeroq/membership
2. Receive your unique supporter code **instantly via email**
3. Install the addon (URL above)
4. Configure it with your supporter code
5. Unlock all movies! 🎉

### 💎 Become a Supporter

Support the project for **$5/month** and get:

- ✅ **All movies** (vs 100 free)
- ✅ **RPDB poster overlays** (bring your own free key from ratingposterdb.com)
- ✅ **Instant code delivery** via automated email
- ✅ **Priority support** for issues and requests
- ✅ **Future features** as they're developed
- ✅ Help keep the project alive!

**Subscribe here:** https://ko-fi.com/zeroq/membership

Codes auto-renew monthly with your subscription and are delivered instantly via email.

---

## 🛠️ Technical Details

- **Source**: r/movieleaks subreddit (public posts)
- **Metadata**: Cinemeta API (official Stremio)
- **Updates**: Automated weekly scraping
- **Hosting**: Vercel (serverless)
- **Caching**: 5-minute refresh cycle
- **Code Validation**: 30-day expiry with auto-renewal

### How It Works

1. Addon scrapes r/movieleaks posts regularly
2. Extracts IMDb IDs and metadata
3. Fetches proper movie info from Cinemeta
4. Applies RPDB posters for supporters (optional)
5. Serves catalog to Stremio

**Disclaimer**: This addon only provides catalog information. Actual streaming links come from the Reddit posts themselves. We don't host any content.

---

## 📝 Guidelines

Before creating an issue:

- **Search existing issues** to avoid duplicates
- **Be specific** - Include steps to reproduce bugs
- **Include details**:
  - Stremio version (Desktop/Web/Android/iOS)
  - Device/OS
  - Whether you're using free or supporter tier
  - Screenshots if possible
- **Be respectful** - This is a community project
- **Be patient** - Responses may take time

---

## 🔒 Security & Privacy

- **No tracking** - We don't collect personal data
- **Supporter codes** - Stored securely, only used for validation
- **RPDB keys** - User-provided, not stored on our servers
- **Email delivery** - Only for supporter code delivery

If you discover a security vulnerability, please email directly instead of creating a public issue.

---

## 🙏 Support the Project

Love the addon? Here's how you can help:

- ☕ **Become a Supporter** - $5/month unlocks everything: https://ko-fi.com/zeroq/membership
- ⭐ **Star this repository** to show your support
- 🐛 **Report bugs** to help improve quality
- 💬 **Share with friends** who use Stremio
- 📢 **Spread the word** on Reddit, Discord, etc.

Your support helps cover:
- Vercel hosting costs
- Reddit API usage
- Development time
- Future features and improvements

---

## 📱 Community

- **Stremio Discord**: discord.gg/zNRf6YF
- **Reddit**: r/StremioAddons, r/Stremio
- **Ko-fi**: ko-fi.com/zeroq

---

## 🔗 Links

- **Install Addon**: https://movie-leaks.vercel.app/manifest.json
- **Become a Supporter**: https://ko-fi.com/zeroq/membership
- **Free RPDB Key**: https://ratingposterdb.com
- **Source Subreddit**: r/movieleaks

---

## 📋 Roadmap

Upcoming features (vote for your favorites in Issues!):

- [✅] More sort/filter options
- [ ] Genre categories
- [ ] Quality indicators
- [✅] Release date filtering
- [✅] Search functionality
- [ ] Custom lists
- [ ] Watchlist integration

Have another idea? Create a Feature Request!

---

## ❓ FAQ

**Q: Is this legal?**  
A: Yes. We're a search engine/aggregator for public Reddit posts. We don't host any content.

**Q: Why charge for the full catalog?**  
A: The free tier (100 movies) is generous! Supporters help cover hosting costs, Reddit API usage, and development time. It's optional - enjoy the free version!

**Q: Do I need an RPDB key?**  
A: No, it's completely optional. RPDB adds custom posters with RT scores, but requires a supporter code to use.

**Q: How do I get an RPDB key?**  
A: Free at ratingposterdb.com - create an account and generate an API key.

**Q: What if I cancel my Ko-fi subscription?**  
A: Your code will expire and you'll return to the free tier (100 movies). No hard feelings!

**Q: Can I share my supporter code?**  
A: Codes are for personal use only. Sharing may result in deactivation.

**Q: How often is the catalog updated?**  
A: Movies are refreshed every 5 minutes from r/movieleaks.

**Q: Does this work on all devices?**  
A: Yes! Works on Stremio Desktop, Web, Android, and iOS.

---

**Note**: This repository is for issue tracking only. The source code is in a private repository.

Made with ❤️ for the Stremio community | v1.4.0
