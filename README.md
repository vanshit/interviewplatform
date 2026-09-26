# Interview Manager — Free Interview Management System

**Interview Manager** is a free, standalone interview management platform for hiring managers, recruiters, and HR teams. Use it to organize interview rubrics, score candidate answers, capture evidence-based feedback, and produce a shareable PDF or editable Markdown evaluation report.

> **Project type:** Single-file, client-side HTML5 application  
> **Author:** [Vanshit Malhotra](https://in.linkedin.com/in/vanshitmalhotra)  
> **Cost:** Free to use  
> **Requirements:** A modern web browser; no account, installation, or backend required

## What this interview platform does

Interview Manager helps teams bring structure and consistency to candidate evaluation. Instead of scattered notes, interviewers can group questions by competency or interview rubric, rate each answer on a 0–10 scale, and record specific feedback alongside a final assessment.

It can be used as a lightweight **interview management system**, interview scorecard, candidate evaluation tool, or recruitment workflow aid for technical and non-technical interviews.

## Features

- **Interview rubrics:** Add as many rubric categories as needed, such as communication, problem solving, role expertise, leadership, or culture contribution.
- **Up to five questions per rubric:** Keep each rubric focused and easy to review.
- **0–10 question ratings:** Rate an answer using a slider; new questions start at 0.
- **Question-level feedback:** Document evidence, strengths, concerns, and follow-up points for each response.
- **Rubric-level feedback:** Add a summary for every interview competency or section.
- **Candidate details:** Record the candidate's name, years of experience, and interview difficulty.
- **Overall interview feedback:** Capture a final summary and recommendation at the end of the assessment.
- **PDF report:** Generate a themed, paginated PDF with ratings and feedback, suitable for sharing or archiving.
- **Markdown report:** Download an editable `.md` report that is easy to copy, version, or use in documentation.
- **Choose report formats:** Select PDF, Markdown, or both in the report dialog. Both formats are unchecked by default.
- **Light and dark themes:** Switch between accessible light and dark dashboard appearances.
- **Responsive liquid-glass interface:** A modern, translucent dashboard design that adapts to desktop and mobile screens.
- **Clear workspace:** Clear the current evaluation from the page when beginning a new assessment.
- **Privacy-friendly, browser-based operation:** The application has no server connection and does not submit interview details to a service.

## How to use Interview Manager

1. Open `interview-manager.html` in a modern browser.
2. Enter the candidate name, years of experience, and interview difficulty.
3. Select **Add interview rubric** and name the competency or evaluation area.
4. Add up to five questions to that rubric.
5. Move each rating slider from 0 to 10 and enter question feedback.
6. Add the overall feedback for each rubric.
7. Enter an overall interview summary and recommendation at the end.
8. Select **Generate report** at the top or **Save and Generate Report** at the bottom.
9. Choose PDF, Markdown, or both formats, then select **Generate selected** to download the report(s).

Use **Clear** to remove the current in-page interview data. The app is deliberately standalone: it does not currently provide user accounts, a shared database, autosave, or cross-device syncing. The interview data is held in the open page and is cleared when the page is refreshed or closed, so download the report before leaving the page.

## Run locally

No build step or package installation is required.

- Double-click `interview-manager.html`, or
- Open it from your browser using **File → Open**, or
- Serve the project folder from any static web host.

All core page styling, interface behavior, and PDF/Markdown report generation are included in the HTML file. The report generator uses client-side JavaScript and does not require a PDF library or an external service.

## Files

- `interview-manager.html` — Complete standalone interview evaluation application.
- `README.md` — Project overview, features, usage guide, and search optimization notes.

## Search and SEO information

The application page includes an SEO-oriented title and meta description, a concise introduction, social sharing metadata, crawl directives, and `SoftwareApplication` structured data describing the product and its features. This README uses relevant search phrases naturally, including **free interview management platform**, **interview management system**, **interview management software**, **interview scorecard**, **candidate evaluation**, **interview rubric**, **recruitment tools**, and **HR platforms**.

### Recommended steps before publishing

On-page SEO is only one part of search visibility. Search engines determine indexing and rankings independently, and no keyword list or metadata can guarantee a top position. When deploying this project publicly:

1. Use a stable, public HTTPS URL and ensure that search crawlers can access the page.
2. Add a canonical URL for the final hosted page and update Open Graph metadata with the live URL and a suitable preview image.
3. Publish a `robots.txt` file and XML sitemap for the website, then submit the sitemap in Google Search Console and Bing Webmaster Tools.
4. Check the live page with Google Search Console URL Inspection and Google's Rich Results Test; resolve crawl, mobile usability, and structured-data issues.
5. Keep the title and description unique and accurate. Write useful, original content for interviewers rather than repeating keyword phrases unnaturally.
6. Build relevant links from legitimate HR, recruiting, hiring, and product resources. Avoid paid link schemes and automated keyword stuffing.
7. Measure organic visits and search queries after launch, then improve the page based on real search intent and user feedback.

The project is a browser-based interview tool, not a hosted HR information system: it currently has no candidate database, collaboration layer, ATS integration, authentication, or recruitment analytics. Describe it accurately when publishing so prospective users know what it does and what it does not do.

## Suggested search phrases

These are descriptive topics for discovery, not ranking guarantees:

- Free interview management platform
- Free interview management system
- Interview management software for hiring teams
- Candidate evaluation and interview feedback tool
- Interview rubric and scorecard template
- Structured interview questions and candidate scoring
- Recruitment tools for HR professionals
- Human resource platforms and hiring workflow tools
- Interview assessment report generator

## Creator

Created by [Vanshit Malhotra](https://in.linkedin.com/in/vanshitmalhotra).
