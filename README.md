# GitHub Profile README — Complete Resource Index

A comprehensive reference for every tool, action, widget, and resource available to build an exceptional GitHub profile README. Organized by category with descriptions of what each tool does and what you can achieve with it.

---

## Table of Contents

- [Stats and Metrics](#stats-and-metrics)
- [Contribution Visualizations](#contribution-visualizations)
- [Dynamic Content Injectors](#dynamic-content-injectors)
- [Badges and Shields](#badges-and-shields)
- [Trophies and Achievements](#trophies-and-achievements)
- [Cards and Summary Widgets](#cards-and-summary-widgets)
- [Coding Activity and Time Tracking](#coding-activity-and-time-tracking)
- [Music and Spotify](#music-and-spotify)
- [Social and Content Feeds](#social-and-content-feeds)
- [Visitor Counters](#visitor-counters)
- [Jokes and Fun Widgets](#jokes-and-fun-widgets)
- [Profile Generators and Builders](#profile-generators-and-builders)
- [Animations and SVG Art](#animations-and-svg-art)
- [Repository Visualizers](#repository-visualizers)
- [Workflow and Automation Helpers](#workflow-and-automation-helpers)
- [Curated Inspiration Lists](#curated-inspiration-lists)

---

## Stats and Metrics

### [lowlighter/metrics](https://github.com/lowlighter/metrics)

The most comprehensive GitHub metrics generator available. Runs as a GitHub Action and produces a fully customizable SVG that you embed in your README. Supports over 30 plugins covering languages, contributions, calendar heatmaps, notable pull requests, followup issues, reactions, achievements, habits, traffic, sponsors, and more. Every section is opt-in and configurable. The output is a single self-contained SVG file committed to your repository.

What you can do:
- Display language breakdown with percentage bars
- Show an isometric 3D contribution calendar for a full year
- Highlight notable pull requests made to major organizations
- Show your most starred and forked repositories
- Display coding habits by time of day and day of week
- Show sponsor information and tiers
- Generate achievement badges based on milestones
- Display reactions to your comments and issues
- Show pagespeed scores for your website
- Embed a world map of your stargazers

Documentation: https://metrics.lecoq.io

---

### [anuraghazra/github-readme-stats](https://github.com/anuraghazra/github-readme-stats)

The most widely used GitHub stats card. Generates SVG cards on demand via a public API — no GitHub Action required, just embed a URL in your README as an image. Supports multiple card types and extensive theme customization via URL parameters.

What you can do:
- Display total stars, commits, PRs, issues, and contribution rank
- Show top languages by repository or by lines of code
- Display a Wakatime coding activity card
- Apply one of 30+ built-in themes or create a fully custom color scheme
- Add a gist stats card
- Control which stats are shown or hidden individually
- Combine multiple cards in a single row using HTML table layout

Live demo and theme preview: https://github.com/anuraghazra/github-readme-stats#themes

---

### [DenverCoder1/github-readme-streak-stats](https://github.com/DenverCoder1/github-readme-streak-stats)

Dedicated contribution streak card. Shows your current streak, longest streak, and total contributions in a compact SVG card served from a public API.

What you can do:
- Display current consecutive day streak
- Show all-time longest streak with date range
- Display total contribution count since account creation
- Choose from dozens of themes or build a custom palette
- Configure date format and timezone
- Hide specific sections of the card

Configurator tool: https://streak-stats.demolab.com/demo/

---

### [vvo/tzdb](https://github.com/nicedoc/awesome-profile-readme)

Not a stats card, but a useful reference when setting timezone-aware metrics. Many metrics tools accept a timezone parameter that affects how daily contribution windows are calculated.

---

## Contribution Visualizations

### [Platane/snk](https://github.com/Platane/snk)

Generates an animated snake that eats your contribution grid dots. The output is either an animated SVG or a GIF. Runs as a GitHub Action on a schedule and commits the output to your repository or a separate branch.

What you can do:
- Create a dark-mode and light-mode version simultaneously
- Control snake color, grid color, and dot colors
- Output as SVG (smaller, scalable) or GIF (broader compatibility)
- Embed in your README with a picture tag to switch between dark and light automatically

---

### [jasonlong/isometric-contributions](https://github.com/jasonlong/isometric-contributions)

A browser extension (Chrome and Firefox) that replaces the standard contribution graph on GitHub with a 3D isometric view. Not embeddable in a README directly, but the lowlighter/metrics isocalendar plugin produces a similar embeddable output.

---

### [2016rshah/githubchart-api](https://github.com/2016rshah/githubchart-api)

API that returns your GitHub contribution chart as a PNG image. Embed with a simple image tag. No setup required.

What you can do:
- Embed a contribution heatmap without any GitHub Action
- Use as a fallback when Actions minutes are limited

---

### [sallar/github-contributions-chart](https://github.com/sallar/github-contributions-chart)

Generates a full contribution graph image covering all years of your GitHub history on a single canvas.

What you can do:
- Download a high-resolution PNG of your entire GitHub contribution history
- Choose between multiple color themes
- Use the hosted version at https://github-contributions.vercel.app without any setup

---

### [ghchart](https://ghchart.rshah.org)

The simplest possible contribution chart embed. A single image URL that returns your contribution graph as an SVG. No token, no action, no configuration needed.

Usage: embed `https://ghchart.rshah.org/yourusername` as an image in your README.

---

## Dynamic Content Injectors

### [JamesIves/github-readme-feed](https://github.com/gautamkrishnar/blog-post-workflow)

Fetches your latest blog or RSS feed entries and injects them into a marked section of your README automatically via a GitHub Action.

What you can do:
- Pull posts from any RSS or Atom feed (Dev.to, Hashnode, Medium, personal blog, YouTube, Reddit, Stack Overflow, and more)
- Control how many items are displayed
- Customize the display format (title only, title with date, title with description)
- Support multiple feed sources simultaneously

---

### [jamesgeorge007/github-activity-readme](https://github.com/jamesgeorge007/github-activity-readme)

Injects your recent GitHub activity (push events, PR reviews, issue comments, etc.) directly into a section of your README.

What you can do:
- Show the last N GitHub events from your public activity feed
- Customize the event display format
- Schedule updates to run hourly or daily

---

### [readme-jokes](https://github.com/ABSphreak/readme-jokes)

Injects a random programming joke into your README via an API image embed or GitHub Action. The joke changes on every page load or on a schedule.

---

### [simonw/simonw](https://github.com/simonw/simonw)

A well-known example of a fully automated README that pulls in blog posts, TIL entries, recent projects, and other dynamic content. Study the source for patterns you can adapt to your own profile.

---

### [lowlighter/readme-42](https://github.com/nicedoc/awesome-profile-readme)

Pattern for injecting 42 School project data. Useful as a reference for how to build custom data injectors for any platform that has an API.

---

### [MikeCodesDotNET/ColoredBadges](https://github.com/MikeCodesDotNET/ColoredBadges)

A large collection of pre-made SVG technology badges covering languages, tools, frameworks, platforms, and IDEs. Download and host the SVGs yourself for full control over appearance.

What you can do:
- Add technology stack badges without depending on an external API
- Use consistent styling across all badges
- Combine with shields.io for live data badges alongside static tech badges

---

## Badges and Shields

### [shields.io](https://shields.io)

The standard badge generation service. Produces SVG and PNG badges for virtually any data source — GitHub stats, npm versions, PyPI versions, license types, build status, custom text, and anything reachable via a JSON API.

What you can do:
- Create live version badges for any package registry (npm, PyPI, crates.io, Maven, NuGet, Hex, RubyGems, and more)
- Display build and CI status from GitHub Actions, Travis, CircleCI, AppVeyor, Jenkins, and others
- Show download counts, open issue counts, PR counts, and stars
- Create custom static badges with any text, color, and logo
- Use social-style badges showing GitHub followers, Twitter followers, and YouTube subscribers
- Add a logo from Simple Icons to any badge

Badge builder: https://shields.io/badges

---

### [Simple Icons](https://simpleicons.org)

A library of over 3000 SVG icons for brands and technologies, designed to be used as logos inside shields.io badges or embedded directly in SVG layouts.

What you can do:
- Find the exact brand color and icon slug for any major technology
- Embed brand icons inside shields.io badges using the `logo=` parameter
- Download SVGs for use in custom layouts

---

### [badge-generator by Ryo-ma](https://michaelcurrin.github.io/badge-generator/)

A visual badge builder tool that generates shields.io markdown for common use cases without needing to know the URL structure manually.

---

### [for-the-badge](https://forthebadge.com)

Produces large, stylized badges for humorous or decorative use. Covers categories like languages used, powered-by claims, and general-purpose statements.

---

### [badgen.net](https://badgen.net)

An alternative to shields.io with a slightly different visual style (no rounded ends by default) and its own set of data providers. Useful as a fallback or for a different aesthetic.

---

## Trophies and Achievements

### [ryo-ma/github-profile-trophy](https://github.com/ryo-ma/github-profile-trophy)

Generates a row of achievement trophies based on your GitHub statistics. Served as an image from a public API — no Action required.

What you can do:
- Display trophies for total stars, followers, commits, pull requests, issues, and reviews
- Choose from multiple themes
- Control how many trophies are shown per row
- Filter to show only trophies above a certain rank (Secret, SSS, SS, S, AAA, AA, A, B, C)
- Hide specific trophy types

---

### [lowlighter/metrics achievements plugin](https://github.com/lowlighter/metrics)

The achievements plugin within lowlighter/metrics generates a different set of milestone-based badges covering things like sponsoring others, having a repository reach certain star counts, making contributions to many different languages, and other behavioral milestones.

---

## Cards and Summary Widgets

### [vn7n24fzkq/github-profile-summary-cards](https://github.com/vn7n24fzkq/github-profile-summary-cards)

Generates a suite of five summary cards as a GitHub Action and commits them to your repository.

What you can do:
- Show commits grouped by time of day (productive time card)
- Show commits broken down by language
- Show commits broken down by repository
- Show a contribution stats summary card
- Display a profile details card with overall stats
- Apply themed color schemes to all cards simultaneously

---

### [anmol098/waka-readme-stats](https://github.com/anmol098/waka-readme-stats)

Injects a richly formatted stats block into your README using data from both GitHub and Wakatime.

What you can do:
- Show a weekly coding breakdown by language, editor, OS, and project
- Display GitHub stats alongside Wakatime data in a unified block
- Show time zones and most productive hours
- Configure which sections appear and in what order
- Support for multiple languages in the display format

---

### [GitHubPoster](https://github.com/yihong0618/GitHubPoster)

Generates poster-style visualizations of your activity across many platforms (GitHub, Strava, Duolingo, Leetcode, Wakatime, Spotify, and more) as SVG images.

What you can do:
- Create a full-year heatmap poster for any supported platform
- Combine data from multiple sources into a single poster
- Export as SVG for embedding or as high-resolution PNG for printing

---

### [github-profile-header-generator](https://github.com/leviarista/github-profile-header-generator)

A web tool for generating a custom header image (PNG or SVG) for your GitHub profile with text, icons, and background styles. No design software required.

---

### [capsule-render](https://github.com/kyechan99/capsule-render)

Generates decorative header and footer SVG images for your README via a simple API URL. Supports animated waves, gradients, cylinders, eggs, sharks, and other shapes with custom text overlaid.

What you can do:
- Create a dynamic animated header with your name or any text
- Apply gradient color combinations across a wide color range
- Choose from multiple shape types for the background
- Add a custom font size, color, and alignment to the text
- Switch between animation types (fadeIn, twinkling, blinking)

API endpoint: https://capsule-render.vercel.app

---

### [readme-typing-svg](https://github.com/DenverCoder1/readme-typing-svg)

Generates an animated SVG that displays a typing animation cycling through a list of phrases you define.

What you can do:
- Animate any list of strings in a typewriter effect
- Control typing speed, pause duration, cursor style, and loop behavior
- Customize font, font size, color, background, and width
- Use the online configurator to preview changes in real time

Configurator: https://readme-typing-svg.demolab.com

---

### [Animated Fluent Emojis](https://github.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis)

A collection of animated versions of Microsoft's Fluent emoji set, provided as GIF and PNG files hosted on GitHub, ready to embed directly in a README.

---

### [Animated-Fluent-Emojis by Tarikul-Islam-Anik](https://github.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis)

Over 1000 animated emojis available as direct image embeds. Use in headers, skill lists, or anywhere a small animated visual element adds personality without requiring an external service.

---

## Coding Activity and Time Tracking

### [Wakatime](https://wakatime.com)

A plugin for all major editors and IDEs that tracks exactly how much time you spend coding, broken down by language, project, file, branch, and editor. The data is accessible via an API and used by multiple README widgets.

What you can do:
- Track coding time automatically in VS Code, JetBrains, Vim, Neovim, Emacs, Sublime, Xcode, and more
- Generate weekly coding stat embeds for your README
- Use the data with anuraghazra/github-readme-stats, anmol098/waka-readme-stats, or lowlighter/metrics
- Set daily coding goals and track streaks

Dashboard: https://wakatime.com/dashboard

---

### [WakaTime Readme](https://github.com/athul/waka-readme)

A GitHub Action that fetches your Wakatime weekly stats and injects them into a marked section of your README as a formatted code block.

What you can do:
- Show hours and minutes per language for the past week
- Show a simple bar-style breakdown
- Schedule updates to run weekly

---

### [cr-mitmit/Profile-Readme-WakaTime](https://github.com/chethanuk-plutoflume/waka-readme)

An alternative Wakatime README injector with slightly different formatting options.

---

## Music and Spotify

### [novatorem/novatorem](https://github.com/novatorem/novatorem)

Displays your currently playing Spotify track in real time as an animated SVG card embedded in your README. Requires deploying a small server (Vercel recommended).

What you can do:
- Show album art, song title, and artist name
- Animate a progress bar while a song is playing
- Fall back gracefully to a "not currently listening" state
- Choose from multiple themes

---

### [kittinan/spotify-github-profile](https://github.com/kittinan/spotify-github-profile)

Another Spotify now-playing widget with different visual styles. Hosted service available so no self-deployment is required.

What you can do:
- Choose from natemoo-re, novatorem, default, and other widget styles
- Display recently played track when nothing is currently playing

Hosted at: https://spotify-github-profile.kittinan.dev

---

### [spotify-recently-played-readme](https://github.com/JeffreyCA/spotify-recently-played-readme)

Displays your most recently played Spotify tracks as a list card rather than a single now-playing widget.

What you can do:
- Show up to 10 recently played tracks with album art
- Display track title and artist
- Self-host on Vercel

---

### [last-fm-readme](https://github.com/nicedoc/awesome-profile-readme)

Similar to the Spotify widgets but using Last.fm as the data source, which works with any music player that scrobbles.

---

## Social and Content Feeds

### [gautamkrishnar/blog-post-workflow](https://github.com/gautamkrishnar/blog-post-workflow)

Pulls recent posts from any RSS or Atom feed and injects them into a section of your README on a schedule.

Supported sources include: Dev.to, Hashnode, Medium, WordPress, Ghost, Blogger, YouTube, Twitch, Reddit, Stack Overflow, Goodreads, Letterboxd, and any standard RSS feed.

What you can do:
- Show latest 5 blog posts with title and link
- Show latest YouTube videos with titles
- Pull from multiple feeds simultaneously
- Customize the display template

---

### [actions/readme-scribe](https://github.com/nicedoc/awesome-profile-readme)

A general-purpose template engine for README generation. Define a template file and inject any data you can fetch via shell commands or API calls.

---

### [twitter-badge](https://github.com/nicedoc/awesome-profile-readme)

Multiple projects exist for embedding a Twitter/X follower count badge or recent tweets into a README. Search GitHub for `twitter readme badge` for current options as API access policies for Twitter/X change frequently.

---

## Visitor Counters

### [visitor-badge](https://github.com/nicedoc/awesome-profile-readme)

Generates a badge that increments a counter each time your README is viewed.

API: https://visitor-badge.laobi.icu

What you can do:
- Display a total page view count
- Optionally show a colored badge with a label

---

### [page-views-counter by antonkomarev](https://github.com/antonkomarev/github-profile-views-counter)

A GitHub Action that stores a view counter in a dedicated file in your repository and displays it as a badge.

What you can do:
- Maintain a persistent view count stored entirely within your own repository
- No dependency on a third-party API

---

### [hits.sh](https://hits.sh)

A simple hit counter service. Generate a badge URL, embed it, and the count increments on each page render.

---

### [komarev.com/ghpvc](https://github.com/antonkomarev/github-profile-views-counter)

API-based profile view counter maintained by Anton Komarev. Widely used and reliable. Generates a badge you embed with a single image tag.

Badge URL pattern: `https://komarev.com/ghpvc/?username=yourusername`

---

## Jokes and Fun Widgets

### [readme-jokes](https://github.com/ABSphreak/readme-jokes)

Embeds a random programming joke into your README as an SVG image. Refreshes on each page load.

What you can do:
- Choose from multiple themes
- Embed via API URL with no setup

API: https://readme-jokes.vercel.app

---

### [ProgrammerHumor.io badge](https://programmerhumor.io)

Static humor badges and meme-style images for adding personality to a README.

---

### [meme-driven-development](https://github.com/nicedoc/awesome-profile-readme)

A reference to the pattern of using reaction GIFs and meme images hosted on GitHub's CDN within README files. Embed any image by dragging it into a GitHub issue editor, then using the generated CDN URL in your README.

---

## Profile Generators and Builders

### [GitHub Profile README Generator](https://rahuldkjain.github.io/gh-profile-readme-generator/)

A visual web form where you fill in your information (name, skills, social links, stats preferences) and it generates a complete README markdown file you can copy and paste.

What you can do:
- Generate a structured README in under a minute
- Select from a checklist of badges and plugins
- Include GitHub stats, streak cards, trophy cards, and visitor counters in one pass
- Download the result as a markdown file

---

### [profile-readme-generator by maurodesouza](https://profile-readme-generator.com)

A drag-and-drop visual editor for GitHub profile READMEs. Add blocks for about sections, skill grids, stats cards, social links, and more without writing markdown manually.

---

### [arturssmirnovs/github-profile-readme-generator](https://arturssmirnovs.github.io/github-profile-readme-generator/)

Another visual generator with a focus on simplicity. Fills in a template with your details and copies the resulting markdown.

---

### [profilinator](https://profilinator.rishav.dev)

A modular README builder that lets you assemble sections independently and preview the output in real time. Strong coverage of skill badge sections.

---

## Animations and SVG Art

### [capsule-render](https://github.com/kyechan99/capsule-render)

Covered above under Cards. Generates animated wave, gradient, and shape headers via a URL parameter API. The most widely used animated header tool.

API docs: https://github.com/kyechan99/capsule-render#types

---

### [readme-typing-svg](https://github.com/DenverCoder1/readme-typing-svg)

Covered above under Cards. The standard tool for animated typewriter text in a README.

---

### [svg-banners](https://github.com/Akshay090/svg-banners)

Generates styled SVG banner images for repository READMEs with gradient backgrounds and tech stack icons.

---

### [custom-icon-badges](https://github.com/DenverCoder1/custom-icon-badges)

Extends shields.io to support custom SVG icons, including Devicons and Octicons, inside standard badge layouts. Useful when the logo you want is not available in Simple Icons.

What you can do:
- Use any Devicon logo inside a shields.io-style badge
- Use any Octicon inside a badge
- Upload a custom SVG icon for a unique badge

---

### [skill-icons](https://github.com/tandpfun/skill-icons)

A collection of clean, consistent technology skill icons served via a single API URL. Pass a comma-separated list of icon names and receive a row of icons as an SVG.

What you can do:
- Display a visual technology stack in one line
- Choose between light and dark icon variants
- Control icon size and padding
- Display icons in a themed grid layout

API: https://skillicons.dev

---

### [devicons](https://devicons.github.io/devicon/)

A comprehensive icon set covering programming languages, frameworks, and developer tools, available as SVG files and a CDN-hosted font. Used in many badge and skill icon generators.

CDN: https://cdn.jsdelivr.net/gh/devicons/devicon/icons/

---

### [3D Contribution Calendar](https://github.com/nicedoc/awesome-profile-readme)

Several community projects generate a 3D rendered version of your contribution calendar as a video or GIF. Search GitHub for `3d contribution graph` for current maintained forks.

---

## Repository Visualizers

### [githubocto/repo-visualizer](https://github.com/githubocto/repo-visualizer)

A GitHub Action developed by GitHub's own octo team that generates a bubble chart visualization of your repository's file and directory structure. Each file is a circle sized by file size and colored by file type.

What you can do:
- Generate a `diagram.svg` on every push to your main branch
- Embed the visualization in your repository README
- Track how your codebase structure evolves over time
- Exclude specific directories (like `node_modules`) from the diagram

---

### [code-complexity](https://github.com/nicedoc/awesome-profile-readme)

Various tools for generating code complexity visualizations exist as GitHub Actions or CLI tools. Search for `code complexity visualization github action` for current options.

---

### [linguist](https://github.com/github-linguist/linguist)

The library GitHub itself uses to detect languages and generate the repository language bar. Understanding how it works lets you control which files are counted by adding a `.gitattributes` file to your repository.

What you can do:
- Mark generated files so they are excluded from language stats
- Mark vendor files to exclude third-party code from your stats
- Override language detection for files with ambiguous extensions
- This directly affects what lowlighter/metrics and github-readme-stats show for your languages

---

## Workflow and Automation Helpers

### [actions/checkout](https://github.com/actions/checkout)

The standard action for checking out your repository code in a workflow. Required by most profile README automation workflows that need to commit generated files back to the repository.

---

### [stefanzweifel/git-auto-commit-action](https://github.com/stefanzweifel/git-auto-commit-action)

Automatically commits and pushes any changed files in a GitHub Actions workflow. Used by many profile README generators to commit the updated SVG or markdown files after generation.

What you can do:
- Commit generated files with a custom commit message
- Push to any branch
- Skip the commit if no files changed (prevents empty commits)
- Sign commits automatically

---

### [EndBug/add-and-commit](https://github.com/EndBug/add-and-commit)

An alternative to the above with additional options for controlling which files are staged and how the commit is authored.

---

### [actions/cache](https://github.com/actions/cache)

Caches dependencies between workflow runs to speed up scheduled jobs. Useful when your metrics workflow installs tools or dependencies that do not change between runs.

---

### [peaceiris/actions-gh-pages](https://github.com/peaceiris/actions-gh-pages)

Deploys files to a `gh-pages` branch. Useful if you want to publish your metrics or profile assets to GitHub Pages rather than committing them directly to your repository root.

---

## Curated Inspiration Lists

### [abhisheknaiidu/awesome-github-profile-readme](https://github.com/abhisheknaiidu/awesome-github-profile-readme)

The most comprehensive curated list of impressive GitHub profile READMEs. Organized by category (animations, minimalist, descriptive, elaborate, etc.). Hundreds of real examples with links to the source repositories so you can study how they are built.

---

### [nicedoc/awesome-profile-readme](https://github.com/nicedoc/awesome-profile-readme)

Another curated collection focused on tools, generators, and tutorials in addition to example profiles.

---

### [durgeshsamariya/awesome-github-profile-readme-templates](https://github.com/durgeshsamariya/awesome-github-profile-readme-templates)

A collection of ready-to-use README templates. Fork, fill in your details, and you have a complete profile immediately.

---

### [elangosundar/awesome-README-templates](https://github.com/elangosundar/awesome-README-templates)

Templates organized by style and purpose. Good starting point if you want a structured template to customize rather than building from scratch.

---

### [matiassingers/awesome-readme](https://github.com/matiassingers/awesome-readme)

Focuses specifically on repository READMEs rather than profile READMEs, but contains valuable examples of structure, documentation quality, and visual presentation that apply to both contexts.

---

### [GitHub Profile README Examples](https://zzetao.github.io/awesome-github-profile/)

A visual gallery of profile READMEs with live previews and links to source repositories. Browsable by category.

---

## Reference

### [GitHub Markdown Reference](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

The official GitHub documentation for markdown syntax supported in READMEs, including alerts, tables, code blocks, task lists, footnotes, and collapsed sections using `<details>`.

---

### [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)

The full specification for GitHub Flavored Markdown. Useful for understanding edge cases in table rendering, HTML embedding, and link handling.

---

### [HTML in GitHub Markdown](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-collapsed-sections)

GitHub allows a subset of HTML tags inside markdown. Supported tags include `<details>`, `<summary>`, `<picture>`, `<table>`, `<kbd>`, `<sub>`, `<sup>`, `<br>`, `<div>`, and `<img>` with limited attribute support. Understanding which attributes are allowed (and which are stripped) is essential for building complex multi-column layouts and dark/light mode image switching.

---

### [GitHub Actions Documentation](https://docs.github.com/en/actions)

The authoritative reference for writing and debugging the workflow YAML files that power all scheduled README updates.

---

### [Cron Syntax Reference](https://crontab.guru)

An interactive tool for building and verifying cron expressions used in GitHub Actions `schedule` triggers. GitHub Actions uses UTC for all cron schedules.

---
