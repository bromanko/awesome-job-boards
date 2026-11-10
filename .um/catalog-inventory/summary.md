# Catalog review inventory

**48 proposed changes · 54 uncertain · 329 unresolved keeps**

579 entries researched. 148 saved reviews for recurring runs.

Research recommendations from the initial Opus review. The full set has not passed prior-discussion or patch validation. Proposed diffs are previews, not approved patches. Nothing was applied or submitted.

Catalog: `5acdc0ef03e87566684279c7a6ed419b5947642e` · README SHA-256: `3c6b05510ebe5e0030bd969b6daa0e33895d21c8340496ad3319613711476bab`

## Proposed changes

<h3>Autojob — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -68,7 +68,7 @@
 - [PrepNPlaced](https://www.prepnplaced.com/ats-resume-checker) - Free ATS resume check that scores your resume against a specific job description.
 - [CVExpert](https://cvexpert.com/) - AI-assisted career coaching, CV tailoring, job tracking, application review, and networking in one workspace.
 - [GetMattered](https://getmattered.com/) - Submits on the employer's own careers page and reports back the status their ATS returns, including failures.
-- [Autojob](https://autojob.org/jobs) - Job board with 20,000+ jobs and an auto-apply feature.
+- [Autojob](https://autojob.org/jobs) - Job board aggregating listings from employer job boards, with an auto-apply feature.
 - [Resume Roaster](https://resume.roastlabai.com) - AI resume roast with ATS scoring that grades your resume against a job description and flags missing keywords.
 - [Cviya](https://cviya.com) - A fully customizable, watermark-free resume builder featuring native RTL support and multilingual capabilities for global professionals.
 - [ResumeInvited](https://resumeinvited.com/) - Browser-based resume builder with professional templates, live preview, and PDF or editable Word downloads. Currently free without sign-up; drafts are saved locally.
```

<details>
<summary>Evidence and limitations</summary>

<p>Autojob is still a job board with auto-apply. The listed count is out of date: the site now shows 19,357 jobs, below the claimed &#x27;20,000+&#x27;. The count changes over time, so durable wording without a number is better.</p>

<p>https://autojob.org/jobs — Title &#x27;Jobs | Autojob Job Board&#x27;. Meta: &#x27;19,357 jobs from employer job boards. Upload your resume and automatically apply to the jobs you select.&#x27; Page header: &#x27;19,357+ jobs on Autojob&#x27;.</p>

<p>Caveats: Job counts fluctuate. The count could go back above 20,000, which is why the update drops the number instead of replacing it.</p>

<p>Independent source check: Official page shows 19,357 listings, below the catalog claim of 20,000+. Removing a volatile exact count is supported, but this is a weak outreach example because the count can change.</p>

<p>https://autojob.org/jobs — Official job-board page displayed 19,357+ jobs and an auto-apply feature.</p>

</details>

<h3>Headcount Labs — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -82,7 +82,7 @@
 - [JobEmerge](https://www.jobemerge.work) - AI career workspace with a free tier for resumes, job-fit analysis, text-based interview practice, and application tracking.
 - [Mock Interview Copilot](https://mic.zapxlabs.com) - Mock interview practice with an AI interviewer that asks questions from your CV and the job description, scores each answer and measures pace and filler words; free trial, or free with your own AI provider keys.
 - [speaking.app](https://speaking.app/behavioral-interview-practice) - AI behavioral interview practice with feedback on answer structure, pacing, and filler words.
-- [Headcount Labs](https://headcountlabs.com) - Job postings API and MCP server with about 8.4 million open jobs from employer career sites, deduplicated; the first 100,000 records each month are free.
+- [Headcount Labs](https://headcountlabs.com) - Job postings API and MCP server with millions of deduplicated open jobs from employer career sites; the first 100,000 records each month are free.
 - [AI Job Search](https://github.com/ai-job-search-dev/ai-job-search) - Open-source AI job application framework built on Claude Code that runs locally to evaluate postings, tailor CVs, write cover letters, and prepare for interviews.
 - [FindAJobAI](https://findajobai.com) - Jobs read from 15,000+ company career boards (Greenhouse, Lever, Ashby, Workable and others) across the US and Europe, each scored 0-100 against your CV. Free plan and a free autofill Chrome extension.
 - [Hiretop ATS Resume Checker](https://hiretop.com/ats-resume-checker) - Free ATS check against a job description: shows the text the ATS extracts, missing keywords and which requirements your resume proves. No signup.
```

<details>
<summary>Evidence and limitations</summary>

<p>The product fits the entry (a jobs API and MCP server built from employer career sites, deduplicated, with 100,000 free records a month). The specific &#x27;about 8.4 million&#x27; figure is outdated and the official page contradicts itself: the title says 9M+ and the body says 7M+. Count-free wording is more durable.</p>

<p>https://headcountlabs.com/ — Title: &#x27;Jobs API and MCP server: 9M+ open jobs, 100K free&#x27;. Hero: &#x27;Jobs API and MCP server for 7M+ open job postings&#x27;. Stat block: &#x27;7M+ Open postings&#x27;. It says &#x27;read, merge and check every posting, so one real job appears once&#x27; and &#x27;Your first 100,000 records are free, every month.&#x27;</p>

<p>Caveats: The posting count changes daily.</p>

</details>

<h3>FindAJobAI — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -84,7 +84,7 @@
 - [speaking.app](https://speaking.app/behavioral-interview-practice) - AI behavioral interview practice with feedback on answer structure, pacing, and filler words.
 - [Headcount Labs](https://headcountlabs.com) - Job postings API and MCP server with about 8.4 million open jobs from employer career sites, deduplicated; the first 100,000 records each month are free.
 - [AI Job Search](https://github.com/ai-job-search-dev/ai-job-search) - Open-source AI job application framework built on Claude Code that runs locally to evaluate postings, tailor CVs, write cover letters, and prepare for interviews.
-- [FindAJobAI](https://findajobai.com) - Jobs read from 15,000+ company career boards (Greenhouse, Lever, Ashby, Workable and others) across the US and Europe, each scored 0-100 against your CV. Free plan and a free autofill Chrome extension.
+- [FindAJobAI](https://findajobai.com) - Jobs from company career pages and job boards (Greenhouse, Lever, Ashby and others) across the US and Europe, each scored 0-100 against your CV, with paid plans that apply for you. Free job matching and a free autofill Chrome extension.
 - [Hiretop ATS Resume Checker](https://hiretop.com/ats-resume-checker) - Free ATS check against a job description: shows the text the ATS extracts, missing keywords and which requirements your resume proves. No signup.
 - [LAYIQ](https://www.layiq.co) - Candidate-first job search workspace to find, score, and prioritize the roles worth your time, without sponsored listings or selling user data.
 - [The Briefed](https://www.thebriefed.co/) - Remote, onsite and hybrid jobs and internships in Pakistan, the US and worldwide, plus a free CV maker and ATS checker.
```

<details>
<summary>Evidence and limitations</summary>

<p>FindAJobAI is live and still scores jobs 0–100 against your CV, covers the US and Europe, pulls from Greenhouse/Lever/Ashby career pages, has a free autofill Chrome extension, and has a free tier for seeing matches. The &#x27;15,000+ company career boards&#x27; figure appears nowhere on current official pages, which state 16 ATS sources and about 519,700 open jobs. The product now centers on paid Autopilot auto-apply plans.</p>

<p>https://findajobai.com/en — Meta: &#x27;For job seekers in the US and Europe: AI finds the jobs you fit, scores each one 0–100&#x27;. The FAQ says &#x27;public job boards and company career pages (Greenhouse, Lever, Ashby and many more)&#x27;. Plans are Autopilot Basic/Plus/Ultra, $9.99–$99.99 a month. No &#x27;15,000&#x27; text appears.</p>

<p>https://findajobai.com/en/pricing — &#x27;open jobs right now, refreshed daily 519,700+&#x27;. It lists 16 &#x27;applicant tracking systems we read jobs from directly&#x27;. The FAQ answers &#x27;Is there a free plan? Yes. Seeing the jobs that match you is free&#x27;.</p>

<p>https://findajobai.com/en/extension — &#x27;The free FindAJobAI extension fills in application forms on Greenhouse, Lever, Ashby, Workable, SmartRecruiters, Workday and iCIMS&#x27;.</p>

<p>Caveats: The proposed wording mentions Autopilot as a clarification. A maintainer may prefer only to remove the unsupported count.</p>

</details>

<h3>Agentic Engineering Jobs — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -96,7 +96,7 @@
 
 ## AI
 
-- [Agentic Engineering Jobs](https://agentic-engineering-jobs.com) - Job board for engineers building agentic systems (RAG, AI agents, LLM-powered products, agent orchestration). Free to post, free to browse.
+- [Agentic Engineering Jobs](https://agentic-engineering-jobs.com) - Job board for engineers building agentic systems (RAG, AI agents, LLM-powered products, agent orchestration). Free to browse; paid job posts.
 - [AI Dev Jobs](https://aidevboard.com) - The specialized job board for AI/ML developers. 5000+ curated roles with salary data and a REST API for agents.
 - [AI Jobs](https://www.moaijobs.com/) - Find a job at a cutting-edge AI company. Filter by title, location, company, etc.
 - [AI Tech Suite](https://www.aitechsuite.com/jobs) - AI tools and jobs aggregator with over 20k tools and 5k jobs, updated daily.
```

<details>
<summary>Evidence and limitations</summary>

<p>The board is live and still fits the AI section: jobs for engineers who build AI agents, RAG pipelines, multi-agent systems and LLM products. However, &#x27;Free to post&#x27; is now false. The official post page charges $150 per listing. Browsing is free.</p>

<p>https://agentic-engineering-jobs.com/ — Meta: &#x27;The job board for engineers who build AI agents, RAG pipelines, multi-agent systems, and LLM-powered products.&#x27; Job listings are publicly browsable, and it also offers a public REST API and MCP server.</p>

<p>https://agentic-engineering-jobs.com/post — &#x27;$150 one-time · excl. VAT Post your job for 60 days&#x27;. Featuring costs $49, and a membership is &#x27;From $249/mo&#x27;. Posting is free only with a paid membership.</p>

<p>Independent source check: The catalog says posting is free; the current official form charges $150 for 60 days. The free publishing option requires an already-paid membership, so it does not support the unqualified catalog claim.</p>

<p>https://agentic-engineering-jobs.com/post — Independently fetched HTTP 200: standard posting costs $150 excluding VAT; memberships start at $249/month and include posting.</p>

</details>

<h3>Gridnaut Recruiting — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -101,7 +101,7 @@
 - [AI Jobs](https://www.moaijobs.com/) - Find a job at a cutting-edge AI company. Filter by title, location, company, etc.
 - [AI Tech Suite](https://www.aitechsuite.com/jobs) - AI tools and jobs aggregator with over 20k tools and 5k jobs, updated daily.
 - [ExploreJobs.ai](https://explorejobs.ai) - Find engineering, product, and research roles at the top AI startups.
-- [Gridnaut Recruiting](https://gridnaut.site/jobs/) - Curated AI training, evaluation, and domain-expert contractor roles (Mercor referrals). 100% remote, hourly contracts ($23-$180/hr).
+- [Gridnaut Recruiting](https://gridnaut.site/jobs/) - Curated AI training, evaluation, and domain-expert contractor roles (Mercor referrals). 100% remote, mostly hourly contracts.
 - [Specialist AI Work](https://specialistaiwork.com) - Reviewed remote AI evaluation, training, and expert-review roles with pay, eligibility, platform, and last-checked context.
 - [Human Pages](https://humanpages.ai) - The open directory AI agents use to hire humans for real-world tasks. Zero platform fees.
 - [Jobs in AI](https://jobsinai.com) - Marketplace for AI, machine learning, data science, and AI agent roles.
```

<details>
<summary>Evidence and limitations</summary>

<p>The site is still a remote AI-evaluation and domain-expert contractor board, and its Apply buttons link to t.mercor.com referral URLs, so identity, the Mercor claim and section fit hold. The &#x27;$23-$180/hr&#x27; range is out of date: current listings run from $14-$42/hr (Music Production Expert) up to $350/hr (Radiologist), with some ranges to $500/hr. Some roles also pay a fixed total (e.g. &#x27;$400 total&#x27;, &#x27;$150 total&#x27;) rather than hourly. The suggested wording drops the volatile pay range.</p>

<p>https://gridnaut.site/jobs/ — &#x27;Browse 333 open positions&#x27;. All 333 listed as Remote, every role tagged &#x27;Remote Contractor&#x27;. Apply links point to https://t.mercor.com/... Pay examples: &#x27;$14-$42 per hour&#x27;, &#x27;Radiologist $350 per hour&#x27;, &#x27;Retail Trader $400 total&#x27;, &#x27;Neurologists ... $150 total&#x27;. Highest listed range reaches $500.</p>

<p>Caveats: The listings are a snapshot from 2026-11-10 and change frequently.</p>

</details>

<h3>warpjobs — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -112,7 +112,7 @@
 - [JobsByCulture](https://jobsbyculture.com/) - Culture-first AI & tech job board with Glassdoor ratings, culture values, and employee reviews for 45+ companies.
 - [Jobtensor](https://jobtensor.com/) - AI, tech, and science job board.
 - [AimVantage](https://aimvantage.uk) - AI-powered interview preparation and job search tool with 20+ free career tools.
-- [warpjobs](https://warpjobs.com) - Niche board of GPU/CUDA, ML-systems, inference & performance-engineering roles, scraped daily from AI-lab & infra companies' ATS feeds (Greenhouse/Lever/Ashby); free, open-source, RSS/JSON feeds.
+- [warpjobs](https://warpjobs.com) - Niche board of GPU/CUDA, ML-systems, inference & performance-engineering roles, scraped daily from AI-lab & infra companies' ATS feeds (Greenhouse/Lever/Ashby); free, source on GitHub, RSS/JSON feeds.
 - [Landed](https://landed.jobs) - Daily matched AI-native roles with fit scores and drafted application answers, plus interview prep. Free tier; also queryable from any editor via a public MCP server.
 - [Level](https://jobsbylevel.com) - Job board that rates every listing from Level 1 to Level 4 by how central AI is to the work, from "AI is not the work" to "AI is the job"; listings pulled from company ATS every 6 hours, with public XML feeds.
 - [AITraining.jobs](https://aitraining.jobs) - Every open AI training role (AI trainer, evaluator, data annotation, domain expert) from about 60 platforms, with the hourly pay each states. Updated daily, free.
```

<details>
<summary>Evidence and limitations</summary>

<p>The niche (GPU/CUDA, ML-systems, inference, performance roles), daily refresh, Greenhouse/Lever/Ashby sourcing, and RSS/JSON feeds are all confirmed. The &#x27;open-source&#x27; claim is not supported. The linked repo ququyixiaozei/aijobs has no LICENSE file on its master branch, and its README says &#x27;See LICENSE if present; otherwise all rights reserved by the author.&#x27; The source is public but not under an open-source license.</p>

<p>https://warpjobs.com/ — &#x27;136 open GPU, CUDA, ML-systems, inference &amp; performance engineering roles from 28 AI labs and infrastructure companies — one board, refreshed daily&#x27;. Footer: &#x27;Aggregated from public company career pages (Greenhouse · Lever · Ashby APIs)&#x27;, &#x27;Subscribe: RSS · JSON&#x27;. Links /feed.xml, /jobs.json and github.com/ququyixiaozei/aijobs.</p>

<p>https://github.com/ququyixiaozei/aijobs — Repo description: &#x27;Daily scraper aggregating GPU/CUDA/ML-systems... Powers warpjobs.com - RSS + JSON feeds.&#x27; Root file list has no LICENSE. Default branch is master.</p>

<p>https://raw.githubusercontent.com/ququyixiaozei/aijobs/master/README.md — License section: &#x27;See `LICENSE` if present; otherwise all rights reserved by the author.&#x27; Raw LICENSE, LICENSE.md, LICENSE.txt and COPYING all return 404. package.json has no license field.</p>

<p>Caveats: The owner could add a license later, which would make &#x27;open-source&#x27; accurate again.</p>

</details>

<h3>Level — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -114,7 +114,7 @@
 - [AimVantage](https://aimvantage.uk) - AI-powered interview preparation and job search tool with 20+ free career tools.
 - [warpjobs](https://warpjobs.com) - Niche board of GPU/CUDA, ML-systems, inference & performance-engineering roles, scraped daily from AI-lab & infra companies' ATS feeds (Greenhouse/Lever/Ashby); free, open-source, RSS/JSON feeds.
 - [Landed](https://landed.jobs) - Daily matched AI-native roles with fit scores and drafted application answers, plus interview prep. Free tier; also queryable from any editor via a public MCP server.
-- [Level](https://jobsbylevel.com) - Job board that rates every listing from Level 1 to Level 4 by how central AI is to the work, from "AI is not the work" to "AI is the job"; listings pulled from company ATS every 6 hours, with public XML feeds.
+- [Level](https://jobsbylevel.com) - Job board that rates every listing from Level 1 to Level 4 by how central AI is to the work, from "Little AI" to "Builds AI"; listings pulled from company career sites every 6 hours, with public XML feeds.
 - [AITraining.jobs](https://aitraining.jobs) - Every open AI training role (AI trainer, evaluator, data annotation, domain expert) from about 60 platforms, with the hourly pay each states. Updated daily, free.
 - [AI Trainer Jobs](https://aitrainer.jobs) - Remote AI training, data annotation, RLHF and prompt evaluation jobs from 40+ platforms, updated hourly. Free, no signup.
 - [RobotTraining.jobs](https://robottraining.jobs) - Robot teleoperation, demonstration recording, at-home video capture and AV/drone test-operator openings from about 60 robotics and physical-AI employers, read from their own job boards every day and shown with the pay each posts. Free, no signup.
```

<details>
<summary>Evidence and limitations</summary>

<p>The four-level AI rating, refresh every six hours and public XML feeds are confirmed. The quoted labels are not: the site now names the levels Little AI (Level 1), Uses AI (Level 2), Works on AI (Level 3) and Builds AI (Level 4), and the phrase &#x27;AI is not the work&#x27; does not appear. The site also says listings are &#x27;pulled from company career sites&#x27; rather than specifically from ATS.</p>

<p>https://jobsbylevel.com/levels — &#x27;Level uses four: Builds AI (AI Level 4), Works on AI (AI Level 3), Uses AI (AI Level 2) and Little AI (AI Level 1).&#x27; &#x27;Data: 185,000+ live jobs on Level, pulled from company career sites every six hours.&#x27;</p>

<p>https://jobsbylevel.com/feeds — &#x27;XML job feeds, refreshed every six hours, one set of URLs per aggregator&#x27;, e.g. https://jobsbylevel.com/feeds/standard/recent-1.xml.</p>

<p>https://jobsbylevel.com/ — &#x27;185,000+ tech jobs, each rated for how much AI the role really uses&#x27;. Uses the phrase &#x27;Builds AI, where AI is the job itself&#x27;. &#x27;AI is not the work&#x27; is not present.</p>

<p>Caveats: Level names could change again. Quoting the endpoints only keeps the wording concise.</p>

</details>

<h3>RobotTraining.jobs — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -117,7 +117,7 @@
 - [Level](https://jobsbylevel.com) - Job board that rates every listing from Level 1 to Level 4 by how central AI is to the work, from "AI is not the work" to "AI is the job"; listings pulled from company ATS every 6 hours, with public XML feeds.
 - [AITraining.jobs](https://aitraining.jobs) - Every open AI training role (AI trainer, evaluator, data annotation, domain expert) from about 60 platforms, with the hourly pay each states. Updated daily, free.
 - [AI Trainer Jobs](https://aitrainer.jobs) - Remote AI training, data annotation, RLHF and prompt evaluation jobs from 40+ platforms, updated hourly. Free, no signup.
-- [RobotTraining.jobs](https://robottraining.jobs) - Robot teleoperation, demonstration recording, at-home video capture and AV/drone test-operator openings from about 60 robotics and physical-AI employers, read from their own job boards every day and shown with the pay each posts. Free, no signup.
+- [RobotTraining.jobs](https://robottraining.jobs) - Robot teleoperation, demonstration recording, at-home video capture and AV/drone test-operator openings from robotics and physical-AI employers, read from their own job boards every day and shown with the pay each posts. Free, no signup.
 - [USASI Jobs](https://aipeoplewiki.com/jobs/) - About 5,000 current openings at 44 U.S. AI companies, labs, and universities, read from each employer's own Greenhouse or Ashby job board and linking straight to the employer's posting. Free, no signup.
 - [AI Training Board](https://aitrainingboard.com) - About 3,300 work-from-home AI training jobs, each with its hourly rate and the countries that can apply. Rechecked every morning, free.
 - [aitrainer.work](https://aitrainer.work) - About 4,700 remote AI training and data annotation jobs from 22 platforms, with the pay each listing states, plus pay data by country, language and field. Updated daily, free.
```

<details>
<summary>Evidence and limitations</summary>

<p>The job types (teleoperation, demonstration collection, at-home/egocentric capture, AV and drone roles), daily reading of employer job boards, posted pay, and the no-account flow are confirmed. The employer count is outdated: the site now says jobs come from 100 employers&#x27; own job boards, not &#x27;about 60&#x27;. The suggested wording removes the volatile count.</p>

<p>https://robottraining.jobs/ — Meta: &#x27;1,149 robot training jobs open on 10 Nov 2026: filming chores, teleoperating robots, test driving self-driving cars and flying drones, taken from 100 employers&#x27; own job boards, read every day.&#x27; Category counts include Egocentric Capture, Demonstration Collection, Teleoperation and AV &amp; Drone. &#x27;No account needed.&#x27; Pay shown per employer.</p>

<p>Caveats: Job counts and pay ranges are volatile.</p>

</details>

<h3>AI Training Board — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -119,7 +119,7 @@
 - [AI Trainer Jobs](https://aitrainer.jobs) - Remote AI training, data annotation, RLHF and prompt evaluation jobs from 40+ platforms, updated hourly. Free, no signup.
 - [RobotTraining.jobs](https://robottraining.jobs) - Robot teleoperation, demonstration recording, at-home video capture and AV/drone test-operator openings from about 60 robotics and physical-AI employers, read from their own job boards every day and shown with the pay each posts. Free, no signup.
 - [USASI Jobs](https://aipeoplewiki.com/jobs/) - About 5,000 current openings at 44 U.S. AI companies, labs, and universities, read from each employer's own Greenhouse or Ashby job board and linking straight to the employer's posting. Free, no signup.
-- [AI Training Board](https://aitrainingboard.com) - About 3,300 work-from-home AI training jobs, each with its hourly rate and the countries that can apply. Rechecked every morning, free.
+- [AI Training Board](https://aitrainingboard.com) - Work-from-home AI training jobs, each with its hourly rate and the countries that can apply. Rechecked every morning, free.
 - [aitrainer.work](https://aitrainer.work) - About 4,700 remote AI training and data annotation jobs from 22 platforms, with the pay each listing states, plus pay data by country, language and field. Updated daily, free.
 - [Curated AI Jobs](https://job.careers) - Curated AI and machine learning roles across ML engineering, LLMs, research, and MLOps, with US, UK, Europe, and remote listings.
 - [AI Gig Scout](https://aigigscout.com) - Free directory of remote AI training and data annotation gigs from Micro1, Mercor, SME Careers, Sovrano, Ethos, Sannotate and more, updated daily.
```

<details>
<summary>Evidence and limitations</summary>

<p>The board&#x27;s format is confirmed: work-from-home AI training jobs, each with an hourly rate and the countries that can apply, from 45 platforms checked every morning, free. The &#x27;About 3,300&#x27; count is outdated; the site now shows 5,764 open jobs. The suggested wording drops the volatile count.</p>

<p>https://aitrainingboard.com/ — Title &#x27;AI Training Jobs: 5,764 Open Today&#x27;. Meta: &#x27;5,764 remote AI training jobs you can do from home, each with its hourly rate and the countries that can apply. Rechecked daily.&#x27; Body: &#x27;We check 45 platforms every morning&#x27;. Says referral fees keep the board free. Credits job data partly to aitrainer.jobs.</p>

<p>Caveats: The site credits some job data to aitrainer.jobs (entry 119), so the two entries may overlap. Duplication is a maintainer judgment and was not evaluated under the pinned rules.</p>

</details>

<h3>USASI Jobs — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -118,7 +118,6 @@
 - [AITraining.jobs](https://aitraining.jobs) - Every open AI training role (AI trainer, evaluator, data annotation, domain expert) from about 60 platforms, with the hourly pay each states. Updated daily, free.
 - [AI Trainer Jobs](https://aitrainer.jobs) - Remote AI training, data annotation, RLHF and prompt evaluation jobs from 40+ platforms, updated hourly. Free, no signup.
 - [RobotTraining.jobs](https://robottraining.jobs) - Robot teleoperation, demonstration recording, at-home video capture and AV/drone test-operator openings from about 60 robotics and physical-AI employers, read from their own job boards every day and shown with the pay each posts. Free, no signup.
-- [USASI Jobs](https://aipeoplewiki.com/jobs/) - About 5,000 current openings at 44 U.S. AI companies, labs, and universities, read from each employer's own Greenhouse or Ashby job board and linking straight to the employer's posting. Free, no signup.
 - [AI Training Board](https://aitrainingboard.com) - About 3,300 work-from-home AI training jobs, each with its hourly rate and the countries that can apply. Rechecked every morning, free.
 - [aitrainer.work](https://aitrainer.work) - About 4,700 remote AI training and data annotation jobs from 22 platforms, with the pay each listing states, plus pay data by country, language and field. Updated daily, free.
 - [Curated AI Jobs](https://job.careers) - Curated AI and machine learning roles across ML engineering, LLMs, research, and MLOps, with US, UK, Europe, and remote listings.
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed page returns HTTP 410 Gone with an explicit official notice that the jobs board has been retired: &#x27;Job listings, hiring pages and salary pages are no longer published.&#x27; USASI&#x27;s own jobs URL (unitedstatesofamericasuperintelligence.com/jobs/) currently redirects to this same retired page. No working successor job board was found on either domain.</p>

<p>https://aipeoplewiki.com/jobs/ — HTTP 410. Title &#x27;This page has been removed | AI People Wiki&#x27;. &#x27;The jobs board has been retired. AI People Wiki is now focused on the people building AI. Job listings, hiring pages and salary pages are no longer published.&#x27;</p>

<p>https://unitedstatesofamericasuperintelligence.com/jobs/ — Redirects to https://aipeoplewiki.com/jobs/, which returns 410 with the same retirement notice. Search results still show stale USASI jobs pages (&#x27;25,000+ openings&#x27;).</p>

<p>Caveats: A Hugging Face dataset (usasihq/usasi-ai-jobs, snapshot 2026-10-16) exists. It is a static dataset, not a live job board.</p>

<p>Independent source check: The current official jobs page explicitly announces retirement and returns HTTP 410. The former USASI jobs domain redirects to that same retirement notice. A cached web-reader response still showed November 1 listings, so direct current HTTP responses were checked and saved rather than trusting the stale index.</p>

<p>https://aipeoplewiki.com/jobs/ — Independent direct request returned HTTP 410 and an explicit notice that the jobs board retired and no longer publishes jobs, hiring or salary pages.</p>

<p>https://unitedstatesofamericasuperintelligence.com/jobs/ — Independent direct request redirected to the AI People Wiki jobs URL and returned the same HTTP 410 retirement notice.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>aitrainer.work — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -120,7 +120,7 @@
 - [RobotTraining.jobs](https://robottraining.jobs) - Robot teleoperation, demonstration recording, at-home video capture and AV/drone test-operator openings from about 60 robotics and physical-AI employers, read from their own job boards every day and shown with the pay each posts. Free, no signup.
 - [USASI Jobs](https://aipeoplewiki.com/jobs/) - About 5,000 current openings at 44 U.S. AI companies, labs, and universities, read from each employer's own Greenhouse or Ashby job board and linking straight to the employer's posting. Free, no signup.
 - [AI Training Board](https://aitrainingboard.com) - About 3,300 work-from-home AI training jobs, each with its hourly rate and the countries that can apply. Rechecked every morning, free.
-- [aitrainer.work](https://aitrainer.work) - About 4,700 remote AI training and data annotation jobs from 22 platforms, with the pay each listing states, plus pay data by country, language and field. Updated daily, free.
+- [aitrainer.work](https://aitrainer.work) - Thousands of remote AI training and data annotation jobs from more than 20 platforms, with the pay each listing states, plus pay data by country, language and field. Updated daily, free.
 - [Curated AI Jobs](https://job.careers) - Curated AI and machine learning roles across ML engineering, LLMs, research, and MLOps, with US, UK, Europe, and remote listings.
 - [AI Gig Scout](https://aigigscout.com) - Free directory of remote AI training and data annotation gigs from Micro1, Mercor, SME Careers, Sovrano, Ethos, Sannotate and more, updated daily.
 - [AI Work Central](https://aiworkcentral.com) - Free daily list of remote AI training roles (evaluation, coding, language and expert work) from 16 platforms, with listed pay, languages and eligible countries.
```

<details>
<summary>Evidence and limitations</summary>

<p>The site is live and still a remote AI training/data annotation job board that shows the pay each listing states. The entry&#x27;s counts are out of date: the homepage now shows 6,555 jobs from 28 platforms, not about 4,700 from 22. The suggested wording drops the volatile counts.</p>

<p>https://aitrainer.work/ — Title &#x27;Remote AI Training &amp; Data Annotation Jobs | aitrainer.work&#x27;. Meta: &#x27;6,555 remote AI training and data annotation jobs from 28 platforms, with the pay each listing states, checked daily.&#x27; Page says &#x27;Updated Nov 10&#x27; and has filters for field, language (64) and platform.</p>

<p>https://aitrainer.work/pay-tracker — Pay tracker page has category/field groupings plus &#x27;By language&#x27; and &#x27;By country&#x27; sections, which supports the &#x27;pay data by country, language and field&#x27; claim.</p>

<p>Caveats: I did not find an explicit statement that the site is &#x27;free&#x27;. It has sign-in, certification and &#x27;Talent Pool&#x27; products. Browsing jobs appeared to need no payment.; The counts change daily.</p>

</details>

<h3>AI Gig Scout — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -122,7 +122,7 @@
 - [AI Training Board](https://aitrainingboard.com) - About 3,300 work-from-home AI training jobs, each with its hourly rate and the countries that can apply. Rechecked every morning, free.
 - [aitrainer.work](https://aitrainer.work) - About 4,700 remote AI training and data annotation jobs from 22 platforms, with the pay each listing states, plus pay data by country, language and field. Updated daily, free.
 - [Curated AI Jobs](https://job.careers) - Curated AI and machine learning roles across ML engineering, LLMs, research, and MLOps, with US, UK, Europe, and remote listings.
-- [AI Gig Scout](https://aigigscout.com) - Free directory of remote AI training and data annotation gigs from Micro1, Mercor, SME Careers, Sovrano, Ethos, Sannotate and more, updated daily.
+- [AI Gig Scout](https://aigigscout.com) - Free directory of remote AI training and data annotation gigs from Micro1, Mercor, SME Careers, Sovrano, Ethos, AfterQuery, SuperAnnotate and more, updated daily.
 - [AI Work Central](https://aiworkcentral.com) - Free daily list of remote AI training roles (evaluation, coding, language and expert work) from 16 platforms, with listed pay, languages and eligible countries.
 - [Red Pen Jobs](https://redpenjobs.com) - Remote AI training roles sorted into 27 professions (lawyers, doctors, accountants, engineers and more), with the pay each posting states and a free CC BY dataset of pay by profession. Checked every morning, free, no signup.
 - [AI Expat Jobs](https://aiexpatjobs.com) - About 430 AI, ML and data roles in the UK and the Netherlands, only at employers on the official visa-sponsor registers (UK Home Office and Dutch IND). Read from each employer's own job board every day; postings that say they can't sponsor are left out. Free, no signup.
```

<details>
<summary>Evidence and limitations</summary>

<p>Live AI training gig directory with daily updates. However, &#x27;Sannotate&#x27;, one of the platforms named in the description, appears nowhere on the homepage or platforms page. The current platforms are Micro1, SME Careers, Mercor, Sovrano AI, Ethos AI and AfterQuery, and the homepage meta also names SuperAnnotate. The suggested wording swaps the unsupported name for verified ones.</p>

<p>https://aigigscout.com/ — Title &#x27;AI Gigs &amp; Remote AI Training Jobs, Updated Daily | AI Gig Scout&#x27;. Meta: &#x27;Find 1,153 live remote AI training jobs from Mercor, Micro1, Ethos, AfterQuery, Sovrano and SuperAnnotate. Verified AI gigs, updated daily.&#x27; No occurrence of &#x27;Sannotate&#x27;.</p>

<p>https://aigigscout.com/platforms — Lists Micro1, SME Careers, Mercor, Sovrano AI, Ethos AI and AfterQuery, then &#x27;More platforms coming soon&#x27;. Notes that some links are referral links.</p>

<p>https://aigigscout.com/about — Describes itself as &#x27;an independent directory that helps people discover opportunities to contribute to AI training and evaluation projects&#x27;.</p>

<p>Caveats: &#x27;Sannotate&#x27; may have been a typo for SuperAnnotate. I could not confirm this.; There is no explicit &#x27;free&#x27; statement, but browsing needs no payment or signup.; The site uses referral links.</p>

</details>

<h3>AI Work Central — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -123,7 +123,7 @@
 - [aitrainer.work](https://aitrainer.work) - About 4,700 remote AI training and data annotation jobs from 22 platforms, with the pay each listing states, plus pay data by country, language and field. Updated daily, free.
 - [Curated AI Jobs](https://job.careers) - Curated AI and machine learning roles across ML engineering, LLMs, research, and MLOps, with US, UK, Europe, and remote listings.
 - [AI Gig Scout](https://aigigscout.com) - Free directory of remote AI training and data annotation gigs from Micro1, Mercor, SME Careers, Sovrano, Ethos, Sannotate and more, updated daily.
-- [AI Work Central](https://aiworkcentral.com) - Free daily list of remote AI training roles (evaluation, coding, language and expert work) from 16 platforms, with listed pay, languages and eligible countries.
+- [AI Work Central](https://aiworkcentral.com) - Free daily list of remote AI training roles (evaluation, coding, language and expert work) from about 20 platforms, with listed pay, languages and eligible countries.
 - [Red Pen Jobs](https://redpenjobs.com) - Remote AI training roles sorted into 27 professions (lawyers, doctors, accountants, engineers and more), with the pay each posting states and a free CC BY dataset of pay by profession. Checked every morning, free, no signup.
 - [AI Expat Jobs](https://aiexpatjobs.com) - About 430 AI, ML and data roles in the UK and the Netherlands, only at employers on the official visa-sponsor registers (UK Home Office and Dutch IND). Read from each employer's own job board every day; postings that say they can't sponsor are left out. Free, no signup.
 - [NeverApply](https://neverapply.co) - AI job-search agent that matches you to roles, tailors your resume and cover letter for each one, answers screening questions and applies with your approval. Free plan; also usable from Claude, Cursor and other MCP clients.
```

<details>
<summary>Evidence and limitations</summary>

<p>Still a free, daily aggregator of AI training roles with listed pay, languages and countries. The platform count is out of date: the site now says 20 platforms, not 16. The suggested wording uses an approximate count.</p>

<p>https://aiworkcentral.com/ — Title &#x27;AI Training Jobs: 2,293 Roles from 20 Platforms, Updated Daily&#x27;. Meta: &#x27;AI training job aggregator: 2,293 open roles from 20 platforms, with listed pay, languages and countries. Updated 10 November 2026.&#x27; Text: &#x27;Remote roles for bilinguals, experts and coders, checked every day. Free to use.&#x27;</p>

<p>https://aiworkcentral.com/about — About page confirms &#x27;20 read every day&#x27; and the filters for field, languages and country.</p>

<p>Caveats: The platform count changes over time.</p>

</details>

<h3>AI Expat Jobs — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -125,7 +125,7 @@
 - [AI Gig Scout](https://aigigscout.com) - Free directory of remote AI training and data annotation gigs from Micro1, Mercor, SME Careers, Sovrano, Ethos, Sannotate and more, updated daily.
 - [AI Work Central](https://aiworkcentral.com) - Free daily list of remote AI training roles (evaluation, coding, language and expert work) from 16 platforms, with listed pay, languages and eligible countries.
 - [Red Pen Jobs](https://redpenjobs.com) - Remote AI training roles sorted into 27 professions (lawyers, doctors, accountants, engineers and more), with the pay each posting states and a free CC BY dataset of pay by profession. Checked every morning, free, no signup.
-- [AI Expat Jobs](https://aiexpatjobs.com) - About 430 AI, ML and data roles in the UK and the Netherlands, only at employers on the official visa-sponsor registers (UK Home Office and Dutch IND). Read from each employer's own job board every day; postings that say they can't sponsor are left out. Free, no signup.
+- [AI Expat Jobs](https://aiexpatjobs.com) - AI, ML and data roles in the UK, the Netherlands and Germany. UK and Dutch roles are only at employers on the official visa-sponsor registers (UK Home Office and Dutch IND); German ads are read for what they say about visas. Read from each employer's own job board every day; postings that say they can't sponsor are left out. Free, no signup.
 - [NeverApply](https://neverapply.co) - AI job-search agent that matches you to roles, tailors your resume and cover letter for each one, answers screening questions and applies with your approval. Free plan; also usable from Claude, Cursor and other MCP clients.
 - [CookLLM](https://cookllm.com/en/jobs/match) - AI job matcher: scores new roles from the career pages of 1,300+ AI companies, plus hiring posts on X and LinkedIn, against your resume and emails the ones at 70% fit or above, daily or weekly. The AI job board is free; matching starts at $9 a week.
 - [VisionHires](https://visionhires.com/) - Computer vision, machine vision, and perception engineering jobs.
```

<details>
<summary>Evidence and limitations</summary>

<p>The site now covers Germany as well as the UK and the Netherlands. Germany has no sponsor register, so the claim that every role is at an employer on a sponsor register is no longer true. The role count has also moved from about 430 to 586. The other claims still hold: daily reads of employers&#x27; own job boards and exclusion of ads that say they won&#x27;t sponsor.</p>

<p>https://aiexpatjobs.com/ — Title &#x27;AI jobs for visa seekers: UK, Netherlands &amp; Germany&#x27;. Text: &#x27;586 open roles. In the UK and the Netherlands, only at employers on the official sponsor registers. Germany has no register&#x27; and &#x27;30 ads that say they won&#x27;t (we leave them out)&#x27;. Updated 10 Nov 2026.</p>

<p>https://aiexpatjobs.com/about/ — Method section: reads UK Home Office and Dutch IND registers, then &#x27;We read employers&#x27; own job boards&#x27; (Greenhouse, Ashby, Lever, etc.). For Germany, &#x27;we read the ads&#x27;. The weekly email is free.</p>

<p>Caveats: I did not verify that the site needs no signup beyond seeing no account wall.</p>

</details>

<h3>web3vacancy — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -164,7 +164,7 @@
 - [Jobstash](https://jobstash.xyz/)
 - [BeInCrypto Jobs](https://beincrypto.com/jobs/)
 - [Sail on Chain](https://sailonchain.com/)
-- [web3vacancy](https://web3vacancy.com/) - Crypto-native job board aggregating 2,400+ roles from DeFi, L2s, wallets, and infrastructure companies. Updated every 5 minutes.
+- [web3vacancy](https://web3vacancy.com/) - Crypto-native job board listing roles at protocols, DAOs, exchanges, wallets and infrastructure companies. Updated daily.
 - [PredictionJobs](https://predictionjobs.co) - Job board for the prediction market space, featuring roles at Polymarket, Kalshi etc.
 - [Jobs in Crypto](https://jobsincrypto.xyz) - Marketplace for crypto, Web3, and onchain roles.
 - [ChainJobs](https://chainjobs.io/) - Crypto, Web3 and Blockchain roles aggregated daily from companies' official careers pages; every listing links to the employer's own application page.
```

<details>
<summary>Evidence and limitations</summary>

<p>The board is live and relevant, but two claims are out of date. It now shows about 1,270 open roles, not &#x27;2,400+&#x27;. It says &#x27;Updated daily&#x27; (with &#x27;Updated 2 h ago&#x27;), not &#x27;every 5 minutes&#x27;. The new wording drops the counts that keep changing and uses the site&#x27;s own description of the companies it covers.</p>

<p>https://web3vacancy.com/ — Title &#x27;Web3 Jobs &amp; Crypto Jobs: Remote Blockchain Roles, Updated Daily&#x27;. Meta: &#x27;Browse 1270+ web3 jobs... at 257+ crypto companies... Updated daily.&#x27; Header: &#x27;Open roles 1,270 ... Updated 2 h ago&#x27;. Body: &#x27;web3vacancy lists the latest web3 and crypto jobs at protocols, DAOs, exchanges, wallets and infrastructure companies&#x27;.</p>

<p>Caveats: Role counts change. The new description leaves them out on purpose.</p>

</details>

<h3>BeInCrypto Jobs — remove</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>BeInCrypto Jobs was a Web3 industry job board, as the Wayback snapshots through May 2026 show. Today, beincrypto.com/jobs/ and its sub-paths (/jobs/remote/, /jobs/salaries/) redirect to careers.beincrypto.com. That page only lists BeInCrypto&#x27;s own openings (4 roles). The industry job board no longer seems to be offered at this URL, so it no longer fits the Blockchain job-board section.</p>

<p>https://beincrypto.com/jobs/ — Direct curl gets HTTP 403 (Cloudflare challenge). Through r.jina.ai: &#x27;Final URL: https://careers.beincrypto.com/&#x27;, title &#x27;BeInCrypto - Job openings&#x27;, &#x27;BeInCrypto careers... Displaying 1 - 4 of 4 in total&#x27; (Research Analyst, VP Institutional Partnerships, etc.).</p>

<p>http://web.archive.org/web/20260501011024/https://beincrypto.com/jobs/ — The May 2026 snapshot is &#x27;Crypto Jobs in Web3 | BeInCrypto&#x27;, an industry board with Post Your Jobs, Salary Hub, Grants and Hackathons.</p>

<p>https://web.archive.org/cdx/search/cdx?url=beincrypto.com/jobs/&amp;from=202606&amp;output=txt&amp;fl=timestamp,statuscode,original — Captures from 2026-06-24 onward have no 200 status, which is consistent with a redirect starting around mid-2026.</p>

<p>https://beincrypto.com/jobs/remote/ — Through r.jina.ai, this sub-path also ends at https://careers.beincrypto.com/.</p>

<p>Blocking questions: I found no official announcement that the BeInCrypto Jobs board was shut down or moved to another domain. The redirect is the main evidence.</p>

<p>Caveats: Cloudflare blocked direct requests, so I saw the redirect only through a third-party reader and Wayback status codes.; BeInCrypto&#x27;s own careers page is a single-company hiring page, not a multi-company job board.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>CryptoJobsHQ — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -170,7 +170,7 @@
 - [ChainJobs](https://chainjobs.io/) - Crypto, Web3 and Blockchain roles aggregated daily from companies' official careers pages; every listing links to the employer's own application page.
 - [Maneki](https://maneki.work/) - Web3 jobs from 500+ companies' career pages, refreshed nightly; normalized salary data, remote filters, expired listings removed automatically.
 - [Blockchain Jobs](https://www.blockchainjobsboard.com/) - The latest Blockchain jobs from Web3, crypto, DeFi, and protocol companies. 
-- [CryptoJobsHQ](https://cryptojobshq.com/) - Crypto and Web3 jobs in 13 categories with salary data per company; every listing is checked daily and filled or dead jobs are removed automatically.
+- [CryptoJobsHQ](https://cryptojobshq.com/) - Crypto and Web3 jobs filterable by discipline, work setup and experience, with salary data by company.
 - [Jobs Web3](https://jobsweb3.io/) - Crypto, Blockchain and Web3 jobs at 200+ companies, filterable by skill, required language and the countries, regions or time zones each job accepts.
 - [JobsInCrypto](https://jobsincrypto.net) - Crypto jobs with no ghost jobs or fake recruiters: Verified roles from verified companies and Checked roles from 250+ companies' own career pages. Every candidate and company is reviewed by a person.
 - [chainjobs.app](https://chainjobs.app/) - Free Web3 and freelance job board where clients post jobs, freelancers offer services, and both sides chat directly; payment in crypto or bank transfer, 0% platform commission.
```

<details>
<summary>Evidence and limitations</summary>

<p>The board is live and on topic, but two specific claims don&#x27;t hold up. The discipline filter has 14 options, not 13 (Engineering, Product, Design, Marketing, Sales, Business Development, Operations, Research, Community, Finance, Legal &amp; Compliance, Security, Customer Support, Non-Tech). I found no statement on the homepage, About or Pricing pages that every listing is checked daily and dead jobs are removed automatically; the site only says it is &#x27;updated every day&#x27;. Salary data by company exists, but only for employers with at least 10 salary-disclosing listings. The suggested wording drops the volatile count and the unsupported claim.</p>

<p>https://cryptojobshq.com/about — Discipline dropdown has 14 entries. About text says listings are &#x27;refreshed every day&#x27; and filterable by &#x27;discipline, work setup and experience&#x27;. Nothing about daily per-listing checks or automatic removal of filled jobs.</p>

<p>https://cryptojobshq.com/salaries — &#x27;Salaries by company … Only employers with at least 10 salary-disclosing listings get a page.&#x27;</p>

<p>https://cryptojobshq.com/ — Meta: &#x27;Hundreds of remote and onsite jobs at the teams building onchain, updated every day.&#x27; Shows 4,063 open roles. The phrases &#x27;checked daily&#x27;, &#x27;filled&#x27; and &#x27;dead&#x27; don&#x27;t appear.</p>

<p>Caveats: The site may check listings internally without saying so publicly. The edit removes an unverifiable claim rather than proving it false.</p>

</details>

<h3>JobsInCrypto — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -172,7 +172,7 @@
 - [Blockchain Jobs](https://www.blockchainjobsboard.com/) - The latest Blockchain jobs from Web3, crypto, DeFi, and protocol companies. 
 - [CryptoJobsHQ](https://cryptojobshq.com/) - Crypto and Web3 jobs in 13 categories with salary data per company; every listing is checked daily and filled or dead jobs are removed automatically.
 - [Jobs Web3](https://jobsweb3.io/) - Crypto, Blockchain and Web3 jobs at 200+ companies, filterable by skill, required language and the countries, regions or time zones each job accepts.
-- [JobsInCrypto](https://jobsincrypto.net) - Crypto jobs with no ghost jobs or fake recruiters: Verified roles from verified companies and Checked roles from 250+ companies' own career pages. Every candidate and company is reviewed by a person.
+- [JobsInCrypto](https://jobsincrypto.net) - Crypto jobs with no ghost jobs or fake recruiters: Verified roles from reviewed companies and Checked roles from companies' own career pages. Every candidate and company is reviewed by a person.
 - [chainjobs.app](https://chainjobs.app/) - Free Web3 and freelance job board where clients post jobs, freelancers offer services, and both sides chat directly; payment in crypto or bank transfer, 0% platform commission.
 
 ## Design
```

<details>
<summary>Evidence and limitations</summary>

<p>The Verified/Checked model and human review are confirmed by the FAQ. The &#x27;250+ companies&#x27; count is not: the jobs page shows 1,052 roles at 163 companies in total. The suggested wording keeps the supported claims and drops the outdated count.</p>

<p>https://jobsincrypto.net/faq — &#x27;Verified jobs are posted … by the companies themselves. We review each company before it can post … Checked jobs come from the company&#x27;s own careers page. A person at JobsInCrypto reads each one before it appears here.&#x27;</p>

<p>https://jobsincrypto.net/jobs — Header shows &#x27;Verified Checked 1052 roles · 163 companies&#x27;.</p>

<p>https://jobsincrypto.net — Meta: &#x27;every listing is manually verified before it goes live. No ghost jobs, no fake recruiters.&#x27; The team &#x27;moderates both sides: companies before a listing goes live, candidates before an application reaches an employer.&#x27;</p>

<p>Caveats: Company counts change over time; 163 is a snapshot from 2026-11-10.</p>

</details>

<h3>Dribble — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -182,7 +182,7 @@
 - [Behance](https://www.behance.net/joblist)
 - [Coroflot](https://www.coroflot.com/design-jobs)
 - [IXDA](http://ixda.org/jobs/)
-- [Dribble](https://dribbble.com/jobs)
+- [Dribbble](https://dribbble.com/jobs)
 - [Open Source Design Jobs](https://opensourcedesign.net/jobs/)
 - [UX Jobs Board](https://www.uxjobsboard.com)
 - [Designer Jobs](https://designerjobs.co/)
```

<details>
<summary>Evidence and limitations</summary>

<p>The URL is live and correct, and it&#x27;s a good fit for Design. The catalog name &#x27;Dribble&#x27; is a misspelling of the brand, which is &#x27;Dribbble&#x27;. This is a name correction only; the URL stays the same.</p>

<p>https://dribbble.com/jobs — Title: &#x27;Graphic Design Jobs - Browse 100s of Design Jobs | Dribbble&#x27;. Meta: &#x27;Find graphic design jobs on Dribbble&#x27;.</p>

</details>

<h3>UX Jobs Board — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -184,7 +184,6 @@
 - [IXDA](http://ixda.org/jobs/)
 - [Dribble](https://dribbble.com/jobs)
 - [Open Source Design Jobs](https://opensourcedesign.net/jobs/)
-- [UX Jobs Board](https://www.uxjobsboard.com)
 - [Designer Jobs](https://designerjobs.co/)
 - [Design Jobs Board](https://www.designjobsboard.com/)
 - [Design Week Jobs](https://www.designweek.co.uk/jobs/)
```

<details>
<summary>Evidence and limitations</summary>

<p>The domain now serves its hosting platform Niceboard&#x27;s &#x27;This job board is unavailable&#x27; page instead of a UX job board. Wayback Machine captures from December 2025 through July 2026 are all small (~1.4 KB) pages, and the July 2026 one is the same &#x27;Job board unavailable - Niceboard&#x27; page. The board no longer offers job listings. I found no documented successor.</p>

<p>https://www.uxjobsboard.com/ — HTTP 200 from Niceboard. Title &#x27;Job board unavailable - Niceboard&#x27;; body: &#x27;This job board is unavailable. Start a job board for your community…&#x27;. uxjobsboard.com redirects here.</p>

<p>http://web.archive.org/web/20260712183815/https://www.uxjobsboard.com/ — The July 2026 snapshot has the same &#x27;Job board unavailable - Niceboard&#x27; title. CDX shows only ~1.4 KB pages since Dec 2025.</p>

<p>Caveats: The owner could restore the board later, e.g. if the outage is a lapsed subscription.</p>

</details>

<h3>Creativepool — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -190,7 +190,7 @@
 - [Design Week Jobs](https://www.designweek.co.uk/jobs/)
 - [If You Could Jobs](https://www.ifyoucouldjobs.com/)
 - [CreativeMornings](https://creativemornings.com/jobs)
-- [Creativepool](https://creativepool.com/jobs/)
+- [Creativepool](https://jobs.creativepool.com/jobs/)
 - [UI/UX Jobs Board](https://uiuxjobsboard.com)
 
 ## InfoSec
```

<details>
<summary>Evidence and limitations</summary>

<p>https://creativepool.com/jobs/ permanently redirects (HTTP 301) to https://jobs.creativepool.com/jobs/ on Creativepool&#x27;s own subdomain. That page is a live creative-sector jobs board, so it still fits Design. Recommend updating the URL to the canonical destination.</p>

<p>https://creativepool.com/jobs/ — A HEAD request returned &#x27;HTTP/2 301&#x27; with &#x27;location: https://jobs.creativepool.com/jobs/&#x27; (Cloudflare).</p>

<p>https://jobs.creativepool.com/jobs/ — HTTP 200. The title is &#x27;Life-changing jobs and gigs for the creative sector. Advertise for free!&#x27; Navigation includes Jobs Board, Advertise a Job and Studio, and matches the main creativepool.com site (&#x27;The Creative Industry Network | Creativepool&#x27;).</p>

<p>Caveats: The old URL still works through the redirect, so this change is optional.</p>

</details>

<h3>iOS Dev Jobs — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -205,7 +205,6 @@
 ## Programming
 
 - [ClojureJobboard](https://ClojureJobboard.com/)
-- [iOS Dev Jobs](https://iosdevjobs.com/)
 - [Elixir Radar](https://elixir-radar.com/jobs)
 - [Elixir Jobs](https://elixirjobs.net/)
 - [findatechjob](https://findatechjob.dev/)
```

<details>
<summary>Evidence and limitations</summary>

<p>The site itself says it has shut down. The page at the listed URL reads &#x27;iOS Dev Jobs is no longer active&#x27; and has no job listings, so the entry no longer gives readers a job board.</p>

<p>https://iosdevjobs.com/ — HTTP 200, title &#x27;iOS Dev Jobs&#x27;. The only content is: &#x27;iOS Dev Jobs is no longer active. Thanks to everyone who used it to either find amazing candidates or to find a new position!&#x27;</p>

<p>Caveats: The notice names no successor, so there is nothing to replace the entry with.</p>

</details>

<h3>Pycoder&#x27;s Jobs — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -222,7 +222,7 @@
 - [LaraJobs](https://larajobs.com/)
 - [pyJobs](https://www.pyjobs.com/)
 - [Python Job Board](https://www.python.org/jobs/)
-- [Pycoder's Jobs](https://www.pythonjobshq.com/)
+- [Python Jobs HQ](https://www.pythonjobshq.com/)
 - [Django Jobs](https://djangojobs.net/jobs/)
 - [Rust Programming Language Jobs](http://rust-jobs.com/)
 - [JavaScript Jobs](https://jobs.date-fns.org/)
```

<details>
<summary>Evidence and limitations</summary>

<p>The URL still works, but the site now calls itself &#x27;Python Jobs HQ&#x27; rather than &#x27;Pycoder&#x27;s Jobs&#x27;. The page says it is brought to you by the creators of the PyCoder&#x27;s Weekly newsletter. The URL is unchanged; only the display name needs updating.</p>

<p>https://www.pythonjobshq.com/ — HTTP 200 with no redirect. The title is &#x27;Python Job Board – Python Jobs HQ&#x27;. The meta description reads &#x27;The leading resource for the top Python jobs… Brought to you by the creators of the PyCoder’s Weekly Newsletter.&#x27; The page links to twitter.com/pycoders.</p>

<p>Caveats: The homepage loads its listings dynamically, so I could not check how many jobs are posted or how recent they are.</p>

</details>

<h3>Rust Programming Language Jobs — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -224,7 +224,6 @@
 - [Python Job Board](https://www.python.org/jobs/)
 - [Pycoder's Jobs](https://www.pythonjobshq.com/)
 - [Django Jobs](https://djangojobs.net/jobs/)
-- [Rust Programming Language Jobs](http://rust-jobs.com/)
 - [JavaScript Jobs](https://jobs.date-fns.org/)
 - [Jobs in JS](https://jobsinjs.com/)
 - [TypeScriptJobs](https://typescriptjobs.net/) - TypeScript developer positions, updated daily.
```

<details>
<summary>Evidence and limitations</summary>

<p>The site&#x27;s own page shows it is not a job board. It is a pre-launch email signup page (&#x27;We are creating the most complete Rust job board to date. Subscribe below for updates on our launch&#x27;) with no job listings. So the listed URL does not provide what the entry promises. I found no successor documented by the site&#x27;s owner.</p>

<p>http://rust-jobs.com/ — HTTP 200. The page has the heading &#x27;Rust Programming Language Jobs&#x27;, a Mailchimp signup form and the text &#x27;Subscribe below for updates on our launch&#x27;. It has no job listings or job-board features.</p>

<p>Caveats: I did not trace the domain&#x27;s full archive history to find out whether it ever ran a live board.; Other Rust job boards exist, but none is an official successor, so a replacement would be a new addition rather than a swap.</p>

</details>

<h3>Sottava — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -240,7 +240,7 @@
 - [Jobs in Flutter](https://jobsinflutter.com) - Marketplace for Flutter and Dart roles.
 - [Jobs in Rust](https://jobsinrust.com) - Marketplace for Rust engineering roles.
 - [NearMetal](https://nearmetal.dev/) - Systems programming jobs: kernel, compilers, databases, embedded and performance roles, linked to each company's own posting.
-- [Sottava](https://sottava.com/) - Tech jobs read every hour from 1,800 companies' own hiring systems, with the date each was posted.
+- [Sottava](https://sottava.com/) - Tech jobs read every hour from companies' own hiring systems, with the date each was posted.
 
 ## Remote
 
```

<details>
<summary>Evidence and limitations</summary>

<p>The site is live and still reads companies&#x27; own hiring systems every hour and shows real posting dates. The &#x27;1,800 companies&#x27; count is out of date: the site now says 2,106 companies. A count-free wording would not go stale again.</p>

<p>https://sottava.com/ — HTTP 200. Meta: &#x27;76,736 open tech jobs from 2,106 companies, read from their own hiring systems every hour, with the real posting date on each one.&#x27; Header: &#x27;Scanning 2,106 companies&#x27;.</p>

<p>Caveats: Sottava is a subscription service with a permanent free feed (Pro $30/mo). The entry doesn&#x27;t mention pricing, so no correction is needed there.; The listing preview showed &#x27;First seen NaN mo ago&#x27;, a display bug seen on 10 Nov 2026.</p>

</details>

<h3>DynamiteJobs — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -273,7 +273,7 @@
 - [Remoters](https://remoters.net/jobs/)
 - [DailyRemote](https://dailyremote.com/)
 - [Remote Developer Jobs](https://www.remote-developer-jobs.com/)
-- [DynamiteJobs](https://www.dynamitejobs.com/)
+- [DynamiteJobs](https://dynamitejobs.com/)
 - [Remote Index](https://remoteindex.co/)
 - [Devremote](https://devremote.io/)
 - [I love remote](https://iloveremote.io) - High paid remote jobs.
```

<details>
<summary>Evidence and limitations</summary>

<p>The site is an active remote job board, but https://www.dynamitejobs.com/ redirects to https://dynamitejobs.com/. The canonical URL is the apex domain. Keep the name and the bare-link format.</p>

<p>https://dynamitejobs.com/ — Requesting https://www.dynamitejobs.com/ ends at https://dynamitejobs.com/ (HTTP 200). Title: &#x27;Dynamite Jobs: The Best Remote Jobs in November 2026&#x27;. Meta: &#x27;The Best Work-From-Home and Remote Jobs from the top remote-first companies&#x27;.</p>

<p>Caveats: The old www URL still works through the redirect, so this change is cosmetic and low priority.; The site&#x27;s own brand is &#x27;Dynamite Jobs&#x27; (with a space); no rename is proposed.</p>

</details>

<h3>RemoteCorgi — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -285,7 +285,7 @@
 - [Remote100K](https://remote100k.com/)
 - [RemoteRocketship](https://www.remoterocketship.com/)
 - [Remote Job Assistant](https://remotejobassistant.com/) - Remote jobs for moms, career changers & non-technical professionals.
-- [RemoteCorgi](https://www.wfhjobs.co.uk/) - Hand-picked remote and hybrid jobs. Top companies only.
+- [WFH Jobs](https://www.wfhjobs.co.uk/) - Hand-picked remote and hybrid jobs. Top companies only.
 - [TrulyRemote](https://trulyremote.co/)
 - [RemoteJobsFinder](https://remotejobsfinder.co/en)
 - [GlobalWork](https://globalwork.ai/en)
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed URL is now branded &#x27;WFH Jobs&#x27;. Its title says &#x27;(formerly Remote Corgi)&#x27;, which confirms an official rename at the same URL. The description still holds: the page says &#x27;Hand-picked work-from-home jobs... Top companies only.&#x27; and shows both &#x27;100% Remote&#x27; and &#x27;Hybrid&#x27; listings. Only the name needs updating.</p>

<p>https://www.wfhjobs.co.uk/ — HTTP 200. Title is &#x27;WFH Jobs | Find Your Dream Remote Jobs in the UK (formerly Remote Corgi)&#x27;. Body text: &#x27;Hand-picked work-from-home jobs. Full-time and part time. Top companies only.&#x27; The listings show both &#x27;100% Remote&#x27; and &#x27;Hybrid&#x27; (London) roles. &#x27;357 open jobs&#x27; were listed.</p>

<p>Caveats: The site now focuses on the UK. The description makes no region claim, so this is only an optional clarification.</p>

</details>

<h3>Remote1stJobs — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -292,7 +292,7 @@
 - [4DayJob](https://4dayjob.com/) - 4-day work week and remote job board with 1,500+ flexible opportunities.
 - [FindRemoteLawJobs](https://findremotelawjobs.com/) - Remote jobs for legal professionals.
 - [FindRemoteAccountingJobs](https://findremoteaccountingjobs.com/) - Remote jobs for accounting and finance professionals.
-- [Remote1stJobs](https://www.remote1stjobs.com/) - UK, Europe & EMEA remote-first jobs board; filters out US-only and fake-remote roles, direct employer links, salary-visible.
+- [Remote1stJobs](https://www.remote1stjobs.com/) - Eligibility-checked remote jobs across the USA, UK, Canada, Europe and Australia; shows where each employer can hire from and scam-checks listings.
 - [Global Remote Hub](https://globalremotehub.com/) - Remote & relocation jobs requiring German, French, or Spanish. For bilingual candidates.
 - [Remote Nomad Jobs](https://www.remotenomadjobs.com/) - Fully remote, work-from-anywhere jobs for digital nomads.
 - [RoleSense](https://role-sense.com/) - Surfaces per-job country eligibility and work-style signals (autonomy, pace, meeting load) parsed from the posting text; sourced directly from ATS boards (Greenhouse, Lever, Ashby, Workable, and more).
```

<details>
<summary>Evidence and limitations</summary>

<p>The description says the board covers &#x27;UK, Europe &amp; EMEA&#x27; and &#x27;filters out US-only... roles&#x27;. The current site contradicts both claims. It now covers five markets, &#x27;USA, UK, Canada, Australia, Europe&#x27;, has a US filter and lists US/Canada-only roles. Its current pitch is eligibility-checked, scam-checked listings that show where each employer can hire from. The site and URL are unchanged.</p>

<p>https://www.remote1stjobs.com/ — Title is &#x27;Remote1st: Remote jobs you can actually get hired for&#x27;. Meta: &#x27;Eligibility-checked remote jobs across the USA, UK, Canada, Australia and Europe&#x27;. The body says &#x27;5 markets: USA, UK, Canada, Australia, Europe&#x27;, &#x27;Every job shows where the employer can hire from&#x27; and &#x27;38,726 passed every scam check&#x27;. It has UK/US/EU/CA filters, and listings include roles limited to &#x27;United States, Remote; Canada, Remote&#x27;.</p>

<p>Caveats: The claims &#x27;direct employer links&#x27; and &#x27;salary-visible&#x27; were not checked across all listings. Salaries appear on some sampled listings.; The site has free and Pro tiers; free visitors see up to 20 results.</p>

</details>

<h3>Global Remote Hub — update</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Global Remote Hub has repositioned. Its title and hero now describe &#x27;Employer reviews, real pay and guides for US remote customer service and work-from-home jobs, plus bilingual (Spanish and more) roles&#x27;. German-, French- and Spanish-speaking job sections and a &#x27;Relocation &amp; Living&#x27; guide category remain. The current description (jobs &#x27;requiring German, French, or Spanish&#x27;) no longer reflects the site&#x27;s main purpose. It is still remote-work relevant.</p>

<p>https://globalremotehub.com/ — Title is &#x27;US Remote Customer Service &amp; Work-From-Home Jobs&#x27;. Meta: &#x27;Employer reviews, real pay and guides for US remote customer service and work-from-home jobs, plus bilingual (Spanish and more) roles.&#x27; Navigation includes &#x27;German-Speaking Jobs&#x27;, &#x27;French-Speaking Jobs&#x27;, &#x27;Spanish-Speaking Jobs&#x27;, &#x27;Bilingual Jobs&#x27;, employer reviews (Teleperformance, TTEC, Concentrix...) and &#x27;Relocation &amp; Living&#x27;.</p>

<p>Blocking questions: Whether the site, now heavily review- and guide-oriented, still meets the list&#x27;s job-board scope is a maintainer judgment call.</p>

<p>Caveats: Much of the homepage is review and guide content rather than listings. The maintainer may want to consider whether it still counts as a job board for this list.</p>

</details>

<h3>Remote Jobs API — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -297,7 +297,7 @@
 - [Remote Nomad Jobs](https://www.remotenomadjobs.com/) - Fully remote, work-from-anywhere jobs for digital nomads.
 - [RoleSense](https://role-sense.com/) - Surfaces per-job country eligibility and work-style signals (autonomy, pace, meeting load) parsed from the posting text; sourced directly from ATS boards (Greenhouse, Lever, Ashby, Workable, and more).
 - [DoableFromHome](https://doablefromhome.com) - Remote tech jobs checked for country hiring restrictions.
-- [Remote Jobs API](https://remote-jobs-api.tten.no) - Free, no-auth REST feed of 300+ deduplicated remote tech jobs aggregated from Remotive, Remote OK, Jobicy, WWR & HN (salary where available).
+- [Remote Jobs API](https://remote-jobs-api.tten.no) - REST API of normalized remote tech jobs aggregated from Remotive, Remote OK, Jobicy, WWR & HN; API key required, free tier available.
 - [Jobicy](https://jobicy.com/jobs) - Daily remote job listings with salary information where available, apply without an account.
 - [AbroadStack](https://abroadstack.com/jobs) - Remote, visa-friendly and overseas tech jobs with market and skill filters and English/Chinese support.
 - [SpinHire](https://spinhire.io/en/) - iGaming job board: casino, sportsbook, game studios and affiliate jobs with salary benchmarks; open API (CC BY 4.0).
```

<details>
<summary>Evidence and limitations</summary>

<p>The description says the API is a &#x27;Free, no-auth&#x27; feed, but the current site requires API keys. Its example curl sends &#x27;Authorization: Bearer ...&#x27;, and pricing tiers are Free ($0, 100 calls/month) and Pro ($19/month). The sources (Remotive, RemoteOK, Jobicy, We Work Remotely, Hacker News) and the &#x27;300+ listings&#x27; figure are still shown. &#x27;No-auth&#x27; is a confirmed false claim. Deduplication and salary fields were not confirmed and are omitted from the proposed wording.</p>

<p>https://remote-jobs-api.tten.no/ — Title is &#x27;Remote Jobs API — one API for all remote jobs&#x27;. Body: &#x27;Live · 83 job boards · 300+ listings updated every 5 minutes. Normalized listings from Remotive, RemoteOK, Jobicy, We Work Remotely and Hacker News — with skills fit-scoring, JSON/CSV export and predictable API keys. Start free...&#x27; Pricing: Free $0/month with 100 calls/month; Pro $19/month. Example: curl -H &quot;Authorization: Bearer ***&quot; &quot;https://remote-jobs-api.tten.no/v1/jobs?...&quot;</p>

<p>Caveats: The API was not called; unauthenticated access was not tested directly.; The page says &#x27;83 job boards&#x27; but names only five sources. That inconsistency is unresolved, so the proposed wording avoids counts.</p>

</details>

<h3>Aworkado — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -308,7 +308,7 @@
 - [RoleGig](https://rolegig.com/) - Free weekly job lists for technical writing, product, QA, AI and ML, and developer roles, laid out by region, including remote roles that hire across countries.
 - [RemoteHunt](https://remotehunt.app/jobs) - Remote jobs that can hire in your country, from 2,400+ employer career pages, each scored 0-100 against your resume.
 - [NodJobs](https://nodjobs.com) - Hand-picked remote jobs sourced directly from company career pages, with exact salaries shown free and a direct apply link to the employer on every listing; no duplicates or stale posts.
-- [Aworkado](https://aworkado.co/) - About 20,000 remote-only jobs aggregated daily from company Greenhouse, Lever, Ashby and SmartRecruiters boards, normalized by job function and location. Free, no account.
+- [Aworkado](https://aworkado.co/) - Remote and hybrid jobs aggregated from company career pages and ATSs such as Greenhouse, Lever, Ashby and SmartRecruiters, re-checked daily and sorted by job function and location. Free, no account.
 - [HeyRole](https://heyrole.ai/) - Remote jobs with location, role and seniority filters, an AI job-search assistant, and links to original listings.
 - [ApplyRemote](https://applyremote.co/) - Remote job board with worldwide opportunities, an ATS-friendly CV builder, AI cover letters, and application tracking.
   
```

<details>
<summary>Evidence and limitations</summary>

<p>The pipeline snapshot failed, but a direct fetch of https://aworkado.co/ returned HTTP 200 (the /about page returned 522 once, then loaded). Two claims are now wrong. &#x27;Remote-only&#x27; is false: the site lists remote and hybrid jobs and has a dedicated /hybrid section. &#x27;About 20,000&#x27; is outdated: the homepage shows 65,466 jobs. Sourcing from Greenhouse, Lever, Ashby and SmartRecruiters is confirmed, along with Workable and others. Daily re-checking, sorting by function and location, and free use without an account are also confirmed. The suggested wording drops the volatile count.</p>

<p>https://aworkado.co/ — Title: &#x27;Remote and hybrid jobs, without the job-board noise · Aworkado&#x27;. &#x27;One list of remote jobs, with hybrid ones marked plainly. No sponsored slots, no sign-up wall.&#x27; &#x27;Browse 65,466 jobs&#x27;. Function and location facets. &#x27;Re-checked today&#x27;.</p>

<p>https://aworkado.co/about — &#x27;collects job postings from the career pages and applicant tracking systems of thousands of companies: Greenhouse, Lever, Ashby, Workable, SmartRecruiters and more.&#x27; &#x27;Only remote and hybrid jobs stay. A role tied to an office every day is left out.&#x27; &#x27;Free, without an account&#x27;.</p>

<p>https://aworkado.co/hybrid — &#x27;Every role here is hybrid: the employer expects you in an office for part of the week&#x27; — e.g. 3,870 hybrid software engineering roles.</p>

<p>https://aworkado.co/job/senior-devops-engineer-86635 — Job page links to the original Greenhouse posting (job-boards.greenhouse.io/swordhealth/...).</p>

<p>Caveats: The pipeline snapshot was unavailable; this finding rests on a direct fetch on 2026-11-10. The /about page returned 522 on the first try, so availability may be intermittent.; The proposed text keeps the entry in the Remote section; hybrid listings are clearly separated, and remote is still the main focus.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Outsource — remove</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site at outsource.com now presents itself as a managed outsourced-finance service, not a freelancer marketplace or job board. Its title and meta describe dedicated accountants, bookkeepers, payroll specialists and virtual CFOs delivered through &#x27;Manchester-led, Dhaka-powered managed delivery&#x27;. A January 2025 archive already showed an accounting-outsourcing platform. /freelancers and /jobs both serve the same finance-services shell. This is official evidence that the listed site no longer serves the Freelancer section&#x27;s purpose.</p>

<p>https://outsource.com/ — HTTP 200. Title: &#x27;Outsourced Finance Professionals | Outsource.com&#x27;. Meta: &#x27;Extend your finance team with dedicated accountants, bookkeepers, payroll specialists and virtual CFOs. Manchester-led, Dhaka-powered managed delivery.&#x27;</p>

<p>https://outsource.com/freelancers — Returns HTTP 200 with the same &#x27;Outsourced Finance Professionals&#x27; title. This is the SPA shell; there is no distinct freelancer page.</p>

<p>https://web.archive.org/web/20250105090206/https://outsource.com/ — Jan 2025 snapshot: &#x27;Outsource your accounting tasks on a single platform... Bookkeeping, tax, and payroll help on demand&#x27;. This already describes a managed accounting service, not a freelance marketplace.</p>

<p>Blocking questions: The site is a client-rendered SPA, and only its HTML shell, title and meta were read. Without rendering the app, I cannot rule out a freelancer or job interface somewhere inside it.</p>

<p>Caveats: I did not research when or why the domain&#x27;s purpose changed.</p>

</details>

<h3>ClockInToday — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -389,7 +389,7 @@
 ## Creative & Gig Work
 
 - [Creative Gig Jobs](https://creativegigjobs.com) - Freelance and gig jobs for designers, illustrators, photographers, and creative professionals.
-- [ClockInToday](https://clockintoday.com/) - Free directory of 112 US gig apps and jobs you can start without an interview, showing the minimum age, background check, vehicle needs, and payout speed for each.
+- [ClockInToday](https://clockintoday.com/) - Free directory of US gig apps and jobs you can start without an interview, showing the minimum age, background check, vehicle needs, and payout speed for each.
 
 ## Climate & Green Tech
 
```

<details>
<summary>Evidence and limitations</summary>

<p>Identity and fit are confirmed. The volatile platform count is now wrong: the site says &#x27;116 platforms&#x27; and &#x27;Showing 116 of 116&#x27;, while the entry says 112. Recommend dropping the count; the rest of the description is supported.</p>

<p>https://clockintoday.com/ — Canonical https://clockintoday.com/. Meta: &#x27;Compare requirements, minimum age, payout speed, and real pay data for 116 platforms.&#x27; The page shows &#x27;Showing 116 of 116&#x27;. Each card lists background check, vehicle needs, minimum age and payout speed. Headline: &#x27;No interview · No résumé&#x27;.</p>

<p>Caveats: &#x27;Free&#x27; is neither confirmed nor contradicted by the homepage. It is kept from the original wording.</p>

</details>

<h3>ClimateTechList — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -393,7 +393,7 @@
 
 ## Climate & Green Tech
 
-- [ClimateTechList](https://www.climatetechlist.com/) - Climate tech / green energy jobs for software engineers.
+- [ClimateTechList](https://www.climatetechlist.com/) - Climate tech, clean tech, and green energy jobs across engineering and non-engineering roles, aggregated daily from company job boards.
 - [Climatebase](https://climatebase.org/) - Access to job openings at thousands of climate tech companies and nonprofits.
 - [GreenLever](https://greenlever.co/)
 - [Rejobs](https://rejobs.org/en/) - Renewable Energy Jobs.
```

<details>
<summary>Evidence and limitations</summary>

<p>Identity and relevance are confirmed, but &#x27;for software engineers&#x27; is outdated. The official About page says the site started in 2023 to help software engineers, then expanded into a general climate tech jobs list because many users were not engineers. The jobs page has Finance, Marketing, Operations and Sales filters.</p>

<p>https://www.climatetechlist.com/blog/about — &#x27;ClimateTechList started in early 2023 as a side project to help software engineers find climate tech jobs. After launching... many users... were not software engineers and consistently asked for a general list of climate tech jobs. Since then it&#x27;s expanded to be the web&#x27;s largest aggregator of climate tech companies and jobs.&#x27;</p>

<p>https://www.climatetechlist.com/jobs — &#x27;Tracking 16,208 job openings. Updated daily.&#x27; from 767 companies. Category links include Software Engineer, Finance, Marketing, Operations and Sales jobs.</p>

<p>Caveats: The homepage renders its content client-side. Evidence came from its meta tags and from the /jobs and About pages.</p>

</details>

<h3>Joblift — remove</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Adzuna&#x27;s official blog (16 July 2026) says it acquired Joblift&#x27;s assets. In the UK, USA, Belgium, Italy, Netherlands and France, &#x27;Joblift&#x27;s business will be combined fully into Adzuna&#x27;. Only Germany (joblift.de) continues as a standalone brand. The listed joblift.com was the US/international site (archived June 2026 with US state and city job search). Its stated successor, Adzuna, is already listed separately as entry 437, so replacing would create a duplicate. PitchBook and Crunchbase list Joblift as out of business/closed.</p>

<p>https://www.adzuna.co.uk/blog/adzuna-acquires-joblift/ — Official post dated July 16, 2026: &#x27;In Germany, Joblift will continue to operate as a standalone brand&#x27;; &#x27;In the UK, USA, Belgium, Italy, Netherlands and France, Joblift&#x27;s business will be combined fully into Adzuna.&#x27;</p>

<p>http://web.archive.org/web/20260616160818/https://joblift.com/ — Last pre-acquisition capture (2026-06-16). Title: &#x27;Joblift: all jobs on one platform&#x27;, with US states and cities. This confirms joblift.com was the US-market site now folded into Adzuna. No archive captures exist after July 2026.</p>

<p>https://joblift.com/ — Live: HTTP 403 from CloudFront, the same response www.adzuna.com gives to automated clients.</p>

<p>Blocking questions: I could not observe what joblift.com currently serves (403). It may redirect to Adzuna or show a closure notice. A maintainer should check it in a browser before removing.</p>

<p>Caveats: A maintainer could instead keep a Germany-only entry pointing to joblift.de. That would change the entry&#x27;s scope and is not a like-for-like replacement.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>The Guardian Jobs — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -448,7 +448,6 @@
 - [Smashing Magazine](https://www.smashingmagazine.com/jobs/)
 - [Totaljobs](https://www.totaljobs.com/)
 - [XING](https://www.xing.com/)
-- [The Guardian Jobs](https://jobs.theguardian.com/jobs/)
 - [Jobs in Network](https://www.jobsinnetwork.com/)
 - [snagajob](https://www.snagajob.com/)
 - [Robert Half](https://www.roberthalf.com/jobs)
```

<details>
<summary>Evidence and limitations</summary>

<p>The Guardian officially shut down Guardian Jobs. jobs.theguardian.com/jobs/ now redirects to a Guardian notice, &#x27;An update on Guardian Jobs&#x27;, stating &#x27;Guardian Jobs has now closed&#x27; (first published 2 Sep 2026, updated 16 Oct 2026). The notice names no successor service.</p>

<p>https://www.theguardian.com/help/insideguardian/2026/sep/02/an-update-on-guardian-jobs — https://jobs.theguardian.com/jobs/ redirects here. Headline: &#x27;After bringing together like-minded job seekers and employers for many years Guardian Jobs has now closed.&#x27; By Imogen Fox, first published Wed 2 Sep 2026, updated Fri 16 Oct 2026. It thanks employers and job seekers and gives only a queries email, with no successor.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Jobs in Next Tech — update</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>https://jobsinnexttech.com redirects to https://www.jobsinnexttech.com/. The site now presents itself as an employer-facing distribution layer: &#x27;Connect your ATS to the Jobs in Next Tech network through one feed, API or MCP server.&#x27; Its own copy names the network boards as AI, gaming, XR, quantum, Flutter, Rust, Web3, robotics, drones and nuclear technology. The site bundle has no mention of SexTech or jobsinsextech.com, so the listed &#x27;sextech&#x27; vertical is no longer supported. Robotics, drones and nuclear are also missing from the entry.</p>

<p>https://www.jobsinnexttech.com/ — Meta description: &#x27;Connect your ATS to the Jobs in Next Tech network through one feed, API or MCP server.&#x27; Hero text: &#x27;Publish roles across a specialist network of trusted technology job boards—from a single feed, API or MCP connection.&#x27;</p>

<p>https://www.jobsinnexttech.com/assets/index-BZQ6QWFr.js — The bundle maps the network to jobsinai, jobsingames, jobsinxr, jobsinquantum, jobsinflutter, jobsinrust, jobsincrypto (Web3), jobsinrobots, jobsindrones and jobsinnuclear. It says &#x27;connects one structured source to focused job boards across AI, gaming, XR, quantum, Flutter, Rust, Web3, robotics, drones and nuclear technology.&#x27; There are no SexTech references. It also has a &#x27;live network&#x27; section that links candidates to the specialist boards.</p>

<p>Blocking questions: Relevance is ambiguous. The homepage now mostly targets employers (ATS integration) rather than job seekers. The maintainer should decide whether a hub that links to specialist boards still fits this list, or whether the individual boards are enough.</p>

<p>Caveats: The site is a client-rendered SPA. I read the claims from the JS bundle, not a rendered page.; jobsinsextech.com is still live on its own (entry 512). It is just not listed in this network.</p>

</details>

<h3>CrawlJobs — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -513,7 +513,7 @@
 - [Jobs in XR](https://jobsinxr.com) - Marketplace for augmented reality, virtual reality, and extended reality roles.
 - [JobYap](https://jobyap.com) - Search job postings aggregated from companies' official careers sites — salaries, locations, and a community discussion thread on every job.
 - [Open Jobs Search](https://conorscode.github.io/open-jobs-search/) - Free search over 37,000+ live postings from 378 companies across nine ATS platforms (Greenhouse, Lever, Ashby, Workday, and more). No signup, no ads, no tracking.
-- [CrawlJobs](https://crawljobs.com) - Global job board with 550,000+ active listings crawled directly from employers' own career pages instead of other job boards. Covers 200+ countries in 20+ language versions, with filters for location, work mode and salary.
+- [CrawlJobs](https://crawljobs.com) - Global job board with AI-crawled listings from companies worldwide in 20 language versions, with filters for location, work mode and salary.
 - [ParlayJobs](https://www.parlayjobs.com/) - Specialist job board for sports betting, iGaming and betting-tech careers.
 - [TaskFavour](https://www.taskfavour.com/) - AI-powered job search and alert platform for freelance, remote, and full-time opportunities.
 - [PursuitCI](https://www.pursuitci.com/jobs) - Career intelligence and job search platform featuring 500,000+ live US listings by role, with built-in resume tailoring and ATS tools.
```

<details>
<summary>Evidence and limitations</summary>

<p>https://crawljobs.com redirects to https://www.crawljobs.com/ (HTTP 200). The homepage shows 384,062 active English offers plus 87,279 in other language versions, about 471k in total. That contradicts the &#x27;550,000+ active listings&#x27; claim. The site says &#x27;Browse jobs in 20 languages&#x27;, not 20+. The &#x27;200+ countries&#x27; figure refers to where candidates are (&#x27;Trusted by candidates in 200+ countries&#x27;), not job coverage. The site describes its sourcing as &#x27;AI-collected job listings from companies worldwide&#x27; gathered &#x27;from various sources across the globe&#x27;. It does not affirm the &#x27;career pages instead of other job boards&#x27; claim. The location, work-mode and salary filters are confirmed.</p>

<p>https://www.crawljobs.com/ — Text: &#x27;Browse 384,062 active job offers, or check 87,279 offers in other language versions.&#x27; The language switcher lists 20 languages. Footer: &#x27;Browse jobs in 20 languages.&#x27; Banner: &#x27;Trusted by candidates in 200+ countries.&#x27; The filters include Countries, Location, Work Mode (On-site/Remote/Hybrid) and Salary. The About blurb says listings come &#x27;from various sources across the globe&#x27; using AI and web crawling.</p>

<p>Caveats: The about-us page returned HTTP 403 to my fetcher, so a fuller statement of how sourcing works is still unread.; The listing count changes over time. The suggested wording avoids counts.</p>

</details>

<h3>ErasmusIntern — replace</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -528,7 +528,7 @@
 - [Entry Level Jobs](https://www.entryleveljobs.me/)
 - [College Recruiter](https://www.collegerecruiter.com/)
 - [TalentEgg](https://talentegg.ca/)
-- [ErasmusIntern](https://erasmusintern.org/traineeships)
+- [ErasmusCareers](https://erasmuscareers.org/)
 - [AfterCollege](https://www.aftercollege.com/)
 - [Newgrad jobs](https://www.newgrad-jobs.com/)
 - [EntryLevel Careers](https://entrylevel.careers/)
```

<details>
<summary>Evidence and limitations</summary>

<p>ESN (Erasmus Student Network) runs ErasmusIntern, and it officially announced that ErasmusIntern.org has evolved into ErasmusCareers.org. ErasmusIntern.org no longer accepts new traineeship postings or new student accounts. Existing listings stay browsable only until the platform closes for good at the end of 2026. ErasmusCareers.org is the documented successor for traineeships and jobs.</p>

<p>https://socialerasmus.org/news/introducing-erasmuscareersorg-new-platform-international-traineeships-and-jobs — An Erasmus Student Network page states: &#x27;ErasmusIntern.org has evolved into ErasmusCareers.org... ErasmusIntern.org is now closed to new traineeship postings... closed to new account creation. Existing opportunities remain available for browsing and applications until the platform closes definitively at the end of 2026.&#x27; ESN&#x27;s site menu also lists &#x27;ErasmusIntern.org&#x27; under Past Projects and &#x27;ErasmusCareers: Find your traineeship abroad&#x27; under services.</p>

<p>https://erasmusintern.org/traineeships — HTTP 403 Cloudflare challenge when fetched directly. A Wayback snapshot from 2026-01-02 exists.</p>

<p>https://erasmuscareers.org/ — HTTP 403 Cloudflare challenge (&#x27;Just a moment...&#x27;). The domain is the one named by ESN, but I could not read its content directly.</p>

<p>Caveats: I could not render erasmuscareers.org (Cloudflare challenge). Its identity rests on ESN&#x27;s official announcement. I did not check whether it has a traineeships listing path, so the root URL is proposed.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Remote Physician Jobs — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -582,7 +582,7 @@
 - [National Labor Exchange](https://usnlx.com/)
 - [juju](https://www.juju.com/)
 - [Chef Jobs Near.Me](https://chefjobsnearme.com/)
-- [Remote Physician Jobs](https://www.remotephysicianjobs.org/) - Remote jobs for physicians and doctors. Live aggregator of 600 companies' job boards, updated daily.
+- [Remote Physician Jobs](https://www.remotephysicianjobs.org/) - Remote jobs for physicians and doctors. Live aggregator of hundreds of companies' job boards, updated daily.
 - [Library Jobs HQ](https://www.libraryjobshq.com/)
 - [FoundRole](https://foundrole.com/) - AI-powered job search platform and job application tracker for knowledge workers.
 - [USDevJobs](https://usdevjobs.com/) - Real-time job aggregator for software, AI/ML, and data engineer roles at US startups.
```

<details>
<summary>Evidence and limitations</summary>

<p>The site is still a live aggregator of remote physician jobs from company job boards, updated daily. But the description&#x27;s count of &#x27;600 companies&#x27; is out of date: the site now tracks 781 companies (780+). The suggested wording drops the changing number.</p>

<p>https://www.remotephysicianjobs.org/ — HTTP 200. Title: &#x27;Latest 11,000+ remote physician job openings from 780+ Companies&#x27;. Text: &#x27;Tracking 11,070 remote physician jobs. Updated daily.&#x27;, &#x27;Filter 781 companies&#x27;, &#x27;Jobs are updated from individual company job boards daily&#x27;.</p>

<p>Caveats: The company count will keep changing. The suggested description avoids a number on purpose.</p>

</details>

<h3>FoundRole — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -584,7 +584,7 @@
 - [Chef Jobs Near.Me](https://chefjobsnearme.com/)
 - [Remote Physician Jobs](https://www.remotephysicianjobs.org/) - Remote jobs for physicians and doctors. Live aggregator of 600 companies' job boards, updated daily.
 - [Library Jobs HQ](https://www.libraryjobshq.com/)
-- [FoundRole](https://foundrole.com/) - AI-powered job search platform and job application tracker for knowledge workers.
+- [FoundRole](https://foundrole.com/) - AI-powered job search that fact-checks postings (ghost jobs, pay vs market, visa sponsorship), with a job application tracker.
 - [USDevJobs](https://usdevjobs.com/) - Real-time job aggregator for software, AI/ML, and data engineer roles at US startups.
 - [CareJobs.Now](https://carejobs.now/) - Healthcare jobs across the US (nursing, allied health, physicians, techs), read daily from 258 hospitals' and health systems' own career sites, with posted pay.
 - [RemoteWorkUSA](https://www.remoteworkusa.com/) - Remote jobs for US residents, with location and category filters for easy search.
```

<details>
<summary>Evidence and limitations</summary>

<p>Identity and reachability confirmed (foundrole.com redirects to www.foundrole.com). It is still an AI job search tool with an application tracker. However, the claim &#x27;for knowledge workers&#x27; is out of date: the homepage shows forklift operator, warehouse equipment operator, kitchen staff and nurse roles, and says it covers 4.4M+ jobs in 100+ countries and 40+ industries. The current focus is fact-checking postings (ghost jobs, pay vs market, visa sponsorship). It still fits the USA section because of its heavy US salary and H-1B data.</p>

<p>https://www.foundrole.com/ — Title &#x27;AI Job Search &amp; Career Tools — Fact-Checked &amp; Free&#x27;. Meta: &#x27;AI job search that fact-checks every posting — real or ghost, pay vs the market, sponsors or not — then tracks every application.&#x27; Sample listings include DHL Forklift Operator and Rooms To Go Warehouse Equipment Operator. The tracker shows Kitchen Staff and Kitchen Manager entries. &#x27;4,400,000+ open positions worldwide… 100+ Countries 40+ Industries&#x27;. US H1B/DOL wage data is featured. The word &#x27;knowledge&#x27; does not appear on the page.</p>

<p>Caveats: Did not sign in or test Pro features.; Site is global, but its US data focus supports the USA placement.</p>

</details>

<h3>CareJobs.Now — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -586,7 +586,7 @@
 - [Library Jobs HQ](https://www.libraryjobshq.com/)
 - [FoundRole](https://foundrole.com/) - AI-powered job search platform and job application tracker for knowledge workers.
 - [USDevJobs](https://usdevjobs.com/) - Real-time job aggregator for software, AI/ML, and data engineer roles at US startups.
-- [CareJobs.Now](https://carejobs.now/) - Healthcare jobs across the US (nursing, allied health, physicians, techs), read daily from 258 hospitals' and health systems' own career sites, with posted pay.
+- [CareJobs.Now](https://carejobs.now/) - Healthcare jobs across the US (nursing, allied health, physicians, techs), read daily from hospitals', health systems' and other care employers' own career sites, with posted pay where available.
 - [RemoteWorkUSA](https://www.remoteworkusa.com/) - Remote jobs for US residents, with location and category filters for easy search.
 
 ### Australia
```

<details>
<summary>Evidence and limitations</summary>

<p>Still a US healthcare job aggregator that reads employers&#x27; own boards nightly and shows pay. The &#x27;258 hospitals&#x27; count is out of date: the site now reads from 6,628 employers and sources, including clinic groups, care companies and federal job boards. Only 41% of jobs post pay. Suggest durable wording without a count.</p>

<p>https://carejobs.now/ — Fetched via WebFetch (curl got Vercel checkpoint 429). Page says it reads job boards of &#x27;6,628 employers and sources&#x27; every night (6,542 hiring), including &#x27;hospitals, health systems, clinic groups and care companies&#x27; and federal boards. Last update 10 Nov 2026. &#x27;41% post their pay&#x27;. Covers 17 job kinds: RNs, physicians, CNAs, therapists, imaging/lab/surgical techs, and more.</p>

<p>Caveats: Content was read through a summarizing fetch tool; the curl request was blocked by Vercel&#x27;s bot checkpoint.</p>

</details>

<h3>MapleStack — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -608,7 +608,7 @@
 - [CareerBeacon](https://www.careerbeacon.com/)
 - [CanadianNanny.ca](https://canadiannanny.ca/)
 - [Hanzilla Jobs](https://jobs.hanzilla.co/) - Daily-updated Canadian student and recent-grad jobs across internships, co-ops, new grad, junior, and entry-level roles.
-- [MapleStack](https://maplestack.ca/) - Canadian jobs with AI-powered matching.
+- [MapleStack](https://maplestack.ca/) - Canadian jobs compiled directly from company career pages, with free job alerts.
 
 ### UK
 
```

<details>
<summary>Evidence and limitations</summary>

<p>Live Canadian job board that compiles jobs from company career pages, with free alerts and direct apply links. I found no &#x27;AI-powered matching&#x27; on the homepage or the About page, which lists the free features (search, personalised alerts by role and city, direct apply). The listed AI capability is unsupported by official pages, so a factual wording is suggested.</p>

<p>https://maplestack.ca/ — Title &#x27;Canadian Jobs from Company Career Pages | MapleStack&#x27;. Meta: &#x27;Thousands of jobs compiled from Canadian company career pages. Free job alerts, direct links to the original postings, no duplicate reposts.&#x27; No &#x27;AI&#x27; or &#x27;matching&#x27; wording in the page text.</p>

<p>https://maplestack.ca/about — Lists the free features: unlimited job search updated daily, personalised job alerts based on role and city, direct apply links. &#x27;Built by an independent Canadian developer.&#x27; No mention of AI matching.</p>

<p>Caveats: Did not create an account; a signed-in AI matching feature cannot be fully ruled out.</p>

</details>

<h3>Jobsuche — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -630,7 +630,7 @@
 
 ### Germany
 
-- [Jobsuche](https://www.jobsintown.de/jobsuche/)
+- [jobsintown.de](https://www.jobsintown.de/jobsuche/)
 - [StepStone](https://www.stepstone.de/en)
 - [jobvector](https://www.jobvector.de/en/)
 - [Jobware](https://www.jobware.de/)
```

<details>
<summary>Evidence and limitations</summary>

<p>The URL works (HTTP 200) and is a German job board. The listed name &#x27;Jobsuche&#x27; is only the page heading (German for &#x27;job search&#x27;). The site&#x27;s brand is jobsintown.de, so a name correction is suggested. The URL stays the same.</p>

<p>https://www.jobsintown.de/jobsuche/ — HTTP 200. Title: &#x27;Jobsuche | Stellenbörse: Jobs &amp; Stellenangebote auf jobsintown.de&#x27;. Meta description: &#x27;Die Online-Stellenbörse jobsintown.de bietet aktuelle Jobs, eine regionale Jobsuche...&#x27;</p>

<p>Caveats: The rename is cosmetic. The current link works and fits the Germany section.</p>

</details>

<h3>JobScout24 — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -635,7 +635,7 @@
 - [jobvector](https://www.jobvector.de/en/)
 - [Jobware](https://www.jobware.de/)
 - [Stellenanzeigen](https://www.stellenanzeigen.de/)
-- [JobScout24](https://www.jobs.de/)
+- [jobs.de](https://www.jobs.de/)
 - [StellenOnline](https://www.stellenonline.de/)
 - [Berlin Startup Jobs](https://berlinstartupjobs.com/)
 - [Jobs in Berlin](https://www.jobsinberlin.eu/)
```

<details>
<summary>Evidence and limitations</summary>

<p>The URL is a live German job board, but its current branding is JOBS.DE only. The page has no &#x27;JobScout24&#x27; text, the logo alt text is &#x27;JOBS.DE&#x27;, and the operator is jobs.de GmbH. JobScout24 Germany was folded into jobs.de, which co-branded with JobScout24 from 2017 to 2021. jobscout24.de now returns 502. A name update to jobs.de is suggested.</p>

<p>https://www.jobs.de/ — Title &#x27;JOBS.DE – 65.000+ Jobs deutschlandweit&#x27;. Logo alt text &#x27;JOBS.DE&#x27;. No text containing &#x27;Scout&#x27; (via WebFetch; curl hit a bot challenge).</p>

<p>https://www.jobs.de/impressum — Site operator: jobs.de GmbH, Berlin. No mention of JobScout24 or CareerBuilder.</p>

<p>https://www.mynewsdesk.com/de/careerbuilder-germany-gmbh/pressreleases/jobscout24-ist-zurueck-jobs-punkt-de-ab-sofort-mit-zwei-marken-strategie-2093566 — 2017 CareerBuilder Germany press release (title seen in search results): jobs.de adopts a two-brand strategy with JobScout24.</p>

<p>https://www.jobscout24.de/ — HEAD request returns HTTP 502 Bad Gateway. No redirect observed.</p>

<p>Caveats: The page content came through WebFetch&#x27;s summarised extraction because curl hit a bot challenge. A logo image containing JobScout24 text could be missed, but the alt text says &#x27;JOBS.DE&#x27;.; JobScout24.ch is a separate Swiss business and is not related to this entry.</p>

</details>

<h3>NIJOBS — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -716,7 +716,7 @@
 - [No Fluff Jobs](https://nofluffjobs.com/) - Poland & Hungary.
 - [Duunitori](https://duunitori.fi/tyopaikat) - Finland.
 - [jobbsafari.no](https://jobbsafari.no/ledige-stillinger) - Norway.
-- [NIJOBS](https://www.nijobs.com/) - Ireland.
+- [NIJOBS](https://www.nijobs.com/) - Northern Ireland.
 - [Hyper Island](https://jobs.hyperisland.com/)
 - [zuhausejobs.com](https://zuhausejobs.com) - Germany, Austria & Switzerland.
 - [lovejob](https://en.lovejob.lt/)
```

<details>
<summary>Evidence and limitations</summary>

<p>The site is a job board for Northern Ireland, not Ireland. Northern Ireland is part of the UK, so &#x27;Ireland.&#x27; is a factual error. Change it to &#x27;Northern Ireland.&#x27;</p>

<p>https://www.nijobs.com/ — HTTP 200. Title: &#x27;NIJobs.com | Jobs NI, Jobs in Northern Ireland, Recruitment NI&#x27;. Meta description: &#x27;NIJobs is Northern Ireland&#x27;s leading job site, listing thousands of jobs from employers and recruitment agencies throughout NI.&#x27;</p>

<p>Caveats: The site also brands itself &#x27;NIJobs.com&#x27;. The name change is optional, so it isn&#x27;t proposed here.</p>

</details>

<h3>zuhausejobs.com — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -718,7 +718,7 @@
 - [jobbsafari.no](https://jobbsafari.no/ledige-stillinger) - Norway.
 - [NIJOBS](https://www.nijobs.com/) - Ireland.
 - [Hyper Island](https://jobs.hyperisland.com/)
-- [zuhausejobs.com](https://zuhausejobs.com) - Germany, Austria & Switzerland.
+- [zuhausejobs.com](https://zuhausejobs.com) - Germany & Austria.
 - [lovejob](https://en.lovejob.lt/)
 - [Next Level Jobs EU](https://nextleveljobs.eu/) - €100k+ Software Engineering Jobs 🇪🇺.
 - [Euro Top Tech Jobs](https://www.eurotoptech.com/) - Top-Paying Tech Jobs in Europe and Remotely.
```

<details>
<summary>Evidence and limitations</summary>

<p>The site is live and relevant (German-language board of 100% remote/home-office jobs), but it now only covers Germany and Austria. The country picker offers only &#x27;Deutschland&#x27; and &#x27;Österreich&#x27;, the og:description says &#x27;in Deutschland und Österreich&#x27;, and neither the homepage nor the about page mentions Switzerland. The listed &#x27;Switzerland&#x27; coverage is not supported.</p>

<p>https://zuhausejobs.com/ — Title &#x27;Die besten Remote Jobs mit 100% Homeoffice&#x27;. The country selector lists only Deutschland and Österreich, with Germany/Austria flag icons only. og:description: &#x27;Remote Jobs und 100% Home Office Jobs in Deutschland und Österreich&#x27;. No occurrence of &#x27;Schweiz&#x27; or &#x27;Switzerland&#x27; in the HTML.</p>

<p>https://zuhausejobs.com/about — The about page describes searching thousands of job ads daily for 100% remote jobs (1,175 currently available). It does not mention Switzerland.</p>

<p>Caveats: Swiss remote roles may still show up incidentally, but the site no longer presents Switzerland as a supported market.</p>

</details>

<h3>NewLuxJob — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -735,7 +735,7 @@
 - [eububbleJobs](https://eububblejobs.com) - Jobs in Brussels and EU Institutions.
 - [France Dev Jobs](https://francedevjobs.com/) - Tech jobs in France at companies that work in English, taken directly from employers' own career sites. Free.
 - [Spain Dev Jobs](https://spain-devjobs.com/) - Tech jobs in Spain at companies that work in English, taken directly from employers' own career sites. Free.
-- [NewLuxJob](https://newluxjob.com/en/jobs) - Luxembourg and 15 other EU countries, jobs aggregated daily from public sources, in 9 languages.
+- [NewLuxJob](https://newluxjob.com/en/jobs) - Luxembourg and other European countries, jobs aggregated daily from public sources, in multiple languages.
 
 ### Malta
 
```

<details>
<summary>Evidence and limitations</summary>

<p>NewLuxJob is live and still aggregates jobs daily from public sources, with a 9-locale UI (de, en, es, fr, lu, nl, pl, ru, ua). The country claim is outdated: the jobs page now lists 17 countries, which is 16 besides Luxembourg, and they include non-EU Norway, Switzerland and the United States. &#x27;Luxembourg and 15 other EU countries&#x27; is therefore wrong; use durable wording without a count.</p>

<p>https://newluxjob.com/en/jobs — After a JS cookie check: title &#x27;All European jobs by country | NewLuxJob&#x27;; &#x27;955,427 open positions across 17 countries, refreshed daily from public job sources&#x27;. Countries: France, Germany, Belgium, Poland, Sweden, Czechia, United States, Netherlands, Spain, Norway, Luxembourg, Ireland, Italy, Portugal, Switzerland, Austria, Denmark. Locale links: de, en, es, fr, lu, nl, pl, ru, ua.</p>

<p>Caveats: The site serves a JavaScript cookie challenge with noindex before the real page; it is reachable with cookies. The site now also markets an AI career coach.</p>

</details>

## Uncertain findings

<h3>Resume Roaster — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The URL resume.roastlabai.com is live, but the product there is now branded &#x27;ResumeMint by Roast Lab AI&#x27;. The parent site roastlabai.com still lists the product as &#x27;Resume Roaster&#x27;. It offers an AI resume roast, an ATS score and per-job-description tailoring. Two things are unresolved: (1) whether the name should change to ResumeMint, since official pages conflict, and (2) the specific &#x27;flags missing keywords&#x27; claim, which no public page states.</p>

<p>https://resume.roastlabai.com/ — Title &#x27;Free AI Resume Roast + ATS Score | ResumeMint&#x27;; header &#x27;Resume Mint by Roast Lab AI&#x27;. Describes an honest score and tailoring bullets to a pasted job description. No explicit missing-keywords feature text.</p>

<p>https://resume.roastlabai.com/pricing — ResumeMint pricing $5/mo etc. Lists &#x27;Unlimited ATS score reports&#x27; and &#x27;Job match analysis&#x27;. One free tailoring on signup.</p>

<p>https://roastlabai.com/ — Parent Roast Lab AI site still lists a &#x27;Resume Roaster&#x27; product (&#x27;AI tears apart your resume ... gives you an ATS score&#x27;) at $4.99.</p>

<p>Blocking questions: Official pages disagree on the product name: &#x27;ResumeMint&#x27; on the listed domain, &#x27;Resume Roaster&#x27; on the parent site.; Could not confirm the &#x27;flags missing keywords&#x27; claim from public pages.</p>

<p>Caveats: The app is client-rendered and was not used. A missing-keyword feature may exist inside the product.</p>

<p>Independent source check: The listed landing page now presents ResumeMint, while the parent site still presents ResumeRoaster. Identity/branding is inconsistent; do not turn this into a confident rename or removal.</p>

<p>https://resume.roastlabai.com/ — Landing page presents ResumeMint and resume tailoring/scoring.</p>

<p>https://roastlabai.com/ — Parent product site still presents ResumeRoaster.</p>

</details>

<h3>X jobs — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Web search results say X&#x27;s official @XHiring account announced job search at x.com/jobs, and its bio reportedly still says &#x27;Try job search at x.com/jobs (available on web and iOS)&#x27;. But a logged-out fetch of x.com/jobs returned HTTP 404 with X&#x27;s &#x27;This account doesn&#x27;t exist&#x27; profile page. Unresolved: whether x.com/jobs still serves the job search, possibly only when logged in.</p>

<p>https://x.com/jobs — Logged-out fetch: HTTP 404, title &#x27;User Profile Not Found - X | 404 Error&#x27;, body &#x27;This account doesn&#x27;t exist&#x27;.</p>

<p>https://x.com/XHiring/status/1725263281646887300 — Search result for the official @XHiring post (Nov 2023): &#x27;Introducing our job search tool. Start exploring jobs on web at x.com/jobs.&#x27; Only the search snippet was seen; the post itself wasn&#x27;t fetched.</p>

<p>Blocking questions: Couldn&#x27;t confirm whether x.com/jobs currently serves X&#x27;s job search. The logged-out response is a profile-not-found 404.</p>

<p>Caveats: X is a client-rendered app that needs a login for most routes. A logged-out 404 may not reflect what logged-in users see.; Didn&#x27;t log in or render the page in a browser.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Hiretop ATS Resume Checker — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>Most claims are confirmed: free, no sign-up, shows the plain text the ATS extracts, and lists missing keywords against a job description. The one unresolved fact is whether results show &#x27;which requirements your resume proves&#x27;. The static page describes an ATS score, a readiness checklist and missing keywords, but never mentions requirement or evidence matching.</p>

<p>https://hiretop.com/ats-resume-checker — &#x27;See your resume the way an Applicant Tracking System reads it: plain text... Get a match score against the job and a list of the keywords you&#x27;re missing. No sign-up No email Up to 5 free checks a day.&#x27; The page also says &#x27;you get your ATS score, a readiness checklist and the exact keywords you&#x27;re missing&#x27;.</p>

<p>Blocking questions: Unverified: whether the report shows which job requirements the resume demonstrates. If it does not, that clause should be dropped.</p>

<p>Caveats: The checker was not run, so the content of the results UI was not observed.; Free use is capped at 5 checks a day, or 2 if you opt out of saving.</p>

</details>

<h3>ApplyChill — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>ApplyChill is live and its official copy confirms it is a free job search engine for tech and remote jobs from career pages and job boards, with AI resume tailoring and an autofill extension. The two remaining claims, &#x27;duplicates removed&#x27; and &#x27;real posting dates&#x27;, are not stated in any user-facing official text. The page data has repost_count and fake_freshness fields, but the homepage listing showed near-identical &#x27;Software Engineer I&#x27; Textron postings several times.</p>

<p>https://applychill.com/ — Meta: &#x27;ApplyChill is a free job search engine for tech and remote jobs from career pages and job boards. AI resume tailoring, autofill.&#x27; The nav has an &#x27;Autofill extension&#x27; link. Embedded job data includes reality:{repost_count, mass_posting_count, fake_freshness}. The listing shows three near-identical Textron &#x27;Software Engineer I&#x27; rows under different company labels.</p>

<p>https://applychill.com/pricing — Paid option &#x27;$14 once Get 90 days&#x27;. The footer repeats that it is a free job search engine. There is no dedup or posting-date statement.</p>

<p>Blocking questions: No official statement confirms deduplication or &#x27;real posting dates&#x27;. If these can&#x27;t be confirmed, those clauses should be dropped.</p>

<p>Caveats: The extension is not confirmed to be Chrome specifically. The nav only says &#x27;Autofill extension&#x27;.</p>

</details>

<h3>AI Tech Suite — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The site blocked access (HTTP 429 from a Vercel checkpoint on both curl and WebFetch), so current tool and job counts and the &#x27;updated daily&#x27; claim could not be checked. The only source for the counts is the founder&#x27;s August 2024 Hacker News launch post (&#x27;over 20k AI tools and 5000 AI jobs&#x27;), so those figures may be stale. The site&#x27;s identity as an AI tools/news/jobs aggregator is corroborated.</p>

<p>https://news.ycombinator.com/item?id=41395845 — Launch post dated August 29, 2024: &#x27;I used AI to scrape over 20k AI tools and 5000 AI jobs (aitechsuite.com)&#x27;. It describes an AI job board alongside the tool directory.</p>

<p>https://www.aitechsuite.com/jobs — Direct fetch returned HTTP 429 (Vercel Security Checkpoint). The content was not read.</p>

<p>Blocking questions: Current tool and job counts and whether jobs are &#x27;updated daily&#x27; are unverified. The figures date from August 2024.</p>

<p>Caveats: The access failure does not show the site is dead.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Robot Jobs Board — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The site returned HTTP 429 to curl and to WebFetch, then served a Vercel Security Checkpoint (JavaScript challenge), so the content could not be read first-hand. Search-engine snippets suggest it is a live robotics jobs board with AMR, Humanoid, Drone, Field and Industrial filters and ROS/ROS 2 skill tags. The same snippets describe coverage as US, UK, Canada and remote, not &#x27;Europe&#x27;. The regional claim is therefore unresolved.</p>

<p>https://www.robotjobsboard.com/ — Direct fetch returned HTTP 429 with a &#x27;Vercel Security Checkpoint — We&#x27;re verifying your browser&#x27; page. No content was readable.</p>

<p>Blocking questions: Could not confirm first-hand whether the site still covers &#x27;Europe&#x27; or only US/UK/Canada/remote, as search summaries indicate.</p>

<p>Caveats: Category and region details come only from a search-engine summary, not a direct page read. An access challenge is not evidence of a dead site.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Jobtensor — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>jobtensor.com returned HTTP 403 with a Cloudflare &#x27;Just a moment...&#x27; JavaScript challenge to both curl and WebFetch, so the site could not be read first-hand. Third-party listings (Crunchbase, review and directory sites) describe Jobtensor as an AI-powered job board for IT, science and engineering, including AI/ML roles, which is consistent with the entry. No official source confirmed this.</p>

<p>https://jobtensor.com/ — HTTP 403. Body is a Cloudflare challenge (&#x27;Just a moment... Enable JavaScript and cookies to continue&#x27;). No site content was readable.</p>

<p>Blocking questions: No first-party page could be read to confirm the current identity and AI/tech/science focus.</p>

<p>Caveats: Fit is corroborated only by third-party search summaries (e.g. Crunchbase, uxcel.com). The access block is not evidence that the site is defunct.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>AnalyticsVidhya Jobs — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The page loads and is branded Analytics Vidhya Jobs, a data science/AI jobs page, which fits the category. The open question is whether it still carries current listings. The job links in the fetched HTML point to datahack.analyticsvidhya.com/jobathon/... URLs, and the one I sampled resolved to a generic DataHack landing page rather than a job posting. Analytics Vidhya&#x27;s main site links to www.analyticsvidhya.com/jobs/, but that page is about India analytics careers and companies, not a confirmed replacement job board.</p>

<p>https://jobsnew.analyticsvidhya.com/jobs/all — HTTP 200, title &#x27;All Jobs|Analytics Vidhya&#x27;, meta &#x27;get latest jobs in data science, machine learning…&#x27;. Content is mostly login/onboarding shell. Job links go to datahack.analyticsvidhya.com/jobathon/* pages.</p>

<p>https://datahack.analyticsvidhya.com/jobathon/symphonyai-2/data-engineer-8 — Sampled job link returned a generic &#x27;DataHack Platform&#x27; page referencing a Job-A-Thon from Jan 2024, not the specific posting.</p>

<p>https://www.analyticsvidhya.com/jobs/ — Live page titled &#x27;Analytics Jobs | Analytics Career | Analytics Companies In India&#x27;. It is linked from the jobs page but its role as a successor is unconfirmed.</p>

<p>Blocking questions: Unknown whether jobsnew.analyticsvidhya.com currently shows live postings or is an abandoned shell.; No official statement names www.analyticsvidhya.com/jobs/ as the replacement job board.</p>

<p>Caveats: The listings may load via JavaScript that curl did not run.; Inaccessible or stale job links alone do not justify removal.</p>

</details>

<h3>FindADataJob — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>Live, free board for data analyst roles, and the &#x27;focused on data analyst roles&#x27; part holds. The &#x27;Global&#x27; claim is not confirmed: the site&#x27;s own copy gives no geographic scope, and every sampled listing is in the US or remote.</p>

<p>https://findadatajob.com/ — Title &#x27;Data Analyst Jobs | FindADataJob.com&#x27;. Meta: &#x27;Search thousands of real data analyst, data engineer, and business analyst jobs. Updated daily. Free job board…&#x27;. All 11 latest listings are US locations or &#x27;Remote&#x27;. Guides include &#x27;Best states for data analysts&#x27;.</p>

<p>Blocking questions: Unresolved whether the board covers jobs outside the US, so it is unclear whether &#x27;Global&#x27; should be dropped.</p>

<p>Caveats: I sampled only the homepage. A search page may include non-US jobs.</p>

</details>

<h3>CryptoJobs — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>crypto.jobs now 301-redirects to https://cryptojobslist.com/, which is already listed as entry 152. The &#x27;CryptoJobs&#x27; site no longer appears as a separate board, so this entry is effectively a duplicate. Removing it as a duplicate is probably right, but no official statement explains the redirect (acquisition, merger or domain sale). The maintainer should decide.</p>

<p>https://crypto.jobs/ — curl -I returns &#x27;HTTP/2 301&#x27; with &#x27;location: https://cryptojobslist.com/&#x27;. The final page is identical to entry 152 (title &#x27;Cryptocurrency Jobs and Blockchain Jobs (174 new in Nov 2026)&#x27;).</p>

<p>Blocking questions: No official statement confirms that the CryptoJobs board was merged into Crypto Jobs List or discontinued. The only evidence is the redirect.</p>

<p>Caveats: I didn&#x27;t search for an acquisition announcement or check domain ownership.</p>

</details>

<h3>Blockchain Jobs — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The site is live, on topic, and its meta description is close to the catalog wording. One claim is unresolved: whether the board lists jobs from &quot;protocol companies&quot;. The visible employers are mostly exchanges, custodians and analytics firms, and I couldn&#x27;t confirm any are protocol companies.</p>

<p>https://www.blockchainjobsboard.com/ — Title is &#x27;Blockchain Jobs Board | Web3, Crypto &amp; DeFi Careers&#x27;. Meta: &#x27;Browse the latest blockchain jobs from Web3, crypto, DeFi, and protocol companies.&#x27; The page shows recent listings from Kraken, Bitgo, Galaxy, OKX, Chainalysis and Blockstream.</p>

<p>Blocking questions: No current page shows an employer that is clearly a protocol company.</p>

<p>Caveats: The entry text has a trailing space; that&#x27;s formatting only.</p>

</details>

<h3>Maneki — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>Maneki is a live Web3 job board, but maneki.work returned a Vercel security checkpoint (HTTP 429) to every automated request. The official GitHub dataset confirms most claims: nightly refresh, normalized salary data, remote/work-mode fields, and stale listings removed within 24 hours. The &#x27;500+ companies&#x27; figure is unresolved. A search-index copy of the homepage says 283+ companies, and project texts variously say 500+, 600+ and &#x27;60+ sources&#x27;. If the site confirms a lower count, the description should drop the number.</p>

<p>https://github.com/Maneki-Work/jobs-data — README: aggregates roles &#x27;from top companies&#x27; career pages — normalized, deduplicated, and with stale listings removed within 24 hours&#x27;. Sample refreshed nightly. Fields include remote/work_mode and salary_min/max.</p>

<p>https://raw.githubusercontent.com/Maneki-Work/jobs-data/HEAD/meta.json — Generated 2026-11-10; total_active 2500, with_salary 777. No company count.</p>

<p>https://github.com/Maneki-Work/maneki-agent-gateway — README says jobs are &#x27;scraped nightly from 60+ sources&#x27;.</p>

<p>Blocking questions: Company count (&#x27;500+&#x27;) could not be confirmed against the live site.</p>

<p>Caveats: Could not read maneki.work directly (Vercel 429 checkpoint); the site is not dead.; The 283+ figure comes from a search-engine snippet, not a direct read.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>IdentitySecurityJobs — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>I could not read the live site, and the only archived evidence contradicts the description. The entry was added on 2026-11-09 in bulk commit 6318a0e (#335). The domain&#x27;s single Wayback capture (2026-10-14) is a NameBright &#x27;coming soon&#x27; parking page, not a job board. The live domain now returns a Vercel bot checkpoint (HTTP 429), and a web search found no mention of the domain. Whether a job board exists, and whether it covers IAM/PAM/IGA roles in the United States, is unverified.</p>

<p>https://identitysecurityjobs.com/ — curl and WebFetch both returned HTTP 429 with a &#x27;Vercel Security Checkpoint – We&#x27;re verifying your browser&#x27; page. No site content was visible.</p>

<p>http://web.archive.org/web/20261014155633/http://identitysecurityjobs.com/ — This is the only CDX capture of the domain. It reads &#x27;NameBright - Coming Soon. identitysecurityjobs.com is coming soon. This domain is managed at NameBright&#x27;.</p>

<p>Blocking questions: None of the description claims (IAM, PAM, identity governance, United States) can be verified from any readable source. The only historical capture is a parked domain. A maintainer should open the site in a browser before keeping it.</p>

<p>Caveats: The access failure alone does not show the site is dead. A Vercel deployment may have been added after the October capture.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>IndustrialCyberJobs — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>I could not read the live site, and the only archived evidence contradicts the description. The entry was added on 2026-11-09 in bulk commit 6318a0e (#335). The domain&#x27;s single Wayback capture (2026-10-15) is a NameBright &#x27;coming soon&#x27; parking page. The live domain now returns a Vercel bot checkpoint (HTTP 429), and a web search found no mention of the domain. Whether a job board exists, and whether it covers OT/ICS security across energy, utilities and manufacturing, is unverified.</p>

<p>https://industrialcyberjobs.com/ — curl and WebFetch both returned HTTP 429 with a &#x27;Vercel Security Checkpoint&#x27; page. No site content was visible.</p>

<p>http://web.archive.org/web/20261015083924/http://industrialcyberjobs.com/ — This is the only CDX capture of the domain. It reads &#x27;NameBright - Coming Soon. industrialcyberjobs.com is coming soon. This domain is managed at NameBright&#x27;.</p>

<p>Blocking questions: None of the description claims (OT/ICS security; energy, utilities, manufacturing) can be verified from any readable source. The only historical capture is a parked domain. A maintainer should open the site in a browser before keeping it.</p>

<p>Caveats: The access failure alone does not show the site is dead. A Vercel deployment may have been added after the October capture.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Full-Stack Developer Jobs — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The live site sits behind a Cloudflare JavaScript challenge (HTTP 403), so I could not see its content. The latest readable archive (2025-04-22) was a full-stack job board, but its title said &#x27;April 2022&#x27;. That suggests it had stopped updating, though this is not proven. No readable capture exists after April 2025. Whether it is currently a functioning full-stack job board is unknown.</p>

<p>https://fullstackjob.com/ — curl and WebFetch both returned HTTP 403 with a Cloudflare &#x27;Just a moment... Enable JavaScript and cookies to continue&#x27; page.</p>

<p>http://web.archive.org/web/20250422190249/https://fullstackjob.com/ — The title is &#x27;Fullstack Jobs - OnSite and Remote Full Stack Jobs - April 2022&#x27;. It shows full-stack listings (Cisco, Korn Ferry and others) and says it is built on Altafino job board software. CDX shows later captures only as 403s or empty responses, the last on 2026-02-02.</p>

<p>Blocking questions: Whether the site is currently live and how fresh its listings are cannot be determined. The latest readable copy is from April 2025 and was already titled &#x27;April 2022&#x27;.</p>

<p>Caveats: The access failure is not evidence the site is defunct.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>JavaScript Jobs — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The site is reachable and is the date-fns &#x27;JavaScript Jobs&#x27; board, which would fit the section. But its own jobs API currently returns no jobs, and I found no official statement saying whether the board is still running or has been abandoned.</p>

<p>https://jobs.date-fns.org/ — HTTP 200. The title is &#x27;JavaScript Jobs by date-fns&#x27;. The page is a client-rendered app whose bundle refers to api/jobs and to an Open Collective &#x27;promote-your-javascript-job&#x27; checkout.</p>

<p>https://jobs.date-fns.org/api/jobs — Returns {&quot;jobs&quot;:[],&quot;tags&quot;:{}}, meaning no listings right now.</p>

<p>Blocking questions: It is unresolved whether date-fns still runs the board or has quietly abandoned it. No official statement was found.</p>

<p>Caveats: I did not render the client app. I relied on the API response.</p>

</details>

<h3>React JS Jobs — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>reactjsjob.com is currently unreachable because the domain does not resolve (NXDOMAIN). The last successful archive capture is from April 2025, and its title still read &#x27;April 2022&#x27;. A failed connection alone does not justify removal, and I found no official statement that the board has shut down.</p>

<p>https://dns.google/resolve?name=reactjsjob.com&amp;type=A — Google DNS returns Status 3 (NXDOMAIN) for both the A and NS records, meaning the domain does not currently resolve.</p>

<p>http://web.archive.org/cdx/search/cdx?url=reactjsjob.com&amp;limit=-5&amp;output=txt — The last Wayback capture is from 2025-04-22 (HTTP 200). Earlier 2025 captures returned 403.</p>

<p>http://web.archive.org/web/20250422010222id_/https://reactjsjob.com/ — The April 2025 snapshot is a React job board titled &#x27;React Jobs - OnSite and Remote React Jobs - April 2022&#x27;.</p>

<p>Blocking questions: No official evidence that the board has been discontinued, and no documented successor. The maintainer should decide whether a domain that has stopped resolving justifies removal.</p>

<p>Caveats: The NXDOMAIN result came from a single resolver at a single point in time.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Jobless — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>Most of the description holds: the site is AI-powered job search, the free plan scores jobs, and the /jobs page shows about 3.9M open jobs, so &#x27;1M+ listings&#x27; is true. The &#x27;JobPosting schema&#x27; claim could not be checked because job detail pages returned a Cloudflare 403. Jobless is also a general job index rather than a remote-specific board, though it has a /jobs/remote page, so fit with the Remote section is open.</p>

<p>https://www.jobless.dev — HTTP 200. Title: &#x27;Jobless: World Index of Jobs&#x27;. Page text: &#x27;AI-Powered Job Search&#x27;. The Free plan (&#x27;$0 forever&#x27;) includes job scans, scoring and tailored resumes.</p>

<p>https://www.jobless.dev/jobs — HTTP 200. Shows &#x27;3,906,011 open jobs&#x27;, &#x27;272,058 companies hiring&#x27; and listings across all locations (Berlin, London, etc.), plus a link to /jobs/remote.</p>

<p>Blocking questions: Could not confirm the &#x27;JobPosting schema&#x27; claim: job detail pages and /jobs/remote returned a Cloudflare challenge (403).; It is open whether a general job search engine belongs in the Remote section.</p>

<p>Caveats: Job counts change over time; &#x27;1M+&#x27; holds today.</p>

</details>

<h3>Remote Developer Jobs — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The site responds and still presents itself as a remote software-engineer job board, but it looks frozen since March 2022. Its static build timestamp is 1648738932 (31 Mar 2022), and every listing shown is dated &#x27;Mar 30&#x27; or &#x27;Mar 31&#x27;. No official shutdown notice was found, so removal is not supported. Whether the site is still maintained is unresolved.</p>

<p>https://www.remote-developer-jobs.com/ — HTTP 200. Title: &#x27;Remote Developer Jobs&#x27;. Meta: &#x27;The best job board only for software engineers ... to work remotely&#x27;. All 30 listing dates are Mar 30/31. The Nuxt static asset path is /_nuxt/static/1648738932, which decodes to 2022-03-31.</p>

<p>Blocking questions: No official statement says whether the board is discontinued or still accepts postings.</p>

<p>Caveats: The visible dates have no year; the 2022 year comes from the build timestamp.</p>

</details>

<h3>remote.co — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>No remote.co page could be read: curl and WebFetch timed out on /remote-jobs/, the homepage and a blog page. Web search snippets suggest the site is operating in 2026, but no primary source was read. A timeout alone does not justify removal.</p>

<p>Blocking questions: Whether https://remote.co/remote-jobs/ is reachable and still lists jobs remains unverified because every access attempt timed out.</p>

<p>Caveats: Search-result snippets (e.g. a remote.co 2026 blog post) are not treated as verified evidence.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>FlexJobs — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>No FlexJobs page could be read: curl and WebFetch timed out on the homepage, /remote-jobs and a blog page. Search snippets suggest FlexJobs is active in 2026, but no primary source was read. A timeout alone does not justify removal.</p>

<p>Blocking questions: Reachability and current content of https://www.flexjobs.com/ remain unverified because every access attempt timed out.</p>

<p>Caveats: Search-result snippets (e.g. the FlexJobs Q3 2026 remote work index) are not treated as verified evidence.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>4DayJob — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The site redirects to www.4dayjob.com and is still a 4-day work week job board with a Remote filter, so its identity and fit are confirmed. The specific &#x27;1,500+ flexible opportunities&#x27; count could not be found anywhere on the current homepage, and /jobs returns 404. The volatile count is neither confirmed nor refuted.</p>

<p>https://www.4dayjob.com/ — https://4dayjob.com/ redirects here (HTTP 200). Title is &#x27;4DayJob - Find 4-Day Work Week Jobs&#x27;. Meta: &#x27;Discover companies offering 4-day work weeks.&#x27; The page has category and location filters including &#x27;🌍 Remote&#x27; and 11 pages of listings. No total job count such as &#x27;1,500+&#x27; was found on the page.</p>

<p>https://www.4dayjob.com/jobs — Returned HTTP 404, so a dedicated listing count could not be checked.</p>

<p>Caveats: The listings may be rendered client-side, so the total count may exist but not be visible to a non-JS fetch.; Dropping the count (for example: &#x27;4-day work week and remote job board.&#x27;) would be more durable. This is optional unless the count is shown to be wrong.</p>

</details>

<h3>JobCroissant — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The site returned HTTP 429 with a Vercel Security Checkpoint (bot challenge) to every request, including robots.txt and sitemap.xml. The current description could not be verified from the official site. Secondary signals suggest it is an active US bakery job board, which does not justify removal.</p>

<p>https://jobcroissant.com/ — HTTP 429, &#x27;Vercel Security Checkpoint ... Enable JavaScript to continue&#x27;. WebFetch also got a 429.</p>

<p>https://github.com/emredurukn/awesome-job-boards/pull/237 — A search snippet shows the operator added JobCroissant via a PR, describing it as a bakery job board and saying &#x27;I run both of the proposed additions&#x27;. This is the operator&#x27;s own claim, not independent evidence.</p>

<p>https://web.archive.org/web/20250712051922/http://jobcroissant.com/ — The July 2025 archive shows a parked Dynadot &#x27;Website coming soon&#x27; page, so the site is relatively new.</p>

<p>Blocking questions: Could not read the live site to confirm its role coverage, US geography, or that it is free for job seekers.</p>

<p>Caveats: Only search-engine snippets were seen. They describe the site as a US baker, pastry chef and cake decorator job board.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>PrivateClubCareers — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The site returned HTTP 429 with a Vercel bot checkpoint to every request. Its current content and description claims could not be verified.</p>

<p>https://privateclubcareers.com/ — HTTP 429, Vercel Security Checkpoint. WebFetch also got a 429.</p>

<p>https://github.com/emredurukn/awesome-job-boards/pull/335 — Merged Nov 9, 2026. It adds PrivateClubCareers under Hospitality &amp; Food Service. The submitter appears to operate the board through the &#x27;Rolework&#x27; network.</p>

<p>Blocking questions: Could not read the live site to confirm private club management, golf operations and club dining job coverage in the US.</p>

<p>Caveats: The Rolework network page, which reportedly lists the board, also returned a Vercel 429.; The 2011 archive shows an expired, unrelated domain, so the current site is new.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>GymHires — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The site returned HTTP 429 with a Vercel bot checkpoint to every request. Its current content and description claims could not be verified.</p>

<p>https://gymhires.com/ — HTTP 429, Vercel Security Checkpoint. WebFetch also got a 429.</p>

<p>https://github.com/emredurukn/awesome-job-boards/pull/335 — Merged Nov 9, 2026. It adds GymHires under Fitness &amp; Outdoors, submitted by the apparent Rolework operator.</p>

<p>Blocking questions: Could not read the live site to confirm gym management, personal training and group fitness job coverage in the US.</p>

<p>Caveats: A 2025 archive shows an unrelated framed page, so the current board is new.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>GreenLever — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>GreenLever is live, but it is not a climate or green-tech board. It is a general aggregator of jobs posted on the Greenhouse and Lever applicant-tracking systems (the &#x27;Green&#x27;+&#x27;Lever&#x27; name is about those two systems, not the environment). It appears to have been moved into Climate &amp; Green Tech by mistake when the section was created. The identity and URL are correct and the site works. The issue is category fit, and the schema has no &#x27;move&#x27; action. The maintainer should decide whether to move it to General or Job Search Tools, or to drop it.</p>

<p>https://greenlever.co/ — HTTP 200. Meta description: &#x27;Looking for jobs on Greenhouse or Lever? Greenlever.co aggregates 1000+ openings from both platforms. Apply faster as a Developer, Designer, Marketer, and more!&#x27; Footer: &#x27;Apply to your favorite ATS like Greenhouse and Lever quickly and efficiently.&#x27; Popular searches are Engineering, Design, Marketing, Sales and so on. The page never mentions climate or sustainability.</p>

<p>https://github.com/emredurukn/awesome-job-boards/commit/885a3a9 — Added on 2024-08-30 (&#x27;Add GreenLever jobs&#x27;) as a bare &#x27;* [GreenLever]&#x27; line. Commit b2cb322 later moved it into the new Climate &amp; Green Tech section.</p>

<p>Blocking questions: The entry is reachable and correctly identified, but it does not fit the Climate &amp; Green Tech section. The fix is to move it (for example to General or Job Search Tools) or remove it, which needs a maintainer decision this schema cannot express.</p>

<p>Caveats: The server-rendered counters showed &#x27;Organizations: 0 Jobs: 0&#x27;. These are probably loaded client-side, so I did not verify the current listing volume.; The /about page returned 404.</p>

</details>

<h3>BiogasJobs — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>I could not read the current site: it returns HTTP 429 from a Vercel Security Checkpoint, to robots.txt and sitemap requests too. The latest Wayback capture (2026-10-15) shows a NameBright &#x27;coming soon&#x27; parked page. The site was added on 2026-11-09 by its operator (Rolework, PR #335), who says it was live with jobs at that time. Its current content and the biogas/RNG/anaerobic-digestion focus are unverified.</p>

<p>http://web.archive.org/web/20261015003822/http://biogasjobs.com/ — &#x27;NameBright - Coming Soon. biogasjobs.com is coming soon.&#x27; The domain was parked in mid-October 2026.</p>

<p>https://github.com/emredurukn/awesome-job-boards/pull/335 — The submitter (vinbaus) says &#x27;I run these boards through Rolework&#x27; and that the sites were checked on 2026-11-09 for HTTPS and active listings. The maintainer merged it.</p>

<p>Blocking questions: The current site content and whether it has real listings could not be observed.</p>

<p>Caveats: The Vercel bot checkpoint blocks all non-browser fetches. The block itself is not evidence that the site is down.; The listing was added by the operator, not reviewed independently.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>CarbonCaptureCareers — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The live site is blocked by a Vercel Security Checkpoint (HTTP 429) and has no Wayback captures. A search snippet of Rolework&#x27;s network page describes it as &#x27;The Job Board for Carbon Capture, Carbon Removal &amp; CO2 Storage Jobs&#x27;, which matches the entry. I could not read that page directly (also 429), and the site&#x27;s own content is unverified.</p>

<p>https://woodworkingcareers.com/rolework-network — Seen only as a search-result summary, since direct fetch returned 429. It lists CarbonCaptureCareers as &#x27;The Job Board for Carbon Capture, Carbon Removal &amp; CO2 Storage Jobs&#x27;.</p>

<p>https://github.com/emredurukn/awesome-job-boards/pull/335 — Added on 2026-11-09 by the Rolework operator, who disclosed the affiliation.</p>

<p>Blocking questions: The live site could not be read, so the listings and scope are unverified.</p>

<p>Caveats: Access was blocked by a bot checkpoint. This does not show the site is dead.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>DecarbonizationJobs — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The live site is blocked by a Vercel Security Checkpoint (HTTP 429). The only Wayback capture (2025-07-11) has an empty body. The operator added it on 2026-11-09. Its focus (sustainability, carbon accounting, decarbonization) and the &#x27;United States&#x27; scope are unverified.</p>

<p>https://decarbonizationjobs.com/ — HTTP 429, &#x27;Vercel Security Checkpoint&#x27;, for /, /robots.txt and /sitemap.xml.</p>

<p>https://github.com/emredurukn/awesome-job-boards/pull/335 — Added by the Rolework operator, who disclosed the affiliation.</p>

<p>Blocking questions: The live content, including the US-only scope, could not be observed.</p>

<p>Caveats: The access block is not evidence of a dead site.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>ElectrifyJobs — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The live site is blocked by a Vercel Security Checkpoint (HTTP 429) and has no Wayback captures. The operator added it on 2026-11-09. The electrification/EV-charging focus and the US scope are unverified.</p>

<p>https://electrifyjobs.com/ — HTTP 429, &#x27;Vercel Security Checkpoint&#x27;. The Wayback availability API returned no snapshots.</p>

<p>https://github.com/emredurukn/awesome-job-boards/pull/335 — Added by the Rolework operator, who disclosed the affiliation.</p>

<p>Blocking questions: The live content could not be observed.</p>

<p>Caveats: The access block is not evidence of a dead site.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>HydroCareers — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The live site is blocked by a Vercel Security Checkpoint (HTTP 429). The only Wayback capture is from 2016, an unrelated expired-domain parking page, so the domain has changed hands. The operator added the current board on 2026-11-09. Its hydropower focus is unverified.</p>

<p>https://hydrocareers.com/ — HTTP 429, &#x27;Vercel Security Checkpoint&#x27;.</p>

<p>http://web.archive.org/web/20160313143343/http://hydrocareers.com/ — 2016 capture: &#x27;This Domain Name Has Expired&#x27;. It is a spam parking page unrelated to the current operator.</p>

<p>Blocking questions: The live content could not be observed.</p>

<p>Caveats: The access block is not evidence of a dead site.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>NuclearHires — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The live site is blocked by a Vercel Security Checkpoint (HTTP 429). The latest Wayback capture (2026-10-14) shows a NameBright &#x27;coming soon&#x27; parked page. A search snippet of Rolework&#x27;s network page describes it as &#x27;The Job Board for Nuclear Power, SMR &amp; Fusion Energy Jobs&#x27;, which matches the entry. The live listings and the US scope are unverified.</p>

<p>http://web.archive.org/web/20261014230641/http://nuclearhires.com/ — &#x27;NameBright - Coming Soon. nuclearhires.com is coming soon.&#x27;</p>

<p>https://woodworkingcareers.com/rolework-network — Seen only as a search snippet: &#x27;NuclearHires: The Job Board for Nuclear Power, SMR &amp; Fusion Energy Jobs&#x27;.</p>

<p>Blocking questions: The live content and whether it has real listings could not be observed.</p>

<p>Caveats: The access block is not evidence of a dead site.; Added on 2026-11-09 by its operator.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>SolarHires — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The live site is blocked by a Vercel Security Checkpoint (HTTP 429), and the 2025 Wayback capture has an empty body. A search snippet of Rolework&#x27;s network page describes it as &#x27;The Job Board for Solar Installation, Project Development &amp; Engineering Jobs&#x27;, which matches the entry. The live listings and the US scope are unverified.</p>

<p>https://solarhires.com/ — HTTP 429, &#x27;Vercel Security Checkpoint&#x27;.</p>

<p>https://woodworkingcareers.com/rolework-network — Seen only as a search snippet; direct fetch returned 429. It lists SolarHires with a tagline that matches the entry.</p>

<p>Blocking questions: The live content could not be observed.</p>

<p>Caveats: The access block is not evidence of a dead site.; Added on 2026-11-09 by its operator.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Codersrank — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>jobs.codersrank.io still returns HTTP 200 as a WordPress job portal, and the CodersRank main site is live. However, the newest listings I could find date from October 2024, about two years ago. The portal footer also shows placeholder contact details (&#x27;Phone (123) 123-456&#x27;, &#x27;mail@example.com&#x27;). I found no official statement that the job portal has been discontinued, so I can&#x27;t tell whether it is still maintained.</p>

<p>https://jobs.codersrank.io/ — HTTP 200. Title: &#x27;CodersRank Job Portal&#x27;. Links to /job/... listings. The newest datetime on the page is 2024-10-18. Footer contact details are placeholders.</p>

<p>https://jobs.codersrank.io/feed/?post_type=job_listing — Job listing RSS lastBuildDate is Thu, 17 Oct 2024. The newest items were published 16–17 Oct 2024.</p>

<p>https://codersrank.io/ — HTTP 200. Title: &#x27;The Ultimate Developer Profile - CodersRank&#x27;. The parent product is still live.</p>

<p>Blocking questions: No official statement says the CodersRank job portal is discontinued or still maintained. Stale listings alone do not justify removal.</p>

<p>Caveats: The WordPress REST API is restricted (401), so I couldn&#x27;t check whether newer unlisted jobs exist.</p>

</details>

<h3>LinkUp — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>linkup.com now presents itself as a job-market data provider for investors and researchers (&#x27;Job Market Data | LinkUp&#x27;, &#x27;a GlobalData Company&#x27;), not a job search site for job seekers. Its homepage has no job-search links. The old job-seeker search path (www.linkup.com/search/results) redirected to search.linkup.com in Dec 2024, and that host now returns 502 through my proxy. This strongly suggests the job-seeker search is gone. I could not confirm that live because linkup.com returns a Cloudflare 403, and I found no official statement that the job search was retired.</p>

<p>https://linkup.com/ — 301 to https://www.linkup.com/, which returns a Cloudflare 403 challenge to automated clients.</p>

<p>http://web.archive.org/web/20260914122614/https://www.linkup.com/ — Capture from 2026-09-14. Title: &#x27;Job Market Data | LinkUp&#x27;. Description: &#x27;Access 350+ million real-time job postings... Conduct competitive research, find investment opportunities.&#x27; Links are to industry solutions, research and blog posts, with no job search.</p>

<p>https://www.linkup.com/products/raw — Search results show LinkUp selling &#x27;RAW&#x27; job-posting datasets via Snowflake, AWS and other platforms. It is positioned as a data product (GlobalData acquired LinkUp in 2024).</p>

<p>https://hs.globaldata.com/linkup-compass-start-a-free-trial — GlobalData markets LinkUp Compass as a company-hiring analytics tool, not a job board.</p>

<p>Blocking questions: No official LinkUp statement confirms that job seekers can no longer search listings, for example on search.linkup.com. Removal would need that confirmation.</p>

<p>Caveats: Live linkup.com and search.linkup.com could not be read (403 and 502). Evidence comes from archive captures and search-result summaries.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>CSS-Tricks Jobs — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The URL resolves (HTTP 200) to a &#x27;Job Board | CSS-Tricks&#x27; page, but it no longer looks like a working job board. The HTML has an empty &lt;div id=&quot;jobs&quot;&gt;&lt;/div&gt; and no script I could find fills it. The page shows no listings, only a &#x27;Post a job!&#x27; button to codepen.io/jobs/post. Its metadata dates from 2014. Historically this page was fed by the CodePen Job Board. A third-party review says CodePen no longer offers a job board, but I found no official CodePen or CSS-Tricks statement, and codepen.io/jobs sits behind a Cloudflare challenge. Whether the board still has listings, which would mean keep, or is officially discontinued, which would mean remove, is unresolved.</p>

<p>https://css-tricks.com/jobs/ — HTTP 200, title &#x27;Job Board | CSS-Tricks&#x27;. Rendered text has no job listings. The HTML contains an empty &lt;div id=&quot;jobs&quot;&gt;&lt;/div&gt; and a &#x27;Post a job!&#x27; link to https://codepen.io/jobs/post. Schema metadata: datePublished 2014-12-01, dateModified 2014-12-06. No inline script or global-concat.min.js code references jobs.</p>

<p>https://css-tricks.com/codepen-job-board/ — Search result for a CSS-Tricks post introducing the CodePen Job Board as the shared board (historical context).</p>

<p>https://blog.codepen.io/2014/12/08/announcing-codepen-job-board/ — Search result: CodePen announced the board in Dec 2014 as the official board for CodePen, CSS-Tricks and ShopTalk Show.</p>

<p>https://www.betterteam.com/codepen-io — Third-party, not official. Per search summary it states &#x27;CodePen no longer offers a job board for tech professionals&#x27;.</p>

<p>https://codepen.io/jobs — HTTP 403 Cloudflare &#x27;Just a moment...&#x27; challenge, so I could not check whether CodePen Jobs still exists.</p>

<p>Blocking questions: No official source confirms whether the CodePen/CSS-Tricks job board is discontinued.; codepen.io/jobs could not be read because of a bot challenge.</p>

<p>Caveats: Listings could load in a way I did not detect, such as a browser-only widget.</p>

</details>

<h3>StackShare — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>I could not read stackshare.io/match directly: curl and WebFetch both got HTTP 429 from a Vercel Security Checkpoint. A search index shows a page titled &#x27;StackShare Job Search: Find Jobs Near Me&#x27; at /match with a query string, and StackShare previously said Stack Match was rebuilt as &#x27;Jobs on StackShare&#x27;. I could not confirm that the job search currently works, so its status is unresolved. An access failure is not evidence that it is gone.</p>

<p>https://stackshare.io/match — HTTP 429 from the Vercel Security Checkpoint on both curl and WebFetch. Content unreadable.</p>

<p>https://www.stackshare.io/match?selectedTools=integromat — Search index entry titled &#x27;StackShare Job Search: Find Jobs Near Me&#x27;, inviting users to explore part-time, full-time, remote and contracting jobs. The snapshot is undated.</p>

<p>https://stackshare.io/posts/introducing-the-new-job-board — Search result: StackShare announced a redesign of Jobs on StackShare (previously called Stack Match).</p>

<p>Blocking questions: The current function of stackshare.io/match could not be confirmed from a live read.</p>

<p>Caveats: Rate limiting prevented reading the live page.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>CampaignJobs — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>I could not confirm whether CampaignJobs is still operating. The live site (jp.campaignlive.co.uk, and campaignlive.co.uk/jobs) returns a Cloudflare 403 challenge to all my clients. A web-search summary claimed the homepage now says &#x27;Campaignjobs has now closed&#x27;, but I could not read that text on any page. The latest readable Wayback snapshot (30 June 2026) still showed an active Campaign Jobs board for marketing, advertising, creative and media jobs, with only a few listings. Later archive captures (July–Sept 2026) are all 403. Closure is plausible but uncorroborated, so removal is not supported yet.</p>

<p>https://jp.campaignlive.co.uk/jobs — HTTP 403 &#x27;Just a moment...&#x27; (Cloudflare challenge) to both curl and WebFetch.</p>

<p>https://web.archive.org/web/20260630211125/https://jp.campaignlive.co.uk/jobs — Archived 30 June 2026: &#x27;Browse Jobs&#x27; page with job-seeker and recruiter sign-in, job alerts and a handful of listings (e.g. Homeworking (2), London (2)).</p>

<p>https://web.archive.org/web/20260630211125id_/https://jp.campaignlive.co.uk/ — Archived homepage: &#x27;Search jobs in marketing, advertising, creative and media&#x27;. No closure notice in this capture.</p>

<p>https://web.archive.org/cdx/search/cdx?url=jp.campaignlive.co.uk*&amp;from=202607 — All archive captures from July 2026 onward returned 403, so none show the current state.</p>

<p>Blocking questions: A maintainer needs to open https://jp.campaignlive.co.uk/ in a real browser to see whether it shows a &#x27;Campaignjobs has now closed&#x27; notice or live listings.</p>

<p>Caveats: The &#x27;has now closed&#x27; claim came only from a search-engine summary that I could not verify against the page.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>SemiconductorHires — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>I could not read the site. Direct fetches got HTTP 429 from a Vercel Security Checkpoint, so there is no evidence on whether the description is accurate or the site is relevant. A web search for &#x27;SemiconductorHires&#x27; found nothing, and the Wayback Machine has no snapshots. The access failure alone does not justify removal.</p>

<p>https://semiconductorhires.com/ — HTTP 429. The page title is &#x27;Vercel Security Checkpoint&#x27; (a bot challenge). No content was readable.</p>

<p>http://web.archive.org/wayback/available?url=semiconductorhires.com — The Wayback Machine has no archived snapshots.</p>

<p>Blocking questions: Unknown: whether the site lists chip design, fabrication and equipment engineering jobs in the US as the description says.</p>

<p>Caveats: The site may be fine in a real browser. The checkpoint blocked automated access.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>SpaceTechCareers — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>I could not read the site. Direct fetches got HTTP 429 from a Vercel Security Checkpoint. The only Wayback snapshot is from 2021, and search found nothing for &#x27;SpaceTechCareers&#x27;. The description (satellite, launch and space systems jobs in the US) cannot be confirmed. The access failure alone does not justify removal.</p>

<p>https://spacetechcareers.com/ — HTTP 429. The page title is &#x27;Vercel Security Checkpoint&#x27;. No content was readable.</p>

<p>http://web.archive.org/web/20211225094319/http://spacetechcareers.com/ — The only archived capture is from 2021-12-25 and has no meaningful content relevant to the current site.</p>

<p>Blocking questions: Unknown: whether the current site is a US space-industry job board as described.</p>

<p>Caveats: The site may be fine in a real browser.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Internasia — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>internasia.com currently returns a Vercel Security Checkpoint (HTTP 429), so I could not read it. Wayback captures from 2025, including 2025-10-14, show a parked domain page: Google AdSense for domains (caf.js) and &#x27;parked&#x27; markup. Captures from March 2025 returned HTTP 410. I found no evidence that it is currently a site for English-speaking internships in Asia. Search turned up internsinasia.com (Asia Internship Program), which is a different domain and not an officially documented successor.</p>

<p>https://internasia.com/ — HTTP 429. The page title is &#x27;Vercel Security Checkpoint&#x27;. No content was readable.</p>

<p>http://web.archive.org/web/20251014121058/https://www.internasia.com/ — The 2025-10-14 snapshot is a parked-domain ad page: title &#x27;internasia.com&#x27;, AdSense domains caf.js, and &#x27;parked&#x27; CSS/JS markers. The Wayback index shows HTTP 410 captures in March 2025 and HTTP 200 captures from then through Oct 2025.</p>

<p>https://www.internsinasia.com/ — An unrelated-domain internship program for Asia (AIP). Nothing establishes it as a successor of internasia.com.</p>

<p>Blocking questions: Unknown: whether internasia.com currently hosts an internship board or is still parked or repurposed. Removal would need a readable current page.</p>

<p>Caveats: The site may have been relaunched on Vercel after Oct 2025. I could not see the current content.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Startup Jobs — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>Startup.jobs blocks automated fetches with a Cloudflare 403, so I could not read the page myself. Search results and a third-party university page (Penn career services) describe it as a free startup job board that is updated daily. Search snippets show site pages dated September and November 2026. It very likely fits Startups, but I could not read a primary source.</p>

<p>https://startup.jobs/ — HTTP 403 Cloudflare &#x27;Just a moment...&#x27; challenge on direct fetch.</p>

<p>https://careerservices.upenn.edu/resources/startup-jobs/ — Search result: Penn career services lists Startup Jobs as a free startup job board that is updated daily (secondary source).</p>

<p>Blocking questions: The primary page could not be read directly to confirm its current content.</p>

<p>Caveats: The evidence for relevance comes from search snippets and secondary sources only.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>WorkinStartups — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>WorkinStartups returns HTTP 403 on direct fetch, so I could not read the page. Search snippets show the site calls itself &#x27;The UK&#x27;s number 1 site for startup jobs&#x27;, with UK and London startup job search pages, which fits Startups. I could not confirm this from a primary page.</p>

<p>https://workinstartups.com/ — HTTP 403 with an empty body on direct fetch.</p>

<p>https://workinstartups.com/search — Search result titled &#x27;UK startup Jobs&#x27; on the same domain. Snippets describe it as &#x27;The UK&#x27;s number 1 site for startup jobs&#x27; (indexed content, not fetched).</p>

<p>Blocking questions: The primary page could not be read directly to confirm its current content.</p>

<p>Caveats: Secondary sources note the site aggregates many non-startup listings, such as large employers. That is a quality caveat, not a reason to remove it.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Basin.cv — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>basin.cv is currently down. The homepage and its subpages return HTTP 402 with the Vercel error DEPLOYMENT_DISABLED, which is a hosting/deployment state, not an announcement that the project is discontinued. Search-indexed pages show it was recently a startup job board browsable by funding stage and role, which fits the Startups section. Whether the outage is temporary is unknown.</p>

<p>https://basin.cv/ — HTTP/2 402 with header &#x27;x-vercel-error: DEPLOYMENT_DISABLED&#x27; and body &#x27;Payment required DEPLOYMENT_DISABLED&#x27;. /jobs/stages/series-b also returns 402.</p>

<p>https://basin.cv/jobs/stages/series-b — Search-engine results (not read directly) show &#x27;Series B Startup Jobs — Basin&#x27; with listings such as Sentilink, Varda, Reducto and Figure, and the tagline &#x27;Browse roles at high-growth tech companies&#x27;.</p>

<p>Blocking questions: Unresolved: whether basin.cv will be restored or has been abandoned. I found no official statement either way. Recheck later before deciding.</p>

<p>Caveats: The access failure alone doesn&#x27;t justify removal. A disabled deployment can be restored.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>EU-Startups Job Board — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The live page is behind a Cloudflare challenge (HTTP 403). An archived copy from 2026-10-25 shows the board is active under the title &#x27;Startup Jobs in Europe&#x27;, with new postings on most days from Oct 18–24. However, many sampled listings were companies in the US, India and Australia (for example, Los Angeles, Kolkata, Sydney, and US-remote freelance roles). That calls into question the claim &#x27;Jobs at European startups&#x27;. I couldn&#x27;t confirm the current listing mix or the &#x27;updated daily&#x27; claim on the live site.</p>

<p>https://www.eu-startups.com/startup-jobs/ — Live fetch: HTTP 403 &#x27;Just a moment… Enable JavaScript and cookies to continue&#x27; (Cloudflare challenge).</p>

<p>https://web.archive.org/web/20261025000322/https://www.eu-startups.com/startup-jobs/ — Archived 2026-10-25, page &#x27;Startup Jobs in Europe&#x27; on the EU-Startups site. Listings were dated Oct 18–24, among them MonTeams (Los Angeles), drone pathshala (Kolkata, India), Custom Iron on Patches (Sydney), several US-remote contractor roles, and WiT Money UK (London) and Weights AI (Edinburgh).</p>

<p>Blocking questions: Unresolved: whether the current listings are mainly European startups. If not, &#x27;Jobs at European startups&#x27; would need rewording, and I couldn&#x27;t read the live page to confirm.; I couldn&#x27;t confirm the &#x27;updated daily&#x27; cadence from the live site.</p>

<p>Caveats: Based on one archived snapshot, not the current live page.; The board is still part of a European startup media site and is presented as European, so it remains broadly relevant to the Startups section.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Hanzilla Jobs — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The site is reachable and still describes itself as a daily-updated Canadian board for student and new-grad jobs (internships, co-ops, new grad, junior, entry-level). However, the homepage, /new-grad/ and /internships/ all showed &#x27;0 positions&#x27; and &#x27;No positions available at the moment&#x27; on 2026-11-10, and its GitHub source repo lists &#x27;No roles currently&#x27; in every category. Unresolved: is this a temporary pipeline outage or has the board stopped publishing jobs? That decides whether &#x27;Daily-updated&#x27; is still accurate.</p>

<p>https://jobs.hanzilla.co/ — Title &#x27;2026 Canada Student New Grad &amp; Entry-Level Jobs | Updated Daily&#x27;. Body: &#x27;Search 0 new grad/junior positions…&#x27; and &#x27;No positions available at the moment. Check back soon!&#x27; Meta says &#x27;0 roles updated daily&#x27;.</p>

<p>https://jobs.hanzilla.co/internships/ — &#x27;Search 0 internship positions…&#x27;, &#x27;No positions available at the moment.&#x27; &#x27;Updated daily at 09:00 UTC.&#x27;</p>

<p>https://github.com/hanzili/canada_sde_junior_new_grad_position — Linked source repo is not archived, has 511 commits, and is described as daily-updated. Every category currently shows &#x27;No roles currently&#x27;. Latest commit date was not retrieved (GitHub API TLS failure in sandbox).</p>

<p>Blocking questions: Unknown whether the zero-listing state is a temporary data-pipeline failure or a sign that the board has stopped publishing jobs; recheck later.</p>

<p>Caveats: Single-day observation; job counts may come back.; Could not get the latest commit date from the GitHub API.</p>

</details>

<h3>SpotJobs — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>spotjobs.com sits behind a Vercel security checkpoint (429) and could not be read. Its terms of service (via search) describe a general Australian job board run by Lespino Group (France). An older LinkedIn profile described retail and hospitality jobs. The only FIFO-related page indexed on spotjobs.com is an old BHP intern listing. The specific claim of a FIFO / remote-site / mining / camp-services focus is unconfirmed.</p>

<p>https://spotjobs.com/ — curl and WebFetch both returned HTTP 429 &#x27;Vercel Security Checkpoint&#x27;; no content read.</p>

<p>https://spotjobs.com/terms-of-service/ — Via search snippet (direct fetch got 429): describes a job board platform operated by Lespino Group for employers, agencies and job seekers in Australia; no FIFO focus mentioned in the snippet.</p>

<p>https://spotjobs.com/job-offer/2025-australian-intern-campaign/ — Indexed BHP intern listing mentioning FIFO; this was the only FIFO-related spotjobs.com result.</p>

<p>Blocking questions: Unverified whether SpotJobs currently focuses on FIFO / remote-site / mining / camp-services jobs or is a general Australian job board; the homepage must be read in a browser.</p>

<p>Caveats: The site could not be accessed directly; the access failure says nothing about whether the project is alive.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>FireSafetyCareers UK — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The site returns HTTP 429 (Vercel Security Checkpoint) to both curl and WebFetch, so its content could not be read. Search results suggest the board belongs to the Rolework network and covers fire risk assessor, fire engineer and building safety jobs in the UK. That matches the description, but only through search summaries of operator-written pages.</p>

<p>https://firesafetycareers.co.uk/ — HTTP 429 with a Vercel Security Checkpoint page. Content was not readable.</p>

<p>https://github.com/emredurukn/awesome-job-boards/pull/335 — Search snippet: PR #335 (Nov 2026) by the operator (vinbaus/Rolework) adds FireSafetyCareers UK, PropCareers and QSCareers under UK.</p>

<p>Blocking questions: The board&#x27;s content and focus have not been read directly. The description&#x27;s accuracy is still unconfirmed.</p>

<p>Caveats: Access was blocked by a bot checkpoint, not a site outage. This does not suggest the site is dead.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>PropCareers — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The site returns HTTP 429 (Vercel Security Checkpoint), and the Rolework network page was also blocked. The claim that it covers commercial property jobs in surveying, asset management and valuation could not be checked.</p>

<p>https://propcareers.co.uk/ — HTTP 429 with a Vercel Security Checkpoint page. Content was not readable.</p>

<p>https://woodworkingcareers.com/rolework-network — Direct fetch returned 429. A search summary says PropCareers appears in the Rolework network list without a description.</p>

<p>Blocking questions: The site&#x27;s content and specialisation could not be read. The description claims are still unconfirmed.</p>

<p>Caveats: Access was blocked by a bot checkpoint, which is not evidence that the site is gone.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>QSCareers — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The site returns HTTP 429 (Vercel Security Checkpoint). The claim that it covers quantity surveying, cost consultancy and construction commercial management jobs could not be checked against the site itself.</p>

<p>https://qscareers.co.uk/ — HTTP 429 with a Vercel Security Checkpoint page. Content was not readable.</p>

<p>https://github.com/emredurukn/awesome-job-boards/pull/335 — Search snippet: the operator added QSCareers under UK in PR #335. A search summary says the maintainer&#x27;s reply mentioned quantity surveying.</p>

<p>Blocking questions: The site&#x27;s content and specialisation could not be read. The description claims are still unconfirmed.</p>

<p>Caveats: Access was blocked by a bot checkpoint, which is not evidence that the site is gone.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Subito — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link to the Subito homepage. Direct requests returned HTTP 403 (Access Denied, likely bot protection), so I couldn&#x27;t read the current page. Search-engine indexes show Subito.it has an &#x27;Offerte di lavoro&#x27; (job offers) category for all of Italy. That suggests it is still relevant, but I couldn&#x27;t confirm current reachability first-hand. A 403 is not a reason to remove it.</p>

<p>https://www.subito.it/ — Both curl and WebFetch returned HTTP 403 &#x27;Access Denied&#x27;. I couldn&#x27;t read the page content.</p>

<p>https://www.subito.it/annunci-italia/vendita/offerte-lavoro/ — Search results index this page as &#x27;Lavoro - Offerte e annunci Subito.it&#x27;, with nationwide and city-level job ads. A direct request also returned 403.</p>

<p>Blocking questions: I couldn&#x27;t read the current page content directly because of HTTP 403.</p>

<p>Caveats: The evidence comes from search snippets, not a live fetch.; Subito is a general classifieds site. The jobs category URL would point more precisely to jobs, but that would be an optional change, not a correction.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Crossweb — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. Direct requests got HTTP 403 from a Cloudflare challenge (&#x27;Just a moment...&#x27;), so I couldn&#x27;t read the current page. Search indexes show Crossweb runs an IT job board for Polish cities and remote work, including this exact English URL. That suggests the entry is still relevant, but I couldn&#x27;t confirm current reachability first-hand. A 403 is not a reason to remove it.</p>

<p>https://crossweb.pl/en/job/job-offers/ — Both curl and WebFetch returned HTTP 403 with a Cloudflare &#x27;Just a moment...&#x27; challenge page.</p>

<p>https://crossweb.pl/robots.txt — Returned HTTP 200, so the domain is up and serving pages.</p>

<p>Blocking questions: I couldn&#x27;t read the current page content directly because of the Cloudflare 403.</p>

<p>Caveats: Search results list &#x27;Oferty Pracy IT - Crossweb&#x27; at this exact URL, plus city pages such as /job/oferty-pracy/warszawa/. Those are indexed copies, not a live read.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Yenibiris — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>Direct fetches return 403 (a Cloudflare &#x27;Just a moment...&#x27; challenge), so I couldn&#x27;t read the page itself. Search-engine results show many live Yenibiris /is-ilanlari/ pages with current Turkish listings, which suggests the site is active and relevant. The block is an access issue and is not evidence that the site is dead.</p>

<p>https://www.yenibiris.com/is-ilanlari/ — curl and WebFetch both returned HTTP 403 with the Cloudflare challenge title &#x27;Just a moment...&#x27;.</p>

<p>https://www.yenibiris.com/is-ilanlari/turkiye — Found through web search only, not fetched. Indexed Yenibiris listing pages (Türkiye, Ankara, İzmir, Bugünün İş İlanları) appear with recent postings.</p>

<p>Blocking questions: I could not directly verify that the listed URL serves job listings to a regular browser.</p>

<p>Caveats: Access was blocked by bot protection. The current page content was not checked directly.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Zero Tax Jobs — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>Direct fetches return 403 (a Cloudflare challenge). Search results show zerotaxjobs.com category pages updated in November 2026 and third-party directories describing it as a job board for tech jobs in Dubai, the UAE and Saudi Arabia, which fits the UAE section. I couldn&#x27;t read the homepage itself.</p>

<p>https://zerotaxjobs.com/ — curl and WebFetch both returned HTTP 403 with the Cloudflare challenge &#x27;Just a moment...&#x27;.</p>

<p>https://zerotaxjobs.com/category/rust — Search result only, not fetched. It shows Rust jobs in Dubai and Saudi Arabia, last updated 9 Nov 2026.</p>

<p>https://startup88.com/startups/2025/05/11/zero-tax-jobs-a-job-board-for-software-engineers-in-dubai-uae-saudi-and-other-tax-free-places/70444 — Search result only, not fetched. It describes Zero Tax Jobs as a job board for software engineers in Dubai, the UAE, Saudi Arabia and other tax-free places.</p>

<p>Blocking questions: I could not directly read the official homepage to confirm it currently serves listings.</p>

<p>Caveats: The evidence for activity is indirect, from search snippets and third-party coverage.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<details>
<summary>329 unresolved keeps</summary>

These entries were not added to the baseline.

<h3>LinkedIn — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The URL resolves directly to the official LinkedIn site. Its homepage includes a job and internship search area and a &#x27;Post a job&#x27; link, so it still fits the General job-board section.</p>

<p>https://www.linkedin.com/ — HTTP 200, no redirect. Title &#x27;LinkedIn: Log In or Sign Up&#x27;. Page has a &#x27;Jobs&#x27; nav item, a &#x27;Find the right job or internship for you&#x27; category list and &#x27;Post your job for millions of people to see&#x27;.</p>

<p>Caveats: Most of LinkedIn&#x27;s job features need a login. Only the logged-out homepage was checked.</p>

<p>Independent source check: The bare link still fits a general job-board catalog. Logged-out homepage verification only.</p>

<p>https://www.linkedin.com/ — Official homepage has Jobs navigation, job/internship search and job posting.</p>

</details>

<h3>Glassdoor — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. glassdoor.com is still the official Glassdoor domain. It returned a Glassdoor-branded Cloudflare &#x27;Humans only&#x27; challenge (HTTP 403) to the automated fetch. Secondary and encyclopedic sources say Glassdoor LLC legally merged into Indeed, Inc. on July 1, 2026, and Glassdoor continues as a brand operated by Indeed, with job listings synced from Indeed. The merger changes ownership but is not evidence that the site lost its job-board purpose, so it still fits General.</p>

<p>https://www.glassdoor.com/ — HTTP 403 Cloudflare challenge page titled &#x27;Security | Glassdoor&#x27; that asks the visitor to enable JavaScript and cookies. This is a bot block, not a dead site.</p>

<p>https://en.wikipedia.org/wiki/Glassdoor — States Glassdoor legally merged into Indeed, Inc. on July 1, 2026 and ceased operating as an independent subsidiary.</p>

<p>Caveats: Could not read Glassdoor&#x27;s own job pages because of the bot challenge. Read only through a summarizing fetch tool: the claim that Glassdoor continues as a brand with Indeed-synced job listings comes from third-party search results, not an official Glassdoor page.; The maintainer may want to note that Glassdoor is now part of Indeed, which overlaps with the Indeed entry.</p>

</details>

<h3>wellfound — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. wellfound.com/jobs resolves directly to Wellfound&#x27;s startup job search (formerly AngelList Talent), so it fits General.</p>

<p>https://wellfound.com/jobs — HTTP 200, no redirect. Title &#x27;Find Startup Jobs Near You and Remote Jobs | Wellfound&#x27;. Shows &#x27;Over 130k remote &amp; local startup jobs&#x27; with live listings and Apply buttons.</p>

<p>Caveats: The catalog writes the name in lowercase (&#x27;wellfound&#x27;). The site brands itself &#x27;Wellfound&#x27;. Capitalizing it is optional cosmetic cleanup.</p>

</details>

<h3>CVExpert — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>CVExpert&#x27;s site describes an AI job-search service covering career coaching, CV writing and tailoring, daily job shortlists, application tracking, review-and-approve steps, and introductions to hiring managers and referrers. That broadly matches the listed coaching, CV tailoring, job tracking, application review and networking.</p>

<p>https://cvexpert.com/ — Title &#x27;AI Job Search Agent | CVExpert&#x27;. Copy: &#x27;Career coaching, daily job shortlists, tailored CVs, and introductions to hiring managers and potential referrers&#x27;. Also &#x27;We submit your approved applications and keep track of them&#x27; and &#x27;Review every role and tailored CV&#x27;.</p>

<p>Caveats: The coaching is described as one-on-one with a human career coach, with AI handling job search and tailoring. &#x27;AI-assisted&#x27; still fits.; Pricing and the logged-in product were not checked.</p>

<p>Independent source check: The AI-assisted career-coaching description remains supported; the service also involves human coaching. No application flow was executed.</p>

<p>https://cvexpert.com/ — Official page describes career coaching, AI job agent, tailored CVs, application approval and tracking.</p>

</details>

<h3>GetMattered — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>GetMattered&#x27;s site says it submits applications on the company&#x27;s own hiring system (30+ ATSes), confirms submission when the employer responds, and explains failures (posting closed, bot defence, etc.) on each application. This supports the description.</p>

<p>https://getmattered.com/ — Copy includes &#x27;files the finished application on the company&#x27;s own hiring system ... GetMattered submits on 30+ of those systems: Greenhouse, Lever, Ashby, Workd[ay]...&#x27;. FAQ: &#x27;What happens when a GetMattered application fails? GetMattered tells you exactly why, on the application itself...&#x27;. Also says &#x27;Their email marks it done, not our click&#x27;.</p>

<p>Caveats: Confirmation appears to come partly from employer emails rather than purely from ATS status responses. The wording is close enough not to be a factual error.; The service was not used.</p>

<p>Independent source check: The application/status-reporting claim is broadly supported. Employer confirmation emails are part of the described mechanism; do not imply a verified direct ATS API integration.</p>

<p>https://getmattered.com/ — Official site describes applications submitted through employer ATS systems, confirmation tracking and explanations when submission fails.</p>

</details>

<h3>Cviya — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Cviya is a live resume/CV builder. It has Arabic (dir=rtl), German, Spanish and French locales and advertises no watermark and free use, which supports the RTL, multilingual and watermark-free claims.</p>

<p>https://cviya.com/ — Title &#x27;Free CV Builder &amp; Resume Maker - ATS Friendly | Cviya&#x27;. Meta: &#x27;Build, customize, and download professional resumes in PDF or image. 100% free, no watermark&#x27;. Links to /ar, /de, /es, /fr locales. Page JS bundle has &#x27;noWatermark&#x27; strings.</p>

<p>https://cviya.com/ar — HTTP 200. The page declares Arabic with right-to-left layout (&lt;html lang=&quot;ar&quot; dir=&quot;rtl&quot;&gt;).</p>

<p>Caveats: &#x27;Fully customizable&#x27; is marketing wording and was not tested.; The site shows Google ads, which doesn&#x27;t conflict with the description.</p>

</details>

<h3>Foorilla — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>foorilla.com/hiring/ is Foorilla&#x27;s hiring/jobs section in its workspace for coders. It has job filters (seniority, remote, salary) and a &#x27;Post a job&#x27; link, which supports &#x27;Tech and coding job listings&#x27;.</p>

<p>https://foorilla.com/hiring/ — HTTP 200. Title &#x27;all Hiring - foorilla&#x27;. Meta &#x27;the intelligence workspace for coders, builders, hackers and makers&#x27;. Legend has job filters (Entry/Mid/Senior, Remote, Salary information filter, Job search) and a &#x27;Post a job&#x27; link.</p>

<p>Caveats: Listings load dynamically, so individual jobs weren&#x27;t seen in the static HTML.</p>

</details>

<h3>Indeed — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. www.indeed.com is the official Indeed domain. The automated fetch got an Indeed-branded &#x27;Security Check&#x27; (HTTP 403) bot challenge, and robots.txt is served normally (200). An access block isn&#x27;t evidence of a problem. Indeed is still operating, and in 2026 it absorbed Glassdoor. It still fits General.</p>

<p>https://www.indeed.com/ — HTTP 403 page titled &#x27;Security Check - Indeed.com&#x27; asking to enable JavaScript and cookies. This is a bot block on the official domain.</p>

<p>https://www.indeed.com/robots.txt — HTTP 200 robots.txt served normally, so the domain is live.</p>

<p>Caveats: Couldn&#x27;t load Indeed&#x27;s job search content because of the bot challenge. Its continued operation is confirmed only through secondary sources about the 2026 Glassdoor merger.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>MoneticAI — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>MoneticAI is live and is an AI resume-tailoring service that also writes cover letters for a specific job posting, which matches the entry.</p>

<p>https://moneticai.com/ — Title: &#x27;MoneticAI — Tailor your resume to any job in minutes&#x27;. The page says &#x27;Upload your resume once. Paste any job posting. Get a perfectly tailored version&#x27; and &#x27;Download your tailored resume and cover letter in PDF or DOCX format&#x27;.</p>

<p>Caveats: It now also offers LinkedIn optimization, candidate review and a career assistant. These are additions only, not a correction.; Full results are paid from a balance. The free part is an analysis preview, and the entry makes no claim about pricing.</p>

</details>

<h3>The Briefed — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The Briefed is live and lists remote, onsite and hybrid jobs and internships in Pakistan, the US and remote worldwide, with a free CV/resume builder and ATS checker. This matches the entry.</p>

<p>https://www.thebriefed.co/ — Meta: &#x27;Find remote, onsite and hybrid jobs and internships in Pakistan, the US and worldwide... Free resume builder and ATS checker.&#x27; The page shows &#x27;944 jobs and 103 internships open now&#x27; and &#x27;Free CV maker, resume builder and ATS checker&#x27;.</p>

<p>Caveats: Country coverage may grow; the UK is marked &#x27;Coming soon&#x27;.</p>

</details>

<h3>Compass OS — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Compass OS confirms every claim: per-role resume tailoring that flags claims it can&#x27;t trace to your profile, fit scoring of matches, role-specific mock interviews, a Chrome extension that fills applications and never submits, and a free plan.</p>

<p>https://compass-os.dev/ — &#x27;checks every number and claim against the profile you gave it. Anything it can&#x27;t trace is flagged.&#x27; It says &#x27;scores every role on how well your experience fits&#x27;, offers &#x27;a mock interview where a coach scores every answer&#x27;, and calls Compass Apply a Chrome extension that &#x27;Never submits. That click stays yours.&#x27; Also &#x27;Free plan. No card needed.&#x27;</p>

<p>Caveats: The product is now positioned as a broader &#x27;Career OS&#x27; that also covers LinkedIn and networking. That is an addition, not a correction.</p>

</details>

<h3>Cover Me — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Cover Me is live and is a Chrome extension that tailors your resume and writes a cover letter for the open posting on LinkedIn, Indeed, Workday and others. It gives an ATS match score and missing keywords, rewrites &#x27;without adding anything new&#x27;, and has a hosted free plan.</p>

<p>https://www.cover-me.dev/ — Meta: &#x27;Tailor your resume and write a matching cover letter for the job posting you have open, with an ATS match score and the keywords you&#x27;re missing. Free plan to start.&#x27; It reads postings on &#x27;LinkedIn Indeed Greenhouse Lever Workday Ashby BambooHR Workable&#x27;. The page says it rewrites &#x27;without adding anything new&#x27; and that &#x27;The hosted free plan gives you 10 AI generations to start, then 5 a week&#x27;.</p>

<p>Caveats: It can also run free with your own API key and is described as open source. These are additions only.</p>

</details>

<h3>AI Dev Jobs — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>AI Dev Jobs is live and is an AI/ML developer job board with salary data and a public REST API and MCP server for agents. It lists 9,384 jobs, so &#x27;5000+&#x27; is still true as a lower bound.</p>

<p>https://aidevboard.com/ — Title: &#x27;AI Dev Jobs — 9384 AI Developer Jobs&#x27;. The page says &#x27;9384 jobs · 551 companies · $234k avg salary&#x27; and &#x27;Agentic API &amp; MCP Server... REST API public for discovery, free API keys for recurring search.&#x27;</p>

<p>Caveats: The job count is volatile. A maintainer could optionally switch to count-free wording.; &#x27;Curated&#x27; and &#x27;The specialized&#x27; are the site&#x27;s own marketing framing.</p>

</details>

<h3>AI Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>MoAIJobs is live and is an AI-company job board, which matches the entry. The homepage says you can browse by role, location and remote, and the site has category pages.</p>

<p>https://www.moaijobs.com/ — Meta: &#x27;Discover the best AI jobs at frontier AI companies across machine learning, AI research, data science, AI training, and robotics.&#x27; The page says &#x27;Curated from top AI labs and companies. Browse by role, location, and remote.&#x27; It has category pages such as /ai-engineer-jobs and /remote-ai-jobs.</p>

<p>Caveats: A company-specific filter was not observed in the static HTML. The entry&#x27;s &#x27;etc.&#x27; wording is loose but not contradicted.</p>

</details>

<h3>LAYIQ — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>curl and WebFetch both got HTTP 429 (a Vercel security checkpoint), which is an access block, not evidence that the site is dead. Alternate sources quote LAYIQ&#x27;s own self-description, operated by Roleworthy Labs Inc., word for word as the catalog entry. Search results show live layiq.co job and company pages.</p>

<p>https://glama.ai/mcp/servers/roleworthylabs/layiq-mcp — Quotes LAYIQ&#x27;s description: &#x27;a candidate-first job search workspace that helps job seekers find, score, and prioritize the roles worth their time, without sponsored listings or selling user data.&#x27; It says the service is &#x27;provided by Roleworthy Labs Inc.&#x27;</p>

<p>https://www.layiq.co/ — Direct fetch returned HTTP 429 with a Vercel Security Checkpoint page. Search results list live layiq.co pages such as /jobs/941190 and /companies/bankrate-608.</p>

<p>Caveats: The official homepage could not be read directly. The claims rest on a third-party MCP directory that quotes the operator, plus search-engine excerpts.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Jobs in AI — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>jobsinai.com redirects to the canonical https://www.jobsinai.com/. It calls itself the &#x27;Jobs in AI marketplace&#x27; with categories for Machine Learning, Agents, Data Science, Computer Vision and NLP, plus roles for both humans and AI agents. The description matches.</p>

<p>https://www.jobsinai.com/ — &#x27;Jobs in AI marketplace&#x27;. &#x27;Search roles for humans and AI agents across the AI ecosystem — full-time, contract, bounty, and gig work.&#x27; Category filters include Machine Learning, Agents and Data Science. &#x27;16,391 published AI roles&#x27;.</p>

<p>Caveats: The bare domain redirects to www. A URL normalization is optional and not required.</p>

</details>

<h3>Present of AI — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Every claim checks out. The public API reports 9,743 open jobs, so &#x27;9,600+&#x27; still holds. A free, no-key REST API at /api/v1, a remote MCP server at /mcp and a jobs XML feed at /jobs/feed.xml are all documented and respond.</p>

<p>https://presentofai.com/jobs — AI jobs page. Text includes &#x27;9,743 open roles&#x27;. Links to https://presentofai.com/jobs/feed.xml.</p>

<p>https://presentofai.com/developers — &#x27;A free, read-only API and a remote MCP server... No key, no sign-up.&#x27; Documents GET /api/v1/jobs and an MCP tool find_ai_jobs. Data is under CC BY 4.0.</p>

<p>https://presentofai.com/api/v1/jobs?limit=1 — Returns JSON with total: 9743.</p>

<p>https://presentofai.com/jobs/feed.xml — XML &lt;source&gt; feed with publisher &#x27;Present of AI&#x27; and &lt;count&gt;10382&lt;/count&gt; jobs.</p>

<p>Caveats: The &#x27;9,600+&#x27; figure is volatile. A durable wording such as &#x27;Thousands of open roles&#x27; could be considered later, but the current claim is accurate.</p>

</details>

<h3>Vibehackers Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The page is a vibe-coding / AI-assisted development job board, which matches the description.</p>

<p>https://vibehackers.io/jobs — Title &#x27;Vibe Coding Jobs — Curated AI-Assisted Roles (Remote &amp; Hybrid) | Vibehackers&#x27;. Meta: &#x27;Vibe coding jobs are roles where AI-assisted tools (Cursor, Claude Code, Copilot) are part of shipping real artifacts fast.&#x27;</p>

<p>Caveats: Listings span engineering, product, ops and GTM, not only coding. The description does not claim exclusivity.</p>

</details>

<h3>Landed — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>landed.jobs redirects to the canonical www.landed.jobs. Listed claims are still supported: daily-refreshed roles, % match scores, application answers written per role, interview prep, a &#x27;$0 forever&#x27; Free plan, and a public MCP server (20 anonymous free requests). The product now positions itself as an AI agent that also submits applications, but the entry&#x27;s claims remain true.</p>

<p>https://www.landed.jobs/ — Title &#x27;landed · the AI agent that applies to jobs for you&#x27;. Shows &#x27;94 % match&#x27; scores, &#x27;Fresh roles, dropped daily&#x27;, interview prep, and an MCP server for Claude/Cursor.</p>

<p>https://www.landed.jobs/pricing — &#x27;Free $0 forever&#x27;, Pro $19/month, Max $49/month. &#x27;Every plan includes matches, courses and roadmaps.&#x27;</p>

<p>https://www.landed.jobs/mcp — &#x27;Anonymous gets 20 free requests; a token unlocks unmetered, personalized results.&#x27;</p>

<p>Caveats: The product has shifted toward auto-applying, which a maintainer may optionally reflect. &#x27;AI-native roles&#x27; is the site&#x27;s framing; it scans 50,000+ startup and company career pages.</p>

</details>

<h3>AITraining.jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site aggregates AI trainer, evaluator, annotation and domain-expert roles with hourly pay. It reports 4,401 jobs from the job boards of 62 platforms, read every hour, and offers free, no-signup matching. &#x27;About 60 platforms&#x27;, &#x27;updated daily&#x27; and &#x27;free&#x27; remain accurate (hourly refresh exceeds daily).</p>

<p>https://aitraining.jobs/ — Meta: &#x27;4,401 AI training and AI trainer jobs... from the job boards of 62 platforms, read every hour, typically $30–$125/hr.&#x27; Page shows &#x27;86 platforms tracked&#x27; and &#x27;Free, no sign-up&#x27;.</p>

<p>Caveats: &#x27;Every open AI training role&#x27; is the site&#x27;s own completeness claim and cannot be independently verified. Counts are volatile (62 platforms in the feed, 86 tracked).</p>

</details>

<h3>AI Trainer Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site lists remote AI training, annotation, RLHF and prompt-evaluation jobs updated hourly. It now covers 95 platforms, which still satisfies &#x27;40+&#x27;. Free tools state &#x27;Free, no sign-up&#x27; and no login is needed to browse.</p>

<p>https://aitrainer.jobs/ — &#x27;16,831 open AI training jobs from 95 platforms — prompt evaluation, data annotation, RLHF, coding and expert work. Updated every hour.&#x27; Shows &#x27;Free, no sign-up&#x27; and an RSS feed of all jobs.</p>

<p>Caveats: &#x27;40+&#x27; is understated but true. The count is volatile.</p>

</details>

<h3>Curated AI Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Live AI/ML job board under the same name. It lists roles in ML engineering, LLM &amp; NLP, AI research and MLOps, with US, UK, Europe and remote filters, which matches the description.</p>

<p>https://job.careers/ — Title &#x27;AI &amp; Machine Learning Jobs | Curated AI Jobs&#x27;. Text: &#x27;Find your next role in ML engineering, LLMs, research or MLOps. Explore US, UK, European and remote opportunities&#x27;. Shows 17,530 AI job listings with categories LLM &amp; NLP, ML Engineering, AI Research and MLOps &amp; Infra.</p>

<p>Caveats: The site also covers other categories (robotics, data, GTM, operations). This is not a correction.</p>

</details>

<h3>Red Pen Jobs — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Every claim checks out: 27 professions, the pay each posting lists, a CC BY pay dataset, checks every morning, and no signup.</p>

<p>https://redpenjobs.com/about/ — &#x27;Checked every morning. The current data was checked 10 Nov 2026. Covers 27 professions and 1649 open roles on 6 platforms today.&#x27; Also: &#x27;No accounts, no logins, no email sign-up.&#x27; Notes that apply buttons use referral links.</p>

<p>https://redpenjobs.com/pay/ — Pay table by profession with a CSV download, marked &#x27;Free to reuse under CC BY 4.0&#x27;.</p>

<p>https://redpenjobs.com/ — Homepage title &#x27;Remote AI training jobs and what they pay (Nov 2026)&#x27;. Profession picker includes lawyers, doctors, accountants and engineers.</p>

<p>Caveats: The profession count could change later.; Apply links are referral links. The entry does not mention this.</p>

</details>

<h3>NeverApply — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Live AI job-search agent. Its own pages support every claim: matching, tailored resumes and cover letters, filling every application field, an approve-each-job &#x27;Ask mode&#x27;, a free plan, and a free MCP connector for Claude, ChatGPT and Cursor.</p>

<p>https://neverapply.co/ — &#x27;Otto opens each application, fills in every field from your resume and sends it.&#x27; &#x27;Free MCP connector… Free to add to Claude, ChatGPT, Cursor and more.&#x27; The FAQ says Otto sends tailored cover letters, and in Ask mode &#x27;opens no form until you approve the job&#x27;.</p>

<p>https://neverapply.co/pricing — Free plan at $0 forever with 10 free applications. Pro includes &#x27;Ask mode: you approve each job&#x27; and resume rewrites.</p>

<p>Caveats: Approval-before-applying is tied to Ask mode on the paid plans. The free plan gives only 10 one-time applications.; &#x27;Answers screening questions&#x27; is implied by &#x27;fills in every field&#x27; rather than stated in those words.</p>

</details>

<h3>CookLLM — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Every claim checks out: career pages of 1,300+ AI companies, hiring posts on X and LinkedIn, a 70% fit threshold, daily or weekly email, a free job board, and job membership from $9 a week.</p>

<p>https://cookllm.com/en/jobs/match — FAQ: &#x27;the career pages of 1,300+ AI companies… and hiring posts that hiring team members share on X and LinkedIn&#x27;. &#x27;Only jobs at 70% or above reach your inbox.&#x27; &#x27;A daily digest by default… or once a week&#x27;.</p>

<p>https://cookllm.com/en/pricing — Meta: &#x27;Job membership from $9 a week&#x27;. Also says &#x27;The job board stays free&#x27;.</p>

<p>https://cookllm.com/en/jobs/board — Job board heading: &#x27;1,400 AI companies are hiring for 24,144 jobs right now&#x27;.</p>

<p>Caveats: Prices and company counts can change.</p>

</details>

<h3>DataJobs.com — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The site is reachable under the same identity and is a data science, analytics and data engineering job board, so it fits the Data section.</p>

<p>https://datajobs.com/ — Title &#x27;DataJobs.com: Analytics Jobs, Hadoop Jobs, DBA Jobs, Data Science Jobs&#x27;. Has category pages (Data-Scientist-Jobs, Data-Engineer-Jobs, etc.) and individual job posting links.</p>

<p>Caveats: Much of the site copy is dated (Hadoop focus). I did not verify how recent the listings are.</p>

</details>

<h3>StatsJobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. StatsJobs is reachable and lists current statistics and data jobs, so it fits the Data section.</p>

<p>https://www.statsjobs.com/ — Title &#x27;StatsJobs&#x27;, meta &#x27;Statistics Jobs, Data Science &amp; Data Analyst Jobs&#x27;. Featured jobs include one with an application deadline of 13 November 2026.</p>

<p>Caveats: Listings appear UK-heavy.</p>

</details>

<h3>VisionHires — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>A direct fetch hit a Vercel bot checkpoint (HTTP 429), but a reader-proxy render showed the live site under the same identity. It is a job board for computer vision, machine vision and perception engineering with recent postings, which matches the description exactly.</p>

<p>https://visionhires.com/ — Direct curl returned HTTP 429 &#x27;Vercel Security Checkpoint&#x27;. Via r.jina.ai: title &#x27;VisionHires | The Job Board for Computer Vision, Machine Vision &amp; Perception Engineering Jobs&#x27;, with roles (Apple, Promethion) &#x27;Published 4 days ago&#x27;.</p>

<p>Caveats: I saw the content only through a third-party reader proxy because of the bot protection.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>DataScienceJobs — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The live site returns a Cloudflare challenge (HTTP 403), which reflects bot protection, not a dead site. A Wayback snapshot from 1 Oct 2026 shows a working data science/AI job board under the same name, consistent with the generic description.</p>

<p>https://datasciencejobs.com/ — HTTP 403 &#x27;Just a moment…&#x27; Cloudflare security verification, both direct and via a reader proxy.</p>

<p>http://web.archive.org/web/20261001225533/https://datasciencejobs.com/ — Title &#x27;Data Science Jobs &amp; AI Careers | DataScienceJobs&#x27;. &#x27;The #1 Job Board for finding your next AI, data science, machine learning, deep learning job&#x27;, with categories, companies and &#x27;Post a job&#x27;.</p>

<p>Caveats: The current state is known only from a snapshot about 6 weeks old; the live page was blocked by bot protection.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>RealAnalystJobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Site is live and on-topic. It is an analyst job board built from company career pages and ATS feeds and checked daily. Its listings include data, business and product analyst roles, matching the entry. The site now also covers financial analysts and H-1B/visa records. Those are additions, not a correction.</p>

<p>https://realanalystjobs.com/ — Title &#x27;Real Analyst Jobs: 14,600+ Analyst Jobs With H-1B Records&#x27;. Meta: &#x27;The job board for data, business and financial analysts... Straight from company career pages, checked daily.&#x27; Body: &#x27;1,839 companies&#x27; career pages, checked daily&#x27;, &#x27;Read straight from the hiring systems companies use (Greenhouse, Lever, Ashby, Workday...)&#x27;. Popular searches include Business Analyst Jobs and Product Analyst Jobs, and the listings include e.g. &#x27;Staff Product Analyst&#x27;.</p>

<p>Caveats: Financial analyst roles and visa-sponsor records are newer additions the entry doesn&#x27;t mention. You could add them, but nothing in the entry is wrong.</p>

</details>

<h3>Get Data Engineering Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Every claim checks out. The About page names job boards, company career pages, ATSs and the monthly Hacker News &#x27;Who is hiring?&#x27; thread as sources. The homepage has filters for tech stack, salary, work arrangement (remote/hybrid/on-site) and visa sponsorship.</p>

<p>https://getdataengineeringjobs.com/about/ — &#x27;We collect postings several times a day from job boards, company career pages, applicant tracking systems such as Greenhouse, Lever and Ashby, and the monthly Hacker News &quot;Who is hiring?&quot; thread.&#x27;</p>

<p>https://getdataengineeringjobs.com/ — Filter panel has Work arrangement (Remote/Hybrid/On-site), Tech stack (Spark, Airflow, dbt...), Salary (minimum per year), and Visa sponsorship (Offered/Not offered). 4,401 jobs listed.</p>

</details>

<h3>Crypto Jobs List — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. It resolves to Crypto Jobs List, an active crypto/Web3 job board, so it fits the Blockchain section.</p>

<p>https://cryptojobslist.com/ — HTTP 200, no redirect. Title &#x27;Cryptocurrency Jobs and Blockchain Jobs (174 new in Nov 2026)&#x27;. Meta: &#x27;New Crypto Jobs, Web3 Jobs and Blockchain Jobs on CryptoJobsList&#x27;.</p>

<p>Caveats: Entry 153 (crypto.jobs) now redirects here, so the list effectively has this site twice.</p>

</details>

<h3>Workew Crypto Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Live Workew page listing remote crypto/Web3/blockchain jobs, which matches &#x27;Crypto and Blockchain roles&#x27;.</p>

<p>https://workew.com/crypto-jobs/ — Title &#x27;Remote Crypto Jobs - Workew&#x27;. &#x27;Crypto · 21 Remote Jobs&#x27;. Meta: &#x27;curated blockchain, DeFi, NFT, and cryptocurrency jobs from leading startups hiring worldwide.&#x27;</p>

<p>Caveats: Every listing is remote, which the entry doesn&#x27;t mention. Only 21 jobs were listed at check time.</p>

</details>

<h3>Cryptocurrency Jobs — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Cryptocurrency Jobs is live and lists crypto/blockchain jobs, so it fits the section.</p>

<p>https://cryptocurrencyjobs.co/ — HTTP 200. Title &#x27;Cryptocurrency Jobs and Blockchain Jobs - Cryptocurrency Jobs&#x27;. Categories include role, blockchain (Ethereum, Bitcoin, Solana, DeFi...) and location.</p>

</details>

<h3>JobsInBlockchain — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. JobsInBlockchain is live and lists blockchain/crypto jobs. Its sitemap shows job pages updated in late October 2026.</p>

<p>https://jobsinblockchain.com/ — Title &#x27;Blockchain &amp; Crypto Jobs | JobsInBlockchain&#x27;. Has filters for work type, level and date. A banner reads &#x27;This job board is for sale&#x27;.</p>

<p>https://jobsinblockchain.com/sitemap.xml — Lists job pages (e.g. Bybit, Revolut crypto roles) with lastmod 2026-10-26.</p>

<p>Caveats: The &#x27;for sale&#x27; banner means ownership or upkeep could change. That alone isn&#x27;t a reason to remove it.</p>

</details>

<h3>Web3 Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. web3.career is live and lists Web3/blockchain/crypto jobs, so it fits the section.</p>

<p>https://web3.career/ — HTTP 200. Title &#x27;Web3 Jobs: Blockchain, Smart Contract and Crypto Jobs&#x27;. Has Post Job, salaries and internship sections.</p>

</details>

<h3>Ethereum Job Board — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Ethereum Job Board is live (redirects to www) and lists jobs at Ethereum-ecosystem companies.</p>

<p>https://www.ethereumjobboard.com/ — Title &#x27;Ethereum Job Board&#x27;. Lists companies (Offchain/Arbitrum, Gensyn...) and jobs at Gnosis, Morpho, Metamask, Privy with remote/hybrid labels.</p>

</details>

<h3>Avalanche Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. This is the official Avalanche ecosystem job board (Getro-powered), and it is live.</p>

<p>https://jobs.avax.network/jobs — Title &#x27;Jobs | Avalanche Job Board&#x27;. &#x27;Avalanche Ecosystem Job Board... Powered by Getro. Showing 39 jobs&#x27;, with recent postings.</p>

<p>Caveats: Only 39 jobs were listed at check time.</p>

</details>

<h3>Solana Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The Solana network job board (Getro) is live with hundreds of current jobs.</p>

<p>https://jobs.solana.com/jobs — Title &#x27;Jobs | Solana Network Opportunities Job Board&#x27;. &#x27;Showing 459 jobs&#x27;, with postings dated &#x27;Today&#x27; (Phantom, Wormhole...).</p>

<p>Caveats: The site&#x27;s own title is &#x27;Solana Network Opportunities Job Board&#x27;. The current name &#x27;Solana Jobs&#x27; still works.</p>

</details>

<h3>Dragonfly Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Dragonfly&#x27;s portfolio job board (Getro) is live and lists crypto-industry roles.</p>

<p>https://jobs.dragonfly.xyz/jobs — Title &#x27;Jobs | Dragonfly Job Board&#x27;. &#x27;Showing 977 jobs&#x27;, e.g. Bybit roles posted &#x27;Today&#x27; and tagged Blockchain/Cryptocurrency.</p>

<p>Caveats: This is a VC-portfolio board, so it only lists roles at Dragonfly-network companies.</p>

</details>

<h3>Remote3 — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The Remote3 remote Web3 jobs page is live and on-topic. The sitemap still marks it daily-updated. Some of the page looks stale, though.</p>

<p>https://www.remote3.co/remote-web3-jobs — HTTP 200. Title &#x27;Remote Web3 Jobs (975 New in Sep 2025)&#x27;. Meta still says &#x27;Sep 2025&#x27;. The listings shown (Bybit roles) are labeled &#x27;3 months ago&#x27;, and embedded dates go up to 2026-08-24.</p>

<p>https://www.remote3.co/sitemap.xml — remote-web3-jobs has lastmod 2026-11-09 and changefreq daily.</p>

<p>Caveats: The &#x27;Sep 2025&#x27; headline and 3-month-old jobs in the static HTML suggest stale server-side rendering or slower updates. I didn&#x27;t check whether the page loads newer jobs in a browser.</p>

</details>

<h3>Sail on Chain — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. SailOnchain is live and lists crypto/Web3/blockchain jobs.</p>

<p>https://sailonchain.com/ — Title &#x27;Crypto Jobs &amp; Web3 Careers | 2,946+ Blockchain Jobs | SailOnchain&#x27;. Meta: &#x27;Browse 2,946+ crypto, Web3, and blockchain jobs at 1254+ companies... Updated daily.&#x27;</p>

</details>

<h3>PredictionJobs — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Live prediction-market job board with current Polymarket and Kalshi roles, as the entry says.</p>

<p>https://predictionjobs.co/ — Title &#x27;PredictionJobs — The largest job board for prediction markets&#x27;. Meta: &#x27;Find prediction market jobs at Kalshi, Polymarket, Manifold, and quant trading firms&#x27;. Listings include Kalshi and Polymarket roles posted within 1–8 days.</p>

<p>Caveats: Prediction markets only partly overlap with blockchain (Kalshi is not crypto-based). It already sits in the Blockchain section, and I&#x27;m not recommending a move.</p>

</details>

<h3>GeospatialCareers — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>A direct fetch was blocked by Vercel&#x27;s security checkpoint (HTTP 429), not a dead site. Through the r.jina.ai reader, the homepage shows a live GIS/geospatial job board. It browses by US states, lists US jobs published days ago, and has remote-sensing searches. That supports the description.</p>

<p>https://geospatialcareers.com/ — Direct curl gets HTTP 429 &#x27;Vercel Security Checkpoint&#x27;. Rendered through r.jina.ai: title &#x27;GeospatialCareers | The Job Board for Geospatial, GIS &amp; Remote Sensing Jobs&#x27;. &#x27;Opportunities in GIS, remote sensing, and geospatial analysis&#x27;. &#x27;Browse jobs by states and territories&#x27; links to /jobs/usa. Latest jobs (Peraton, Vantor, Minnkota) say &#x27;Published 4 days ago&#x27;.</p>

<p>Caveats: I read the content through a third-party reader because the site blocks automated requests. I didn&#x27;t confirm that every listing is US-based.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Jobstash — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. A direct fetch worked and shows JobStash is a live crypto job board. It now also covers AI, fintech and robotics roles, but crypto/Web3 is still its main focus.</p>

<p>https://jobstash.xyz/ — HTTP 200. Title &#x27;Crypto Jobs — Web3, DeFi &amp; Blockchain Jobs | JobStash&#x27;. Meta: &#x27;Browse crypto native jobs across the entire Web3 ecosystem... Aggregated from thousands of crypto organizations and updated daily.&#x27; The page also has &#x27;Fintech Jobs&#x27;, &#x27;AI Jobs&#x27; and &#x27;Robotics Jobs&#x27; tabs.</p>

<p>Caveats: The pipeline&#x27;s snapshot failed with a ValueError, but my direct fetch succeeded.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Jobs in Crypto — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site is live and redirects to www.jobsincrypto.xyz. It calls itself the &quot;Jobs in Crypto marketplace&quot; and lists crypto roles (full-time, contract, bounty, gig) for people and AI agents. That matches the description and the Blockchain section.</p>

<p>https://www.jobsincrypto.xyz/ — Title is &#x27;Crypto Jobs — Live Roles, Updated Daily&#x27;. The page says &#x27;Jobs in Crypto marketplace … Search roles for humans and AI agents across the Crypto ecosystem — full-time, contract, bounty, and gig work&#x27;, shows 1,829 published roles, and has filters for Solidity, DeFi, NFT and Wallets.</p>

<p>Caveats: Checked the homepage only; listing quality was not audited.; The site also lists roles for AI agents. This is extra scope and doesn&#x27;t contradict the description.</p>

</details>

<h3>Jobs Web3 — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site is live with 4,044 roles at 287 companies, so &#x27;200+ companies&#x27; is accurate. There are Skills and Languages filters. Listing data carries countries, and location and region browsing exist. I didn&#x27;t see a time-zone filter, but the entry lists countries, regions or time zones as alternatives, so the description is still broadly accurate.</p>

<p>https://jobsweb3.io/ — Meta: &#x27;4,044 open roles at 287 hiring companies.&#x27; Filters: Work mode, Skills, Languages, Location, Seniority, Posted. Regions section covers Africa, Asia, Europe, etc.</p>

<p>https://jobsweb3.io/jobs — Each job record includes &quot;skills&quot;, &quot;langs&quot; and &quot;countries&quot; fields, which back filtering by skill, language and country.</p>

<p>Caveats: No explicit time-zone filter seen; that part of the wording may be loose.</p>

</details>

<h3>chainjobs.app — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Live Web3 freelance board with Jobs, Services and Freelancers sections. A private chat with the client opens when a freelancer applies. Payment is in crypto or by bank transfer, with no fees or commission. All description claims are supported.</p>

<p>https://chainjobs.app/ — Says &#x27;Clients post a gig, freelancers browse…&#x27;, &#x27;Apply &amp; chat … a private chat with the client opens instantly&#x27;, &#x27;USDC USDT ETH BTC SOL Bank transfer&#x27;, &#x27;chainjobs never holds your money and takes 0% fees&#x27;, &#x27;No middleman, no fees&#x27;, &#x27;✓ No commission.&#x27;</p>

<p>Caveats: &#x27;Free&#x27; was inferred from the no-fees wording; I didn&#x27;t check whether paid options exist.</p>

</details>

<h3>AIGA — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The AIGA design careers site is live with current design jobs (posts dated Nov 2026). Identity and Design section fit are confirmed.</p>

<p>https://designcareers.aiga.org/ — Title: &#x27;Home | AIGA, the professional association for design&#x27;. Has Search Jobs and Internships, and featured design jobs posted November 2026.</p>

</details>

<h3>Coroflot — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Live Coroflot design-jobs page with current listings; fits the Design section.</p>

<p>https://www.coroflot.com/design-jobs — Title: &#x27;Design Jobs &amp; Employment Opportunities | Coroflot.com&#x27;. Meta: &#x27;96 design jobs available&#x27;. Filters cover design roles such as Industrial and Product Designer.</p>

</details>

<h3>Design Jobs Board — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Live Design Jobs Board showing 67 opportunities as of November 10 (e.g. Midweight Designer, London); fits the Design section.</p>

<p>https://www.designjobsboard.com/ — Title &#x27;Design Jobs Board&#x27;. Shows &#x27;November 10 OPPORTUNITIES TODAY 67&#x27; and design listings with level and contract filters.</p>

</details>

<h3>Design Week Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Live Design Week jobs board for UK design-industry roles; fits the Design section.</p>

<p>https://www.designweek.co.uk/jobs/ — Title: &#x27;Design industry jobs and opportunities - Design Week&#x27;. Meta: &#x27;View Design Week Jobs Board and reach thousands of designers…&#x27;. Footer © 2026.</p>

<p>Caveats: Listings load via JavaScript, so I didn&#x27;t count them.</p>

</details>

<h3>Behance — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Direct fetches return 403 (bot blocking), but a Wayback Machine capture from Sept 2026 returned HTTP 200. Search results index behance.net/joblist as &#x27;Find Creative Jobs :: Behance&#x27;, with full-time and freelance creative jobs posted Aug–Sept 2026. Identity and Design fit are supported.</p>

<p>https://www.behance.net/joblist — Direct requests return 403. Search index title: &#x27;Find Creative Jobs :: Behance&#x27;. Individual job pages such as /joblist/fulltime/361975/Photography are indexed with 2026 post dates.</p>

<p>http://web.archive.org/web/20260921203815/https://www.behance.net/joblist — Wayback has an HTTP 200 capture of /joblist dated 2026-09-21.</p>

<p>Caveats: Could not read the live page directly (403); current state is inferred from Sept 2026 captures and the search index.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>If You Could Jobs — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The site is live with 70 creative and design jobs and still uses the If You Could Jobs name. It now also calls itself &#x27;The It&#x27;s Nice That Jobs Board&#x27;. Fits the Design section.</p>

<p>https://www.ifyoucouldjobs.com/ — Title: &#x27;If You Could Jobs | Creative Jobs Board&#x27;. Page says &#x27;The It&#x27;s Nice That Jobs Board — The place to find jobs in the creative industry&#x27; and &#x27;70 jobs waiting&#x27; (e.g. Midweight Designer, Senior Designer).</p>

<p>Caveats: The packet snapshot fetch failed, but the site loaded fine in this review. The It&#x27;s Nice That co-branding is a possible future name note, not a confirmed rename.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>UI/UX Jobs Board — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site is live and is a UI/UX and product-design job board, which fits Design. This is a bare-link entry.</p>

<p>https://uiuxjobsboard.com — HTTP 200. The meta description is &#x27;Browse our daily updated job board and find great UI/UX design jobs, product design jobs and UX researcher jobs&#x27;. The page says it has been &#x27;connecting talented designers with top companies since 2018&#x27; and offers &#x27;Post a job · $99&#x27;.</p>

</details>

<h3>CyberSecurityJobs — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site is live and is a cybersecurity job board, which fits InfoSec. This is a bare-link entry.</p>

<p>https://www.cybersecurityjobs.com/ — HTTP 200. The title is &#x27;Cyber Security Jobs: IT Security Jobs &amp; Careers&#x27; and the page says &#x27;Welcome to CyberSecurityJobs.com&#x27;. It has job search and posting, plus browse-by-role links (SOC Analyst, CISO, CISSP).</p>

<p>Caveats: I did not check how fresh the individual listings are.</p>

</details>

<h3>ClearedJobs.Net — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The description matches the site. ClearedJobs.Net is a veteran-owned job board for security-cleared defense, intelligence and government roles. It fits InfoSec as a clearance-related board.</p>

<p>https://clearedjobs.net — HTTP 200. The title is &#x27;Security Clearance Jobs, Cleared Jobs | ClearedJobs.Net&#x27;. The meta description reads &#x27;Find security-cleared jobs with top defense, intelligence, and government employers at veteran-owned ClearedJobs.Net&#x27;. The page has clearance-level filters from Public Trust to TS/SCI + Full Scope Poly, DoE L/Q and DHS, and says &#x27;Trusted Since 2001&#x27;.</p>

<p>Caveats: The site also offers a &#x27;None - Willing to Obtain&#x27; clearance filter, which only adds to the described scope.</p>

</details>

<h3>Elixir Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site is live and is an Elixir job board with listings dated up to 15 Oct (2026). It fits Programming.</p>

<p>https://elixirjobs.net/ — HTTP 200. The title is &#x27;Find your next job the right way · Elixir Jobs&#x27;. It shows &#x27;Showing page 1 of 114&#x27;, with recent offers dated 15 Oct, 17 Sep and 4 Sep (Treat Health, Driftrock and others), plus Telegram, Bluesky and RSS feeds.</p>

</details>

<h3>findatechjob — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site is live and is a tech and engineering job search engine that indexes company career pages. It fits Programming.</p>

<p>https://findatechjob.dev/ — HTTP 200. The title is &#x27;Find Your Next Role | findatechjob&#x27;. It says &#x27;Search engineering roles by language, location, and level, pulled straight from company career pages&#x27;, shows &#x27;38,614 Live roles, 4424 Companies, 130 Countries&#x27;, and lists roles posted 1–8 days ago.</p>

<p>Caveats: The listing counts change constantly. The entry has no description that uses them.</p>

</details>

<h3>Golang Forum Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The official Go Forum Jobs category is live and active, with topics through November 4, 2026. It fits Programming.</p>

<p>https://forum.golangbridge.org/c/jobs/8 — HTTP 200. The title is &#x27;Jobs - Go Forum&#x27;. The category description reads &#x27;You may post jobs and availability here…&#x27;. Recent topics include &#x27;Looking for a Golang Developer - Internship&#x27; (November 4, 2026) and &#x27;[Hiring] Senior/Lead Go Backend Engineer&#x27; (October 15, 2026).</p>

<p>Caveats: It is a discussion forum category rather than a dedicated job board, and it includes posts from job seekers.</p>

</details>

<h3>CyberSecurityJobsite — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The earlier snapshot failure was temporary. The URL now returns a live UK cybersecurity job board with thousands of listings, which fits InfoSec.</p>

<p>https://www.cybersecurityjobsite.com/jobs/ — HTTP 200. The title is &#x27;Browse Information Security Jobs | Cyber Security Jobs Search UK&#x27;. It shows filter counts, for example Security 6604, Security Engineer 943 and Permanent 7091, with UK salary bands and locations.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Golang Cafe — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The live site returned a Vercel bot checkpoint (HTTP 429), but this is an access failure only. The most recent readable archive (June 2026) shows an active Go-specific job board with a © 2026 footer. It fits Programming. This is a bare-link entry.</p>

<p>https://golang.cafe/ — curl and WebFetch both returned HTTP 429 with a &#x27;Vercel Security Checkpoint&#x27; page.</p>

<p>http://web.archive.org/web/20260615103645/https://golang.cafe/ — The title is &#x27;Golang Jobs | Golang.cafe&#x27; and the description is &#x27;the leading hiring platform for Golang developers&#x27;. The page has an FAQ (&#x27;Every listing is exclusive to the platform and posted directly by hiring companies&#x27;), a Talent Network, and remote/Europe/US job pages. The footer reads © 2026.</p>

<p>Caveats: The current live state was not directly observed. The keep decision rests on a capture from about five months ago.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Vue.js Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site is live and is clearly a Vue.js job board, which fits the Programming section.</p>

<p>https://vuejobs.com/ — HTTP 200 with no redirect. The title is &#x27;Vue.js jobs – Browse through dozens of Vue.js openings&#x27;, and the page says &#x27;The largest collection of Vue.js jobs on the web… Vue and Nuxt jobs… updated hourly&#x27;. It showed about 1,178 jobs, with listings dated within the last few days.</p>

<p>Caveats: The job counts change constantly. I only read the homepage.</p>

</details>

<h3>LaraJobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site is live and calls itself the official Laravel job board, which fits the section.</p>

<p>https://larajobs.com/ — HTTP 200. The title is &#x27;The Official Laravel Job Board - LaraJobs&#x27;, and the page shows current job listings and filters.</p>

</details>

<h3>pyJobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site is live and is a Python developer job board, which fits the section.</p>

<p>https://www.pyjobs.com/ — HTTP 200. The title is &#x27;Python Jobs - Find Your Next Python Developer Role - PyJobs&#x27;, and the meta description says &#x27;Browse Python jobs… Updated daily.&#x27;</p>

<p>Caveats: The site styles its name &#x27;PyJobs&#x27;, while the entry says &#x27;pyJobs&#x27;. The capitalization difference is minor and optional to fix.</p>

</details>

<h3>Python Job Board — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The official python.org job board is live and has current postings.</p>

<p>https://www.python.org/jobs/ — HTTP 200. The title is &#x27;Python Job Board | Python.org&#x27;, and the page has job type, category and location filters. The newest posting dates in the HTML are 2026-10-28, 2026-11-05 and 2026-11-06.</p>

</details>

<h3>Django Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site is live and is a Django job board. Changing the trailing slash is optional.</p>

<p>https://djangojobs.net/jobs — https://djangojobs.net/jobs/ redirects to https://djangojobs.net/jobs, which returns HTTP 200. The title is &#x27;Django Developer Jobs — Browse Open Roles | DjangoJobs.net&#x27;.</p>

<p>Caveats: The listed URL with the trailing slash still works through the redirect. Normalizing it to /jobs is optional.</p>

</details>

<h3>TypeScriptJobs — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site is live and is a TypeScript job board that adds jobs daily, which supports the description.</p>

<p>https://typescriptjobs.net/ — HTTP 200. The title is &#x27;TypeScript Jobs - Find Your Next TypeScript Developer Role&#x27;. The page showed about 22,039 jobs and &#x27;197 New Today&#x27;, with listings marked &#x27;Today&#x27;.</p>

<p>Caveats: The site brands itself &#x27;TypeScript Jobs&#x27; or &#x27;TS Jobs&#x27;, while the entry says &#x27;TypeScriptJobs&#x27;. The difference is cosmetic.</p>

</details>

<h3>R-users — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site resolves and is still a job board for R users, which fits the section. Its listings are old, but the site does not say it has closed.</p>

<p>https://www.r-users.com/ — HTTP 200. The page says &#x27;Jobs for R-users: A job board for people and companies looking to hire R users&#x27; and still offers &#x27;Submit a Job&#x27;. The newest listings are dated 28 Feb 2024, 17 Feb 2024 and 12 Feb 2024.</p>

<p>Caveats: The newest listing is about 2.7 years old, so the board looks low-activity. The maintainer may want to reconsider it, but age alone is not grounds for removal.</p>

</details>

<h3>Jobbsy — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site is live and is a Symfony job board, which matches the description.</p>

<p>https://jobbsy.dev/ — HTTP 200. The title is &#x27;Job board Symfony - Jobbsy&#x27;, and the page lists current Symfony/PHP developer jobs.</p>

<p>Caveats: Most listings are French-language and France-based.</p>

</details>

<h3>QA Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site is live and is a QA and test-automation job board, which fits the section.</p>

<p>https://www.qajobs.co/ — HTTP 200. The title is &#x27;Quality Assurance Jobs | QA Jobs&#x27;, and the page says &#x27;The premier job board for Quality Assurance, SDET, and all other Test Automation Engineer opportunities&#x27;.</p>

</details>

<h3>androidDev.careers — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site is live and is an Android developer job board, which fits the section.</p>

<p>https://androiddev.careers/ — HTTP 200. It normalizes to a trailing-slash URL. The title is &#x27;Browse 3382 Android Developer jobs with salaries – androidDev.careers&#x27;.</p>

</details>

<h3>GrepJob — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site is live and is an aggregator of software engineering jobs scraped from company career pages, which supports the description&#x27;s main claim.</p>

<p>https://grepjob.com/ — HTTP 200. The page says &#x27;Find Your Next Software Engineering Role Faster: 70,000+ jobs scraped hourly from company career pages. No ghost jobs, reposts, or sponsored listings.&#x27; The meta description mentions &#x27;curated tech jobs from top companies&#x27;.</p>

<p>Caveats: I could not verify the &#x27;high paying&#x27; part of the description. The site says &#x27;top companies&#x27;, not high pay, and its listings include a broad range of employers. A maintainer could optionally soften the wording, but I did not show the claim to be false.</p>

</details>

<h3>Software Tech Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site is live and is a software and tech job board focused on the US and Canada, which matches the description.</p>

<p>https://softwaretechjobs.com/ — HTTP 200. The title is &#x27;Software Tech Jobs - US &amp; Canada Tech Jobs&#x27;, and the meta description says &#x27;dedicated to finding you tech related software jobs - specially from USA and Canada&#x27;. Some categories have jobs (DevOps 349, AI/Blockchain 388), while several show 0.</p>

<p>Caveats: Several job categories are currently empty.</p>

</details>

<h3>Scala Jobs — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The live site sits behind a Vercel bot checkpoint (HTTP 429), but the latest archived page (July 2026) shows an active Scala job board with 2026 listings. A blocked request is not evidence the site is dead.</p>

<p>https://scalajobs.com/ — Direct fetch returned HTTP 429 with the title &#x27;Vercel Security Checkpoint&#x27;, which is a bot challenge, not an error page.</p>

<p>http://web.archive.org/web/20260717113132id_/https://scalajobs.com/ — The 2026-07-17 snapshot is titled &#x27;Scala Jobs | ScalaJobs.com&#x27; and lists Scala roles posted on 21 May 2026, 29 April 2026 and other dates.</p>

<p>Caveats: I could not read the live site directly because of the Vercel checkpoint. My evidence comes from a July 2026 archive snapshot.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Index.dev — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>index.dev redirects to www.index.dev, which is still a software/AI engineering talent platform. It markets AI-first engineers and a proprietary AI delivery workflow, and has a &#x27;Find a Job&#x27; sign-up for engineers. The short description &#x27;AI-powered platform for software talent&#x27; is still broadly accurate.</p>

<p>https://www.index.dev/ — index.dev redirects here (200). Title: &#x27;Index.dev | Build Faster with AI-First Engineers&#x27;. Text mentions a &#x27;proprietary AI delivery workflow&#x27;, &#x27;Verified Global Talent… 30,000 senior engineers&#x27;, and Hire Talent / Find a Job navigation.</p>

<p>https://workspace.index.dev/register — The &#x27;Find a Job&#x27; link points to this registration page, so engineers have a candidate-side entry point.</p>

<p>Caveats: The site is mainly employer-facing (talent network and delivery services), not a public job listing board. The maintainer may want to judge fit with the Programming job-board section.; The candidate registration flow was not explored past the link target.</p>

</details>

<h3>Jobs in Rust — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Live Rust jobs marketplace (it redirects to www). The description matches.</p>

<p>https://www.jobsinrust.com/ — jobsinrust.com redirects here (200). Title: &#x27;Rust Jobs — Live Roles, Updated Daily&#x27;. Text: &#x27;Jobs in Rust marketplace… across the Rust ecosystem&#x27;. It showed 7,526 published Rust roles, updated 10 Nov 2026.</p>

<p>Caveats: Same operator and template as Jobs in Flutter. The site also lists AI-agent roles.</p>

</details>

<h3>NearMetal — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site matches every claim in the description: systems programming roles across kernel, compilers, databases, embedded and performance, each linked to the company&#x27;s own posting.</p>

<p>https://nearmetal.dev/ — HTTP 200. Text: &#x27;Systems programming jobs, close to the metal. Kernels, compilers, databases, storage, networking, virtualization, embedded, performance. Every role links to the company&#x27;s own posting&#x27;. It showed 252 roles from 78 companies.</p>

</details>

<h3>Meridian — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Live remote tech board that matches jobs to timezones and aggregates and deduplicates from job boards and ATS feeds. Its region filters now include APAC as well as Europe and the Americas. The listed US/LATAM/EU coverage is still supported, and the entry doesn&#x27;t claim to be limited to those regions.</p>

<p>https://meridianremote.com/ — HTTP 200. Title: &#x27;Remote Tech Jobs Matched to Your Timezone · Meridian&#x27;. Text: &#x27;Sourced from 15 job boards &amp; ATS feeds · deduplicated · always links to the original posting&#x27;. Region filters: Anywhere, Europe, Americas, APAC. It showed 3,698 open roles.</p>

<p>Caveats: The listings sampled on the homepage included non-tech roles (e.g. teaching English).; The &#x27;US, LATAM, EU&#x27; wording could optionally be broadened to mention APAC. That would be a clarification, not a correction.</p>

</details>

<h3>Career Vault — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The site is reachable, the identity matches, and it is a remote job board, so it fits the Remote section.</p>

<p>https://careervault.io/ — HTTP 200. Title: &#x27;Career Vault - Remote jobs in Programming, Design, Marketing, and more.&#x27; Meta: &#x27;Career Vault is a remote job board.&#x27; It has job category browsing and &#x27;Post a job — $199&#x27;.</p>

</details>

<h3>Jobspresso — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The listed /remote-work/ page is live and is Jobspresso&#x27;s remote jobs listing, so it fits the Remote section.</p>

<p>https://jobspresso.co/remote-work/ — HTTP 200. Title: &#x27;Remote Jobs: 1,000+ Openings, Updated Daily | Jobspresso&#x27;. Text: &#x27;Browse every remote job on Jobspresso… New jobs are added daily&#x27;.</p>

</details>

<h3>We Work Remotely — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. We Work Remotely is reachable and is a remote job board, so it fits the Remote section.</p>

<p>https://weworkremotely.com/ — HTTP 200, no redirect. Title: &#x27;We Work Remotely: Advanced Remote Job Search&#x27;. It has remote job categories across programming, design, support and more.</p>

</details>

<h3>RemoteOrNothing — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site supports every claim in the description: listings carry &#x27;Source checked&#x27; badges, show location eligibility, and send applicants to the original employer application page.</p>

<p>https://remoteornothing.com/ — HTTP 200. Meta: &#x27;Find remote opportunities with clearer location eligibility, source-linked applications…&#x27;. Listings show &#x27;✓ Source checked 1d ago&#x27; and eligibility such as &#x27;Worldwide&#x27; or &#x27;USA Only&#x27;. Text: &#x27;apply through the original employer application page.&#x27;</p>

<p>Caveats: I did not check whether every listing is fully remote, but the site&#x27;s framing is remote-only.</p>

</details>

<h3>RemoteYeah — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. RemoteYeah is reachable and is a remote job board, so it fits the Remote section.</p>

<p>https://remoteyeah.com/ — HTTP 200. Title: &#x27;Remote jobs: Front-end, Back-end, DevOps, QA &amp; More&#x27;. Meta: &#x27;Browse 10550+ engineer jobs…&#x27;. Brand: RemoteYeah.</p>

</details>

<h3>Remotive — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Remotive is reachable and is a remote job board, so it fits the Remote section.</p>

<p>https://remotive.com/ — HTTP 200. Title: &#x27;Remote Jobs in Programming, Support, Design and more&#x27;. Meta: &#x27;All our 134,376 jobs are curated and fully remote.&#x27; It offers paid &#x27;Unlock all jobs&#x27; access.</p>

</details>

<h3>Remoote — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site supports every claim in the description: remote job listings, country, skill and experience-level filtering, and optional paid Premium plans.</p>

<p>https://remoote.app/remote-working — HTTP 200. Title: &#x27;Remote Working Jobs, Companies, and Salaries | Remoote&#x27;. It showed 71,624 remote jobs and filter text covering country, skills and experience level.</p>

<p>https://remoote.app/pricing — Premium plans: €5/week, €15/month, €60/year, with unlimited applications and advanced filters. A free tier exists, so subscriptions are optional.</p>

<p>Caveats: Filters were confirmed from page text only, not by using them.</p>

</details>

<h3>Remote — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Remote.com&#x27;s jobs page is reachable and lists remote roles, so it fits the Remote section.</p>

<p>https://remote.com/jobs/all — HTTP 200. Meta: &#x27;Find a remote job at the best companies on the planet&#x27;. It lists jobs with Workplace and country/timezone filters.</p>

<p>Caveats: Some listings are hybrid rather than fully remote.; The page footer still says &#x27;Copyright © 2024&#x27;, but the listings are current.</p>

</details>

<h3>remote | OK — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Remote OK is reachable and is a remote job board, so it fits the Remote section. The link text &#x27;remote | OK&#x27; is the catalog&#x27;s own styling of the name.</p>

<p>https://remoteok.com/ — HTTP 200. Title: &#x27;Remote Jobs in Programming, Design, Sales and more #OpenSalaries&#x27;. Meta: &#x27;Remote OK® is the #1 Remote Job Platform…&#x27;.</p>

<p>Caveats: The site&#x27;s brand is &#x27;Remote OK&#x27;. Restyling the link text is optional and was not checked against the catalog&#x27;s conventions.</p>

</details>

<h3>JustRemote — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. JustRemote is reachable, lists current remote jobs, and fits the Remote section.</p>

<p>https://justremote.co/ — HTTP 200. Title: &#x27;Remote Jobs: Design, Marketing, Programming, Writing &amp; More&#x27;. Its latest listings are dated 10 Nov, and it says it covers &#x27;fully and partially remote jobs&#x27;.</p>

</details>

<h3>SkipTheDrive — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. SkipTheDrive is reachable and is a remote / work-from-home job board, so it fits the Remote section.</p>

<p>https://www.skipthedrive.com/ — HTTP 200. Title: &#x27;Find remote jobs on SkipTheDrive - Work From Home&#x27;. Text: &#x27;Search 40,000+ jobs from more than 3,700 companies. Jobs are updated on a daily basis.&#x27;</p>

</details>

<h3>Working Nomads — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Working Nomads loads at the listed URL and is a fully remote job board.</p>

<p>https://www.workingnomads.com/jobs — HTTP 200. Title: &#x27;Remote Jobs | Working Nomads&#x27;. og:description: &#x27;Discover fully remote jobs worldwide for digital nomads and remote workers&#x27;. Page text: &#x27;50K+ Remote Jobs Updated daily&#x27;.</p>

<p>Caveats: Individual posting dates did not show up in the fetched HTML.</p>

</details>

<h3>Jaabz — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The description (tech jobs with visa sponsorship, relocation and remote filters) matches the live site, and remote roles fit the section.</p>

<p>https://jaabz.com/ — HTTP 200. Title: &#x27;Jaabz – Discover Tech Jobs Worldwide | Remote &amp; Relocation&#x27;. Meta: &#x27;Explore 5126+ tech jobs ... Browse remote roles, relocation packages, and sponsored careers&#x27;. Navigation has Visa Sponsorship, Relocation and Remote sections with daily-updated &#x27;November 2026&#x27; rankings.</p>

<p>Caveats: The site is about relocation and visa sponsorship as much as remote work; listing it under Remote is the maintainer&#x27;s existing choice.</p>

</details>

<h3>Remote Python — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Remote Python is reachable and still describes itself as a remote-only Python job board, with a posting from about 10 days ago.</p>

<p>https://www.remotepython.com/ — HTTP 200. Meta: &#x27;Job board and aggregator for remote Python jobs and only remote Python jobs&#x27;. Latest listing on the homepage: &#x27;1 week, 3 days ago&#x27;.</p>

<p>Caveats: Posting volume is low: the next listing is about 2 months old.</p>

</details>

<h3>Remote JavaScript Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The URL is the remote-filtered view of Javascript.Jobs and shows current remote JS listings.</p>

<p>https://javascript.jobs/remote — HTTP 200. Title: &#x27;Remote Javascript Jobs&#x27;. Recent remote listings include Northbeam (3 days ago) and Mozilla (4 days ago). The site calls itself &#x27;the biggest job board dedicated to Javascript Jobs&#x27;.</p>

<p>Caveats: The site also lists non-remote jobs; the URL points at its remote filter.</p>

</details>

<h3>Workew — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Workew&#x27;s remote jobs page is reachable and still describes itself as a remote hiring platform.</p>

<p>https://workew.com/remote-jobs/ — HTTP 200. Title: &#x27;Remote Jobs - Workew&#x27;. Region filters (Remote EMEA, LATAM, US, etc.). Page text: &#x27;The easiest way to hire and get hired remotely&#x27;. Page carries 2026-11-11 date stamps.</p>

<p>Caveats: Listings load through JavaScript and were not rendered, so individual postings were not inspected.</p>

</details>

<h3>Remoters — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Remoters is reachable and is a remote and digital-nomad job board.</p>

<p>https://remoters.net/jobs/ — HTTP 200. Title: &#x27;Remote, Work From Home and Digital Nomad Jobs - Remoters Job Board&#x27;. Page says it has &#x27;over 100 hand-screened, free to publish remote jobs per month&#x27;.</p>

<p>Caveats: Posting dates were not visible in the fetched content.</p>

</details>

<h3>DailyRemote — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. DailyRemote is reachable and has listings from today.</p>

<p>https://dailyremote.com/ — HTTP 200. Title: &#x27;DailyRemote: Remote Jobs &amp; Work From Home Jobs&#x27;. 17 listings dated &#x27;Nov 10, 2026&#x27;.</p>

</details>

<h3>Ruby On Remote — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. curl got a Cloudflare 403 challenge, but WebFetch read the page: a live Ruby/Rails remote job board with current listings.</p>

<p>https://rubyonremote.com/ — curl returned 403 &#x27;Just a moment...&#x27; (Cloudflare). WebFetch read the page: it calls itself &#x27;the #1 Ruby on Rails remote job board&#x27; and shows listings, including a &#x27;New&#x27; GitLab Intermediate Fullstack Engineer role and featured roles from Better Stack, Figma and others.</p>

<p>Caveats: Exact posting dates were not shown; only &#x27;New&#x27; and &#x27;Featured&#x27; labels.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>RemoteSource — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link resolves directly (HTTP 200, no redirect) to Remote Source&#x27;s fully remote jobs search page. This fits the Remote section.</p>

<p>https://www.remotesource.com/jobs — HTTP 200. Title is &#x27;Fully Remote Jobs | Remote Source&#x27;. Meta description: &#x27;Search fully remote jobs from company career pages... location requirements, and current openings with free access to every listing.&#x27;</p>

<p>Caveats: Only the landing page was checked; listing quality was not audited.</p>

</details>

<h3>tryremotely — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link resolves (HTTP 200) to the &#x27;Remotely - Remote Jobs&#x27; board. It still presents itself as a remote job board, so it fits the Remote section.</p>

<p>https://tryremotely.com/ — Title is &#x27;Remotely - Remote Jobs&#x27;. Meta: &#x27;Find the best remote jobs worldwide. Browse thousands of work-from-home opportunities in engineering, design, marketing, sales, and product. Hybrid and on-si...&#x27;</p>

<p>Caveats: The site also mentions hybrid and on-site roles. Its main positioning is still remote jobs.; The site brands itself &#x27;Remotely&#x27;. The catalog name &#x27;tryremotely&#x27; matches the domain, so this is optional cosmetic cleanup.</p>

</details>

<h3>Find My Remote — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link resolves (HTTP 200) to the Find My Remote remote job aggregator. The name matches and it fits the Remote section.</p>

<p>https://findmyremote.ai/ — Title is &#x27;Find My Remote — Thousands of Remote Jobs Updated Daily&#x27;. Meta: &#x27;thousands of remote jobs from top companies, all in one place. Engineering, design, marketing, and more. Updated daily.&#x27;</p>

<p>Caveats: Only the homepage metadata was checked.</p>

</details>

<h3>Benture — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link resolves (HTTP 200, adds a trailing slash) to Benture&#x27;s remote job board. The name matches and it fits the Remote section.</p>

<p>https://benture.io/ — Title is &#x27;Find Remote Jobs | Benture&#x27;. Meta: &#x27;Discover top remote jobs. Create your resume using Benture and apply for remote jobs today.&#x27;</p>

<p>Caveats: Only the homepage metadata was checked.</p>

</details>

<h3>Remote100K — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link resolves (HTTP 200) to Remote100K, a board for remote jobs paying $100K+. The name matches and it fits the Remote section.</p>

<p>https://remote100k.com/ — Title is &#x27;Remote100K - Remote Jobs Paying $100K+&#x27;. Meta: &#x27;Find remote jobs paying $100K+ at top companies... Apply directly, no account required.&#x27;</p>

<p>Caveats: Only the homepage metadata was checked.</p>

</details>

<h3>RemoteRocketship — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link resolves (HTTP 200) to Remote Rocketship, a remote job aggregator. It fits the Remote section.</p>

<p>https://www.remoterocketship.com/ — Title is &#x27;Remote Rocketship | Remote Jobs You Won&#x27;t Find on LinkedIn&#x27;. Meta: &#x27;We find new remote jobs minutes after companies post them... The most remote jobs on the internet.&#x27;</p>

<p>Caveats: The site brands itself &#x27;Remote Rocketship&#x27; (two words). The catalog&#x27;s &#x27;RemoteRocketship&#x27; is a cosmetic difference, not an identity error.</p>

</details>

<h3>TrulyRemote — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link resolves (HTTP 200) to Truly Remote, a board for international and work-from-anywhere remote jobs. It fits the Remote section.</p>

<p>https://trulyremote.co/ — Title is &#x27;International Remote Jobs &amp; Work From Anywhere Jobs | Truly Remote&#x27;. Meta: &#x27;Explore legit remote jobs that hire worldwide, updated daily.&#x27;</p>

<p>Caveats: Only the homepage metadata was checked.</p>

</details>

<h3>FindRemoteLawJobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Find Remote Law Jobs is still a remote-only legal job board. The page header reads &#x27;Remote Law Jobs... for attorneys, in-house counsel, and paralegals. Only remote roles&#x27;. This matches the description.</p>

<p>https://findremotelawjobs.com/ — HTTP 200. Title is &#x27;Remote Law Jobs | 100% Remote Attorney &amp; Legal Jobs&#x27;. The page lists 22,921 remote legal jobs, &#x27;Only remote roles · Updated daily · Apply directly&#x27;, with listings updated Nov 10, 2026.</p>

</details>

<h3>FindRemoteAccountingJobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Find Remote Accounting Jobs is still a remote-only accounting and finance job board. This matches the description.</p>

<p>https://findremoteaccountingjobs.com/ — HTTP 200. Title is &#x27;Remote Accounting Jobs | 100% Remote Accounting Roles&#x27;. Meta: &#x27;Browse remote accounting and finance jobs only.&#x27; The page shows 36,806 jobs, &#x27;Only remote roles · Updated daily&#x27;, updated Nov 10, 2026.</p>

</details>

<h3>Remote Nomad Jobs — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Remote Nomad Jobs is still a curated board of 100% fully remote, work-from-anywhere jobs for digital nomads. This matches the description.</p>

<p>https://www.remotenomadjobs.com/ — HTTP 200. Title is &#x27;Remote Nomad Jobs: Fully Remote Jobs for Digital Nomads&#x27;. Body: &#x27;a curated job board that helps digital nomads find 100% fully remote, work-from-anywhere jobs from remote-first companies worldwide.&#x27;</p>

<p>Caveats: The site has a paid &#x27;Unlock All Jobs&#x27; tier. The description makes no claim about cost.</p>

</details>

<h3>RoleSense — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>All of the description&#x27;s claims are confirmed: per-job country eligibility, work-style signals (pace, autonomy, meeting load) quoted from the posting, and sourcing from ATS boards including Greenhouse, Lever, Ashby and Workable.</p>

<p>https://role-sense.com/ — Homepage: &#x27;We read the country fence out of every remote ad&#x27;, &#x27;see what the ad says about pace, autonomy and work–life balance, quoted from the posting&#x27;. The signals list includes &#x27;Autonomy&#x27;, &#x27;Fast Pace&#x27; and &#x27;Minimal Meetings&#x27;.</p>

<p>https://role-sense.com/about — &#x27;Jobs come from employers&#x27; public applicant tracking system boards, such as Greenhouse, Lever, Ashby and Workable, and link back to the employer&#x27;s own posting. An AI model reads each posting and extracts its country limits...&#x27;</p>

<p>Caveats: The site now also offers AI resume analysis and paid Pro alerts. These additions do not contradict the description.</p>

</details>

<h3>Jobicy — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Jobicy&#x27;s remote jobs page loaded (HTTP 200, no redirect). It describes itself as a remote job board with fresh listings every day, salary info where available, and applying without an account. That matches every claim in the entry.</p>

<p>https://jobicy.com/jobs — Title &#x27;Remote Jobs — 70k+ Open Roles (November 2026) | Jobicy&#x27;. Meta description: &#x27;Find remote jobs fast. Fresh listings every day, salary info where available. Apply in minutes — no account needed.&#x27; Canonical is https://jobicy.com/jobs.</p>

<p>Caveats: Applying without an account was not tested; the evidence is the site&#x27;s own wording.</p>

</details>

<h3>Low Key Remote — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>lowkeyremote.com resolves to https://lowkeyremote.com/. The site describes low-stress, async remote roles with no phone calls or meetings, hand-checked and curated for introverts, people with social anxiety and people with disabilities. All description claims match.</p>

<p>https://lowkeyremote.com/ — Meta: &#x27;Low stress remote jobs with no phone calls, no meetings, no on-call hours... Hand-checked for introverts and people with social anxiety.&#x27; Body: &#x27;Low stress, async remote roles with minimal live interaction. Curated for introverts, people with social anxiety, and people with disabilities.&#x27; It shows 308 live roles, each tagged with &#x27;0 calls · 0 meetings&#x27;.</p>

<p>Caveats: Many current listings are AI-training/contract gigs; the board is still a remote job board.</p>

</details>

<h3>Covesight — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Covesight is live. It describes remote jobs checked daily against the user&#x27;s country, hours and languages, which matches the entry. It now presents itself mainly as a matching service (resume or quiz), but the listed claim is still accurate.</p>

<p>https://covesight.com/ — Meta: &#x27;Free remote job matching. Every job is checked daily against where you live, your hours and languages.&#x27; Body: &#x27;Every day we check each remote job against your country, timezone a[nd]...&#x27;. It also has a public &#x27;Jobs / Open worldwide&#x27; board.</p>

<p>Caveats: The site is now framed as a matching service; the maintainer may want to mention that, but it is not a correction.</p>

</details>

<h3>Remote Landers — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Remote Landers is live at https://remotelanders.com. It lists 100% remote jobs straight from each company&#x27;s own careers page, shows a salary on every listing, and filters out listings without a salary, hybrid and on-site roles. The entry&#x27;s &#x27;employers&#x27; own ATS&#x27; wording is equivalent to the site&#x27;s &#x27;company&#x27;s own careers page&#x27;.</p>

<p>https://remotelanders.com — Meta: &#x27;Browse 100% remote, work from home jobs with the salary on every listing.&#x27; Body: &#x27;lists 6,755 remote jobs from 1,533 companies, each with its salary shown and a link to the company&#x27;s own careers page&#x27;. FAQ: &#x27;Every listing passes a filter that rejects hybrid and on-site roles, listings without a salary, and stale postings&#x27;.</p>

</details>

<h3>RemoteHunt — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>RemoteHunt confirms all three claims: remote jobs filtered by whether they can hire in your country, sourced from employer career pages (the how-we-check page says it follows 2,476 such pages), and a 0–100 score against your resume. The &#x27;2,400+&#x27; figure is currently accurate but will drift.</p>

<p>https://remotehunt.app/jobs — &#x27;64,096 remote jobs by role, updated hourly... Almost all come from employers&#x27; own careers pages&#x27;. Section: &#x27;Remote jobs by the country you live in&#x27;.</p>

<p>https://remotehunt.app/how-we-check — &#x27;...applicant tracking systems such as Greenhouse, Lever or Ashby. We follow 2,476 of these pages.&#x27; Includes a section titled &#x27;How the 0–100 score is made&#x27;.</p>

<p>https://remotehunt.app/ — Title: &#x27;RemoteHunt — Remote jobs that can hire you, scored against your resume&#x27;. &#x27;Free to start. No card needed.&#x27;</p>

<p>Caveats: &#x27;2,400+&#x27; is a volatile count; a durable rewording without the number may be better later. It is accurate today.</p>

</details>

<h3>NodJobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>NodJobs is live (launched October 2026). It lists remote jobs straight from employers, rechecked every few hours, with no duplicates or stale listings and direct apply links to the employer. It is free and needs no account. The About page says listings are reviewed against the employer&#x27;s posting, so &#x27;hand-picked&#x27; is plausible but not stated verbatim. Salary is shown when the employer publishes it, not on every listing. The entry ties &#x27;every listing&#x27; to the apply link, so this reads as an overstatement rather than a false claim.</p>

<p>https://nodjobs.com — Meta: &#x27;Remote jobs straight from the companies hiring, rechecked every few hours. No duplicates, no stale listings — and you always apply directly with the company.&#x27; It has a &#x27;$ With salary&#x27; filter; some listings show no salary.</p>

<p>https://nodjobs.com/about — &#x27;free job board for fully remote roles that people in the United States can apply for... Pay is shown whenever the employer publishes it. No account and no fees.&#x27; Also: &#x27;We check each listing&#x27;s work type, who can apply, and pay against the employer&#x27;s own posting.&#x27;</p>

<p>https://nodjobs.com/faq — Free and no account needed. Hybrid and in-office jobs are planned and would be listed in separate labeled sections.</p>

<p>Caveats: The site is currently limited to US-eligible remote roles; the entry doesn&#x27;t say so. Optional clarification.; &#x27;Hand-picked&#x27; and &#x27;exact salaries&#x27; are somewhat promotional; the site says pay is shown when published. A maintainer might soften this to &#x27;pay shown when the employer publishes it&#x27;.</p>

</details>

<h3>HeyRole — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>HeyRole is live. It offers remote jobs with location, function and seniority filters, an AI &#x27;Agent&#x27; that searches and explains matches, and job pages that link to the employer&#x27;s original listing (a Greenhouse link was observed). All claims are supported.</p>

<p>https://heyrole.ai/ — &#x27;22,721 remote jobs from 1,719 companies&#x27;. Filters: locations, Function, Seniority, Employment type, Skills. Navigation includes &#x27;Agent&#x27;.</p>

<p>https://heyrole.ai/agent — &#x27;Tell me what you do and where you can work from. I&#x27;ll search every remote job on HeyRole and explain the best matches.&#x27;</p>

<p>https://heyrole.ai/job/0184a234-85ea-46a4-9760-591e66f5847e — The job page for Proof&#x27;s Product Design Lead links to the original listing at proofserve.com/careers/...?gh_jid=4744267005.</p>

</details>

<h3>ApplyRemote — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>ApplyRemote is live. It lists remote jobs from companies hiring worldwide and has an application-tracking board, an ATS-focused CV builder and tailored cover letters. The CV builder and cover letters are Pro (paid) features; the entry does not claim they are free, so it stays accurate.</p>

<p>https://applyremote.co/ — Meta: &#x27;Search 8,100+ open remote jobs in every industry, apply on the original posting and track every application. CV builder and cover letters with Pro.&#x27; Body: &#x27;Track every application&#x27;; &#x27;A CV built for ATS screening — Pro&#x27;; &#x27;Cover letters in seconds — Pro: A tailored letter for each role&#x27;.</p>

<p>Caveats: The CV builder and cover letters are behind the Pro tier. The maintainer may optionally note that.; The page did not say the cover letters are AI-generated in those words; &#x27;tailored... in the tone you choose&#x27; implies generation.</p>

</details>

<h3>APM Career — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>APM Career is live. It lists associate PM internships, full-time new-grad, junior and rotational PM roles for the 2026–2027 season. That matches &#x27;entry-level and junior PM positions&#x27;.</p>

<p>https://www.apmcareer.com/ — &#x27;Your comprehensive platform for discovering associate product manager internships, full-time positions, and rotational programs&#x27;. Listings include Meta RPM, Google APM 2027, Databricks APM New Grad, IBM Entry Level PM and Spotify Junior PM.</p>

<p>Caveats: Many listings show &#x27;Posted 30+ days ago&#x27;. Listing freshness was not checked individually.</p>

</details>

<h3>APM List — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>APM List (by Aced) is live. It describes itself as a curated list of APM programs, PM internships and new-grad PM jobs, updated weekly, and shows 2027 program statuses. The description is accurate.</p>

<p>https://apmlist.com/ — &#x27;APM List is a curated list of top APM programs, product management internships, and product manager jobs for new graduates. The list is maintained and updated weekly by Aced.&#x27; Shows statuses such as &#x27;Google Closed for 2027&#x27; and &#x27;Indeed Open&#x27;.</p>

</details>

<h3>Best PM Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. www.bestpmjobs.com loads without redirect (canonical https://www.bestpmjobs.com/) and is a product-management job board that aggregates PM roles from company career pages. Identity, reachability and fit with the Product section are confirmed.</p>

<p>https://www.bestpmjobs.com/ — Title: &#x27;Best PM Jobs | Exclusive Product Management Opportunities&#x27;. &#x27;We scan thousands of company career pages every day and aggregate the best product management opportunities here&#x27;. PM categories include AI PM, Director of Product and Entry Level PM.</p>

<p>Caveats: Some features (advanced filters) appear gated; not material to a bare link.</p>

</details>

<h3>Mind the Product — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The Mind the Product jobs board is live at the listed URL. It covers product management, design and engineering roles (2,549 open roles). The entry&#x27;s &#x27;product managers and designers&#x27; is still accurate; adding engineering is an expansion, not a correction.</p>

<p>https://www.mindtheproduct.com/jobs/ — Title: &#x27;Product Management, Design &amp; Engineering Jobs | Mind the Product&#x27;. &#x27;The #1 job board for product professionals. Find your next role in product management, design or engineering.&#x27; &#x27;2,549 open roles&#x27;.</p>

<p>Caveats: &#x27;Well-known&#x27; is subjective and was not assessed.</p>

</details>

<h3>Remote PM Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Remote PM Jobs is live and matches every claim: PM-only, sourced from each company&#x27;s own ATS, verified remote, synced daily, with salary data (65% of listings show a salary range).</p>

<p>https://remotepmjobs.com/ — &#x27;The job search built only for product managers. Every listing is sourced directly from the company&#x27;s own ATS, verified remote, and synced daily&#x27;. Meta: &#x27;1870 verified-remote product manager jobs from 1010 companies... 65% show a salary range.&#x27;</p>

</details>

<h3>ProductManagementJob.com — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>ProductManagementJob.com redirects to the trailing-slash canonical and is live. It lists PM jobs from APM up, and the latest jobs are mostly in India. Its meta says &#x27;APM to Director&#x27;, but its jobs-page content also mentions VP Product and CPO opportunities, so &#x27;APM to VP level&#x27; is not contradicted. &#x27;Strongest in India&#x27; is supported by the India-heavy listings.</p>

<p>https://productmanagementjob.com/ — Meta: &#x27;Find product manager jobs across India, USA, Canada, UK, Germany, UAE, Australia, Ireland and remote. APM to Director PM roles — updated daily.&#x27; &#x27;Latest PM Jobs — Fresh product manager job openings from top companies across India.&#x27;</p>

<p>https://productmanagementjob.com/jobs — Page content mentions &#x27;VP Product&#x27;, &#x27;VP and CPO opportunities&#x27; and &#x27;VP of Product. These roles are available at...&#x27;</p>

<p>Caveats: The site now advertises coverage of several countries beyond India; &#x27;strongest in India&#x27; is still consistent.</p>

</details>

<h3>Lenny&#x27;s Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Lenny&#x27;s Jobs is live. Its meta description almost exactly matches the entry: &#x27;product, growth, AI, and startup jobs curated for Lenny&#x27;s community, with open roles from top tech companies and high-growth startups&#x27;. It now also covers engineering and design, which is an expansion, not a correction.</p>

<p>https://www.lennysjobs.com/ — Title: &#x27;Lenny&#x27;s Jobs: Product, Engineering, Design &amp; Growth Jobs&#x27;. Meta: &#x27;Find product, growth, AI, and startup jobs curated for Lenny&#x27;s community, with open roles from top tech companies and high-growth startups.&#x27; Shows &#x27;7,000+ jobs&#x27;.</p>

<p>Caveats: The homepage tagline &#x27;All the roles at every tech company&#x27; sits a little awkwardly with &#x27;curated&#x27;, but the meta still says curated.</p>

</details>

<h3>Guru — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare-link entry. Direct requests get HTTP 403, which looks like bot protection. A Wayback snapshot from 2 Nov 2026 shows the official Guru site still describes itself as a freelance platform connecting businesses and freelancers. Per the review rules, a 403 alone is not grounds for removal.</p>

<p>https://www.guru.com/ — Direct curl and WebFetch both returned HTTP 403 (bot protection); page content was not readable.</p>

<p>https://web.archive.org/web/20261102163905/https://www.guru.com/ — Snapshot dated 2026-11-02. Meta description: &#x27;On Guru, businesses and expert freelancers from around the globe connect, collaborate, and get work done on a flexible and secure platform.&#x27;</p>

<p>Caveats: The live page could not be read directly because of the 403. Current content was confirmed only through an archive snapshot from about a week ago.</p>

</details>

<h3>People Per Hour — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare-link entry. PeoplePerHour is live and remains a marketplace for hiring freelancers and finding freelance work.</p>

<p>https://www.peopleperhour.com/ — HTTP 200. Title: &#x27;PeoplePerHour.com - Hire Freelancers Online &amp; Find Freelance Work&#x27;. Meta: &#x27;Post a project for free to find professional freelancers and find freelance jobs in minutes!&#x27;</p>

</details>

<h3>Fiverr — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare-link entry. Fiverr is live and remains a freelance services marketplace.</p>

<p>https://www.fiverr.com/ — HTTP 200. Title: &#x27;Fiverr | Freelance services marketplace | Find top global talent&#x27;. Meta: &#x27;One marketplace, millions of professional services.&#x27;</p>

<p>Caveats: Fiverr is a gig/services marketplace where freelancers list services, not a traditional job board. It still fits the Freelancer section.</p>

</details>

<h3>Hubstaff — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare-link entry. hubstafftalent.net is live and offers free hiring of freelancers and remote workers, which fits the section. The link text says &#x27;Hubstaff&#x27; while the product is Hubstaff Talent. This is a naming nuance, not an identity error.</p>

<p>https://hubstafftalent.net/ — HTTP 200, no redirect. Title: &#x27;Hire Freelancers &amp; Remote Workers For Free&#x27;. Meta: &#x27;Find and hire the highest quality freelancers from around the world - for free.&#x27;</p>

<p>Caveats: The maintainer may want to rename the link text to &#x27;Hubstaff Talent&#x27; for clarity. The current name is not wrong, so this is not a factual correction.</p>

</details>

<h3>GigGrabbers — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare-link entry. The URL is live and serves GigGrabbers&#x27; freelance jobs page. The site is a freelance marketplace with project posting and escrow.</p>

<p>https://www.giggrabbers.com/freelance-jobs — HTTP 200, no redirect. Title: &#x27;Freelance Jobs in 2026 — Find Remote &amp; Online Work | Giggrabbers&#x27;. Meta: &#x27;Hire vetted freelancers for web development, design, SEO, AI content, and more. Post a project free... Escrow protection on every job.&#x27;</p>

</details>

<h3>Techamana — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare-link entry. www.techamana.com redirects to techamana.com, which is a vetted freelance-experts platform. That fits the section. The www link still works, so no URL change is required.</p>

<p>https://techamana.com/ — Reached by redirect from https://www.techamana.com; HTTP 200. Title: &#x27;Hire the Best 5% of Verified Freelance Experts | Techamana&#x27;. Meta mentions freelance experts in software development, design, and product and project management.</p>

<p>Caveats: Optionally, the maintainer could normalize the link to the apex domain https://techamana.com/. This is not required.</p>

</details>

<h3>CreatorJobBoard — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site is live and describes itself as a job board for the creator economy. It lists video editing, graphic design, social media management, UGC and growth roles, which matches the description.</p>

<p>https://creatorjobboard.com/ — HTTP 200. Title: &#x27;CreatorJobBoard - The largest job board for the creator economy&#x27;. Meta: &#x27;Creator economy jobs across YouTube, Instagram, TikTok and more — video editing, social media, UGC, paid ads...&#x27;. Body categories include graphic design, social media management, UGC creation, and growth &amp; strategy.</p>

<p>Caveats: The site also lists full-time salaried roles, not only freelance gigs. The entry doesn&#x27;t claim exclusivity, and the site mentions hourly and per-project work, so the Freelancer section still fits.</p>

</details>

<h3>Fashion Workie — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare-link entry. Fashion Workie is live and lists fashion jobs, internships, work placements and castings. That fits the Fashion section.</p>

<p>https://www.fashionworkie.com/ — HTTP 200. Title: &#x27;Fashion Internships &amp; Jobs | Fashion Work Placements &amp; Castings&#x27;. Meta: &#x27;Entry level, Graduate and Retail Fashion Jobs, Internships, Work Placements, Castings and Collaborations listings...&#x27;</p>

</details>

<h3>LuxuryRecruit — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare-link entry. LuxuryRecruit is live. It is an executive search and recruitment agency focused on fashion, luxury goods and specialty retail, and it publishes a jobs archive. That is a reasonable fit for the Fashion section.</p>

<p>https://www.luxuryrecruit.com/ — HTTP 200. Title: &#x27;Luxury Recruit – Executive Search and Recruitment&#x27;. Meta: &#x27;Specialist executive search and recruitment agency. Focusing on Speciality Retail, Fashion, Luxury Goods, Travel &amp; Leisure, Digital, and Brands Jobs&#x27;.</p>

<p>https://www.luxuryrecruit.com/jobs — HTTP 200. Title: &#x27;Jobs Archive – Luxury Recruit&#x27;. This is a WordPress jobs post-type archive.</p>

<p>Caveats: This is a recruitment agency with job listings rather than an open job board. I did not count active listings.</p>

</details>

<h3>Upwork — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare-link entry. Direct access returns HTTP 403 from a bot challenge (&#x27;Challenge - Upwork&#x27;), which explains the incomplete snapshot. A Wayback snapshot from 22 Oct 2026 shows the official site still describes Upwork as a freelance marketplace. Per the review rules, an access failure is not grounds for removal.</p>

<p>https://www.upwork.com/ — curl got HTTP 403 with the title &#x27;Challenge - Upwork&#x27; (bot protection); WebFetch also got 403.</p>

<p>https://web.archive.org/web/20261022160239/https://www.upwork.com/ — Snapshot dated 2026-10-22. Title: &#x27;Upwork | Hire Top Freelance Talent with Confidence&#x27;. Meta: &#x27;Upwork is the world&#x27;s largest human and AI-powered freelance marketplace to hire top talent&#x27;.</p>

<p>Caveats: The live page could not be read directly because of bot protection. Current content was confirmed only through an archive snapshot from about three weeks ago.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Only Hiring — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The snapshot was incomplete, but a fresh fetch succeeded (HTTP 200). The site&#x27;s own meta description confirms every claim in the entry: hiring posts from r/forhire and other job subreddits, self-promotion and spam filtered out, and a scam score on every job.</p>

<p>https://onlyhiring.hassandev.me/ — HTTP 200. Title: &#x27;Reddit job board: hiring posts only, scam-checked | Only Hiring&#x27;. Meta: &#x27;Hiring posts only, from r/forhire, r/hiring, r/RemoteJobs and other job subreddits. Self-promotion and spam are filtered out, and every job gets a scam score.&#x27;</p>

<p>Caveats: The site is hosted on a personal subdomain (hassandev.me), so it may be less durable. That is informational only. I verified only the title and meta, not individual listings.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>NannyLane — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Reachable with no redirect, canonical www.nannylane.com. It is a nanny marketplace with &#x27;For Families&#x27; and &#x27;For Nannies&#x27; sides, so it still fits Care Services.</p>

<p>https://www.nannylane.com/ — HTTP 200. Title &#x27;Find a Nanny | Nanny Lane&#x27;. The page has &#x27;For Families&#x27; and &#x27;For Nannies&#x27; sections and offers nanny share, background checks and nanny payroll. It claims more than 1,500,000 families and nannies.</p>

<p>Caveats: Did not check the nanny-side job listings beyond the homepage.</p>

</details>

<h3>Sitter.com — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Reachable, canonical https://sitter.com/. It is a babysitter, nanny and daycare marketplace with job sections, so it fits Care Services.</p>

<p>https://sitter.com/ — HTTP 200. Title &#x27;Find Babysitters, Nannies &amp; Child Care | Sitter.com&#x27;. Navigation includes &#x27;Get a Sitter Job&#x27;, &#x27;Babysitting Jobs&#x27;, &#x27;Nanny Jobs&#x27; and &#x27;Daycare Jobs&#x27;.</p>

</details>

<h3>PetSitter.com — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Reachable, canonical https://petsitter.com/. It is a pet-care marketplace with pet sitting, dog walking and other job sections, so it fits Care Services.</p>

<p>https://petsitter.com/ — HTTP 200. Title &#x27;Find Trusted Professional Pet Sitters | PetSitter.com&#x27;. Navigation includes &#x27;Get a Pet Sitter Job&#x27;, &#x27;Dog Walking Jobs&#x27;, &#x27;Pet Grooming Jobs&#x27; and &#x27;Dog Training Jobs&#x27;.</p>

</details>

<h3>Nightlife Employees — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Reachable and active: 3,643 open roles. The role filters cover bartenders, DJs, promoters and security, which matches the description.</p>

<p>https://nightlifeemployees.com/ — Title &#x27;Nightlife Employees — Where bars, clubs, and venues hire.&#x27; The meta description reads &#x27;Bartenders, DJs, security, hosts, promoters.&#x27;</p>

<p>https://nightlifeemployees.com/jobs — &#x27;3,643 open nightlife employees roles&#x27;. Role filters: Bartender 1,120, Barback, Server/Cocktail, DJ 13, Security/Door 76, Host, Promoter 17, Manager/GM. Listings are US-focused.</p>

<p>Caveats: Part of a network of sister boards on one template (Music &amp; Sound, Culinary, Tattoo, Event Crew, Fitness, Wedding, Wilderness, Creative Gig). Ownership was not verified.; Many listings appear aggregated from large employers (Marriott, Compass Group).</p>

</details>

<h3>WildWork — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Reachable and active: 432 jobs. The navigation and meta confirm ranch hand, fishing/hunting guide, wildland firefighter and deckhand categories across US states, with pay, housing and season dates shown up front.</p>

<p>https://wildwork.io/ — Title &#x27;Outdoor Jobs in Wild Places | WildWork&#x27;. Meta: &#x27;Outdoor jobs with pay, housing and season dates up front: ranch hands, hunting and fishing guides, wildland fire and Alaska fishing. Free to apply.&#x27; Navigation: Deckhand 11, Ranch Hand 84, Hunting Guide 9, Wildland Firefighter, Seasonal Jobs, All 432 Jobs, plus a state list covering the US.</p>

<p>Caveats: The page download timed out partway, but the header, navigation and meta were captured.; The site also sells a $5/mo early-access tier. Applying is stated as free.</p>

</details>

<h3>Rejobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Rejobs is a renewable-energy job board (solar, wind, storage, grid and more), which matches &#x27;Renewable Energy Jobs.&#x27; and fits the section.</p>

<p>https://rejobs.org/en/ — Fetched through WebFetch (plain curl hit a Cloudflare 403). Title: &#x27;Renewable energy jobs - solar, wind, grid, storage, and more&#x27;. Tagline: &#x27;Your next role in renewable energy&#x27;. It lists thousands of jobs across solar, storage, wind, grid, bioenergy, hydropower, geothermal and fusion.</p>

<p>Caveats: Plain HTTP clients get a Cloudflare challenge (403). The content was read through a fetch tool instead.</p>

</details>

<h3>Remote Impact — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Remote Impact lists remote impact roles in climate, global health, nonprofits and other areas, as the entry says.</p>

<p>https://remoteimpact.org/jobs/ — HTTP 200. Meta: &#x27;Browse 3329 remote impact jobs in climate, AI safety, nonprofit, global health, education, and social good.&#x27; Body: &#x27;Remote roles at nonprofits, social enterprises and research groups working on climate, AI safety, global health, education...&#x27;</p>

</details>

<h3>GitHub Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The URL resolves to GitHub&#x27;s official corporate careers job search, a legitimate bare link in Other next to Amazon Jobs. The old standalone GitHub Jobs board (jobs.github.com) shut down years ago, but this entry already points to GitHub&#x27;s own careers site.</p>

<p>https://www.github.careers/careers-home/jobs — HTTP 200 with no redirect. Title: &#x27;GitHub Careers | GitHub Careers Home Job Search - Jobs&#x27;. The page uses GitHub&#x27;s site navigation and policy links.</p>

<p>Caveats: The listings are loaded client-side, so I did not count the current openings.; The name &#x27;GitHub Jobs&#x27; echoes the retired jobs.github.com product. &#x27;GitHub Careers&#x27; would be clearer, but this is optional, not a factual error.</p>

</details>

<h3>Amazon Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is Amazon&#x27;s official careers site, reachable and correct for a bare link in Other.</p>

<p>https://www.amazon.jobs/en — HTTP 200. Title: &#x27;Amazon Careers: Impact the Future, Today&#x27;. Meta: &#x27;Explore corporate jobs and career programs at Amazon...&#x27;</p>

</details>

<h3>Climatebase — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The live site blocks automated clients (Cloudflare 403), but a Wayback capture from 2026-09-19 shows Climatebase as a climate jobs platform that says &#x27;thousands of climate organizations&#x27; hire on it. That supports the description and section fit. The access failure is not evidence of decline.</p>

<p>http://web.archive.org/web/20260919151229/https://www.climatebase.org/ — Title: &#x27;Climatebase | Climate Jobs, Careers, Fellowship &amp; Organizations&#x27;. Text: &#x27;Discover your next job in climate&#x27;, &#x27;Join thousands of climate organizations hiring on Climatebase&#x27;.</p>

<p>https://climatebase.org/ — Both curl and WebFetch got a 403 Cloudflare challenge (&#x27;Just a moment...&#x27;).</p>

<p>Caveats: I could not read the live site directly. The evidence comes from a Wayback capture about seven weeks old.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Black Tech Pipeline — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Black Tech Pipeline is an established platform that connects Black technologists with hiring companies through a job board, talent directory and newsletter, so the description and Impact fit are supported. The live site currently returns a WordPress &#x27;Database Error&#x27; (HTTP 500). That looks like an outage, not discontinuation: the organization&#x27;s newsletter was publishing as recently as 2026-11-05.</p>

<p>https://blacktechpipeline.com/ — HTTP 500, page title &#x27;Database Error&#x27;. /app/ also returns 500.</p>

<p>http://web.archive.org/web/20260109004853/https://blacktechpipeline.com/ — January 2026 capture: &#x27;Bringing Black Tech Talent to Your Hiring Pipeline&#x27;. Navigation includes Job Board, Companies and Events.</p>

<p>https://blacktechpipeline.substack.com/feed — Newsletter posts dated 2026-11-05, 2026-10-21 and 2026-10-13. The organization is active.</p>

<p>Caveats: The site is down with a server error as of 2026-11-10. Re-check later. An access failure alone does not justify removal.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Job Board Search — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>JobBoardSearch is a live directory of niche job boards. That fits Other and is relevant to a job-boards list.</p>

<p>https://jobboardsearch.com/ — HTTP 200. Title: &#x27;Top job boards (2026): 920 best niche job boards by industry | JobBoardSearch&#x27;. It is &#x27;A directory of the best niche job boards in the world&#x27;.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Monster — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Monster&#x27;s live site blocks automated clients (403), but a Wayback capture from 2026-11-08 shows the job search site working normally.</p>

<p>http://web.archive.org/web/20261108030510/https://www.monster.com/ — Title: &#x27;Monster Jobs Search - Find Jobs Near Me | Monster.com&#x27;. Meta: &#x27;Search millions of job openings...&#x27;</p>

<p>https://www.monster.com/ — Both curl and WebFetch got HTTP 403, which is bot blocking.</p>

<p>Caveats: I could not read the live site directly. The evidence comes from a capture two days old.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>whoishiring.io — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>whoishiring.io returns HTTP 200 at the listed URL and is a client-side React/MapLibre app. Its current JS bundle describes the site as &quot;The map with the collection of jobs for Software Engineers... Aggregator of job post from Hacker News, Stack Overflow, Github, and many more&quot; and includes job search/remote/visa filter logic. Identity and category fit are supported for a bare-link entry.</p>

<p>https://whoishiring.io/ — HTTP 200, no redirect. The HTML is an SPA shell that loads /assets/index-BJVhYVJZ.js.</p>

<p>https://whoishiring.io/assets/index-BJVhYVJZ.js — Bundle metadata: name whoishiring.io; description &#x27;The map with the collection of jobs for Software Engineers... Aggregator of job post from Hacker News, Stack Overflow, Github...&#x27;. Search code has remote/visa/location filters against an Elasticsearch item index.</p>

<p>Caveats: Listings are loaded client-side from a credentialed search backend. I did not render the app or query that backend, so I could not confirm how recent the listings are.</p>

</details>

<h3>Dice — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Dice is live at the listed URL and presents itself as a tech job search site. Identity and category fit are confirmed.</p>

<p>https://www.dice.com/ — HTTP 200, no redirect. Title: &#x27;Find Tech Jobs | Advance Your Tech Career | Job Search on Dice.com&#x27;.</p>

</details>

<h3>ZipRecruiter — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>ZipRecruiter is live at the listed URL as a job search site.</p>

<p>https://www.ziprecruiter.com/ — HTTP 200, no redirect. Title: &#x27;Job Search: Millions of US Jobs (HIRING NOW) Near You - ZipRecruiter&#x27;.</p>

</details>

<h3>Aquent — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Aquent&#x27;s find-work page is live and lists jobs. The only redirect is trailing-slash normalization.</p>

<p>https://aquent.com/find-work — https://aquent.com/find-work/ resolves here with HTTP 200. Title: &#x27;Explore Jobs | Aquent&#x27;.</p>

<p>Caveats: Aquent is a staffing agency, not an open job board. That still fits the catch-all &#x27;Other&#x27; section.</p>

</details>

<h3>The Muse — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The Muse is live at the listed URL as a job search and career advice site.</p>

<p>https://www.themuse.com/ — HTTP 200. Title: &#x27;The Muse - Career advice and better job search&#x27;.</p>

</details>

<h3>Jobs2Careers — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Jobs2Careers is live and job search works. A sample search returned current listings.</p>

<p>https://www.jobs2careers.com/ — HTTP 200. Title: &#x27;Jobs and Employment Near Me Now Hiring November 2026 | Jobs2Careers&#x27;. The page has a job search form.</p>

<p>https://www.jobs2careers.com/search/results?q=nurse&amp;l=Chicago%2C+IL — Returned &#x27;1042 nurse jobs in Chicago, IL&#x27;, including current postings.</p>

<p>Caveats: The homepage meta description says &#x27;Discover over 0 top-tier jobs&#x27;, which looks like a template bug. Search results show the site is working.</p>

</details>

<h3>jobbit subreddit — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The link is a Reddit search across r/forhire, r/jobbit and r/jobopenings for [Hiring] posts. It fits the section as a job-listing source. The packet snapshot fetched it successfully, and third-party sources describe r/jobbit as a job board subreddit using Hiring/For hire tags. The label names only jobbit while the URL covers three subreddits. That is a naming quirk of a bare link, not a confirmed factual error.</p>

<p>https://www.reddit.com/r/forhire/search/?q=test — Reddit search on r/forhire responds with HTTP 200. The listed URL resolves to the same /search/ path pattern.</p>

<p>https://careerarc.com/blog/4-it-talent-communities-on-reddit — Third-party article describes r/jobbit as a subreddit for posting IT jobs and availability, using [Hiring]/[For hire] tags and flair.</p>

<p>Caveats: Reddit redirected unauthenticated old.reddit and JSON requests to login, so I could not confirm current subscriber counts or posting activity in r/jobbit.; A maintainer may want to relabel the link to reflect that it searches three subreddits. This is optional.</p>

</details>

<h3>Jora — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Jora is an active job search engine. www.jora.com redirects (301) to the regional au.jora.com, which is a normal geo/regional redirect. The live site returned a Cloudflare challenge (403), so I used a recent archive capture to confirm it serves job search.</p>

<p>https://www.jora.com/ — HTTP 301 to https://au.jora.com/ (Cloudflare). The live fetch got a 403 &#x27;Just a moment...&#x27; bot challenge.</p>

<p>http://web.archive.org/web/20261030135013/https://au.jora.com/ — Capture from 2026-10-30. Title: &#x27;Job Search Australia | Jora&#x27;. Description: &#x27;More than 317,700 jobs, all on one job search site.&#x27;</p>

<p>Caveats: The live site blocked automated access. Current state was confirmed from an archive capture 11 days old.; The root redirect may vary by visitor region. Keeping www.jora.com as the neutral entry point seems appropriate.</p>

</details>

<h3>HNHIRING — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>HNHIRING is live and current. It indexes jobs from Hacker News &#x27;Who is Hiring?&#x27; posts and was updated in November 2026.</p>

<p>https://hnhiring.com/ — HTTP 200. Page text: &#x27;HNHIRING is an index of jobs from Hacker News&#x27; Who is Hiring? posts... The latest post is: November 2026, Updated on November 10&#x27;.</p>

</details>

<h3>Relocate.me — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Relocate.me is live. Its homepage now leads with relocation and expat guides, but it still runs a tech job board for relocation roles, so category fit holds.</p>

<p>https://relocate.me/ — HTTP 200. Title: &#x27;Relocate.me - Your First Stop for Moving and Living Abroad&#x27;. Text: &#x27;Your guide to tech jobs + living abroad&#x27;, &#x27;Post your jobs on our job board&#x27;.</p>

<p>https://relocate.me/international-jobs — HTTP 200. Title: &#x27;Find International Jobs: Explore Global Career Opportunities | Relocate.me&#x27;. Lists current relocation jobs, e.g. Picnic and Catawiki in Amsterdam and PayPay in Tokyo.</p>

<p>Caveats: The site&#x27;s emphasis has broadened toward relocation content. A maintainer could optionally link /international-jobs directly. This is not a required correction.</p>

</details>

<h3>SimplyHired — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The live site returned a Cloudflare bot challenge (403), which is an access block, not evidence the site is gone. An archive capture from 31 Oct 2026 shows SimplyHired operating as a job search engine with an employer job-posting tool.</p>

<p>https://www.simplyhired.com/ — Live: HTTP 403 Cloudflare &#x27;Just a moment...&#x27; challenge, no redirect.</p>

<p>http://web.archive.org/web/20261031032225/https://www.simplyhired.com/ — Capture from 2026-10-31. Title: &#x27;Job Search Engine | SimplyHired&#x27;. Description: &#x27;Search for job opportunities across the United States on SimplyHired...&#x27; Has Post Jobs and country selectors.</p>

<p>Caveats: Verified through an archive capture because the live site blocked automated access.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>CareerBuilder — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>CareerBuilder + Monster went through Chapter 11 in 2025. The bankruptcy court approved selling the CareerBuilder and Monster job boards to BOLD, which kept the brands. An archive capture from 2 Nov 2026 shows careerbuilder.com still running as a job search site. The live 403 is a bot block, not a shutdown.</p>

<p>https://www.careerbuilder.com/ — Live: HTTP 403 from CloudFront with &#x27;Please enable JS and disable any ad blocker&#x27;. This is bot protection.</p>

<p>http://web.archive.org/web/20261102075124/https://www.careerbuilder.com/ — Capture from 2026-11-02. Title: &#x27;CareerBuilder® - Search Jobs Hiring Now&#x27;. Description: &#x27;Browse millions of recent job listings, upload your resume, get job alerts.&#x27;</p>

<p>https://www.staffingindustry.com/news/global-daily-news/court-approves-sales-of-careerbuilder-monster-businesses — Reports court approval of selling the CareerBuilder + Monster businesses. Search summaries state BOLD acquired the job boards and brand rights for about $28M (July 2025).</p>

<p>Caveats: Ownership change is from trade press, not a company page I read directly. It does not affect the URL or category fit.; The live site blocked automated access, so current state comes from an archive capture.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Techstars — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The Techstars job board is live at the listed URL. The packet&#x27;s timeout was transient.</p>

<p>https://jobs.techstars.com/jobs — HTTP 200, about 435 KB, no redirect. Title: &#x27;Jobs | Techstars Job Board&#x27;.</p>

<p>Caveats: The page&#x27;s meta description is generic Techstars marketing copy. The title confirms it is the job board.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Adzuna — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Adzuna is an active job search aggregator and recently acquired Joblift (July 2026). The live 403 is CloudFront bot protection. An archive capture from 27 Aug 2026 shows the US job search site working.</p>

<p>https://www.adzuna.com/ — Live: HTTP 403 from CloudFront to automated clients, no redirect.</p>

<p>http://web.archive.org/web/20260827190935/https://www.adzuna.com/ — Capture from 2026-08-27. Title: &#x27;Job Search - Find Every Job, Everywhere with Adzuna&#x27;. Description: &#x27;We search thousands of job sites so that you don&#x27;t have to.&#x27;</p>

<p>https://www.adzuna.co.uk/blog/adzuna-acquires-joblift/ — Official Adzuna blog post from July 2026 about acquiring Joblift. The company is actively operating and expanding.</p>

<p>Caveats: The live site blocked automated access, so current state comes from an archive capture.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>PeopleFirstJobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>peoplefirstjobs.com loads (HTTP 200) with the title &#x27;People-First Jobs — Remote, flexible jobs at companies with a people-first culture&#x27;. It is a live job board that fits the section.</p>

<p>https://peoplefirstjobs.com/ — HTTP 200, no redirect. Title: &#x27;People-First Jobs — Remote, flexible jobs at companies with a people-first culture&#x27;.</p>

<p>Caveats: Only the homepage title and status were checked.</p>

</details>

<h3>Smashing Magazine — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>smashingmagazine.com/jobs loads (HTTP 200) as Smashing Magazine&#x27;s job board (&#x27;Job Board that helps designers and developers find great jobs&#x27;). It has filters and Find/Post a job calls to action. The listings themselves load client-side.</p>

<p>https://www.smashingmagazine.com/jobs/ — HTTP 200, title &#x27;Jobs — Smashing Magazine&#x27;. Text: &#x27;Job Board that helps designers and developers find great jobs, and connect with great companies. Find a job ↓ Post a job →&#x27;. It has Location/Hours/Specialism filters. The server HTML has an empty jobs__list, so listings render client-side.</p>

<p>Caveats: I did not render JavaScript, so the number of current listings is unverified.</p>

</details>

<h3>Totaljobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>totaljobs.com is live (HTTP 200, &#x27;Jobs are our job | Totaljobs&#x27;). The homepage redirects to an onboarding page, which is a session/UX redirect rather than a canonical URL change.</p>

<p>https://www.totaljobs.com/ — HTTP 200 after a redirect to /onboarding?onboardingSource=hp-redirect. Title &#x27;Jobs are our job | Totaljobs&#x27;.</p>

</details>

<h3>XING — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>xing.com loads (HTTP 200). Its title is German for &#x27;Find the job that suits you. Or let yourself be found!&#x27;, so XING is still positioned as a job platform.</p>

<p>https://www.xing.com/ — HTTP 200, no redirect. Title &#x27;XING - Finde den Job, der zu Dir passt. Oder lass Dich finden!&#x27;.</p>

<p>Caveats: The site is German-language. Only the title and status were checked.</p>

</details>

<h3>Jobs in Network — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The www URL redirects to the apex domain jobsinnetwork.com (HTTP 200), titled &#x27;JobsinNetwork | English &amp; International Jobs: Europe, USA, Asia&#x27;. That is a trivial host redirect, and the job-board fit is unchanged.</p>

<p>https://jobsinnetwork.com/ — https://www.jobsinnetwork.com/ redirects here, HTTP 200. Title &#x27;JobsinNetwork | English &amp; International Jobs: Europe, USA, Asia&#x27;.</p>

<p>Caveats: A maintainer could normalise the URL to the apex domain, but the www link works.</p>

</details>

<h3>Robert Half — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>roberthalf.com/jobs redirects to the locale path /us/en/jobs (&#x27;Search Jobs&#x27;, HTTP 200). This looks like a locale/geo redirect, so the generic URL is still a reasonable entry point.</p>

<p>https://www.roberthalf.com/us/en/jobs — https://www.roberthalf.com/jobs redirects here, HTTP 200, title &#x27;Search Jobs&#x27;.</p>

<p>Caveats: The redirect target may vary by visitor region. Not verified.</p>

</details>

<h3>HigherEdJobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>HigherEdJobs is an active higher-education job board. A direct fetch returned HTTP 200, but with an Incapsula block body. A search index snapshot shows a current homepage: &#x27;now listing 75,499 jobs. Updated daily. Free to job seekers.&#x27;, with Oct 2026 articles.</p>

<p>https://www.higheredjobs.com/ — HTTP 200, but the body is &#x27;Request unsuccessful. Incapsula incident ID…&#x27; (bot protection).</p>

<p>https://www.higheredjobs.com/?nis=5&amp;ch=1 — Search index snapshot of &#x27;HigherEdJobs - Jobs in Higher Education&#x27;: faculty/administrative jobs at 2,161 institutions, &#x27;Updated daily. Free to job seekers.&#x27;, and an article dated Oct 14, 2026.</p>

<p>Caveats: The live page was read only through a search index because of bot protection.</p>

</details>

<h3>Mediabistro — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>mediabistro.com loads (HTTP 200) titled &#x27;Media &amp; Creative Jobs | Social, Design &amp; Copywriting | Mediabistro&#x27;. It is a live media and creative job board.</p>

<p>https://www.mediabistro.com/ — HTTP 200, no redirect. Title &#x27;Media &amp; Creative Jobs | Social, Design &amp; Copywriting | Mediabistro&#x27;.</p>

</details>

<h3>Workatastartup — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>curl received HTTP 406, but WebFetch read the page. Its title is &#x27;Software Engineer jobs at Y Combinator startups | Y Combinator&#x27;s Work at a Startup&#x27;, so it is YC&#x27;s live startup job board.</p>

<p>https://www.workatastartup.com/jobs — curl returned 406. WebFetch read the title &#x27;Software Engineer jobs at Y Combinator startups | Y Combinator&#x27;s Work at a Startup&#x27;.</p>

<p>Caveats: The official name is styled &#x27;Work at a Startup&#x27;. The entry&#x27;s &#x27;Workatastartup&#x27; styling is cosmetic and was not treated as an error.</p>

</details>

<h3>VirtualVocations — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>virtualvocations.com loads (HTTP 200) titled &#x27;Best Remote and Work from Home Jobs - Virtual Vocations&#x27;. It is a live remote-jobs board.</p>

<p>https://www.virtualvocations.com/ — HTTP 200, no redirect. Title &#x27;Best Remote and Work from Home Jobs - Virtual Vocations&#x27;.</p>

</details>

<h3>snagajob — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>A direct fetch got a Cloudflare 403 challenge. That is an access failure, not evidence the site is dead. Search results show current snagajob.com search pages and 2026 third-party coverage describing Snagajob as a US hourly-jobs board, so it is still a relevant job board.</p>

<p>https://www.snagajob.com/ — HTTP 403 Cloudflare &#x27;Just a moment...&#x27; challenge.</p>

<p>https://www.snagajob.com/find-jobs/c-all+jobs — Search index lists current snagajob.com job search pages (&#x27;All Jobs Jobs - Now Hiring&#x27;).</p>

<p>https://www.techradar.com/pro/snagajob-review — 2026 review (per search summary) describes Snagajob as a marketplace for hourly and gig jobs.</p>

<p>Caveats: The live site was not read directly because of bot protection.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>BusinessSchoolCareers — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>A direct fetch got HTTP 429 from a Vercel checkpoint. A search index snapshot of businessschoolcareers.com describes it as &#x27;The Job Board for Faculty, Research &amp; Administrative Jobs at Business Schools&#x27; covering &#x27;faculty, research, leadership and administrative roles at business schools worldwide&#x27;. That matches the entry&#x27;s description, and the snapshot shows current listings (Babson, INSEAD, Melbourne Business School). I did not confirm the &#x27;Free for job seekers&#x27; claim.</p>

<p>https://businessschoolcareers.com/ — Live fetch returned HTTP 429 (Vercel Security Checkpoint). Search index snapshot: &#x27;The Job Board for Faculty, Research &amp; Administrative Jobs at Business Schools… explore faculty, research, leadership and administrative roles at business schools worldwide&#x27;. Listings include Babson College and INSEAD Singapore.</p>

<p>Caveats: The &#x27;Free for job seekers&#x27; claim was not seen in the indexed text. I found no contrary evidence.; The live page was read only through a search index.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Joblist — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Direct access got a Cloudflare 403 challenge. Search results show joblist.com live, with a homepage titled &#x27;Find Jobs Anywhere with the Best Job Search Site&#x27; and an FAQ. Third-party sources describe it as an active job-search aggregator in 2026, reportedly acquired by Bold in May 2026. The joblist.com domain still serves the service, so it is still a relevant job board.</p>

<p>https://www.joblist.com/ — HTTP 403 Cloudflare challenge on curl. Search index title: &#x27;Find Jobs Anywhere with the Best Job Search Site&#x27;.</p>

<p>https://www.joblist.com/faq — Search index (summary): Joblist aggregates listings from employers, career sites and partners, and redirects to partners to apply.</p>

<p>https://www.crunchbase.com/organization/joblist — Third-party, via search summary: founded by Wilbur Labs in 2019, acquired by Bold in May 2026.</p>

<p>Caveats: The acquisition claim comes from third-party sources and was not verified officially. It does not affect the bare link.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>f6s — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>f6s.com/jobs returns an F6S &#x27;Checking your browser&#x27; bot page, which is an access failure only. Search results and 2026 third-party reviews describe F6S as an active startup platform whose job board lives at f6s.com/jobs. It still fits the section.</p>

<p>https://www.f6s.com/jobs — HTTP 200 &#x27;Checking your browser&#x27; bot page from F6S Network Limited. Content unreadable.</p>

<p>https://startup.jobs/job-boards/f6s — Search result (third-party): describes F6S as a job board for startup jobs worldwide at https://www.f6s.com/jobs.</p>

<p>https://noonlaunch.com/blog/f6s-review — 2026 third-party review: F6S is active as a founder platform covering funding, accelerators and jobs.</p>

<p>Caveats: The live job listings were not read because of bot protection.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Ladders — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>A direct fetch got a Cloudflare 403 challenge. Search results show theladders.com still serving current $100K+ job pages (e.g. /jobs/software-engineer-jobs). Ladders is a live job board fitting the section.</p>

<p>https://www.theladders.com/jobs/search-jobs — HTTP 403 Cloudflare &#x27;Just a moment...&#x27; challenge.</p>

<p>https://www.theladders.com/jobs/software-engineer-jobs — Search index: &#x27;Software Engineer Jobs Paying $100,000+&#x27;, with current salary-listed roles.</p>

<p>Caveats: I did not confirm that the exact /jobs/search-jobs path still renders search results rather than redirecting.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Hitmarker — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. hitmarker.net/jobs is live and is a job board for gaming, esports and content roles. Identity and fit are confirmed.</p>

<p>https://hitmarker.net/jobs — HTTP 200. Title: &#x27;Gaming, Esports &amp; Content Jobs | Hitmarker&#x27;. Meta: &#x27;Browse thousands of verified roles at the studios, esports orgs, agencies and creator teams hiring right now.&#x27;</p>

</details>

<h3>PRSA Job Center — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. jobs.prsa.org is live and is the Public Relations Society of America&#x27;s job board for PR and communications roles.</p>

<p>https://jobs.prsa.org/ — HTTP 200. Title: &#x27;Public Relations &amp; Communications Jobs | PRSA Job Center&#x27;. Meta mentions &#x27;the PRSA Job Center from the Public Relations Society of America&#x27;.</p>

</details>

<h3>TechFetch — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. TechFetch is a live US IT/tech job board. Identity and fit are confirmed.</p>

<p>https://www.techfetch.com/ — HTTP 200. Meta: &#x27;Techfetch is a leading tech job board serving over 2.5 million users in the US. A complete IT job portal for USA recruiters and candidates.&#x27;</p>

</details>

<h3>DiversityJobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. DiversityJobs is a live job board focused on diversity. Identity and fit are confirmed.</p>

<p>https://www.diversityjobs.com/ — HTTP 200. Title: &#x27;Diversity Job Board - Uniting DEI-Focused Employers With Diverse Candidates | DiversityJobs&#x27;.</p>

</details>

<h3>ClearanceJobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. ClearanceJobs is a live job board for defense and intelligence jobs that require a security clearance.</p>

<p>https://www.clearancejobs.com/ — HTTP 200. Title: &#x27;Security Clearance Jobs - ClearanceJobs&#x27;. Meta: &#x27;Find defense and intelligence jobs requiring federal government security clearance...&#x27;</p>

</details>

<h3>Wait, What Do You Do? — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. waitwhatdoyoudo.com is live and works as a job listing and search site. The homepage shows &#x27;Recently added&#x27; jobs and a &#x27;View all jobs&#x27; link. It also adds job-intelligence features such as first-seen date, repost detection and open status. It still fits a job-board list.</p>

<p>https://waitwhatdoyoudo.com/ — HTTP 200. Title: &#x27;Know what a job really is | Wait, What Do You Do?&#x27;. Meta: &#x27;Know what a job really is before you apply: when it first appeared, whether it was reposted, if it is still open...&#x27; The page lists current jobs (e.g. AMD, American Express) with &#x27;Actively hiring, first seen by us 37 minutes ago&#x27;.</p>

<p>Caveats: The site&#x27;s framing is job transparency and intelligence, not only a board. It still lists and links to jobs.</p>

</details>

<h3>Lensa — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. Lensa is a live job search board. Identity and fit are confirmed.</p>

<p>https://lensa.com/ — HTTP 200. Title: &#x27;Search jobs online - Lensa&#x27;. Meta: &#x27;Search millions of jobs online and find companies who are hiring now on our new job board.&#x27;</p>

</details>

<h3>arbeitnow — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. arbeitnow is a live job board for jobs in Germany, including English-speaking, visa-sponsorship and remote roles.</p>

<p>https://www.arbeitnow.com — HTTP 200 (resolves to https://www.arbeitnow.com/). Title: &#x27;Jobs in Germany: Remote, Visa Sponsorship &amp; English Speaking - November 2026&#x27;. Meta: &#x27;Online job search website to find your next job in Germany...&#x27;</p>

</details>

<h3>4 day week — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. 4dayweek.io is a live job board for 4-day-week and reduced-schedule roles.</p>

<p>https://4dayweek.io/ — HTTP 200. Title: &#x27;4-Day Week Jobs (32hrs @ 100% Salary) | 4dayweek.io&#x27;. Meta: &#x27;Browse 37800+ jobs at 2300+ companies offering 4-day work weeks...&#x27;</p>

</details>

<h3>eFinancialCareers — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. The earlier snapshot failed, but a browser-like request returned the live eFinancialCareers finance and tech job site. Identity and fit are confirmed.</p>

<p>https://www.efinancialcareers.com/ — HTTP 200. Title: &#x27;Finance Jobs Site | Finance &amp; Tech Job Site | eFinancialCareers US&#x27;. Meta: &#x27;the no. 1 job site for finance and tech professionals&#x27;.</p>

<p>Caveats: Served the US locale to this client. Other visitors may get geo-localized content.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Tech Jobs for Good — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. The earlier snapshot failed with RemoteDisconnected, but a retry returned the live Tech Jobs for Good site, a social-impact tech job board.</p>

<p>https://techjobsforgood.com/ — HTTP 200. Title: &#x27;Tech Jobs for Good | Social Impact Tech Job Board&#x27;.</p>

<p>Caveats: The earlier fetch failure appears to have been transient.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Getwork — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. getwork.com returns a CloudFront 403 to automated clients, which is access blocking, not evidence of shutdown. A March 2026 archived copy shows Getwork as an active job search engine that sources verified jobs directly from employer career sites. Its footer reads &#x27;© 2026 Getwork, part of the Adzuna family&#x27;. Several 2026 &#x27;best job sites&#x27; roundups still list it. Identity and fit are supported.</p>

<p>https://getwork.com/ — HTTP 403 CloudFront &#x27;Request blocked&#x27; to curl and WebFetch. www.getwork.com behaved the same.</p>

<p>https://web.archive.org/web/20260321222019id_/https://www.getwork.com/ — Title &#x27;Getwork | Getwork US&#x27;. Text: &#x27;Millions of jobs for you. Verified by us... listings that connect you directly to company career sites&#x27;. Footer: &#x27;© 2026 Getwork, part of the Adzuna family&#x27;.</p>

<p>https://www.techradar.com/best/us-job-sites — A search result showed Getwork listed among the best US job sites of 2026. I relied on the search summary and did not read the page.</p>

<p>Caveats: I could not see the live site after March 2026 because of bot blocking.; Getwork is now part of Adzuna. The brand and URL are unchanged, so no update is implied.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Jobgether — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. A browser-like request returned the live Jobgether remote-jobs platform. Identity and fit are confirmed.</p>

<p>https://jobgether.com — HTTP 200 (resolves to https://jobgether.com/). Title: &#x27;The largest remote job platform with over 200,000 remote jobs&#x27;. Meta: &#x27;Get matched with the best flexible and remote jobs in the world with Jobgether.&#x27;</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Himalayas — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. himalayas.app/jobs returns a Cloudflare challenge (403) to automated clients. Other public Himalayas sources respond: robots.txt is served, and the public jobs API returns a live job feed with changelog notes dated 2026. The remote-job board is active and fits the section.</p>

<p>https://himalayas.app/jobs — HTTP 403 &#x27;Just a moment...&#x27; (Cloudflare challenge) to curl.</p>

<p>https://himalayas.app/jobs/api?limit=1 — HTTP 200 JSON job feed. Comments note cursor pagination added &#x27;21/08/2026&#x27; and a companySlug field added &#x27;13/03/2026&#x27;.</p>

<p>https://himalayas.app/robots.txt — HTTP 200. Allows crawling of /jobs and /companies paths.</p>

<p>Caveats: I did not read the rendered /jobs page because of the bot challenge.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>gamesjobsdirect — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The site is reachable and is the Games Jobs Direct video games industry job board, so it fits the Other section.</p>

<p>https://www.gamesjobsdirect.com/ — A browser-like user agent got HTTP 403. A plain curl request got HTTP 200 with the title &#x27;Games Jobs Direct | Video Games Industry Jobs | UK, USA, Canada, Australia&#x27; and a meta description calling it a careers portal.</p>

<p>Caveats: The site blocks some user agents with a 403. That is bot filtering, not a dead site.</p>

</details>

<h3>AquariumsHiring — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>AquariumsHiring is live and still a job board for the aquarium industry, which matches the &#x27;Nature.&#x27; niche label.</p>

<p>https://aquariumshiring.com/ — HTTP 200 (adds a trailing slash). The title is &#x27;Aquariums Hiring&#x27; and the meta description reads &#x27;Job board for professionals in the aquarium industry and related fields.&#x27;</p>

<p>Caveats: I did not check how many listings are open.</p>

</details>

<h3>ZoosHiring — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>ZoosHiring is live and still a job board for the zoo industry, which matches the &#x27;Nature.&#x27; niche label.</p>

<p>https://zooshiring.com/ — HTTP 200. The title is &#x27;Zoos Hiring&#x27; and the meta description reads &#x27;Job board for professionals in the zoo industry and related fields.&#x27;</p>

<p>Caveats: I did not check how many listings are open.</p>

</details>

<h3>Hidden Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The Hidden Jobs site is reachable and is a job search site with remote, hybrid and onsite listings, so it fits.</p>

<p>https://hidden-jobs.com/ — HTTP 200. The title is &#x27;Hidden Jobs | Remote, Hybrid &amp; Onsite Job Search&#x27;. The meta description says users can search current jobs by role, company and region, and that each listing links to its source.</p>

</details>

<h3>Jobs by Workable — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Jobs by Workable is reachable and is Workable&#x27;s public job search across postings hosted on its platform.</p>

<p>https://jobs.workable.com/ — HTTP 200. The title is &#x27;Jobs by Workable&#x27;. The meta description says users can search thousands of open listings hosted on Workable&#x27;s recruitment software.</p>

</details>

<h3>Engineering Manager Jobs (EngMgrJobs) — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. EngMgrJobs is reachable and still presents itself as a job board for engineering management roles, so the identity and fit hold. Listing activity is very low.</p>

<p>https://engmgrjobs.com/ — HTTP 200. The page says &#x27;Discover companies looking to hire for all software engineering management jobs&#x27; (Team Lead, VPE, Director, CTO) and &#x27;Jobs are checked regularly&#x27;. It shows &#x27;All jobs (1)&#x27;: one VP Engineering posting from Identity Digital, dated &#x27;10 months ago&#x27;.</p>

<p>Caveats: Only one listing about 10 months old was visible, so the board may be dormant. The contribution rules set no activity threshold, and there is no official discontinuation notice. The maintainer may want to recheck later.</p>

</details>

<h3>Influencer Marketing Society — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Influencer Marketing Society is reachable and runs a job board for influencer marketing and creator-economy roles.</p>

<p>https://www.influencermarketingsociety.com/ — HTTP 200. The title is &#x27;Influencer Marketing Jobs, Careers, &amp; Gigs | Influencer Marketing Society&#x27;. The meta description says IMS is &#x27;the official job board and professional community for all involved in the creator economy.&#x27;</p>

</details>

<h3>Christian Tech Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Christian Tech Jobs is reachable and is a job board for roles at Christian companies, churches and nonprofits.</p>

<p>https://www.christiantechjobs.io/ — HTTP 200. The title is &#x27;Christian Job Board for Tech, Design &amp; Marketing Jobs | Christian Tech Jobs&#x27;. The meta description says it covers tech, design, marketing, communications and sales roles at Christian companies, churches and nonprofits.</p>

</details>

<h3>Jobright — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Jobright is reachable and is an AI job search copilot that surfaces matching job openings, so it still fits as a job search resource.</p>

<p>https://jobright.ai/ — HTTP 200. The title is &#x27;Jobright: Your AI Job Search Copilot&#x27;. The meta description talks about finding tailored job opportunities and filtered matches, plus resume tailoring and application autofill.</p>

<p>Caveats: Jobright is an AI job-matching service, not a traditional job board. Whether that fits the list is a maintainer judgement.</p>

</details>

<h3>JobFound — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. www.jobfound.org redirects to jobfound.org, a remote job board. Identity and fit are confirmed.</p>

<p>https://jobfound.org/ — https://www.jobfound.org/ redirects to https://jobfound.org/ (HTTP 200). The title is &#x27;Jobfound — Remote Jobs in US, UK, India &amp; Worldwide&#x27;. The meta description mentions verified work-from-home jobs in tech, marketing and design.</p>

<p>Caveats: The www to apex redirect is minor. Updating the link is optional.</p>

</details>

<h3>Woody — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Woody (WoodyJobs) is reachable and is a job board for product design, UX and product roles at creative-tools companies.</p>

<p>https://www.woodyjobs.com/ — HTTP 200. The title is &#x27;Product Design, UX &amp; Product Jobs at Creative Companies | WoodyJobs.com&#x27;. The meta description mentions companies building 3D apps, design platforms, game engines, video and AI tools.</p>

<p>Caveats: The site brands itself as &#x27;WoodyJobs&#x27;. The catalog name &#x27;Woody&#x27; is a shorter form, not an error.</p>

</details>

<h3>jobsdb — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Jobsdb (Jobsdb by SEEK) is still an operating job platform for Hong Kong and Thailand. http://jobsdb.com permanently redirects (308) to the listed https://www.jobsdb.com/. Direct fetches of the page hit a Cloudflare challenge, so the root page itself could not be read.</p>

<p>https://www.jobsdb.com/ — HTTPS GET returns 403 with a Cloudflare &#x27;Just a moment...&#x27; challenge. http://jobsdb.com returns 308 to https://www.jobsdb.com/ from a Cloudflare server. /robots.txt serves the site&#x27;s React HTML shell, so the host is serving its app.</p>

<p>https://hk.jobsdb.com/JobsDB-by-SEEK-jobs — Search results show the active regional Jobsdb by SEEK sites hk.jobsdb.com and th.jobsdb.com, with listings dated 2026.</p>

<p>https://en.wikipedia.org/wiki/Seek_Limited — Search results describe Jobsdb as part of SEEK Asia, owned by SEEK.</p>

<p>Caveats: I could not read the root www.jobsdb.com page past the Cloudflare challenge. I assume it acts as a country selector or landing page for hk/th.jobsdb.com, but I did not confirm that. A regional URL could be an optional alternative.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>scholarshipdb — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. ScholarshipDB is an active aggregator of PhD scholarships, research jobs and university jobs. Its robots.txt is served, but pages are behind a Cloudflare challenge. Search-indexed pages from the site show current listings.</p>

<p>https://scholarshipdb.net/ — GET returns 403 with a Cloudflare &#x27;Just a moment...&#x27; challenge. /robots.txt returns 200 with Cloudflare content-signal text.</p>

<p>https://scholarshipdb.net/PhD-scholarships — The search-indexed page shows about 20,856 PhD positions, split into Uni Job, Research Job and Scholarship categories. Listings include 2026–2027 positions.</p>

<p>Caveats: I could not read the pages directly. Evidence on listing content comes from search-engine snippets of the official domain.; The site covers academic and research positions as well as scholarships. That fits a job-boards list, but it is a niche fit.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>HiringCafe — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. HiringCafe is an active free job search engine that collects jobs from employers&#x27; career pages. Its robots.txt is readable and allows the job pages, but the homepage is behind a Cloudflare challenge.</p>

<p>https://hiringcafe.com/robots.txt — HTTP 200. It allows /, /about, /jobs, /job/, /recently-posted-jobs, /talent-network and similar paths, which matches a live job search product.</p>

<p>https://hiringcafe.com/about — Search result for the official About page: &#x27;About HiringCafe - The Job Search Engine Built for People&#x27;.</p>

<p>https://www.citybiz.co/article/910203/hiringcafe-raises-6-8m-for-ai-job-search-engine-that-find-the-hidden-80-of-open-roles/ — A third-party report on HiringCafe&#x27;s $6.8M pre-seed round. It describes the product as a job search engine.</p>

<p>Caveats: The homepage and about page returned a Cloudflare 403 to direct fetches. Product details come from search snippets and third-party reviews.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Econ-Jobs — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Econ-Jobs.com is a job board for economists. The host currently returns a Vercel security checkpoint (429) to automated clients. Search-indexed official pages show it is active with current listings.</p>

<p>https://econ-jobs.com/ — GET returns HTTP 429 with a &#x27;Vercel Security Checkpoint&#x27; page. That is bot protection and does not show the site is dead.</p>

<p>https://econ-jobs.com/about-us/ — Search snippet of the official About page: a global job board exclusively for economists, launched in 2008 and now run by Rolework (Paris).</p>

<p>https://x.com/EconJobs_com — The official X account posts new economics job openings.</p>

<p>Caveats: I could not read the site directly because of the Vercel checkpoint. Current content comes from search-engine snippets.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>JobMesh — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. https://jobmesh.io/ returns HTTP 200 with no redirect. The page is titled &quot;JobMESH - Find all jobs now&quot; and offers a general job search (full-time, part-time, no-experience jobs). Its identity and its fit as a job board in Other are confirmed.</p>

<p>https://jobmesh.io/ — HTTP 200. Title: &#x27;JobMESH - Find all jobs now&#x27;. Meta description: &#x27;JobMESH is a large job exchange with a wide range of vacancies.&#x27; The page has a job search and links for Full time jobs, Part time jobs and No Experience jobs.</p>

<p>Caveats: The landing page is thin. I did not check how many listings it has or how good they are.</p>

</details>

<h3>Built In — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. https://builtin.com/ returns HTTP 200 and is canonical. The site is titled &quot;Built In: Job Search &amp; Company Research&quot; and has job listings (it claims 500K+ jobs) and company profiles. It is clearly a job board.</p>

<p>https://builtin.com/ — HTTP 200, no redirect. Title: &#x27;Built In: Job Search &amp; Company Research&#x27;. It shows 500K+ jobs, 100K+ companies, all tech jobs and remote tech jobs.</p>

</details>

<h3>Jobs in Games — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>https://jobsingames.com redirects to https://www.jobsingames.com/ (HTTP 200). The site is titled &#x27;Games Jobs — Live Roles, Updated Daily&#x27; and calls itself the &#x27;Jobs in Games marketplace&#x27;, with 27,786 published Games roles. The description is accurate.</p>

<p>https://www.jobsingames.com/ — The page says &#x27;Jobs in Games marketplace&#x27; and &#x27;Find your next job in Games&#x27;, with 27,786 published Games roles and filters for Unity, Unreal, Gameplay and Multiplayer. Listings include PlayStation and Scopely.</p>

<p>Caveats: The marketplace also lists roles for AI agents, bounties and gigs. This adds to the description but does not contradict it.; The URL redirects to the www host. The bare domain still works.</p>

</details>

<h3>Jobs in SexTech — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>https://jobsinsextech.com redirects to https://www.jobsinsextech.com/ (HTTP 200). The site is titled &#x27;SexTech Jobs — Live Roles, Updated Daily&#x27; and calls itself the &#x27;Jobs in SexTech marketplace&#x27;, with 2,277 roles and category filters for Hardware, App and Health. Current listings include Midi Health marketing and clinical roles. The description is accurate.</p>

<p>https://www.jobsinsextech.com/ — The page says &#x27;Jobs in SexTech marketplace&#x27; and has 2,277 published SexTech roles. The filter chips include Hardware, App, Health, Agents, Full-time and Contract. It also says &#x27;Roles for engineers, researchers &amp; AI agents.&#x27;</p>

<p>Caveats: I did not check the role mix in detail. Many current listings are in health/femtech.; The site is not listed in the Jobs in Next Tech network bundle (see 511).</p>

</details>

<h3>Jobs in XR — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>https://jobsinxr.com redirects to https://www.jobsinxr.com/ (HTTP 200). The site is titled &#x27;XR Jobs — Live Roles, Updated Daily&#x27; and calls itself the &#x27;Jobs in XR marketplace&#x27;, with 2,104 roles and AR, VR, Unity, 3D Graphics and Computer Vision filters. The description is accurate.</p>

<p>https://www.jobsinxr.com/ — The page says &#x27;Jobs in XR marketplace&#x27; and has 2,104 published XR roles, with filter chips for AR, VR, Unity, 3D Graphics and Computer Vision. Listings include Roblox.</p>

</details>

<h3>JobYap — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>https://jobyap.com returns HTTP 200. It is titled &#x27;JobYap - Tech Jobs with Open Discussions&#x27; and has a feed of about 159k jobs with salary ranges, location filters and a &#x27;Has Comments&#x27; filter. A sample job page applies through the employer&#x27;s own Workday careers site, which supports the &#x27;official careers sites&#x27; claim. The description is accurate.</p>

<p>https://jobyap.com/ — Meta: &#x27;An up-to-the-minute feed of tech jobs with open comment sections for everyone.&#x27; The page shows 158,569 jobs, salary ranges such as &#x27;177 k - 365 k USD&#x27;, and Company, Location and &#x27;Has Comments&#x27; filters.</p>

<p>https://jobyap.com/job/principal-business-operations-manager-at-cadence-553623 — The job page shows location and time type. Its apply link goes to cadence.wd1.myworkdayjobs.com/External_Careers, the employer&#x27;s official careers site.</p>

<p>Caveats: The homepage does not state the sourcing method. I inferred it from one sample job page.</p>

</details>

<h3>ParlayJobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>https://www.parlayjobs.com/ returns HTTP 200. It is titled &#x27;Parlay Jobs - The Best Sports Betting Jobs&#x27; and calls itself &#x27;The Sports Betting Job Board&#x27;, covering sportsbooks, iGaming, predictions, analytics and media. It lists roles at Sportradar, Stake, BetMGM and others. The description is accurate.</p>

<p>https://www.parlayjobs.com/ — Header: &#x27;The Sports Betting Job Board — Sportsbooks / igaming / Predictions / Analytics / Media&#x27;. Meta: &#x27;verified jobs from sportsbooks, DFS platforms, odds providers, data companies and betting technology firms.&#x27; There is a &#x27;Latest iGaming Jobs&#x27; feed.</p>

</details>

<h3>JobLeads — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. https://www.jobleads.com/ returned HTTP 403 with a Cloudflare challenge (cf-mitigated: challenge). That is bot protection, not evidence the site is dead. Search results show it is active: indexed as &#x27;Jobs That Fit&#x27;, with current 2026 blog content and support pages describing a job platform that aggregates listings from career pages, recruitment sites and headhunters. Its identity and fit as a job board are supported.</p>

<p>https://www.jobleads.com/ — curl returned HTTP 403 with header cf-mitigated: challenge (Cloudflare bot protection). The search-indexed title is &#x27;Jobs That Fit&#x27;.</p>

<p>https://www.jobleads.com/us/blog/job-search/job-search-tools — A blog post titled &#x27;11 Best Job Search Engines and Tools [2026]&#x27; is indexed under jobleads.com, which suggests the site is still active.</p>

<p>https://support.jobleads.com/hc/en-us/articles/21152173789458-About-us — The search summary of the JobLeads support About page describes a Hamburg-based job platform aggregating listings from many sources. Direct fetch returned 403.</p>

<p>Caveats: Both the homepage and the support page returned 403 to my automated fetchers. Reachability and content come from search-engine indexes, not from pages I loaded.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>TaskFavour — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>curl of the homepage got a Cloudflare challenge (HTTP 403), but the /about page loaded through WebFetch. It describes TaskFavour as an AI-powered job search platform with AI-driven job alerts. Search-indexed copy from the site and its iOS/Google Play listings (&#x27;TaskFavour - AI Job Search&#x27;) says it covers &#x27;freelance gigs, full-time remote work, or side hustles&#x27; and full-time/part-time roles, with real-time alerts. The description is supported.</p>

<p>https://www.taskfavour.com/about — Loaded. It describes an AI-powered job search platform with AI-driven job alerts that &#x27;surfaces hidden opportunities 24/7&#x27;.</p>

<p>https://www.taskfavour.com/ — curl returned HTTP 403 with cf-mitigated: challenge. Search-indexed copy says the system &#x27;monitors the web and notifies you… whether you are looking for freelance gigs, full-time remote work, or side hustles.&#x27;</p>

<p>https://play.google.com/store/apps/details?id=com.taskfavour.jobsearch&amp;hl=en-US — The app is listed as &#x27;TaskFavour - AI Job Search&#x27; (per search result). The search summary says it has been on Google Play since April 2026 and recently changed from a marketplace to a job search/alerts tool.</p>

<p>Caveats: The homepage itself was not readable directly. The freelance/remote/full-time coverage comes from search-indexed site copy and app-store summaries.; A third-party automated checker (scam-detector) rates the domain &#x27;medium-risk&#x27;. That is not authoritative and is outside the contribution rules.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>College Recruiter — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>College Recruiter is live and describes itself as a job board for students and recent graduates looking for internships and entry-level jobs, so it fits Entry Level.</p>

<p>https://www.collegerecruiter.com/ — HTTP 200. The title mentions internships, apprenticeships and entry-level jobs for students and recent grads. The meta description reads: &#x27;Leading niche job board for college and university students searching for internships... and recent graduates hunting for entry-level jobs&#x27;.</p>

</details>

<h3>TalentEgg — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>TalentEgg is live. Its title calls it an online career resource for student and grad jobs, which fits Entry Level.</p>

<p>https://talentegg.ca/ — HTTP 200. The page title is &#x27;Home - TalentEgg | Online Career Resource for Student &amp; Grad Jobs&#x27;.</p>

<p>Caveats: Only the homepage title and metadata were checked. The listings were not browsed in depth.</p>

</details>

<h3>AfterCollege — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>AfterCollege is reachable and still runs as a job search site under the same name. The brand targets college students and graduates, which fits Entry Level, but the current homepage metadata is generic.</p>

<p>https://www.aftercollege.com/ — HTTP 200. The title is &#x27;AfterCollege&#x27;. The meta description is a generic job-search pitch: &#x27;Use AfterCollege job search engine... Find employers hiring near you and quickly apply to job openings.&#x27;</p>

<p>Caveats: The homepage metadata no longer says &#x27;students/new grads&#x27; explicitly. I did not browse deeper pages to confirm the focus is still on students. The entry is bare-link and makes no claim to check.</p>

</details>

<h3>Fresh Commits — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Fresh Commits is live, and its content supports each claim in the description: verified listings, 0–2 YoE, entry-level/new-grad, and the data, QA and product categories. The site&#x27;s metadata also mentions global and remote roles, but that only adds to the US scope. It does not make the description false.</p>

<p>https://www.freshcommits.com — HTTP 200 (redirects to https://www.freshcommits.com/). The title is &#x27;FreshCommits – Entry Level &amp; New Grad Software Engineer Jobs&#x27;. The meta description reads: &#x27;Verified entry level, new graduates, junior engineer, early career, and freshers software engineering opportunities across US &amp; global tech hubs and remote&#x27;.</p>

<p>https://www.freshcommits.com/ — The page text mentions &#x27;0-2&#x27;/&#x27;0–2&#x27; YoE many times. It also mentions &#x27;Verified&#x27; and the QA/Quality Assurance, Data and Product categories.</p>

<p>Caveats: The site also covers non-US &#x27;global tech hubs&#x27; and remote roles. &#x27;US&#x27; in the entry is narrower than the site, but it is not a false claim. A maintainer could optionally drop &#x27;US&#x27;.</p>

</details>

<h3>The Hub — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The Hub is live and lists jobs at Nordic startups, which fits Startups.</p>

<p>https://thehub.io/ — HTTP 200. The title is &#x27;The Hub | Find your next exciting startup job&#x27;. The meta description reads: &#x27;We connect global talents with career opportunities in Nordic startups.&#x27;</p>

</details>

<h3>Work in biotech — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Work In Biotech is live and describes itself as a job board for biotech startups, which fits Startups.</p>

<p>https://workinbiotech.com/ — HTTP 200. The title is &#x27;Work In Biotech - All startup biotech jobs. Checked daily.&#x27; The meta description reads: &#x27;Most popular job board for biotech startups.&#x27;</p>

<p>Caveats: The &#x27;most popular&#x27; line is the site&#x27;s own marketing and is not part of the entry.</p>

</details>

<h3>devtooljobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>devtooljobs is live, and its title matches the description: GTM jobs at developer tooling companies.</p>

<p>https://devtooljobs.com/ — HTTP 200. The title is &#x27;GTM Jobs in Developer Tooling Companies&#x27;. The meta description reads: &#x27;Your fortress of solitude when looking for the next GTM role in a developer tooling company.&#x27;</p>

<p>Caveats: Developer tooling companies are not necessarily startups. The site&#x27;s fit with the Startups section is loose but was already the case when it was added.</p>

</details>

<h3>DMtheFounder — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The homepage confirms every part of the description: early engineering and founding roles that founders post on X and Hacker News, checked by hand, with the founder&#x27;s own post shown.</p>

<p>https://dmthefounder.com/ — HTTP 200. Page text: &#x27;Startup jobs, straight from the founders. Early engineering roles that founders post on X and Hacker News. We check every one by hand&#x27;. Step 2 is &#x27;See who&#x27;s hiring: The founder&#x27;s own post, company research and funding filings.&#x27; It listed 412 roles, including a &#x27;Founding engineer&#x27; category, plus pre-seed and seed stage filters.</p>

</details>

<h3>Free &amp; Open Source Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. It is reachable, the identity matches the name, and it fits the Open Source section: the board lists only paid FOSS and open-hardware jobs, with recent postings.</p>

<p>https://www.fossjobs.net/ — HTTP 200. The title is &#x27;Free &amp; Open Source Jobs - fossjobs.net&#x27;. The page says it is &#x27;a job board exclusively for paid free &amp; open source jobs: We only list jobs at organizations that improve and involve FOSS or open hardware projects.&#x27; The latest listings are dated 2026-07 through 2026-10-13 (Baserow, FSF, Sovereign Tech Agency).</p>

<p>Caveats: Posting volume is low: 6 recent jobs at the time of checking.</p>

</details>

<h3>freehire — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The official README and the live site support every claim. freehire is MIT-licensed open source, pulls jobs from company ATS platforms and from Telegram channels, normalizes and deduplicates postings, and stores AI enrichment data on its job records.</p>

<p>https://freehire.me/jobs — HTTP 200. Title: &#x27;Tech jobs — search 4.9M+ openings · freehire&#x27;. The page links to github.com/strelov1/freehire and calls itself &#x27;Free &amp; open-source&#x27;. Job records embed &#x27;enrichment&#x27; objects (summary, requirements) with enriched_at and enrichment_version fields.</p>

<p>https://raw.githubusercontent.com/strelov1/freehire/HEAD/README.md — The README says it aggregates postings from &#x27;168 ATS platforms, a long tail of aggregators and direct feeds, and 97 Telegram channels&#x27;. It describes &#x27;One schema, deduplicated&#x27;, crawling from Workday, Greenhouse, Lever and Ashby, and an MIT license badge.</p>

<p>Caveats: The listing counts are volatile. The description doesn&#x27;t use them, which is good.; Some AI features are paid (Pro) or need an LLM endpoint when self-hosted.</p>

</details>

<h3>Kube Careers — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. kube.careers is reachable, is clearly a curated Kubernetes job board with current listings, and fits the DevOps section.</p>

<p>https://kube.careers — Redirects to https://kube.careers/ with HTTP 200. Title: &#x27;Kubernetes jobs in November 26 (6 new) | Kube Careers&#x27;. Text reads &#x27;Hand-picked Kubernetes jobs. Clear salary ranges and apply directly to companies. Last updated today&#x27;, with DevOps and SRE roles listed.</p>

</details>

<h3>Jobs in Quantum — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site calls itself the &#x27;Jobs in Quantum marketplace&#x27; and lists quantum roles, with filters for Quantum Algorithms and Quantum Hardware. The description is supported.</p>

<p>https://jobsinquantum.com — Redirects to https://www.jobsinquantum.com/ with HTTP 200. Title: &#x27;Quantum Jobs — Live Roles, Updated Daily&#x27;. Text: &#x27;Jobs in Quantum marketplace&#x27;, &#x27;1,383 published Quantum roles&#x27;, filters for &#x27;Qiskit Cirq Quantum Algorithms Quantum Hardware&#x27;, and listings from IonQ and Quantinuum.</p>

<p>Caveats: The marketplace also advertises roles for AI agents and bounty or gig work. That adds to what the entry describes but doesn&#x27;t contradict it.</p>

</details>

<h3>US Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. USA.jobs is reachable, is a general US job board with listings by category and US city, and fits the USA section.</p>

<p>https://www.usa.jobs/ — HTTP 200. Title: &#x27;USA.jobs&#x27;. Text: &#x27;Jobs in the USA. Real Jobs for Everyday People&#x27;, category job counts (for example IT &amp; Engineering 11342 jobs), and trending US cities.</p>

</details>

<h3>Careerjet — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. careerjet.com returned HTTP 200 but served a bot-verification page, so I couldn&#x27;t read its content directly. Third-party and Careerjet-adjacent sources identify it as an active job search engine (aggregator) covering more than 130 countries, including the US. That is enough to keep it in the USA section.</p>

<p>https://www.careerjet.com/ — HTTP 200 with title &#x27;Careerjet&#x27;, but the body was &#x27;Verification required. Our systems have detected unusual traffic…&#x27;, a bot check rather than site content.</p>

<p>https://www.careerjet.com/recruiter — According to the search summary, Careerjet&#x27;s recruiter page says its job search engine is available in more than 130 countries and 30+ languages. I did not read the page directly.</p>

<p>Caveats: Because of the bot check, I couldn&#x27;t confirm which country version careerjet.com shows to US visitors.; Careerjet is international, not US-specific. Placing it in the USA section is a maintainer judgment.</p>

</details>

<h3>Nexxt — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. Nexxt is reachable and is an active US recruiting company with job-seeker search (&#x27;FOR JOB SEEKERS … SEARCH JOBS&#x27;) and a network of 50+ niche career sites. It fits the USA section.</p>

<p>https://www.nexxt.com/ — HTTP 200. Title: &#x27;Start hiring with Nexxt&#x27;. The homepage is aimed at employers (150M+ candidates, 30M+ resumes), but the navigation includes &#x27;FOR JOB SEEKERS HOME SEARCH JOBS JOIN NOW&#x27;. Meta: &#x27;multichannel marketing across more than 50 niche career sites&#x27;.</p>

<p>Caveats: The root URL now opens on employer marketing. If the maintainer wants a seeker-facing link, a job-search URL might be better, but I didn&#x27;t verify one.</p>

</details>

<h3>National Labor Exchange — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. The US National Labor Exchange (NLx) is reachable and offers job search. It is a partnership between DirectEmployers and NASWA (the National Association of State Workforce Agencies), and it fits the USA section.</p>

<p>https://usnlx.com/ — HTTP 200. Title: &#x27;US National Labor Exchange&#x27;. Text: &#x27;Established in 2007, the National Labor Exchange (NLx) represents a unique, public-private partnership between DirectEmployers (DE) and the National Association of State Workforce Agencies (NASWA)… Current Employer Count: 300,000 Daily Job Count: 3 million&#x27;. It has a job search box.</p>

</details>

<h3>juju — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. Juju is reachable and is an active job search aggregator focused on US cities. It fits the USA section.</p>

<p>https://www.juju.com/ — HTTP 200. Title: &#x27;Job Search — over 2M+ jobs from across the web | Juju&#x27;. Text: &#x27;Juju aggregates listings from thousands of job sites, company career pages, and staffing agencies&#x27;, &#x27;4,905,183 jobs updated today&#x27;, &#x27;Jobs in cities across the United States&#x27;.</p>

</details>

<h3>Chef Jobs Near.Me — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. Chef Jobs Near Me is reachable and is an active chef and cook job search with current listings, so the identity matches the name. But the site describes itself as worldwide (&#x27;Kitchen roles, worldwide&#x27;). Its featured searches are London, Toronto and Melbourne, and sampled listings were in the UAE, Canada and France, so its fit for the USA section is weak.</p>

<p>https://chefjobsnearme.com/ — HTTP 200. Text: &#x27;Chef Jobs Near Me | Find Chef and Cook Jobs&#x27;, &#x27;Kitchen roles, worldwide&#x27;, popular searches &#x27;Sous Chef jobs in London… Chef jobs in Toronto… Chef de Partie jobs in Melbourne&#x27;. Listings sampled: Abu Dhabi, Saskatoon (Canada), Épernon (France). Employer posting is marked &#x27;Coming soon&#x27;.</p>

<p>Caveats: Whether a worldwide kitchen-jobs board belongs in the USA section is a maintainer placement decision. The site is relevant and active, so this isn&#x27;t grounds for removal.; I didn&#x27;t measure how many listings are in the US.</p>

</details>

<h3>Library Jobs HQ — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. Library Jobs HQ is reachable and is an active board of hand-picked library and information science jobs in the U.S. It fits the USA section.</p>

<p>https://www.libraryjobshq.com/ — HTTP 200. Title: &#x27;Library Jobs HQ | Library &amp; Information Science Jobs&#x27;. Meta: &#x27;Hand-picked library and information science jobs across the U.S.&#x27; Text: &#x27;There are 366 jobs live currently!&#x27;</p>

</details>

<h3>Hypetrain — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Search results show the page title &#x27;13,000+ jobs at AI startups near Caltrain and BART&#x27;. The PR that added the entry (merged 2026-10-10, one month ago) describes roles at Bay Area AI and tech startups, each mapped by the walk from the nearest Caltrain or BART station. That matches the description. The live site is up but put my automated requests behind Vercel&#x27;s rate-limit checkpoint.</p>

<p>https://hypetrain.fyi/ — Direct fetch returned HTTP 429 &#x27;Vercel Security Checkpoint&#x27;, a bot challenge rather than an outage. The search index title is &#x27;13,000+ jobs at AI startups near Caltrain and BART&#x27;.</p>

<p>https://github.com/emredurukn/awesome-job-boards/pull/248 — PR &#x27;Add Hypetrain to Startups&#x27; by glgh, merged Oct 10, 2026: &#x27;about 13,800 open roles at 460 Bay Area AI and tech startups, with each office on a map by its walk from the nearest Caltrain or BART station.&#x27;</p>

<p>Caveats: I couldn&#x27;t read the live page content directly because of the Vercel checkpoint. The match relies on the indexed title and a recent PR.; The PR says &#x27;AI and tech startups&#x27;, which is slightly broader than the entry&#x27;s &#x27;AI startups&#x27;. It isn&#x27;t a contradiction.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>RemoteWorkUSA — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Live curated board of remote/hybrid jobs open to US applicants, with filters for all US states and job categories (Engineering, Design, Product, etc.). The description is supported.</p>

<p>https://www.remoteworkusa.com/ — &#x27;A Curated Job Board for Remote Jobs in the United States. Browse hundreds of fully remote and hybrid jobs open to applicants across the United States.&#x27; Has a state selector listing all states and category navigation. Shows &#x27;No jobs match this search. Please try again using other terms or filters.&#x27;</p>

<p>Caveats: The site also lists hybrid roles; this does not contradict the entry.</p>

</details>

<h3>Grapevine Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Reachable Australian job board for the TV, film and broadcast screen industry. Fits the Australia section.</p>

<p>https://www.grapevinejobs.com.au/ — HTTP 200. Title &#x27;Grapevine Jobs: TV &amp; Film Screen Jobs Australia&#x27;. Meta: &#x27;Dedicated job board for screen industry; TV, Film &amp; Broadcast media jobs.&#x27;</p>

</details>

<h3>Student Job Board — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Reachable Australian student job board (casual, part-time and entry-level jobs for university students). Fits the Australia section.</p>

<p>https://www.studentjobboard.com.au/ — HTTP 200. Title &#x27;Student Jobs Australia: Search for Jobs with Student Job Board&#x27;. Meta: &#x27;Australia&#x27;s favourite employment website for university students searching for casual jobs and entry-level part-time jobs in Australia.&#x27;</p>

</details>

<h3>Work in Tech — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. &#x27;Work In Tech&#x27; is Communitech&#x27;s job board (Kitchener, Ontario), powered by Getro, with thousands of live jobs. The name matches the page title, and it fits the Canada section.</p>

<p>https://www1.communitech.ca/jobs — HTTP 200, no redirect. Title &#x27;Jobs | Work In Tech Job Board&#x27;. &#x27;Search job openings across the Work In Tech network.&#x27; &#x27;Showing 5,725 jobs&#x27;. Footer: Communitech Hub, 151 Charles Street West, Kitchener, Ontario; &#x27;Powered by Getro&#x27;.</p>

</details>

<h3>Jobbank — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The official Government of Canada Job Bank search page is live. Fits the Canada section.</p>

<p>https://www.jobbank.gc.ca/jobsearch/ — HTTP 200. Title &#x27;Available jobs - Search - Job Bank&#x27;. Meta: &#x27;View 68,989 job postings … on Job Bank, Canada&#x27;s one-stop job board.&#x27;</p>

</details>

<h3>CanadianNanny.ca — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Reachable Canadian nanny and babysitter marketplace where families post care jobs. Fits the Canada section as a niche care-jobs board.</p>

<p>https://canadiannanny.ca/ — HTTP 200. Title &#x27;Trusted Babysitter and Nanny services in Canada | CanadianNanny.ca&#x27;. Meta: &#x27;Find trusted local nannies and babysitters… Post jobs for all your care needs.&#x27;</p>

<p>Caveats: It is a two-sided caregiver marketplace rather than a traditional employer job board.</p>

</details>

<h3>SEEK — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. SEEK is Australia&#x27;s major job marketplace. Direct fetch got a Cloudflare 403, but the returned body still carried the SEEK title. SEEK publishes ongoing 2026 employment reports. An access failure is not evidence of a problem.</p>

<p>https://www.seek.com.au/ — HTTP 403 (Cloudflare) to automated client, but the body title was &#x27;SEEK - Australia&#x27;s no. 1 jobs, employment, career and recruitment site&#x27; and the meta described an employment marketplace.</p>

<p>https://au.seek.com/about/news/article/seek-employment-report-june26 — Search result shows SEEK publishing monthly 2026 employment reports, so the business is active.</p>

<p>Caveats: Could not render the full page because of bot protection.; Some SEEK corporate content lives on au.seek.com; the jobs homepage at seek.com.au did not redirect.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>CareerOne — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Direct fetches returned Cloudflare 403 challenges, but search results show live careerone.com.au job pages dated November 2026 (about 105k jobs across Australia). Fits the Australia section.</p>

<p>https://www.careerone.com.au/jobs/in-australia — Search result &#x27;Jobs in All Australia - Nov 2026&#x27; on careerone.com.au, reported at about 105,056 jobs.</p>

<p>https://www.careerone.com.au/ — Direct curl and WebFetch got HTTP 403 Cloudflare &#x27;Just a moment...&#x27; challenge; page content was not read directly.</p>

<p>Caveats: Evidence is from search-engine snippets, not a direct page read.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Jobboom — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Jobboom is a long-running Quebec job board. Jobillico acquired it in November 2025, but third-party 2026 roundups still list it as a separate, running brand. No official evidence of shutdown or redirect. Direct fetches were blocked by Cloudflare 403.</p>

<p>https://www.jobillico.com/blog/acquisition-de-jobboom-jobillico-renforce-sa-position-sur-le-marche-de-lemploi-au-quebec/ — Official Jobillico blog announcing the acquisition of Jobboom; the companies plan to build the largest job network in Quebec. Content seen via search summary.</p>

<p>https://www.jobboom.com/en/job/ — HTTP 403 Cloudflare challenge; no redirect observed in response headers.</p>

<p>Caveats: Could not read the page directly; post-acquisition brand plans could change.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Jobillico — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Jobillico is an active Quebec/Canadian job board (part of Harris Computer) that acquired Jobboom in 2025. The search page returned a Cloudflare 403 to automated clients; no redirect seen.</p>

<p>https://www.jobillico.com/blog/acquisition-de-jobboom-jobillico-renforce-sa-position-sur-le-marche-de-lemploi-au-quebec/ — Official Jobillico blog post (via search) on its November 2025 acquisition of Jobboom; shows the company is active.</p>

<p>https://www.jobillico.com/search-jobs — HTTP 403 Cloudflare challenge to curl/WebFetch.</p>

<p>Caveats: Page content not read directly.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Eluta — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Eluta.ca is reachable: a Canadian job search engine and the official job search of Canada&#x27;s Top 100 Employers project, with about 182k jobs. Fits the Canada section.</p>

<p>https://www.eluta.ca/ — HTTP 200. Title &#x27;Job Search Canada | Eluta.ca&#x27;. Meta: &#x27;official job search engine of the Canada&#x27;s Top 100 Employers project&#x27;. &#x27;182,222 jobs available right now&#x27;. © 2026 Mediacorp Canada.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>CareerBeacon — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. CareerBeacon is a Canadian (Atlantic-focused) job board. Indexed careerbeacon.com search and job pages and 2026 third-party guides show it is active. The direct fetch got a Cloudflare 403.</p>

<p>https://www.careerbeacon.com/en/job/2204888/atlantic-lottery/environment-specialist/moncton-nb — Indexed CareerBeacon job posting (Atlantic Lottery, Moncton NB).</p>

<p>https://www.careerbeacon.com/ — HTTP 403 Cloudflare challenge to automated client; no redirect seen.</p>

<p>Caveats: Page content not read directly; activity inferred from indexed pages and 2026 guides.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Jobsite — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Jobsite.co.uk is a StepStone-owned UK job board. Since 2018 it has cross-listed jobs and shared a CV database and employer accounts with Totaljobs. Third-party sources say it remains online as a separate, lower-profile brand. No official shutdown or redirect was observed; the direct fetch was an Akamai 403.</p>

<p>https://www.jobsite.co.uk/ — HTTP 403 &#x27;Access Denied&#x27; (Akamai) to automated clients; no Location redirect header.</p>

<p>https://aimgroup.com/2018/05/01/jobsite-and-totaljobs-consolidate-in-the-u-k/ — Reports Jobsite and Totaljobs cross-listing jobs and combining CV databases under StepStone (from search summary).</p>

<p>https://en-qa.whatjobs.com/news/what-happened-to-jobsite-co-uk/ — Third-party article (via search) saying Jobsite was not shut down but became secondary to Totaljobs.</p>

<p>Caveats: Could not read the live site; its standing as a separate brand comes from third-party reports, not official StepStone material.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Job Serve — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The JobServe job-search URL returns HTTP 200 with no redirect. Its meta description presents JobServe as a UK site for permanent and contract jobs. It still fits the UK section.</p>

<p>https://www.jobserve.com/gb/en/Job-Search/ — HTTP 200 at the same URL. Meta description: &#x27;Specialising in Permanent and Contract jobs in the UK with thousands advertised daily... The #1 UK Job site for IT Jobs, Finance Jobs...&#x27;</p>

<p>Caveats: The page&#x27;s &lt;title&gt; was empty in the fetched HTML. Identity was confirmed from the meta description only.</p>

</details>

<h3>reed — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>reed.co.uk returns HTTP 200 and calls itself a UK job site. It fits the UK section.</p>

<p>https://www.reed.co.uk/ — HTTP 200. Title: &#x27;Jobs and Recruitment on Reed.co.uk, the UK&#x27;s #1 job site&#x27;. Meta description mentions finding a job from the 200,000 available.</p>

<p>Caveats: Job counts on the page change over time. The entry has no description, so nothing needs correcting.</p>

</details>

<h3>CV-Library — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>CV-Library returns HTTP 200 and is a live UK job board.</p>

<p>https://www.cv-library.co.uk/ — HTTP 200. Title: &#x27;Job Search - Find 138,562 UK jobs on CV-Library&#x27;. Meta description: &#x27;Start your job search with 138,562 live UK vacancies on award-winning CV-Library.&#x27;</p>

</details>

<h3>Gumtree — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The Gumtree jobs section returns HTTP 200 and lists job vacancies on the UK classifieds site.</p>

<p>https://www.gumtree.com/jobs — HTTP 200. Title &#x27;Jobs | Gumtree&#x27;, og:site_name &#x27;Gumtree.com&#x27;. Meta description mentions a range of positions and job alerts.</p>

<p>Caveats: Gumtree is a general classifieds site, and this entry links to its jobs section.</p>

</details>

<h3>Hunt UK Visa Sponsors — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site is live and searches UK jobs at companies licensed to sponsor visas. That fits the UK section. The www URL redirects to the domain without www.</p>

<p>https://huntukvisasponsors.com/ — https://www.huntukvisasponsors.com/ redirects to https://huntukvisasponsors.com/ (HTTP 200). Title: &#x27;UK Visa Sponsorship Jobs | Hunt UK Visa Sponsors&#x27;. Meta description: &#x27;Search 133,900+ live jobs at UK companies licensed to sponsor Skilled Worker visas.&#x27;</p>

<p>Caveats: The address without www is the canonical one. The www link still works, so changing it is optional.</p>

</details>

<h3>Welcome to the jungle — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Welcome to the Jungle UK (formerly Otta) returns HTTP 200 and is a live job-search platform. The name and URL match the current branding.</p>

<p>https://uk.welcometothejungle.com/ — HTTP 200. Title: &#x27;Welcome To The Jungle UK (formerly Otta) - Find a job&#x27;. Meta description: &#x27;Otta is now Welcome To The Jungle.&#x27;</p>

<p>Caveats: The site mainly targets tech jobs and is not limited to UK roles. The maintainer may want to capitalise the name as &#x27;Welcome to the Jungle&#x27; (optional).</p>

</details>

<h3>DefiniteJobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The DefiniteJobs search page returns HTTP 200 and advertises UK job listings.</p>

<p>https://definitejobs.co.uk/find-jobs/ — HTTP 200. Title: &#x27;Job Search | Find Over 53000+ UK Jobs With DefiniteJobs&#x27;. Meta description mentions remote, freelance, part-time and full-time jobs.</p>

<p>Caveats: Nothing beyond the homepage metadata was checked, such as how listings are sourced or aggregated.</p>

</details>

<h3>UK Visa Jobs — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>UK Visa Jobs returns HTTP 200 and lists UK visa-sponsorship jobs. It fits the UK section.</p>

<p>https://www.ukvisajobs.com/ — HTTP 200. Title: &#x27;UK Visa Sponsorship Jobs | Verified UK Employers | UK Visa Jobs&#x27;. Meta description mentions Skilled Worker visa and Health and Care Worker visa roles.</p>

</details>

<h3>StepStone — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>StepStone Germany is live and remains a major German job board. In a non-browser fetch, /en redirected to an onboarding page served in German.</p>

<p>https://www.stepstone.de/en — Redirected to https://www.stepstone.de/onboarding?onboardingSource=hp-redirect (HTTP 200). Title: &#x27;Jobs sind unser Job: Die Jobbörse mit 150.000+ Jobs | Stepstone&#x27;.</p>

<p>Caveats: The English page may depend on cookies or a browser session. It is unclear whether /en still serves an English UI to normal browsers.</p>

</details>

<h3>Jobware — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Jobware is a German job board. Direct curl returned 403 (bot protection), but WebFetch read the page and it shows job listings by field and German city.</p>

<p>https://www.jobware.de/ — curl: HTTP 403. WebFetch read the page: tagline &#x27;Jobware, da hab&#x27; ich den Job her!&#x27;, listings for IT, engineering, healthcare and others, German cities, and a &#x27;no ghosting&#x27; feedback policy.</p>

<p>Caveats: Direct HTTP access was blocked for automated clients. That is not evidence of a problem with the site.</p>

</details>

<h3>CWJobs — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Direct fetches return 403 (bot protection). Secondary sources from 2026 confirm CWJobs is an active UK IT/tech job board run by The Stepstone Group UK. That fits the UK section.</p>

<p>https://www.cwjobs.co.uk/ — curl and WebFetch both returned HTTP 403, so the site could not be read directly.</p>

<p>https://play.google.com/store/apps/details?id=com.stepstone.cwjobs&amp;hl=en_GB — Search result: the CWJobs app is published by The Stepstone Group UK and was updated 6 Nov 2026. It describes an IT job board with 9,000+ live ads each month.</p>

<p>https://www.cwjobs.co.uk/jobs/the-stepstone-group?cmp=1 — This cwjobs.co.uk listing page is indexed in search results, which suggests the site serves job pages.</p>

<p>Caveats: The homepage could not be read directly because of a 403. Identity rests on the app-store listing and third-party sources.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>jobvector — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Direct fetches return 403 (Cloudflare challenge). Search results show jobvector.de pages live in 2026, including its own January 2026 press release. It is a German job board for engineers, IT, natural sciences and medicine, so it fits the Germany section.</p>

<p>https://www.jobvector.de/en/ — curl and WebFetch returned 403 with a &#x27;Just a moment...&#x27; Cloudflare challenge.</p>

<p>https://www.jobvector.de/presse/jobvector-als-bestes-jobportal-fuer-ingenieure-und-it-2026-ausgezeichnet/ — Search result: jobvector press release saying it was again named best job portal for engineers and IT in 2026.</p>

<p>https://www.jobvector.de/jobs/ingenieure/ — An engineering job listings page on jobvector.de appears in search results.</p>

<p>Caveats: The /en/ page was not read directly. It is unconfirmed whether the English-language path still serves English content.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Stellenanzeigen — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Direct fetch returns 403. Third-party sources from 2026 describe stellenanzeigen.de as an active general German job board, which fits the Germany section.</p>

<p>https://www.stellenanzeigen.de/ — curl returned 403 and WebFetch could not fetch the page.</p>

<p>https://jobboersencheck.de/testsieger/jahr-2026/bewerberbewertung/generalisten/gold-big-cluster — Search summary: stellenanzeigen.de won Gold in the 2026 job-seeker ratings for large general job boards.</p>

<p>https://www.mhm-hr.com/aktuelles/jobplattformen-vergleich-2026/ — Search summary: a 2026 comparison describes it as a classic, well-known German job board.</p>

<p>Caveats: The homepage could not be read directly. Its status rests on third-party 2026 sources.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>StellenOnline — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The site loads at the listed URL with no redirect and calls itself a German Jobbörse (job board), so it fits the Germany section.</p>

<p>https://www.stellenonline.de/ — HTTP 200, canonical https://www.stellenonline.de/. Title &#x27;Die Jobbörse für Jobs und Stellenangebote – stellenonline.de&#x27;. The meta description says it is &#x27;eine der großen Jobbörsen in Deutschland&#x27;.</p>

<p>Caveats: Checked only the homepage metadata and that it loads. Listing volume and freshness were not checked.</p>

</details>

<h3>Berlin Startup Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Berlin Startup Jobs is live at its canonical URL and is still a Berlin startup job board, which fits the Germany section.</p>

<p>https://berlinstartupjobs.com/ — HTTP 200, canonical https://berlinstartupjobs.com/. Title &#x27;Berlin Startup Jobs | IT Jobs, Marketing, Internships, Sales, HR, Freelance&#x27;.</p>

<p>Caveats: Did not check how current the listings are.</p>

</details>

<h3>Jobs in Berlin — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The site is live and lists English-speaking jobs in Berlin and Germany. The URL redirects from www to the bare domain, but the page&#x27;s own canonical tag is the listed www URL, so the link needs no change.</p>

<p>https://www.jobsinberlin.eu/ — Redirects to https://jobsinberlin.eu/ (HTTP 200), but rel=canonical is https://www.jobsinberlin.eu/. Title &#x27;Jobs in Berlin and Germany - job vacancies for English Speaking workers&#x27;.</p>

<p>Caveats: Did not check how current the listings are.</p>

</details>

<h3>academics — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. academics.de is live and is a German job market for science, research and the public sector, which fits the Germany section.</p>

<p>https://www.academics.de/ — HTTP 200. Title &#x27;academics - der führende Stellenmarkt für Wissenschaft, Forschung, Öffentliches &amp; Gesellschaft&#x27;. The description offers Stellenangebote (job ads) in those fields.</p>

<p>Caveats: Checked only the homepage metadata.</p>

</details>

<h3>karrieresprung — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The homepage now leads with a free AI cover-letter generator, but the site still runs a job listing section (&#x27;Jobs finden&#x27;, &#x27;70.000+ Jobs, stündlich frisch&#x27;, /jobs pages). It is still at least partly a German job board, so it remains within the section&#x27;s scope.</p>

<p>https://www.karrieresprung.de/ — HTTP 200. Title &#x27;Anschreiben erstellen – kostenlos, nach DIN 5008 | KarriereSprung&#x27;. The page shows a &#x27;Jobs finden&#x27; nav item, the claim &#x27;70.000+ Jobs, stündlich frisch&#x27;, a &#x27;Jobs anzeigen&#x27; button and links to /jobs and /jobs?start=1.</p>

<p>Caveats: The site&#x27;s main focus seems to have moved to AI-generated job applications, with the job listings now secondary. The maintainer may want to judge whether it still counts as a job board. I did not open the /jobs listing pages themselves.</p>

</details>

<h3>JobJump — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. JobJump is live and is a German job board for jobs across Germany.</p>

<p>https://jobjump.net/ — HTTP 200, canonical https://jobjump.net. Title &#x27;JobJump – Jobbörse für Jobs &amp; Stellenangebote in Deutschland&#x27;. The description says it covers jobs from all over Germany and that searching and applying are free.</p>

<p>Caveats: Checked only the homepage metadata.</p>

</details>

<h3>Germany Dev Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The description is supported. The site lists tech jobs in Germany and Austria at companies where English is the working language, sourced from company career sites, and shows visa sponsorship only when the ad or company says so. It charges employers (it has a Pricing page) but nothing visible charges jobseekers.</p>

<p>https://germanydevjobs.com/ — Says &#x27;curated jobs at companies where English is the working language&#x27;. The meta description reads &#x27;Curated IT and developer jobs in Berlin, Munich and across Germany &amp; Austria for English speakers, with visa sponsorship noted&#x27;. There are visa-sponsorship filters and free job alerts.</p>

<p>https://germanydevjobs.com/about — Says &#x27;Jobs come from the career sites of the companies we list&#x27;, &#x27;We check every job on the company&#x27;s own careers page every day&#x27;, and &#x27;We show visa sponsorship or relocation support only when the job post or the company itself says so.&#x27; The footer links to employer &#x27;Post a job&#x27; and &#x27;Pricing&#x27; pages.</p>

<p>Caveats: No page explicitly says the site is &#x27;free&#x27; for jobseekers. That is inferred from open browsing and free alerts, with paid features shown only for employers.</p>

</details>

<h3>Jobs in Amsterdam — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The listed http URL redirects to the live HTTPS site, a board of English-speaking jobs in Amsterdam and the Netherlands. The site&#x27;s canonical URL is https://www.jobinamsterdam.com/, so the http link could optionally be changed to HTTPS, but it is not broken.</p>

<p>https://jobinamsterdam.com/ — http://www.jobinamsterdam.com/ redirects to https://jobinamsterdam.com/ (HTTP 200). Canonical is https://www.jobinamsterdam.com/. Title &#x27;Jobs in Amsterdam - Netherlands (Holland) - for English Speaking Professionals&#x27;.</p>

<p>Caveats: Switching the link from http to https would be cosmetic only. The redirect works.</p>

</details>

<h3>Together Abroad — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The Together Abroad jobs page is live at its canonical URL and has a job search for the Netherlands.</p>

<p>https://www.togetherabroad.nl/jobs.html — HTTP 200, canonical https://www.togetherabroad.nl/jobs.html. Title &#x27;Jobs in the Netherlands&#x27;. The page has job search fields (title, keywords, salary, reference numbers) and career services for internationals.</p>

<p>Caveats: Did not check how many listings there are or how current they are.</p>

</details>

<h3>Jobindex — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Jobindex is live and is a Danish job portal, which fits the Denmark section.</p>

<p>https://www.jobindex.dk/ — HTTP 200. Title &#x27;Alle job samlet ét sted – søg nyt job her | Jobindex&#x27;. The description mentions more than 30,000 open positions.</p>

<p>Caveats: Did not verify the listing count.</p>

</details>

<h3>It Job Bank — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The site is live and is Computerworld&#x27;s IT job board for Denmark. The entry name &#x27;It Job Bank&#x27; still matches the domain and the &#x27;it-jobbank&#x27; branding.</p>

<p>https://www.it-jobbank.dk/ — HTTP 200. Title &#x27;Specialister i it-job til it-kandidater | Computerworld it-jobbank&#x27;. The description calls it Denmark&#x27;s leading career site for IT professionals.</p>

<p>Caveats: The official branding is &#x27;Computerworld it-jobbank&#x27;. A rename is optional and not needed for accuracy.</p>

</details>

<h3>Jobs in Copenhagen — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The site is live and lists English-speaking jobs in Copenhagen and Denmark. www redirects to the bare domain, but the canonical tag is the listed www URL.</p>

<p>https://jobsincopenhagen.com/ — https://www.jobsincopenhagen.com/ redirects to https://jobsincopenhagen.com/ (HTTP 200). Canonical is https://www.jobsincopenhagen.com/. Title &#x27;Jobs in Copenhagen - Denmark - for English Speaking Professionals&#x27;.</p>

<p>Caveats: Did not check how current the listings are.</p>

</details>

<h3>meinestadt — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Direct curl got HTTP 403 (bot protection), but WebFetch read the homepage. meinestadt.de is a German local portal with a prominent job section that calls itself a &#x27;Führendes Jobportal für Fachkräfte mit Berufsausbildung&#x27; (leading job portal for skilled tradespeople). It still fits the Germany section.</p>

<p>https://www.meinestadt.de/ — curl returned 403 &#x27;Forbidden&#x27; (an anti-bot error page). WebFetch got the content: &#x27;Das Portal für alle Städte Deutschlands&#x27;, a job section described as &#x27;Führendes Jobportal für Fachkräfte mit Berufsausbildung&#x27;, and &#x27;Freie Stellen in ganz Deutschland&#x27;.</p>

<p>https://www.meinestadt.de/robots.txt — Served with HTTP 200, so the domain is up. The 403 is access filtering, not an outage.</p>

<p>Caveats: Direct HTTP access was blocked, so the evidence relies on WebFetch&#x27;s summary of the page.; meinestadt.de is a general local portal and jobs are one of several sections.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Pegel — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Every claim in the description is supported by public sources: a free Berlin startup job board updated three times a day from public company ATS (applicant tracking system) feeds. The direct page is behind a Cloudflare challenge (403), which is an access failure, not a dead site. robots.txt is served normally.</p>

<p>https://pegel.berlin/robots.txt — Served with HTTP 200 and lists /jobs, /companies and city paths such as /hamburg/jobs, so the domain is up. The /jobs page itself returns a Cloudflare &#x27;Just a moment...&#x27; challenge (403) to curl and WebFetch.</p>

<p>https://pegel.berlin/ — The search-indexed page title is &#x27;Pegel · Berlin startup jobs, refreshed three times daily&#x27;. Search summaries of the site&#x27;s FAQ say it is free for candidates and employers and polls company ATS feeds three times a day, at 04:05, 10:05 and 16:05 UTC.</p>

<p>https://github.com/ElxMaj/pegel-berlin-job-skill — The README describes &#x27;Berlin startup job search&#x27; with roles from Pegel&#x27;s public API, &#x27;sourced from employers&#x27; public ATS feeds&#x27;.</p>

<p>Caveats: Could not read pegel.berlin pages directly because of the Cloudflare challenge. The free and three-times-daily claims rest on search-engine summaries of the official site and FAQ, not a first-hand read.; The site now also has pages for other cities (Hamburg, Munich, Paris, London), but the listed /jobs URL and the Berlin description still hold.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>DanishTech — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site is live and focused on software and tech jobs in Denmark. That fits the Denmark section and supports the description &#x27;Software engineering jobs only.&#x27;</p>

<p>https://danishtech.co/ — HTTP 200 with no redirect. The page title is &#x27;Current software engineering jobs in Denmark (322)&#x27;. The hero text says &#x27;Discover your next tech job in Denmark / Tech and software jobs in Denmark&#x27;. Filters include Technology, Workplace, Experience and Salary.</p>

<p>Caveats: The site&#x27;s own hero text says &#x27;tech and software jobs&#x27;, which is slightly broader than &#x27;software engineering&#x27;. I checked only the landing page, not individual listings, so I can&#x27;t confirm that no non-engineering tech roles appear.; The job count in the title changes over time and isn&#x27;t in the entry.</p>

</details>

<h3>Jobrapido — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. It loads directly as Jobrapido&#x27;s Italian job search site, which fits the Italy section.</p>

<p>https://it.jobrapido.com/ — HTTP 200 with no redirect. The meta description reads &#x27;Scopri migliaia di offerte di lavoro in Italia in IT, marketing, sanità e altro... con Jobrapido!&#x27;</p>

<p>Caveats: I checked only the landing page metadata.</p>

</details>

<h3>Experteer — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. Experteer&#x27;s Italian site is live and offers job listings and headhunter access for managers in Italy, which fits the Italy section.</p>

<p>https://www.experteer.it/ — HTTP 200. The title is &#x27;Offerte di lavoro e Head hunter per Manager su experteer.it&#x27;. The meta description talks about high-level jobs and access to headhunting and recruiting for managers and executives.</p>

<p>Caveats: Experteer targets senior and executive roles. Some features may need a paid membership, but I didn&#x27;t check that.</p>

</details>

<h3>Experis — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. Experis Italy is live and offers IT job opportunities in Italy, which fits the Italy section.</p>

<p>https://www.experis.it/ — HTTP 200. The title is &#x27;Experis - Soluzioni e offerte di lavoro nel settore IT&#x27;. The meta description says it is a partner for people looking for IT job opportunities.</p>

<p>Caveats: Experis is a ManpowerGroup IT staffing and recruitment brand, not an open job board.</p>

</details>

<h3>Rete Informatica Lavoro — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. Rete Informatica Lavoro is live as an Italian job portal for IT professionals, which fits the Italy section.</p>

<p>https://reteinformaticalavoro.it/ — HTTP 200. The title is &#x27;Portale del lavoro per informatici | Reteinformaticalavoro&#x27;. The meta description mentions job ads for programmers and sysadmins, and CV upload.</p>

<p>Caveats: I checked only the landing page metadata. I didn&#x27;t check how many listings there are or how recent they are.</p>

</details>

<h3>Bulldogjob — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. Bulldogjob is live as a Polish IT job and community platform, which fits the Poland section.</p>

<p>https://bulldogjob.com/ — HTTP 200. The title is &#x27;Bulldogjob - Think IT.&#x27; The meta description reads &#x27;Data. Community. Job. IT jobs that fit you the best!&#x27;</p>

<p>Caveats: I checked only the landing page metadata.</p>

</details>

<h3>Just Join IT — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. Just Join IT is live and lists tens of thousands of jobs, which fits the Poland section.</p>

<p>https://justjoin.it/ — HTTP 200. The title is &#x27;Jobs - 20 255 job offers (November 2026) | Just Join IT&#x27;.</p>

<p>Caveats: I didn&#x27;t check the regional focus in depth. The site is widely known as a Polish IT board, but this check rests on the landing page only.</p>

</details>

<h3>Poland Dev Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site supports every claim in the description. It lists tech jobs in Poland at companies where English is the working language. Jobs come from and are checked against the companies&#x27; own career pages. Visa sponsorship is shown only when the job post or company says so. It fits the Poland section.</p>

<p>https://poland-devjobs.com/ — HTTP 200. The title is &#x27;Poland Dev Jobs: IT &amp; developer jobs for English speakers&#x27;. The homepage shows &#x27;3,569 curated jobs at companies&#x27; where English is the working language, with filters for Visa sponsorship, Apply from abroad, Remote, Junior and Internships. The job-alert signup is free.</p>

<p>https://poland-devjobs.com/about/ — The about page says: &#x27;Jobs come from the career sites of the companies we list&#x27;. It also says: &#x27;We check every job on the company&#x27;s own careers page every day and remove closed jobs.&#x27; On visas: &#x27;We show visa sponsorship or relocation support only when the job post or the company itself says so.&#x27; Jobs that require fluent Polish are excluded.</p>

<p>Caveats: The site has &#x27;Post a job&#x27; and &#x27;Pricing&#x27; pages for employers. The &#x27;Free&#x27; claim refers to job seekers, and I saw no charge for seekers.; The publisher appears to be a &#x27;borderlessdevs&#x27; organization according to the site&#x27;s schema.org metadata. I didn&#x27;t investigate ownership further.</p>

</details>

<h3>noexp.it — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site supports the description. It is a Polish-language site listing IT jobs, internships and placements for people without experience. Listings visibly come from many other boards (justjoin.it, pracuj.pl, rocketjobs.pl, theprotocol.it, jobsbylevel.com and others). Browsing works without logging in. It fits the Poland section.</p>

<p>https://noexp.it/ — HTTP 200. The title is &#x27;Oferty pracy IT dla juniorów bez doświadczenia | noexp.it&#x27;. It shows 1,448 offers labeled with source boards such as justjoin.it, pracuj.pl, rocketjobs.pl, theprotocol.it and jobsbylevel.com. The footer says offers come from external sources and employers, and that noexp.it does not act as a recruiter. Listings load without logging in.</p>

<p>Caveats: The site has an optional &#x27;Zaloguj się&#x27; (log in) link. &#x27;No account&#x27; reads correctly as &#x27;no account needed to browse&#x27;.</p>

</details>

<h3>Jobwinner — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. Jobwinner.ch is live as a Swiss job market covering many fields, which fits the Switzerland section. The listed URL redirects to https://www.jobwinner.ch/en, which is the same site, so no update is needed.</p>

<p>https://www.jobwinner.ch/en — https://jobwinner.ch/en/ redirects here with HTTP 200. The title is &#x27;Jobwinner.ch is an efficient and reliable job market for job seekers with jobs from various fields and industries.&#x27;</p>

<p>Caveats: The redirect only adds &#x27;www&#x27; and drops the trailing slash. Updating the URL to match it would be optional.</p>

</details>

<h3>JobScout24 — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>This is a bare link. JobScout24.ch is live as a Swiss job portal, which fits the Switzerland section.</p>

<p>https://www.jobscout24.ch/en — HTTP 200 with no redirect. The title is &#x27;Jobs in Switzerland Job ads Jobs CH JobScout24.ch&#x27;. The meta description says &#x27;Search and find jobs on the JobScout24.ch job portal&#x27;.</p>

<p>Caveats: I checked only the landing page metadata.</p>

</details>

<h3>SwissAIJob — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The site loads at the listed URL without a redirect and says it lists AI/ML jobs in Switzerland, so it fits the Switzerland section.</p>

<p>https://swissaijob.ch/ — HTTP 200, no redirect. Title: &#x27;SwissAIJob | Every AI Job in Switzerland&#x27;. Meta description: &#x27;Every active AI and ML job in Switzerland, across academia and industry. Scraped from employer sites and updated daily.&#x27;</p>

<p>Caveats: Did not check how complete or fresh the listings are.</p>

</details>

<h3>Statsskuld.se — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The site loads at the listed URL and is a Swedish job board, so it fits the Sweden section.</p>

<p>https://statsskuld.se/lediga-jobb — HTTP 200, no redirect. Title: &#x27;Lediga jobb i Sverige - 31 340 annonser&#x27;. Meta description says users can search current job ads in Sweden and filter by salary, category, region and municipality.</p>

<p>Caveats: The listing count changes over time and is not part of the entry.</p>

</details>

<h3>Arbetsförmedlingen Platsbanken — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The page is Arbetsförmedlingen&#x27;s own Platsbanken job search. Arbetsförmedlingen is Sweden&#x27;s public employment service, so the description is accurate.</p>

<p>https://arbetsformedlingen.se/platsbanken — HTTP 200, no redirect. Title: &#x27;Sök lediga jobb i Platsbanken - Arbetsförmedlingen&#x27;. Meta description says Platsbanken has tens of thousands of open jobs. The site navigation describes Arbetsförmedlingen as a government agency (&#x27;vår myndighet&#x27;).</p>

</details>

<h3>eurojobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The site loads and describes itself as a Europe-wide job board, so it fits Europe Other.</p>

<p>https://eurojobs.com/ — HTTP 200. Title: &#x27;Eurojobs.com | Jobs across Europe&#x27;. The page has &#x27;Featured and Priority Jobs&#x27;, &#x27;Latest Jobs&#x27; and &#x27;Remote Jobs&#x27; sections.</p>

<p>Caveats: The site&#x27;s meta description is an unfilled placeholder (&#x27;ui.phase834_home_meta_description&#x27;), which looks like a cosmetic site bug and doesn&#x27;t affect the entry.</p>

</details>

<h3>eurobrussels — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The site loads and is a job board for EU-affairs jobs in Brussels, which fits Europe Other.</p>

<p>https://www.eurobrussels.com/ — HTTP 200. Title: &#x27;EuroBrussels: Find EU Jobs in Brussels and EU Institutions&#x27;. Meta description mentions EU institutions, agencies, associations, NGOs and internships.</p>

</details>

<h3>Landing.jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The site loads and is a European tech job platform, which fits Europe Other.</p>

<p>https://landing.jobs/ — HTTP 200. Title: &#x27;Find Tech Jobs in Europe | Landing.Jobs&#x27;. Meta description says it connects companies and tech talent.</p>

</details>

<h3>Work in Estonia — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The page lists Estonian job vacancies and is run by Estonia&#x27;s public business agency, which fits Europe Other.</p>

<p>https://workinestonia.com/job/ — HTTP 200. Title: &#x27;Jobs Archive - Work in Estonia&#x27;. Lists jobs such as &#x27;Senior Software Engineer&#x27; and &#x27;Data Warehouse Analyst&#x27;. Says it is managed by the Estonian Business and Innovation Agency.</p>

</details>

<h3>CV Keskus — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The site loads and is a major Estonian job portal, which fits Europe Other.</p>

<p>https://www.cvkeskus.ee/ — HTTP 200. Title: &#x27;CV Keskus – suurim arv tööpakkumisi Eestis&#x27;. Meta description calls it Estonia&#x27;s most popular job portal, with listings in Estonia and abroad.</p>

<p>Caveats: &#x27;Most popular&#x27; is the site&#x27;s own claim; not checked independently.</p>

</details>

<h3>Zalando Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. This is Zalando&#x27;s official careers job search. The URL redirects only to drop the trailing slash. The entry has always been a single company&#x27;s careers page, and nothing found changes that.</p>

<p>https://jobs.zalando.com/en/jobs — https://jobs.zalando.com/en/jobs/ returns HTTP 200 after redirecting to /en/jobs, which is also the page&#x27;s canonical URL. The page shows Zalando Careers branding.</p>

<p>Caveats: The trailing-slash redirect is cosmetic; no URL update needed.; Whether a single company&#x27;s careers page belongs in a job-board list is for the maintainer to decide; the pinned rules don&#x27;t address it.</p>

</details>

<h3>Euro Engineer Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The site loads and is a job board for engineering jobs across Europe, which fits Europe Other.</p>

<p>https://www.euroengineerjobs.com/ — HTTP 200. Title: &#x27;Engineer Jobs in Europe | EuroEngineerJobs&#x27;. Meta description: &#x27;Find engineer jobs across Europe for international and English speaking job seekers.&#x27;</p>

</details>

<h3>No Fluff Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site redirects to its /pl/ locale. Its own text and country lists show it still operates in Poland and Hungary, so &#x27;Poland &amp; Hungary.&#x27; is accurate. It now also covers Czechia, Slovakia and Ukraine and non-IT fields, but the entry doesn&#x27;t claim to be exhaustive.</p>

<p>https://nofluffjobs.com/pl/ — https://nofluffjobs.com/ redirects to /pl/ (HTTP 200). Page text says it is known &#x27;w Polsce, na Węgrzech, w Czechach, na Słowacji, w Ukrainie&#x27;. Its country list includes pl, hu, cz, sk and ua. Title mentions IT, marketing, sales and HR.</p>

<p>Caveats: The maintainer could optionally broaden the description to &#x27;Central &amp; Eastern Europe&#x27;; the current text isn&#x27;t wrong.; The redirect to /pl/ is a locale choice; the root URL is still the right link.</p>

</details>

<h3>Duunitori — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The automated fetch was blocked by a Cloudflare challenge (HTTP 403). An alternate fetch read the page: Duunitori is a Finnish job search engine listing jobs in Finland, so &#x27;Finland.&#x27; is accurate.</p>

<p>https://duunitori.fi/tyopaikat — curl got HTTP 403 with a Cloudflare &#x27;Just a moment...&#x27; page. WebFetch read the content: &#x27;Suomen suurin työnhakukone&#x27; (Finland&#x27;s largest job search engine), with over 16,000 open positions in Finland.</p>

<p>Caveats: Content was read through a summarising fetch tool, not inspected directly.; Automated clients are blocked by a bot challenge; this is not a sign the site is down.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>jobbsafari.no — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site loads and lists vacancies across Norway, so &#x27;Norway.&#x27; is accurate.</p>

<p>https://jobbsafari.no/ledige-stillinger — HTTP 200. Title: &#x27;12 654 ledige stillinger i Norge | Jobbsafari&#x27;. Meta description says it has vacancies across Norway.</p>

</details>

<h3>Finder Switzerland — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The homepage blocked automated fetches (403), but the site&#x27;s own llms.txt calls it a free job search engine for Switzerland that gathers public job ads. It also lists active Swiss vacancies and median salaries and offers a salary_stats tool. That supports every part of the description.</p>

<p>https://ch.finder.work/llms.txt — &#x27;Free international job search engine for Switzerland. Finder aggregates public vacancies ... links job seekers to the original employer posting. Not an employment agency; always free for seekers.&#x27; Lists 168,762 active Swiss vacancies, with median salaries computed from ads that include pay. Its MCP server offers salary_stats(country, profession, city).</p>

<p>https://ch.finder.work/ — curl and WebFetch both got HTTP 403 (bot challenge &#x27;Just a moment...&#x27;). The robots.txt file on the same host returned 200.</p>

<p>Caveats: The homepage HTML could not be read directly; evidence comes from the site&#x27;s official llms.txt on the same host.; Access appears to be bot-filtered or geo-filtered; this is not a sign the site is down.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>jobbland.se — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. curl was blocked by a Cloudflare challenge, but an alternate fetch read the page. Jobbland is a Swedish job site with over 53,000 listings, so it fits the Sweden section. The site says it is moving to the JobbSafari platform, which is listed separately (id 701). Nothing found says Jobbland has shut down.</p>

<p>https://jobbland.se/lediga-jobb — curl got HTTP 403 (Cloudflare challenge). WebFetch read the content: &#x27;din karriärplattform och jobbsökarsajt i Sverige&#x27;, &#x27;53 387 jobb hittades&#x27;. The page says it is part of Duunitori Group and is moving to a new platform called JobbSafari.</p>

<p>https://jobbsafari.se/lediga-jobb — JobbSafari shows the same listing count (53,387), which suggests both sites share one inventory.</p>

<p>Caveats: Once the move to JobbSafari is finished, this entry may duplicate id 701. There is no official redirect or shutdown notice yet, so neither replacing nor removing it is supported now. Worth re-checking later.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>jobbsafari.se — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. curl was blocked by a Cloudflare challenge, but an alternate fetch read the page. JobbSafari is a Swedish job search platform, so it fits the Sweden section.</p>

<p>https://jobbsafari.se/lediga-jobb — curl got HTTP 403 (Cloudflare challenge). WebFetch read the content: a Swedish job platform showing &#x27;53 387 lediga jobb&#x27;, with filters for location, profession and industry.</p>

<p>Caveats: Content was read through a summarising fetch tool.; It appears to share listings with jobbland.se (id 700), which says it is moving to JobbSafari.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Finder Sweden — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The homepage blocked automated fetches (403), but the site&#x27;s own llms.txt calls it a free job search engine for Sweden that gathers public job ads. It also lists active vacancies and median salaries and offers a salary_stats tool. That supports every part of the description.</p>

<p>https://se.finder.work/llms.txt — &#x27;Free international job search engine for Sweden. Finder aggregates public vacancies ... Not an employment agency; always free for seekers.&#x27; Lists 134,189 jobs in Sweden (as of 2026-11-09), with median salaries computed from ads that include pay. Its MCP server offers salary_stats.</p>

<p>https://se.finder.work/sitemap.xml — HTTP 200. The sitemap index shows lastmod 2026-11-10, so the site is active.</p>

<p>Caveats: The homepage HTML could not be read directly (HTTP 403 bot challenge); evidence comes from official files on the same host.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>lovejob — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link resolves to the live lovejob.lt English site (&#x27;Work in Lithuania, work in Europe&#x27;). Identity and reachability confirmed; fits Europe Other.</p>

<p>https://en.lovejob.lt/ — HTTP 200. Title &#x27;WORK IN LITHUANIA, WORK IN EUROPE | lovejob.lt&#x27;; description &#x27;Find new job proposals in Lithuania, Europe and worldwide... Create Your CV and find a job You Love.&#x27;</p>

</details>

<h3>Next Level Jobs EU — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site matches the description: the heading reads &#x27;€100k+ Software Engineering Jobs in Europe&#x27;, with live roles refreshed hourly from company career pages.</p>

<p>https://nextleveljobs.eu/ — HTTP 200. Title &#x27;€100k+ Software Engineer Jobs in Europe&#x27;. Page says &#x27;2,352 live roles. Refreshed every hour from 168+ company career pages.&#x27; Listings are in Dublin, Vienna, London and other cities.</p>

<p>Caveats: Some of today&#x27;s roles are hidden behind a paid Pro plan; the listing does not claim the site is free.</p>

</details>

<h3>Startup Jobs CZ — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link resolves to the live StartupJobs.cz Czech job board. Identity and reachability confirmed; fits Europe Other.</p>

<p>https://www.startupjobs.cz/ — HTTP 200. Title &#x27;Práce, která vás posune vpřed | StartupJobs.cz&#x27;. Czech-language job board.</p>

</details>

<h3>Jobsportal — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Live Finnish job board, which matches the description &#x27;Finland.&#x27;</p>

<p>https://www.jobsportal.fi/ — HTTP 200. Title &#x27;Find Jobs in Finland – Job Portal for English &amp; Remote Roles&#x27;; meta says &#x27;Browse 841 current openings&#x27; in Finland.</p>

</details>

<h3>DefenceJobs.org — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Search results showing the site&#x27;s own pages describe DefenceJobs.org as a platform for defence tech jobs in Europe (title &#x27;Defence tech jobs in Europe&#x27;), with category pages for European defence roles. This matches the description.</p>

<p>https://www.defencejobs.org/ — Direct curl and WebFetch both returned HTTP 403 (Cloudflare &#x27;Just a moment...&#x27; challenge). Search results show the page title &#x27;Defence tech jobs in Europe&#x27;.</p>

<p>https://www.defencejobs.org/jobs/industry/drones-uav — Indexed page &#x27;Drone and UAV jobs in Europe: 520+ open roles&#x27;. Other indexed pages include communications and HR jobs &#x27;in European defence&#x27; and a 2026 career guide.</p>

<p>Caveats: The bot challenge blocked direct reads, so I relied on search-indexed copies of the site&#x27;s own pages. The 403 is bot protection and does not mean the site is down.</p>

</details>

<h3>CEEhire — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>CEEhire is live and serves remote IT jobs for Central &amp; Eastern European talent. It says listings are manually checked, shows real salaries, and states &#x27;No ghost jobs&#x27; in its footer. It now also lists EU companies alongside US/UK ones; the listed US/UK sourcing is still supported, so this is an addition, not a factual error.</p>

<p>https://ceehire.com/ — Meta: &#x27;Verified remote IT jobs from EU, US and UK companies. Every listing is manually checked. Real salaries, real companies. For developers in Poland, Hungary, Czech Republic, Romania and beyond.&#x27; Footer: &#x27;No ghost jobs. just verified remote IT roles from EU &amp; US.&#x27; Listings show salary ranges such as HUF 16–27M/year.</p>

<p>Caveats: Optional clarification: the description could say &#x27;EU/US/UK companies&#x27;, since EU companies are now included.</p>

</details>

<h3>EuroTechJobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>EuroTechJobs is live with software developer and tech jobs across Europe. Its country browse links cover 16 countries (Belgium, Bulgaria, Croatia, Cyprus, France, Germany, Greece, Ireland, Netherlands, Poland, Portugal, Romania, Spain, Sweden, Switzerland, UK) plus a &#x27;multiple countries&#x27; category, consistent with &#x27;16+ European countries&#x27;.</p>

<p>https://www.eurotechjobs.com/ — HTTP 200. Title &#x27;Software developer and tech jobs in Europe | EuroTechJobs&#x27;. /jobs/&lt;country&gt; links for the 16 countries listed plus /jobs/multiple_countries. Developer, embedded and engineering roles.</p>

<p>Caveats: The country count may change; the &#x27;16+&#x27; wording is volatile.</p>

</details>

<h3>Jobly — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Jobly.fi is a live Finnish job board (part of Alma Career), which matches the description &#x27;Finland.&#x27;</p>

<p>https://www.jobly.fi/ — Direct curl returned a Cloudflare 403 challenge, but WebFetch got through: title &#x27;Katso avoimet työpaikat | Jobly.fi&#x27;, tagline &#x27;Löydä parhaista työpaikoista sopivin&#x27;, part of Alma Career, tens of thousands of openings across Finland.</p>

<p>Caveats: Bot protection blocks some automated clients.</p>

</details>

<h3>eububbleJobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>EU Bubble Jobs is live and lists EU affairs jobs in Brussels and EU institutions, which matches the description.</p>

<p>https://eububblejobs.com/ — HTTP 200. Title &#x27;EU Jobs in Brussels &amp; EU Institutions · EU Bubble Jobs&#x27;; meta &#x27;Find EU affairs jobs in Brussels and across EU institutions — policy, advocacy, communications, research, and operations roles.&#x27;</p>

</details>

<h3>France Dev Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>France Dev Jobs is live: tech/developer jobs in France at companies where English is the working language. The about page confirms jobs come from the career sites of listed companies and are checked daily against the company&#x27;s own careers page.</p>

<p>https://francedevjobs.com/ — HTTP 200. Title &#x27;France Dev Jobs: IT &amp; developer jobs for English speakers&#x27;. &#x27;1,982 curated jobs at companies where English is the working language. No French required.&#x27; Updated 10 November 2026.</p>

<p>https://francedevjobs.com/about — &#x27;We check every job on the company&#x27;s own careers page every day and remove closed jobs. Jobs come from the career sites of the companies we list. We only list companies with public evidence that English is used at work.&#x27; Mentions paid placement for employers.</p>

<p>Caveats: I found no explicit statement that the site is free; job listings and alerts are openly accessible without a visible paywall, but &#x27;Free&#x27; (presumably meaning free for job seekers) is unconfirmed.</p>

</details>

<h3>Spain Dev Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Spain Dev Jobs is live: tech/developer jobs in Spain at English-working-language companies. The about page confirms jobs are sourced from and checked daily against employers&#x27; own career sites.</p>

<p>https://spain-devjobs.com/ — HTTP 200. Title &#x27;Spain Dev Jobs: IT &amp; developer jobs for English speakers&#x27;. &#x27;3,014 curated jobs at companies where English is the working language. No Spanish required.&#x27;</p>

<p>https://spain-devjobs.com/about — &#x27;Jobs come from the career sites of the companies we list&#x27;; every job is checked on the company&#x27;s own careers page daily.</p>

<p>Caveats: I found no explicit statement that the site is free; listings are openly browsable, but &#x27;Free&#x27; is unconfirmed.</p>

</details>

<h3>Impjieg — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Impjieg is live as a Malta job board covering iGaming, tech, finance and digital roles. It shows salary where disclosed and work-mode (remote/hybrid/on-site), with employer posting tools. This matches the description; &#x27;transparent salary&#x27; is qualified on-site as &#x27;where available&#x27;.</p>

<p>https://impjieg.work/ — HTTP 200. Title &#x27;Jobs in Malta — Search the Latest Vacancies | Impjieg&#x27;. &#x27;Salary shown where available, clear work-mode, verified profiles where confirmed — Malta&#x27;s tech, iGaming, finance and digital jobs.&#x27; Also covers healthcare, hospitality and other sectors.</p>

<p>Caveats: Salaries are shown only where employers disclose them; the site now also covers non-tech sectors, which is an addition, not an error.</p>

</details>

<h3>Work in Finland — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The pinned snapshot was unavailable, but the live fetch succeeded. Work in Finland&#x27;s English site lists &#x27;1141 English speaking jobs across Finland&#x27; and targets international talent, which matches the description.</p>

<p>https://www.workinfinland.com/en/ — HTTP 200. Title &#x27;Work in Finland&#x27;; meta &#x27;Build your dream career in Finland. Discover job opportunities...&#x27;. Page: &#x27;Open jobs 1141 English speaking jobs across Finland&#x27;, plus events for international talents and residence-permit guidance.</p>

<p>Caveats: The pinned snapshot failed (source snapshot unavailable); this assessment uses a fresh fetch on 2026-11-10.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Secretcv — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. It loads at the listed URL and is an active, nationwide Turkish job-listings page, so it fits the Turkey section.</p>

<p>https://www.secretcv.com/is-ilanlari/ — Fetched 2026-11-10: HTTP 200 with no redirect. The title is &#x27;Güncel İş İlanları 2026 | Türkiye Genelinde İş Fırsatları&#x27; (current job listings across Turkey).</p>

<p>Caveats: Only the listing page was checked. I did not review individual postings.</p>

</details>

<h3>Eleman.net — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. It redirects to the same path without the trailing slash and is an active Turkish job-listings page, so it fits the Turkey section.</p>

<p>https://www.eleman.net/is-ilanlari/ — HTTP 200 after redirecting to https://www.eleman.net/is-ilanlari. The title is &#x27;iş ilanları &amp; En Yeni iş fırsatları | Eleman.net&#x27;.</p>

<p>Caveats: The trailing-slash redirect is cosmetic, so no URL change is needed.</p>

</details>

<h3>Randstad Türkiye — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. This is Randstad&#x27;s official Turkish job-listings page, it is live, and the name matches. It fits the Turkey section.</p>

<p>https://www.randstad.com.tr/is-ilanlari/ — HTTP 200. The title is &#x27;65 iş ilanları &amp; boş pozisyonlar| şimdi başvur | Randstad Türkiye&#x27; (65 job listings and open positions).</p>

<p>Caveats: Randstad is a staffing agency, so the listings are its own and its clients&#x27; roles. The live job count changes over time.</p>

</details>

<h3>Toptalent — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Toptalent.co&#x27;s job-listings page is live and shows current Turkish job and internship postings, so it fits the Turkey section.</p>

<p>https://toptalent.co/is-ilanlari/ — HTTP 200 after redirecting to /is-ilanlari. The page shows &#x27;Toptalent.co Tüm İlanlar&#x27; (all listings), with postings such as Şube Müdürü in Konya and internships at BSH, Turkcell and DÖHLER, each with an apply button and days remaining.</p>

<p>Caveats: The site also offers CV tools, certificates and talent programmes. The listings appear to lean towards early-career roles.</p>

</details>

<h3>Remote Jobs in Dubai — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. RemoteDXB is live and lists remote and work-from-home jobs in the UAE, which matches the name and the UAE section.</p>

<p>https://www.remotedxb.com — HTTP 200 at https://www.remotedxb.com/. The title is &#x27;Remote jobs in the UAE, 3,499 work from home roles - RemoteDXB&#x27;.</p>

<p>Caveats: The job count in the title changes over time. The brand on the site is RemoteDXB, while the catalog name &#x27;Remote Jobs in Dubai&#x27; is descriptive. That is not a factual error.</p>

</details>

<h3>JobXDubai — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. JobXDubai is live. It presents itself as an AI job-search copilot but has a Jobs section with UAE and Saudi listings and sections for employers, so it remains a job board relevant to the UAE.</p>

<p>https://jobxdubai.com — HTTP 200. The title is &#x27;JobXDubai — Get Hired in Dubai with an AI Job-Search Copilot&#x27;. The meta description reads: &#x27;An AI copilot matches you to 29,800+ real jobs in the UAE and Saudi Arabia… Free to start.&#x27; The navigation includes Jobs, Companies, Salaries and For employers.</p>

<p>Caveats: The site is now positioned mainly as an AI copilot with paid tiers and shows many third-party ad banners. A maintainer may want to judge whether it still fits as a &#x27;job board&#x27;. I did not check the job listings in depth.</p>

</details>

<h3>Gulf Dev Jobs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The official About page supports the description&#x27;s core claims. It lists tech jobs in the UAE and the Gulf at companies where English is the working language, takes jobs from employers&#x27; own career sites, and shows visa sponsorship only when the post or company says so. Job seekers can browse and get alerts without paying, and the paid upgrades are for employers.</p>

<p>https://gulfdevjobs.com/about — The page says: &#x27;job board for software engineers and other tech workers who want to work in the UAE &amp; the Gulf without speaking Arabic. Every job is at a company where English is the working language… Jobs come from the career sites of the companies we list… We show visa sponsorship or relocation support only when the job post or the company itself says so.&#x27; The paid upgrades are &#x27;Featured&#x27; labels for employers.</p>

<p>https://gulfdevjobs.com/ — HTTP 200. The page reads &#x27;IT &amp; developer jobs in Dubai, the UAE, Saudi Arabia &amp; the Gulf for expats&#x27;, with about 1,405 curated jobs, a Visa sponsorship filter and listings verified daily.</p>

<p>Caveats: I found no explicit statement that the site is &#x27;free&#x27; for job seekers. I inferred it from open browsing and job alerts that don&#x27;t require payment.; The site is part of the Borderless Devs network. Some listings are engineering roles beyond strictly IT, which is consistent with &#x27;tech jobs&#x27;.</p>

</details>

<h3>VietnamDevs — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. VietnamDevs is live and lists hand-picked tech jobs in Vietnam for English speakers, which fits the Asia section.</p>

<p>https://vietnamdevs.com — HTTP 200. The title is &#x27;VietnamDevs: Tech Jobs for English speakers in Vietnam&#x27;. The page shows &#x27;Hand-picked software developer roles… updated daily&#x27; and 74 current jobs.</p>

</details>

<h3>Loker Dollar — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site confirms it lists remote jobs paid in USD that accept Indonesian applicants. It has an Indonesian interface with Indonesian summaries, and the jobs come from English-language listings. The root URL redirects to /id, which is locale routing.</p>

<p>https://lokerdollar.com — Redirects to https://lokerdollar.com/id with HTTP 200. The page reads &#x27;Loker Remote Gaji Dollar (USD)… Lowongan remote gaji USD yang mau terima orang Indonesia. Dengan ringkasan Bahasa Indonesia&#x27; (remote jobs paid in USD that accept Indonesians, with Indonesian summaries).</p>

<p>Caveats: I did not separately fetch an English-locale page. The &#x27;English&#x27; part of the claim rests on the source postings and the locale structure.</p>

</details>

<h3>RemoteJobs.lat — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site is a remote job board for professionals in Latin America. It now covers non-tech categories such as sales, support and marketing alongside programming, but the description makes no &#x27;only&#x27; claim, so it remains accurate.</p>

<p>https://remotejobs.lat — Redirects to /en with HTTP 200. The title is &#x27;Remote Jobs in LATAM: 1,656 jobs paid in USD today&#x27;. The meta description reads: &#x27;Remote jobs for Latin Americans, paid in USD: programming, design, marketing, support and more.&#x27;</p>

<p>Caveats: The site is broader than tech. A maintainer could optionally reword to &#x27;Remote jobs for Latin American professionals, many in tech&#x27;.</p>

</details>

<h3>Jobberman Nigeria — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. Jobberman redirects to www.jobberman.com and is an active Nigerian job-vacancy board, matching the name and the Africa section.</p>

<p>https://jobberman.com — Redirects to https://www.jobberman.com/ with HTTP 200. The title is &#x27;Find the Right Job Vacancies in Nigeria | Jobberman&#x27;, and the site has job-seeker and employer sections.</p>

<p>Caveats: The www redirect is cosmetic.</p>

</details>

<h3>Wadifa Info — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The site confirms it covers Moroccan public-sector competitive exams (concours), ANAPEC offers and past exam papers, and has Arabic and French versions.</p>

<p>https://www.wadifa-info.com/ — HTTP 200. The Arabic portal is titled &#x27;الوظيفة العمومية بالمغرب 2026&#x27; (public-sector jobs in Morocco 2026). The menu includes &#x27;عروض أنابيك&#x27; (ANAPEC offers) and &#x27;نماذج المباريات + التصحيح&#x27; (past exam papers with corrections). There are links to /fr/ and /fr/offres-emploi-anapec. The meta description mentions over 4,000 past exam papers.</p>

<p>Caveats: The site also lists private-sector jobs and offers career tools.</p>

</details>

<h3>Kariyer.net — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Bare link. The previous fetch failure didn&#x27;t happen this time. Kariyer.net&#x27;s listings page loads and is a major Turkish job board.</p>

<p>https://www.kariyer.net/is-ilanlari/ — HTTP 200 after redirecting to https://www.kariyer.net/is-ilanlari. The title is &#x27;İş İlanları - Güncel İş Fırsatları&#x27; (job listings, current job opportunities).</p>

<p>Caveats: The earlier snapshot error looks transient.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

</details>

The complete research records remain local. This inventory contains all recommendations and unresolved entries from the saved initial review.

[One-entry integration example](https://github.com/bromanko/awesome-job-boards/blob/codex/catalog-inventory-preview/.um/catalog-inventory/checked-example.md). Saved research with real discussion-history and patch checks.
