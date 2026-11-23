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

## Things that broke

| Date | What went wrong | What I tried | What finally fixed it |
|------|-----------------|--------------|-----------------------|
| Nov 23 | No course template repo, so the project-notes files didn't exist | Looked on Moodle for a template link | Created my own repo and made BUSINESS_CASE.md and PROJECT_LOG.md by hand using the headings in the writing guide |
| Nov 23 | Typed my first prompt into the Copilot desktop app, which wasn't linked to my repo | Looked for my project in the app | Opened a Codespace from the repo and used Copilot Chat there instead |

## What a real version would need

| Feature I faked or skipped | Why a real company would need it | How hard / expensive? |
|----------------------------|----------------------------------|-----------------------|
|                            |                                  |                       |

## Reflection

**After session 1 (Nov 23):** The most surprising part of today was how little of my time went into the website itself. Copilot built a full homepage, a second page and the styling from one prompt in about a minute, and GitHub Pages put it online on the first try. Most of my time went into setup instead: creating a GitHub account, figuring out that the Copilot desktop app wasn't connected to my repo, making the project files by hand because I didn't have the template, and learning what "staging" a commit means.

That tells me something about the business side. If someone with no coding background can get a professional-looking site live in an afternoon, then the website gives StreakFree no advantage at all. Any competitor could copy it just as fast. Whatever makes the business hard to copy has to come from outside the site: the crews, the customers on each street, and what we learn from running jobs. I'll test that idea properly in my "Can it be copied?" section.
