# Job Scraper — Daily London Search

Automated daily job search reports for QA / BA / Supply Chain / ERP roles in London.

Reports are generated each morning and saved in the `reports/` folder, named `daily-job-search-YYYY-MM-DD.md`.

**Target roles:** QA Analyst · Business Analyst · Supply Chain Analyst · ERP Consultant · Test Automation Engineer
**Location:** London / Greater London / Hybrid / Remote UK
**Salary:** £45,000–£75,000+

## Sources (updated 4 July 2026)

**Job boards:** LinkedIn, Indeed UK, NHS Jobs, Civil Service Jobs, Falcon GRP, LocalGov Jobs, WMJobs
**Company career pages:** ~50 companies including Anaplan, KPMG, EY, Accenture, Capgemini, HSBC, Amazon, SAP, Oracle, Coupa, CEVA Logistics, and others — see the scheduled task config for the full list.

Reed, Totaljobs, Robert Walters, JobServe, Welcome to the Jungle, Remote Rocketship, Robert Half, DSJ Global, Bramwith Consulting, Cedar Recruitment, Handle Recruitment, People First, and Lime Talent Group were removed from the active source list on 4 July 2026.

### Known source issues
See the latest report in `reports/` for a full write-up, but in short: Indeed UK and WMJobs are currently blocked (403), Civil Service Jobs sits behind a gov.uk bot-check wall, and NHS Jobs / LocalGov Jobs / Falcon GRP / some company career pages (Anaplan, Amazon) return unfiltered or empty results because of missing query params or client-side rendering. LinkedIn is the most reliable source at present.
