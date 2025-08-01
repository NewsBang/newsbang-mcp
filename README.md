# Newsbang MCP

**Your Intelligent Media Command Platform**

Newsbang MCP is a powerful Model Context Protocol (MCP) server that provides access to real-time news intelligence through three essential tools:

## 🚀 Features

- **`get_today_top_news`** - Stay ahead with real-time top headlines
- **`search_news`** - Instantly access the stories that matter with intelligent search  
- **`get_news_deep_report_and_analysis`** - Go beyond the surface with deep-dive reports and expert analysis

*See the trends. Seek the opportunity.*  
*Newsbang – Transforming News into Value.*

## 📦 Installation & Configuration

Add the following configuration to your MCP settings:

**Note:** This MCP server has integrated authorization protocol. You will be prompted to log in when using the service for the first time to ensure secure access to news intelligence features.


```json
{
    "mcpServers": {
        "newsbang": {
            "command": "npx",
            "args": [
                "mcp-remote",
                "https://mcp.newsbang.com/mcp"
            ]
        }
    }
}
```
## 📋 Examples

### A. Investment Research Example
> **I'm heavily invested in NVIDIA. Can you search for recent NVIDIA news and provide deep analysis of the most important stories?**

**Explanation:** Your agent will:
1. Use `search_news` to find recent NVIDIA-related articles
2. Use `get_news_deep_report_and_analysis` to get detailed insights on key stories
3. Combine the information for comprehensive investment analysis

<img src="pics/demo.jpg" alt="demo" width="300" height="auto">

### B. Graduating Student Example
> **I'm a graduating college student. What news today is relevant to me**

**Explanation:** Your agent will:
1. Use `get_today_top_news` to get current headlines about job market, economy, and industry trends
2. Use `search_news` to find specific news about graduate employment, internships, or career opportunities
3. Use `get_news_deep_report_and_analysis` to get detailed insights on job market trends and career advice

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
