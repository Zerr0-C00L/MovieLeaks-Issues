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

**Movie Leaks** is a Stremio addon that catalogs HD movie releases from rlsbb.to, bringing them directly to your Stremio library.

### 🎬 Features

- **HD Movie Releases** - Automatically scraped from rlsbb.to (1080p, 720p, 4K)
- **IMDB Integration** - Extracts titles, years, and IMDB IDs automatically
- **Auto-updating Catalog** - New movies added daily
- **Rich Metadata** - Movie info, posters, ratings via Cinemeta
- **RPDB Integration** - Optional custom posters with RT scores (supporters only)
- **Two-Tier System**:
  - 🆓 **Free Tier**: 70 latest HD releases, no signup required
  - 💎 **Supporter Tier**: All movies + RPDB support

### 📦 Installation

**Free Tier (70 movies):**
```
https://movie-leaks.vercel.app
```

**Supporter Tier (all movies):**

1. Subscribe on Ko-fi: https://ko-fi.com/zeroq/membership
2. Receive your unique supporter code **instantly via email**
3. Install the addon (URL above)
4. Configure it with your supporter code
5. Unlock all movies! 🎉

### 💎 Become a Supporter

Support the project for **$5/month** and get:

- ✅ **All movies** (vs 70 free)
- ✅ **RPDB poster overlays** (bring your own free key from ratingposterdb.com)
- ✅ **Instant code delivery** via automated email
- ✅ **Priority support** for issues and requests
- ✅ **Future features** as they're developed
- ✅ Help keep the project alive!

**Subscribe here:** https://ko-fi.com/zeroq/membership

Codes auto-renew monthly with your subscription and are delivered instantly via email.

---

## 🛠️ Technical Details

- **Source**: rlsbb.to (HD movie releases)
- **Metadata**: Cinemeta API (official Stremio)
- **IMDB IDs**: Extracted from release pages in parallel
- **Updates**: Automated daily scraping
- **Hosting**: Vercel (serverless)
- **Caching**: 5-minute refresh cycle
- **Code Validation**: 30-day expiry with auto-renewal

### How It Works

1. Addon scrapes rlsbb.to "Recommended movies" widget
2. Fetches IMDB IDs from each movie's detail page (parallel batches)
3. Fetches proper movie info from Cinemeta using IMDB IDs
4. Applies RPDB posters for supporters (optional)
5. Serves catalog to Stremio

**Disclaimer**: This addon only provides catalog information. Actual streaming links come from other Stremio addons (Torrentio, MediaFusion, etc.). We don't host any content.

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
- ⭐ **Star the repository** to show your support
- 🐛 **Report bugs** to help improve quality
- 💬 **Share with friends** who use Stremio
- 📢 **Spread the word** on Reddit, Discord, etc.

Your support helps cover:
- Vercel hosting costs
- Development time
- Future features and improvements
- Server maintenance

---

## 📱 Community

- **Stremio Discord**: discord.gg/zNRf6YF
- **Reddit**: r/StremioAddons, r/Stremio
- **Ko-fi**: https://ko-fi.com/zeroq/membership

---

## 🔗 Links

- **Install Addon**: https://movie-leaks.vercel.app
- **Become a Supporter**: https://ko-fi.com/zeroq/membership
- **Free RPDB Key**: https://ratingposterdb.com
- **Source**: rlsbb.to

---

## 📋 Roadmap

Upcoming features (vote for your favorites in Issues!):

- [ ] More filter options
- [ ] Genre categories
- [ ] Quality indicators (1080p/720p/4K badges)
- [ ] Release date filtering
- [ ] Search functionality
- [ ] Custom lists
- [ ] Watchlist integration

Have another idea? Create a Feature Request!

---

## ❓ FAQ

**Q: Is this legal?**  
A: Yes. We're a catalog aggregator for publicly available movie information. We don't host any content or provide streams.

**Q: Why charge for the full catalog?**  
A: The free tier (70 movies) is generous! Supporters help cover hosting costs, development time, and maintenance. It's optional - enjoy the free version!

**Q: Do I need an RPDB key?**  
A: No, it's completely optional. RPDB adds custom posters with RT scores, but requires a supporter code to use.

**Q: How do I get an RPDB key?**  
A: Free at ratingposterdb.com - create an account and generate an API key.

**Q: What if I cancel my Ko-fi subscription?**  
A: Your code will expire and you'll return to the free tier (70 movies). No hard feelings!

**Q: Can I share my supporter code?**  
A: Codes are for personal use only. Sharing may result in deactivation.

**Q: How often is the catalog updated?**  
A: Movies are refreshed every 5 minutes from rlsbb.to.

**Q: Does this work on all devices?**  
A: Yes! Works on Stremio Desktop, Web, Android, and iOS.

**Q: Where do streams come from?**  
A: This is a catalog-only addon. Install streaming addons like Torrentio, MediaFusion, or Comet for actual streams.

---

**Note**: This repository is for issue tracking only. The source code is in a private repository.

Made with ❤️ for the Stremio community | v2.0.0
