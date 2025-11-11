# 🚀 AI-Powered Content Ideas Generator (n8n + Gemini + Notion)

This workflow automatically pulls trending AI-related Reddit discussions, sends them to Google Gemini to create five creative post ideas, and saves them in a Notion database.

### ⚙️ How It Works
1. **Daily Trigger** runs each morning.  
2. **Reddit Nodes** fetch top discussions from chosen topics.  
3. **Gemini Node** generates content ideas for each trend.  
4. **Notion Node** logs the ideas with date and category.  

### 🧰 Tools Used
- n8n (automation platform)  
- Reddit API (data source)  
- Google Gemini 2.5 Pro (AI model)  
- Notion API (database)  

### 🧩 Setup
1. Import `ai-content-ideas-generator.json` into n8n.  
2. Create your own credentials (Reddit OAuth2, Gemini API, Notion integration).  
3. Replace placeholders like `<YOUR_NOTION_DATABASE_ID>` inside the Set node.  
4. Run or schedule the workflow.


