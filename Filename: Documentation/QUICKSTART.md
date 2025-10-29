# 🚀 5-Minute Setup Guide

## What You'll Need (All Free)
- **n8n account** - [n8n.io](https://n8n.io) (free tier)
- **Google AI API key** - [makersuite.google.com](https://makersuite.google.com)
- **Anthropic API key** - [console.anthropic.com](https://console.anthropic.com) ($5 free credit)
- **DeepSeek API key** - [platform.deepseek.com](https://platform.deepseek.com) (very cheap)
- **GitHub account** - [github.com](https://github.com) (free)

## Step 1: Get n8n (2 minutes)
1. Go to [n8n.io](https://n8n.io)
2. Click "Get Started Free" 
3. Create account or use cloud version
4. You'll see your n8n dashboard

## Step 2: Get API Keys (3 minutes)

### Google AI API (Free)
1. Visit [Google AI Studio](https://makersuite.google.com)
2. Sign in with Google account
3. Click "Get API key"
4. Copy the API key

### Anthropic API ($5 Free Credit)
1. Visit [Anthropic Console](https://console.anthropic.com)
2. Create account
3. Go to "Get API Key"
4. Copy the key - you get $5 free credit

### DeepSeek API (Very Cheap)
1. Visit [DeepSeek Platform](https://platform.deepseek.com)
2. Sign up and verify email
3. Go to "API Keys"
4. Create new key and copy it

### GitHub Personal Token
1. Go to [GitHub Settings > Tokens](https://github.com/settings/tokens)
2. Click "Generate new token"
3. Select "repo" scope
4. Generate and copy the token

## Step 3: Import Workflow (1 minute)
1. In n8n, click "+ Workflow"
2. Click "Import from file"
3. Select the `workflow.json` from this repository
4. Click "Import" - you'll see the workflow with all nodes

## Step 4: Add Credentials (2 minutes)
1. In n8n, go to Settings → Credentials
2. Add each credential:

**Google AI API:**
- Type: "Google AI API"
- API Key: [your Google AI key]

**Anthropic API:**
- Type: "HTTP Header Auth" 
- Name: "Anthropic API"
- Headers: `x-api-key` = [your Anthropic key]

**DeepSeek API:**
- Type: "HTTP Header Auth"
- Name: "DeepSeek API" 
- Headers: `Authorization` = `Bearer [your DeepSeek key]`

**GitHub OAuth:**
- Type: "OAuth2 API"
- Use GitHub OAuth2 setup

## Step 5: Configure & Run (1 minute)
1. In the workflow, find the "⚙️ CONFIG" node
2. Click it and edit:
   - **idea**: Your project idea
   - **projectName**: Name for your project
   - **githubOwner**: Your GitHub username
   - **githubRepo**: Repository to save to
3. Click "Execute Workflow"
4. Wait 20-30 minutes
5. Check your GitHub for the complete project!

## 🎯 Your First Project
Try this tested idea:
**"Build a Chrome extension that saves tweets to Notion with one click"**

Expected results:
- ✅ Complete Chrome extension code
- ✅ Notion integration API  
- ✅ Installation instructions
- ✅ Architecture documentation

**Cost:** ~$0.12 | **Time:** ~25 minutes

## ❓ Troubleshooting

**API Errors:**
- Check you have credits/balance
- Verify API keys are correct
- Ensure proper authentication type

**GitHub Errors:**
- Verify repository exists
- Check GitHub token has "repo" scope
- Ensure you have write access

**Workflow Stops:**
- Check each node for error messages
- Verify all credentials are set
- Ensure internet connection

## 📞 Support
- Check the troubleshooting guide
- Join our Discord community
- Email support: [Your Email]

---

**You're ready to build!** 🚀
