## [Projects](/portfolio/) | JobScraper

<a href="../images/jobscraper/home.png" class="glightbox">
<img src="../images/jobscraper/home.png"/>
</a>

**Project description:** Personal python automation app from July 2025 which I built to automate my daily routine of checking new job applications on different job boards.

**Why?**<br>
Default search/filters on LinkedIn/Glassdoor suck.
You always get some **unrelevant results** like 'DevOps Engineer' for 'Frontend Developer' search, need to use **multiple listings** like 'Fullstack Developer' vs 'Fullstack Engineer' manually checking **duplicates**, **cant filter** out unwanted companies or terms.<br>
See **[JobData](/portfolio/projects/jobdata)** for some job data analysis

**Tech Stack**: Python, ~~Selenium Webdriver~~ Playwright, Pandas, Gspread

## Highlights
- parallel scraping of multiple job board feed urls (currently only LinkedIn & Glassdoor support)
- automated LinkedIn login and scroll (saves and reuses browser_profile)
- custom filters for company,title search term,rating and salary blacklisting 
- persist individual job status/comment fields
- persist all jobs (old jobs get archived)
- grouping by company name (historical data)
- auto-highlight and auto-open new jobs without filters
- already applied filtering
- export to Google Sheet or CSV

## Gallery
<img src="../images/jobscraper/groups.png"/>
*Company grouping (historical data)*
<img src="../images/jobscraper/console_start.png"/>
*Start*
<img src="../images/jobscraper/console_finish.png"/>
*Finish*

