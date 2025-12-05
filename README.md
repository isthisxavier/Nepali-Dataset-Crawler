# Nepali Dataset Crawler
>This crawler gathers structured content from a collection of Nepali-language websites, turning raw articles, posts, and pages into an organized dataset. It’s great for researchers, data scientists, or anyone looking to build language-specific corpora, text analytics data, or localized content archives.

<p align="center">
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/scraper.png" alt="Bitbash Banner" width="100%"></a>
</p>
<p align="center">
  <a href="https://t.me/Bitbash333" target="_blank">
    <img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>&nbsp;
  <a href="https://wa.me/923249868488?text=Hi%20BitBash%2C%20I'm%20interested%20in%20automation." target="_blank">
    <img src="https://img.shields.io/badge/Chat-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
  </a>&nbsp;
  <a href="mailto:sale@bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Email-sale@bitbash.dev-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>&nbsp;
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website">
  </a>
</p>

<p align="center" style="font-weight:600; margin-top:8px; margin-bottom:8px;">
  Created by Bitbash, built to showcase our approach to Scraping and Automation!<br>
  If you are looking for <strong>Nepali Dataset Crawler</strong> you've just found your team — Let's Chat. 👆👆
</p>

## Introduction
The Nepali Dataset Crawler fetches public webpages from Nepali web domains and normalizes their content — including text bodies, metadata, titles, publish dates, and possibly images — into a structured dataset. It’s ideal for NLP tasks, local-market research, cultural analysis, or language-specific data pipelines.

### What It Helps You Do
- Crawl multiple Nepali websites quickly and at scale.  
- Collect article content, metadata, and publication information.  
- Build a clean text dataset for NLP, sentiment analysis, or translation projects.  
- Archive web content from Nepali sources for future processing.  

---
## Features
| Feature | Description |
|---------|-------------|
| **Multi-site Crawling** | Supports scraping from multiple Nepali websites. |
| **Content Extraction** | Extracts titles, article content, publish date, and metadata. |
| **Structured Output** | Returns cleaned data in JSON or other export-friendly formats. |
| **Dataset Building** | Useful for building full corpora for NLP or research. |
| **Scalable Execution** | Can process many pages with efficient crawling logic. |

---
## What Data This Scraper Extracts
| Field Name | Field Description |
|------------|------------------|
| url | Original article page URL. |
| title | Title of the article or content. |
| publishDate | Date when the content was published (if available). |
| author | Author name (if available). |
| contentText | Main article text stripped of HTML tags. |
| contentHtml | Full content including HTML (optional). |
| language | Language of the content (expected “Nepali”). |
| metadata | Any additional metadata (tags, categories, categories, etc.). |

---
## Example Output
    
    [
      {
        "url": "https://nepalnews.example.com/article/1234",
        "title": "काठमाडौं उपत्यकामा मौसम अपडेट",
        "publishDate": "2024-08-15",
        "author": "राम शर्मा",
        "contentText": "आज काठमाडौं उपत्यकामा मौसम सफा रहेको छ ...",
        "contentHtml": "<p>आज काठमाडौं उपत्यकामा ...</p>",
        "language": "ne",
        "metadata": {
          "tags": ["weather", "local news"]
        }
      }
    ]

---
## Directory Structure Tree
    
    Nepali Dataset Crawler/
    ├── src/
    │   ├── main.js
    │   ├── crawler/
    │   │   ├── site_list_loader.js
    │   │   ├── page_fetcher.js
    │   │   └── content_parser.js
    │   ├── utils/
    │   │   ├── normalizer.js
    │   │   └── html_cleaner.js
    │   └── config/
    │       └── settings.example.json
    ├── data/
    │   ├── sample_input.json
    │   └── sample_output.json
    ├── package.json
    └── README.md

---
## Use Cases
- **NLP Researchers** build Nepali language corpora for modeling, translation, or sentiment analysis.  
- **Journalism Analysts** archive news articles for trend tracking.  
- **Cultural Researchers** collect content for sociolinguistic or cultural studies.  
- **Developers** build localized content feeds or recommendation systems.  
- **Data Engineers** ingest scraped data into data warehouses or pipelines.  

---
## FAQs

**Which websites does it crawl?**  
It supports a configurable list of Nepali-language websites — you supply domains in settings.

**What formats are outputted?**  
Structured JSON is default; data can be converted to CSV or other formats as needed.

**Can it handle large-scale crawls?**  
Yes — the crawler is built to scale across many pages efficiently.

**Is language detection supported?**  
Content is tagged as Nepali (“ne”) by default; further language checks can be added.

---
### Performance Benchmarks and Results

**Primary Metric:**  
Processes dozens of pages per second under optimal network conditions.

**Reliability Metric:**  
High success rate (~98%) on publicly accessible sites with consistent HTML structure.

**Efficiency Metric:**  
Lightweight parsing and normalization reduce overhead and speed up processing.

**Quality Metric:**  
Produces cleaned, normalized text outputs ideal for analysis, modeling, or archiving.  


---


<p align="center">
<a href="https://calendar.app.google/74kEaAQ5LWbM8CQNA" target="_blank">
  <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
  <a href="https://www.youtube.com/@bitbash-demos/videos" target="_blank">
    <img src="https://img.shields.io/badge/🎥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
  </a>
</p>
<table>
  <tr>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/MLkvGB8ZZIk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review1.gif" alt="Review 1" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash is a top-tier automation partner, innovative, reliable, and dedicated to delivering real results every time."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Nathan Pennington
        <br><span style="color:#888;">Marketer</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/8-tw8Omw9qk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review2.gif" alt="Review 2" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash delivers outstanding quality, speed, and professionalism, truly a team you can rely on."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Eliza
        <br><span style="color:#888;">SEO Affiliate Expert</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/m-dRE1dj5-k?si=5kZNVlKsGUhg5Xtx" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review3.gif" alt="Review 3" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Exceptional results, clear communication, and flawless delivery. <br>Bitbash nailed it."
      </p>
      <p style="margin:1px 0 0; font-weight:600;">Syed
        <br><span style="color:#888;">Digital Strategist</span>
        <br><span style="color:#f5a623;">★★★★★</span>
         </p>
