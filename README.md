# AI News → Social Media Content Agent

## Overview
This project is an **AI-powered content automation system** that converts the latest AI news into ready-to-post social media content.

The workflow automatically:
- Finds the **latest AI news**
- Generates an **Instagram Reel script**
- Creates a **LinkedIn post**
- Generates an **AI image prompt**
- Sends the content pack via **email**

The automation is built using **Make.com** and **Google Gemini AI**.

---

## **Problem**

Content creators and AI enthusiasts struggle to keep up with rapidly evolving AI news and convert it into engaging content quickly.

Creating:

- Reel scripts  
- LinkedIn posts  
- Visual assets  

can take **30–60 minutes per news item**.

This automation reduces that time to **under 1 minute**.

---

## **Solution**

An **AI content agent** that automatically transforms news articles into social media-ready content.

The system:

1. Fetches the **latest AI news**
2. Uses **AI to summarize and transform it into engaging content**
3. Generates **structured output**
4. Delivers it via **email**

---

## **Workflow Architecture**

```
Scheduler
   ↓
News Source / RSS Feed
   ↓
Gemini AI (Content Generation)
   ↓
Parse Structured Output
   ↓
Generate Image Prompt
   ↓
Send Email (Content Pack)
```

---

## **Features**

### **Automated News Processing**
Fetches the latest AI news from a news source or API.

### **AI Content Generation**
Using **Gemini**, the system generates:

- Instagram Reel script (Hinglish creator style)
- LinkedIn caption
- AI image prompt

### **Structured Output**
The AI output is formatted in **HTML** for easy email delivery.

### **Email Delivery**
A daily content pack is automatically delivered via **Gmail**.

---

## **AI Prompt Design**

The prompt instructs Gemini to act as a **top-tier content strategist** and produce:

1. Instagram Reel Script  
2. LinkedIn Post  
3. News source reference  

The script follows a **creator-style storytelling format**.

---

## **Example Output**

### **Instagram Reel Script**

"AI just changed the game again.

A new breakthrough just dropped and it might change how startups build products forever.

Here’s what’s happening..."

---

### **LinkedIn Post**

🤯 AI innovation is accelerating faster than ever.

A new development just dropped that could redefine how startups build AI products.

Key highlights:

- Faster model deployment  
- Lower infrastructure costs  
- New AI capabilities  

What do you think about this shift?

---

## **Tools Used**

- **Automation Platform:** Make.com  
- **AI Model:** Google Gemini  
- **Email Service:** Gmail  

---

## **Project Structure**

```
ai-news-content-agent/
│
├── README.md
├── workflow-diagram.png
└── prompts/
    └── content_generation_prompt.txt
```

---

## **Future Improvements**

Planned improvements:

- Multi-news analysis  
- Viral topic selection  
- Automatic image generation  
- Direct posting to LinkedIn  
- Social media analytics integration  

---

## **Use Cases**

This system can be used by:

- AI content creators  
- Tech newsletter writers  
- Social media managers  
- Startup founders  
- Product managers  

---

## **Author**

**Tarun Kumar**

AI Automation Builder | Aspiring Product Manager
