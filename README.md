# Le Monde Scraper
>This scraper extracts news articles and content from Le Monde — the French newspaper — and outputs structured data including titles, publication dates, authors, article text, and related media. It’s useful for researchers, analysts, or developers who want a clean news dataset from a major European media source.

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
  If you are looking for <strong>Le Monde Scraper</strong> you've just found your team — Let's Chat. 👆👆
</p>

## Introduction
The Le Monde Scraper crawls Le Monde’s website to collect news articles and related metadata. It transforms the newspaper’s online content into a structured dataset suitable for analysis, archiving, or research applications. Whether you’re building a news aggregator, performing sentiment analysis, or curating a media archive — this tool simplifies the extraction process.

### What It Helps You Do
- Automatically fetch recent and historical articles from Le Monde.  
- Extract article metadata such as title, author, publish date, and article body.  
- Download full content, including images and media links, in a structured JSON format.  
- Build archives or feed data into analytics pipelines for media analysis.

---
## Features
| Feature | Description |
|--------|-------------|
| **Full Article Extraction** | Captures titles, authors, publish dates, body text, and media. |
| **Metadata Capture** | Extracts article metadata like tags, sections, and publication timestamps. |
| **Media Asset Extraction** | Retrieves image URLs and other embedded media from articles. |
| **Structured Output** | Returns clean JSON output suitable for export, storage, or analysis. |
| **Scalable Crawling** | Supports scraping multiple pages and articles automatically. |

---
## What Data This Scraper Extracts
| Field Name | Field Description |
|------------|------------------|
| url | The article URL. |
| title | Article headline. |
| author | Author byline. |
| publishDate | Date and time when the article was published. |
| contentHtml | Full article content in HTML format. |
| contentText | Plaintext version of the article body. |
| images | Array of image URLs included in the article. |
| tags | Associated tags or categories (if available). |

---
## Example Output
    
    [
      {
        "url": "https://www.lemonde.fr/2025/12/05/politique/...",
        "title": "Nouvelles politiques en Europe",
        "author": "Jean Dupont",
        "publishDate": "2025-12-05T08:30:00Z",
        "contentText": "L’Union européenne a annoncé ...",
        "contentHtml": "<p>L’Union européenne a annoncé ...</p>",
        "images": [
          "https://www.lemonde.fr/image1.jpg",
          "https://www.lemonde.fr/image2.jpg"
        ],
        "tags": ["politique", "europe"]
      }
    ]

---
## Directory Structure Tree
    
    Le Monde Scraper/
    ├── src/
    │   ├── main.js
    │   ├── crawler/
    │   │   ├── listing_scraper.js
    │   │   └── article_scraper.js
    │   ├── utils/
    │   │   ├── html_parser.js
    │   │   └── normalizer.js
    │   └── config/
    │       └── settings.example.json
    ├── data/
    │   └── sample_output.json
    ├── package.json
    └── README.md

---
## Use Cases
- **Researchers** analyzing media coverage, language trends, or political reporting.  
- **News Aggregators** building custom feeds from French-language media.  
- **Data Scientists** using article text for NLP tasks, sentiment analysis, or summarization.  
- **Archivists** preserving news content and metadata for future reference.  
- **Developers** integrating news data into apps or dashboards requiring structured media sources.  

---
## FAQs

**Does it scrape pay-walled content?**  
Only publicly accessible articles — pay-walled content may not always be retrievable.  

**Can I fetch old articles in bulk?**  
Yes, by specifying a list of URLs or crawling through archive pages.  

**What output formats are supported?**  
JSON export by default; can be converted to CSV or other formats as needed.  

**Are media assets included?**  
Yes — image URLs and other embedded media are captured when available.  

---
### Performance Benchmarks and Results

**Primary Metric:**  
Handles dozens of articles per minute depending on site structure and network speed.

**Reliability Metric:**  
Consistently extracts fully structured article data for non-blocked pages.

**Efficiency Metric:**  
Optimized parsing ensures minimal overhead, even on extensive crawls.

**Quality Metric:**  
Produces clean, normalized JSON records — making data ready for ingestion or analysis pipelines.


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
