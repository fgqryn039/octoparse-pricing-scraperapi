# octoparse pricing: What Each Plan Really Costs (Free, Standard, Professional), the Add-On Fees Most Reviews Skip, and When an API Like ScraperAPI Is the Cheaper Route

Octoparse pricing starts at $0 with a free-forever plan (10 tasks, 50,000 rows exported per month, no credit card). Paid plans start at **$119/month for Standard** when billed monthly — dropping to the equivalent of **$69–99/month on annual billing** — with Professional at **$299/month ($249/month billed annually)** and Enterprise on custom quotes. Every paid plan carries a 5-day money-back guarantee.

That's the headline answer. But if you've been researching this for more than ten minutes, you've probably noticed something odd: different sites quote wildly different Octoparse prices — $69, $75, $83, $99, $119 for what sounds like the same Standard plan. Some of that is billing-period confusion. Some of it comes from Octoparse's own pricing page, which currently shows three different numbers for Standard in three different places. And a big chunk of the real cost sits in add-ons (proxies, CAPTCHA solving, done-for-you crawlers) that most pricing summaries never mention.

There's also a question worth asking before you pick any plan: does a no-code visual scraper match how you actually want to work? If you're comfortable with a few lines of Python or a simple HTTP call, an API-based service like **ScraperAPI** starts at $49/month, and its pricing works completely differently — you pay per request, not per seat or per task. This guide walks through both sides with verified numbers.

> **Quick take:** If you want point-and-click scraping with templates and scheduled cloud runs, Octoparse's Standard plan is the entry point, and its free plan is genuinely usable for one-off jobs. If you'd rather wire scraping into your own code and pay only for successful requests, [👉 start ScraperAPI's 7-day free trial (5,000 API credits, no credit card required)](https://www.scraperapi.com/signup?fp_ref=coupons) and test it against your real target sites before committing to anything.

## Octoparse pricing at a glance

Octoparse currently sells four tiers. Here's what its official pricing page shows:

| Plan | Monthly billing | Annual billing | Tasks | Cloud concurrency | Devices |
| --- | --- | --- | --- | --- | --- |
| Free | $0 | $0 | 10 | None (local runs only) | 1 |
| Standard | $119/mo | $1,199/yr (FAQ: from $69/mo) | 100 | Up to 6 cloud processes | 3 |
| Professional | $299/mo | $2,999/yr (card: $249/mo) | 250 | Up to 20 cloud processes | 5 |
| Enterprise | Custom quote | Custom quote | 750+ | 40+ | 5+ |

The free plan is more than a teaser. You get 10 scraping tasks, 1 device, local extraction only, single exports up to 10,000 rows, and a 50,000-row monthly cap, with output to Excel, CSV, JSON, HTML, or XML. For a one-off data pull or a semester project, that may genuinely be all you need — and Octoparse states plainly that the free tier is "free forever with no credit card required."

Standard is where most small teams land. Beyond the free plan's limits you get cloud execution, 500+ pre-built templates, unlimited exports, IP rotation with residential proxies, automatic CAPTCHA solving, task scheduling, and a Data Export API. Professional adds 250 tasks, 20 concurrent cloud processes, cloud task monitoring, direct saves to Google Sheets, Google Drive, Dropbox, and S3, an Advanced API, priority support, and 1-on-1 training. Enterprise is quote-based, with 750+ tasks, 40+ concurrent processes, and a dedicated success manager.

## Why you keep seeing different Octoparse prices

Here's something most ranking articles won't tell you: **Octoparse's own pricing page is internally inconsistent on Standard's price right now**. The plan card shows "$99/MO." The comparison table lists $119 monthly, $299 quarterly, and $1,199 yearly. The FAQ text says paid plans "begin at $69/month for the Standard plan... billed annually with 16% savings versus monthly billing."

Those numbers refer to different billing configurations, so they're not strictly contradictory — but they are confusing, and third-party sites have amplified the mess. Reviews from 2025 quote Standard at $75/month (annual), while articles from late 2026 use $83/month or $69/year-billed. Even the cloud concurrency figure for Standard disagrees with itself on the official page: the comparison table says up to 6 concurrent cloud processes, the FAQ says 3.

The practical takeaway: treat $69–$119/month as the honest range for Standard depending on billing period, expect $249–$299/month for Professional, and **confirm the exact figure on the checkout page before you subscribe**. If a review quotes a single confident number for Octoparse Standard without naming the billing period, it's guessing.

## The add-on costs most Octoparse pricing summaries skip

The subscription price is only part of the bill. Octoparse sells several usage-based add-ons, and depending on your targets they can matter more than the plan tier itself:

- **Residential proxies: $3/GB.** Standard includes residential proxies and IP rotation, but heavy proxy consumption is billed on top.
- **Pay-per-result templates: $0.001–$3 per thousand results** for high-protection sites — you pay only for successful results.
- **CAPTCHA solving: $1–$1.50 per 1,000 solves.**
- **Crawler Setup service: from $399** if you want Octoparse to build the crawler for you.
- **Data Service: from $599** for fully managed extraction.

To soften this, Standard includes $4/month and Professional $9/month of free add-on credit. That covers light usage, but a project leaning hard on residential proxies will blow through it quickly.

On the discount side, Octoparse runs two application-based programs rather than public coupons: a **30% discount for one year for startups** (Octoparse for Startups) and special pricing for students and educators (Octoparse for Universities), both applied for through links on the pricing page. Database export to MySQL, SQL Server, PostgreSQL, and Oracle is supported from paid tiers, with Zapier integration for pushing data into other tools — worth knowing if your pipeline ends somewhere other than a spreadsheet.

One more constraint that shapes value: the free plan only runs tasks **locally** on your machine. Cloud execution — the whole reason many people pay — starts at Standard. And data retention is capped at 30 days on Free, 60 on Standard, 90 on Professional.

## Who Octoparse's pricing fits — and who's paying for features they won't use

Octoparse is a visual, no-code tool: you build scraping workflows in a point-and-click interface, run them on a schedule in the cloud, and export spreadsheets. The pricing ladder maps cleanly onto that profile — free tier for learning and one-offs, Standard for recurring scheduled jobs, Professional once monitoring, cloud storage integrations, and API access become necessary.

Where it gets awkward is the opposite profile. The full scraping API — the thing that lets you call Octoparse from your own code — sits behind the Professional tier at $249–299/month. A developer who just wants "call a scraper from my script" is paying for 250 tasks, 20 cloud processes, and 1-on-1 training they may never touch. That gap between what you need and what the plan bundles is exactly where API-first alternatives enter the picture.

## The API alternative: how ScraperAPI's plans are priced

ScraperAPI takes the opposite approach. There's no visual builder. You send an HTTP request to their endpoint with your target URL, and the service handles proxy rotation, headless browsers, CAPTCHAs, and retries server-side. As their docs put it: "Our service handles all these complexities, allowing you to scrape any page with a simple API call."

Every plan includes the same core capabilities: JavaScript rendering, premium residential and mobile IPs, advanced anti-bot bypassing, auto-parsing, rotating proxy pools, custom sessions and headers, unlimited bandwidth, and a 99.9% uptime guarantee. Higher tiers buy you more credits and concurrency, not locked features.

| Plan | Monthly | Billed annually | Credits/month | Concurrent requests | Get started |
| --- | --- | --- | --- | --- | --- |
| Free | $0 | $0 | 1,000 | 5 | [ Claim free credits](https://www.scraperapi.com/signup?fp_ref=coupons) |
| Hobby | $49 | $44.10/mo | 100,000 | 20 | [ Start 7-day free trial](https://www.scraperapi.com/signup?fp_ref=coupons) |
| Startup | $149 | $134.10/mo | 1,000,000 | 50 | [ Start 7-day free trial](https://www.scraperapi.com/signup?fp_ref=coupons) |
| Business | $299 | $269.10/mo | 3,000,000 | 100 | [ Start 7-day free trial](https://www.scraperapi.com/signup?fp_ref=coupons) |
| Scaling | $475 | $427.50/mo | 5,000,000 | 200 | [ Start 7-day free trial](https://www.scraperapi.com/signup?fp_ref=coupons) |
| Professional | $975 | $877.50/mo | 10,500,000 | 300 | [ Start 7-day free trial](https://www.scraperapi.com/signup?fp_ref=coupons) |
| Advanced | $1,975 | $1,777.50/mo | 21,500,000 | 500 | [ Start 7-day free trial](https://www.scraperapi.com/signup?fp_ref=coupons) |
| Enterprise | Custom | Custom | 22,000,000+ | 500+ | [ Talk to sales](https://www.scraperapi.com/contact-sales/?fp_ref=coupons) |

New accounts get a **7-day free trial with 5,000 API credits, no credit card required**, on top of the permanent free plan — and since every paid tier shares the same feature set, the trial is a faithful preview of whichever tier you land on. Annual billing saves 10% across the board. Official integrations exist for cURL, Python, NodeJS, PHP, Ruby, Java, and DataPipeline, and there's an MCP server for hooking scraping into LLM workflows like Claude.

Two details that matter at the top end: self-serve plans top out around 3M credits/month (Business tier), with anything beyond that going through sales; and if your credits run dry, behavior depends on plan — Hobby through Professional offer opt-in auto-upgrade to the next tier, while Scaling and above support pay-as-you-go at a fixed per-credit rate with a monthly spending cap you set. Requests beyond your concurrency limit simply get a 429 response and aren't billed.

## What an "API credit" actually costs — the part nobody explains

This is the single most useful thing to understand before comparing ScraperAPI's $49 entry price against Octoparse's $119: **a credit is the cost of a standard page request, but your real consumption depends on the target site and the parameters you send.** The published multipliers:

| Request type | Credits per request |
| --- | --- |
| Normal site | 1 |
| E-commerce (Amazon, Walmart, eBay) | 5 |
| SERPs (Google, Bing, incl. subdomains) | 25 |
| LinkedIn | 30 |
| Cloudflare / Datadome / PerimeterX / Akamai bypass | +10 |
| `render=true` (JavaScript rendering) | +10 |
| `premium=true` | +10 |
| `premium` + `render` | 25 |
| `ultra_premium=true` (paid plans only) | +30 |

So scraping 20,000 Amazon product pages costs 100,000 credits — exactly one month of the Hobby plan. Pulling 4,000 Google search results pages costs the same 100,000. Plain HTML from unprotected sites stretches that allocation 25× further than Google scraping would.

Before you commit to any plan, you can check the exact cost of your target URLs three ways: the Domain Multiplier in the dashboard, the API Playground for live testing, or a direct cost-check endpoint (`api.scraperapi.com/account/urlcost`). There's also a `max_cost` parameter to cap what any single request can consume.

The billing rule is explicit: only requests that return a 200 or 404 status code — plus requests you cancel yourself before the 70-second window closes — consume credits. Blocked requests and timeouts don't burn your allowance. Each response also includes an `sa-credit-cost` header so you can audit consumption in real time.

A note on reliability claims, straight from ScraperAPI's own guidance: published scraping success rates across the industry "run 40% to 100%," and they recommend measuring reliability against *your* target sites rather than trusting any vendor's average. That's unusually candid for a vendor, and it's also exactly why the free trial exists — run your real targets through it before paying anyone. If you're weighing the refund-based approach against the trial-based one, [👉 the trial signup takes about a minute and asks for no card](https://www.scraperapi.com/signup?fp_ref=coupons).

## Side by side: which pricing model fits your situation

| Dimension | Octoparse | ScraperAPI |
| --- | --- | --- |
| Starting paid price | $119/mo Standard (monthly billing) | $49/mo Hobby |
| Billing model | Per plan (tasks, cloud processes) | Per request (credits) |
| Entry free tier | 10 tasks, 50K rows/mo, local only | 1,000 credits + 7-day/5,000-credit trial |
| API access | Professional tier only ($249–299/mo) | Every plan, including free |
| Anti-bot handling | Included from Standard | Included in all plans; heavy bypasses cost +10 credits |
| Refund / trial | 5-day money-back, all paid plans | 7-day free trial instead of refund window |
| Skills needed | None (visual builder) | Basic coding |

Two honest observations. First, at $299/month the two products' Professional tiers cost the same — but Octoparse's includes a visual platform and managed infrastructure, while ScraperAPI's includes 3 million credits. Which is "better value" depends entirely on whether you want a platform or raw capacity. Second, a standard-page-heavy workload on ScraperAPI Hobby ($44.10/mo annual) gets you 100,000 requests — comparable in raw page volume to what many Octoparse Standard users extract, at well under half the price, if you're willing to write the fetching loop yourself.

## FAQ

**Is Octoparse's free plan really free?**
Yes. It's free forever with no credit card, including 10 tasks, 1 device, local extraction, and up to 50,000 rows exported per month. The main limits are no cloud runs and capped export volume.

**Does Octoparse have a refund policy, and can I cancel anytime?**
All paid plans carry a 5-day money-back guarantee — email their support within the first 5 days of a subscription for a full refund. Beyond that window, you can cancel your subscription or free trial at any time from your account settings, and PDF invoices for past payments are downloadable from the Plans & payment section of the dashboard (custom invoices with a tax ID require contacting support).

**Are there discounts for startups or students?**
Yes. Octoparse offers a 30% discount for one year through its startup program, plus special pricing for students, educators, and nonprofits. Both require an application through the links on the pricing page — there's no public coupon code.

**How much does Octoparse Standard actually cost?**
Between $69 and $119/month depending on billing period, per the numbers currently shown on Octoparse's own page. Confirm on checkout.

**What does ScraperAPI cost for a small project?**
Nothing to start: 1,000 free credits permanently, plus a 7-day trial with 5,000 credits. The cheapest paid tier is Hobby at $49/month ($44.10 billed annually) for 100,000 credits and 20 concurrent requests.

**Does ScraperAPI charge for failed requests?**
No. Only successful requests (HTTP 200 and 404) and requests you cancel within 70 seconds consume credits. Blocked requests and timeouts don't.

**Which is cheaper, Octoparse or an API scraper?**
For standard web pages and a developer, ScraperAPI Hobby is usually cheaper ($44–49/month vs $69–119). For e-commerce domains (5 credits each) the gap narrows; for Google/LinkedIn scraping at volume (25–30 credits per request) Octoparse's flat subscription can be competitive. Run your own numbers with the cost checker before deciding.

## Picking between them: the short version

Need scheduled, no-code scraping with templates and spreadsheet exports → Octoparse's Standard plan, and use its 5-day refund window as your real evaluation period. Need scraping inside your own code, cron jobs, or an AI agent → start with ScraperAPI's free tier, then [👉 move up to Hobby at $44.10/month billed annually](https://www.scraperapi.com/signup?fp_ref=coupons) once your credit consumption pattern is known. Working at 3M+ credits or 250+ tasks per month? That's sales-quote territory on both sides — [👉 request ScraperAPI's enterprise pricing](https://www.scraperapi.com/contact-sales/?fp_ref=coupons) and compare the custom numbers against Octoparse's Enterprise before signing anything.

One last pre-purchase check either way: write down your three most-scraped domains and your monthly page volume, then price them through the trial tools. Ten minutes of math beats a month of discovering you picked the wrong billing model.
