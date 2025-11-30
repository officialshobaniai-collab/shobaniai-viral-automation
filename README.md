# 🚀 ShobaniAI Viral Automation - 24/7 Instagram Content Generator

![Status](https://img.shields.io/badge/Status-Active-success)
![Automated](https://img.shields.io/badge/Automated-24%2F7-blue)
![Posts](https://img.shields.io/badge/Posts-3%2Fday-orange)

## 🎯 What This Does

This repository automatically generates and posts **3 viral AI-powered videos daily** to [@officialshobaniai](https://www.instagram.com/officialshobaniai/) on Instagram.

### ✨ Features
- 🤖 **AI-Generated Videos**: Uses Google Veo 3.0 for 4K video generation
- 🔥 **Viral Optimization**: Scroll-stopping hooks, trending formats, FOMO triggers
- 💰 **INR Focus**: Prominently displays earnings in Indian Rupees
- 📱 **Instagram Reels**: Optimized for maximum engagement
- ⏰ **Automated Schedule**: Posts at 6 AM, 2 PM, and 10 PM IST daily
- 🎨 **ShobaniAI Branding**: Logo included in every video

### 📅 Posting Schedule
- **6:00 AM IST** - Morning post (catch early scrollers)
- **2:00 PM IST** - Afternoon post (lunch break traffic)
- **10:00 PM IST** - Night post (peak engagement time)

---

## 🛠️ Setup Instructions

### 1️⃣ Add Composio API Key (REQUIRED)

To enable automation, you need to add your Composio API key as a GitHub secret:

1. **Get Your API Key**:
   - Go to [https://composio.dev/settings](https://composio.dev/settings)
   - Copy your API key

2. **Add to GitHub**:
   - Go to this repository's **Settings** → **Secrets and variables** → **Actions**
   - Click **"New repository secret"**
   - Name: `COMPOSIO_API_KEY`
   - Value: Paste your API key
   - Click **"Add secret"**

### 2️⃣ Enable GitHub Actions

- Go to the **Actions** tab in this repository
- If prompted, click **"I understand my workflows, go ahead and enable them"**

### 3️⃣ Done! ✅

The automation is now active and will:
- ✅ Run automatically 3 times daily
- ✅ Generate viral content with AI
- ✅ Post directly to Instagram
- ✅ Continue running 24/7 forever (free!)

---

## 🎬 How to Test Manually

Want to test before waiting for the schedule?

1. Go to **Actions** tab
2. Click **"ShobaniAI Viral Agent 24/7"** workflow
3. Click **"Run workflow"** dropdown
4. Click green **"Run workflow"** button

This will immediately generate and post 1 viral video!

---

## 📊 Monitoring & Logs

### View Workflow Runs
- Go to **Actions** tab to see all runs
- Click any run to view detailed logs
- Each run shows:
  - ✅ Success/failure status
  - 📝 Video generation logs
  - 📱 Instagram posting status
  - 🔗 Links to posted content

### Success Indicators
Look for these in the logs:
```
✅ Viral content posted to Instagram!
```

---

## 🔧 Customization

Want to change the schedule or content type?

### Change Posting Times
Edit `.github/workflows/shobaniai-viral.yml`:

```yaml
schedule:
  - cron: '30 0 * * *'   # 6 AM IST (change time here)
  - cron: '30 8 * * *'   # 2 PM IST (change time here)
  - cron: '30 16 * * *'  # 10 PM IST (change time here)
```

**Cron format**: `minute hour * * *` (UTC timezone)
- Convert IST to UTC: IST - 5:30 = UTC
- Example: 6 AM IST = 0:30 UTC = `30 0 * * *`

### Change Content Type
By default, content type is random (Educational, Promotional, Motivational, Trending).

To force a specific type, modify the curl command in the workflow file.

---

## 🎯 Recipe Details

**Recipe ID**: `rcp_WsEkvI_OdoZP`  
**Recipe Name**: ShobaniAI Viral IG Agent  
**Recipe URL**: [View in Rube](https://rube.app/recipes/547bfabb-7392-404e-b487-312c6944e1fe)

### What It Does:
1. 🤖 Generates viral content idea with LLM
2. 🎬 Creates 4K video with Google Veo 3.0
3. 💰 Features INR earnings prominently
4. 📱 Posts to Instagram as Reel
5. 🎨 Includes ShobaniAI logo and branding

---

## ❓ Troubleshooting

### Workflow not running?
- ✅ Check if GitHub Actions are enabled (Actions tab)
- ✅ Verify `COMPOSIO_API_KEY` secret is added correctly
- ✅ Ensure repository is not private (Actions free tier)

### Posts failing?
- ✅ Check Instagram connection is active in Composio
- ✅ Verify recipe is working by running manually first
- ✅ Check workflow logs for specific error messages

### Want to stop automation?
- Go to **Actions** tab
- Click **"ShobaniAI Viral Agent 24/7"**
- Click ••• menu → **"Disable workflow"**

---

## 📈 Expected Results

With this automation, you can expect:
- ✅ **90+ videos/month** automatically generated and posted
- ✅ **Consistent posting schedule** (no manual work)
- ✅ **Viral-optimized content** with AI
- ✅ **Zero cost** (GitHub Actions free tier)
- ✅ **24/7 operation** (no server maintenance)

---

## 🔗 Links

- 📱 Instagram: [@officialshobaniai](https://www.instagram.com/officialshobaniai/)
- 🤖 Rube AI: [rube.app](https://rube.app)
- 📚 Recipe: [View Recipe](https://rube.app/recipes/547bfabb-7392-404e-b487-312c6944e1fe)
- 🛠️ Composio: [composio.dev](https://composio.dev)

---

## 🙌 Built With

- **Rube AI** - Workflow automation
- **Composio** - App integrations
- **Google Veo 3.0** - AI video generation
- **Instagram API** - Content posting
- **GitHub Actions** - 24/7 scheduling

---

Made with ❤️ for ShobaniAI
