# Project Log

**Name:** Dylan Butts
**Startup name:** StreakFree
**Live site:** https://dylanbutts.github.io/ai-to-startup/

## Work sessions

### Session -- Nov 23 -- driver: Dylan

- Goal for this session: set up GitHub, create the repo, and get a first version of the homepage live on GitHub Pages
- Key prompts I gave Copilot:
  1. "Create a website for a fictional startup called StreakFree that lets homeowners on the same street group-book exterior house washing. Neighbours who book the same day get a lower price because the crew saves travel time. Make an index.html homepage with a short headline, a "How it works" section with 3 steps, and a button that goes to a "Your street" page (street.html, just a placeholder for now). Put the styles in style.css. Use plain HTML, CSS and JavaScript only, with no external libraries, fonts or CDN links. Make it look good on a phone. Add a footer on every page saying "Student prototype for BSAD 281 at StFX. Not a real business.""
- What worked: Copilot built index.html, street.html and style.css in one go, and the site went live on GitHub Pages on the first try
- What broke, and how I fixed it: I first typed my prompt into the GitHub Copilot desktop app, which wasn't connected to any repo, so I switched to Copilot Chat inside a Codespace. My first commit failed with "no staged changes"; I clicked "Always" to stage and commit everything. I also checked index.html and style.css for external links (none found).
- Committed? yes -- "First homepage and street page"

  ### Session -- Nov 23 (session 2) -- driver: Dylan

- Goal for this session: build an interactive "Your street" page that shows the network effect, with the price per home dropping as more neighbours join
- Key prompts I gave Copilot:
  1. "Turn street.html into an interactive "Your street" page for StreakFree. Show a fictional street called Maple Ridge Drive with 12 houses drawn as simple cards. Some houses have already joined this month's wash day (start with 3). The visitor can click a house to mark it as joined or not joined, and there's an "Invite a neighbour" button that adds one more joined house. As more houses join, update the price per home in tiers ($240 alone, $210 at 3, $185 at 5, $165 at 8, $150 at 10+), a progress bar to the next price drop, crew travel time saved, total savings for the street, and a message like "2 more neighbours and everyone saves another $25". Plain HTML, CSS and JavaScript only, no external libraries, match style.css, work on a phone, keep the student prototype footer."
- What worked: [what worked when you tested it, e.g. clicking houses changed the price at the right tiers]
- What broke, and how I fixed it: My Codespace didn't have PROJECT_LOG.md because I created it on github.com; I ran "git pull" in the terminal to bring it down. [Add anything that broke while testing the street page, or write "Nothing else broke"]
- Committed? yes -- "Added interactive Your street page"

- ### Session -- Nov 23 (session 3) -- driver: Dylan

- Goal for this session: add a crew dashboard showing the crew side of the business and the data StreakFree collects, then do a polish pass
- Key prompts I gave Copilot:
  1. "Add a new page, crews.html, called "Crew dashboard." It shows a fictional StreakFree crew's week using realistic fake data... comparing a "scattered bookings" week with a "grouped bookings" week..."
  2. "Check every page for broken links, buttons that don't do anything, leftover placeholder text, and anything that doesn't fit on a phone screen. List what you find before changing anything." then "Fix those"
  3. "On crews.html, all the bar charts show only the empty grey track... Make each bar fill to a width proportional to its value. Use the same scale for both weeks..."
  4. "The bars on crews.html are still showing as empty grey tracks on the live site... explain why it isn't showing, and fix only that."
- What worked: the dashboard data and layout, and the side-by-side comparison of scattered vs grouped weeks. [anything the polish pass fixed]
- What broke, and how I fixed it: the dashboard first showed up as plain unstyled text. Then the bar charts showed only empty grey tracks, and my first fix didn't work. Copilot also sat waiting on "confirmations pending" until I approved them. I fixed the bars by describing exactly what I saw and asking Copilot to explain the cause. [the reason Copilot gave]
- Committed? yes -- "Added crew dashboard and polish fixes", "Fixed empty bar charts on crew dashboard", "Fixed bar fill on crew dashboard"

- ### Session -- Nov 24 (session 4)-- driver: Dylan

- Goal for this session: draft business case sections 1–3 (the idea, where IT creates value, network effects)
- Key prompts I gave AI:
  1. Asked Claude to give me key ideas on sections 1–3 from my business idea, my prototype and my experience running a house washing business 
  2. I made sure that operations and marketing and sales were apart of the value chain
  3. Uploaded the Network Effects lecture slides and Gallaugher chapter 10 and asked whether section 3 matched the course terms
- What worked: the key points followed the guide's structure, and checking it against the lecture slides showed which course terms to use (one-sided market, same-side exchange benefits, congestion effect, seeding the market, subsidizing adoption)
- What I changed when checking the draft: raised the solo price to $350 to match what I actually charge, widened the customer to cities and towns in Nova Scotia, and added that crews lose time setting up their gear at every scattered job. 
- What broke, and how I fixed it: my edits made the prices inconsistent ($350 alone in section 1, $240 alone in section 3). I fixed it by explaining how other business's like mine would charge $350, the base price for this website is only $240
- Committed? yes -- "Drafted business case sections 1-3"

### Session 5 -- Nov 25 -- driver: Dylan

- Goal for this session: finish the business case by drafting sections 4–6 (can it be copied, cloud and operations, risks and ethics) and add the AI use line
- Key prompts I gave AI:
  1. Asked Claude to draft sections 4–6 from my business, my prototype and the course concepts (VRIN, staying power, switching costs, SaaS/PaaS/IaaS)
  2. Asked Claude for an AI use line that honestly describes how I used AI on the business case
- What worked: the moat section tests three resources against VRIN (my existing customers, street-level booking data, and equipment), and is honest that equipment fails VRIN and that switching costs are low
- What I changed when checking the draft: filled in my real number of customers, repeat customers and equipment. [Add anything else you changed]
- What broke, and how I fixed it: nothing broke on the site this session. [If you fixed the price mismatch between the business case and the street page, say how here]
- Committed? yes -- "Drafted business case sections 4-6"  

## Things that broke

| Date | What went wrong | What I tried | What finally fixed it |
|------|-----------------|--------------|-----------------------|
| Nov 23 | No course template repo, so the project-notes files didn't exist | Looked on Moodle for a template link | Created my own repo and made BUSINESS_CASE.md and PROJECT_LOG.md by hand using the headings in the writing guide |
| Nov 23 | Typed my first prompt into the Copilot desktop app, which wasn't linked to my repo | Looked for my project in the app | Opened a Codespace from the repo and used Copilot Chat there instead |
| Nov 23 | Codespace was missing PROJECT_LOG.md after I created it on github.com | Looked for the file in the Explorer | Ran "git pull" in the terminal to sync, and turned on automatic git fetch |
| Nov 23 | Crew dashboard showed as plain unstyled text | Hard refresh | Asked Copilot to add the missing styles for crews.html |
| Nov 23 | Bar charts showed empty grey tracks with no fill | Asked Copilot to fix the bars; first fix didn't work | Asked Copilot to explain why the fill wasn't showing, then fix only that |

## What a real version would need

| Feature I faked or skipped | Why a real company would need it | How hard / expensive? |
|----------------------------|----------------------------------|-----------------------|
| Real accounts and logins | Each homeowner needs their own account to book, see their street and manage their visit; crews need a separate login to see their schedule | Medium: a login service (SaaS), roughly free at first and a few hundred dollars a month at scale |
| Shared booking database | On the "Your street" page, clicking a house only changes it in my own browser; real neighbours need to see each other's bookings live so the price drops for everyone | Medium: a hosted database (PaaS) plus a developer to connect it, about $25–100/month to start |
| Real address and street matching | The prototype uses a made-up street with 12 fake houses; a real version has to check that people actually live on the same street before giving them the group price | Medium: a mapping/address API (SaaS) charged per lookup |
| Online payments | Right now nobody pays; a real version needs to take payment at booking, and charge the right tier once the street's final count is known | Medium: a payment processor (SaaS) taking about 3% of each job, plus work to handle refunds and price changes |
| Real neighbour invites | The "Invite a neighbour" button just adds a fake house; a real one would send a text or email invite with a sign-up link | Low to medium: a texting/email service (SaaS), a few cents per message |
| Crew scheduling from real data | The Crew dashboard uses invented numbers; a real version would build each crew's route from actual bookings and track real driving and washing times | High: custom software or a route-planning service, plus my time making sure it matches how crews really work |
| Privacy controls and support | Neighbours could see who on their street booked; a real company needs privacy settings, a privacy policy and a way for customers to cancel or complain | Medium: staff time, a support inbox, and legal help with the privacy policy |

## Reflection

**After session 1 (Nov 23):** The most surprising part of today was how little of my time went into the website itself. Copilot built a full homepage, a second page and the styling from one prompt in about a minute, and GitHub Pages put it online on the first try. Most of my time went into setup instead: creating a GitHub account, figuring out that the Copilot desktop app wasn't connected to my repo, making the project files by hand because I didn't have the template, and learning what "staging" a commit means.

That tells me something about the business side. If someone with no coding background can get a professional-looking site live in an afternoon, then the website gives StreakFree no advantage at all. Any competitor could copy it just as fast. Whatever makes the business hard to copy has to come from outside the site: the crews, the customers on each street, and what we learn from running jobs. I'll test that idea properly in my "Can it be copied?" section.
