# Newsbang MCP

**Your Intelligent Media Command Platform**

Newsbang MCP is a powerful Model Context Protocol (MCP) server that provides access to real-time news intelligence through three essential tools:

## 🚀 Features

- **`get_today_top_news`** - Stay ahead with real-time top headlines
- **`search_news`** - Instantly access the stories that matter with intelligent search  
- **`get_news_deep_report_and_analysis`** - Go beyond the surface with deep-dive reports and expert analysis

*See the trends. Seek the opportunity.*  
*Newsbang – Transforming News into Value.*

## 📦 1. Installation & Configuration

Add the following configuration to your MCP settings:

```json
{
    "mcpServers": {
        "newsbang": {
            "command": "npx",
            "args": [
                "mcp-remote",
                "https://www.newsbang.com/mcp",
                "--header",
                "Authorization:${AUTH_HEADER}"
            ],
            "env": {
                "AUTH_HEADER": "Bearer xxxxxxxxx"
            }
        }
    }
}
```

## 🔑 2. Getting Your API Key

To use Newsbang MCP, you'll need to obtain your API key:

👉 **[Get your API key here with one more click](https://www.newsbang.com/mcp/usage)**

Replace `xxxxxxxxx` in the configuration above with your actual API key.


---

## 📱 Mobile App

**Download NewsBang APP for the Best AI News Experience**

Get our mobile app for a smoother, smarter news reading experience!

<div align="left">
  <table style="border: none; border-collapse: collapse; margin: 20px 0;">
    <tr>
      <td style="border: none; padding: 10px; text-align: center;">
        <a href="https://apps.apple.com/us/app/newsbang-ai-news-insight/id6736856545">
          <img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store" height="60">
        </a>
      </td>
      <td style="border: none; padding: 10px; text-align: center;">
        <a href="https://play.google.com/store/apps/details?id=com.newsbang">
          <img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" alt="Get it on Google Play" height="60">
        </a>
      </td>
    </tr>
  </table>
</div>

