# Selenium Test Lab

An interactive, responsive landing page on **Selenium WebDriver features that make automation testing easier**. Instead of reading a wall of text, you run a live test suite, race fixed sleeps against explicit waits, pick locators that survive a redesign and tick off a QA roadmap.

Built with plain HTML, CSS and a little JavaScript. No frameworks, no build step, nothing to install.

## What is inside

**Live test run.** A terminal card that runs a demo Selenium suite. Switch on flaky mode to see what bad timing does to a build, then switch it off to see the fix.

**Eight core feature cards.** Cross browser support, locators, waits, frames and alerts, language choices, the Page Object Model, data driven testing, and API plus mobile testing. Mark each one as learned and watch the progress bar fill. Progress is saved in your browser.

**Wait Lab.** Drag a slider to change how slow the page is, then race a fixed sleep against an explicit wait and see which one fails.

**Locator Lab.** Click any element on a mock login page to see its locators with stability scores, then redesign the page and watch the fragile ones break.

**Six step roadmap.** A simple path from testing basics to interview preparation.

**Learn more section.** Clickable cards for courses and guides, listed below.

## Design notes

The colour palette is taken from the Selenium logo: Selenium green (`#43B02A`), a deep forest green for contrast and a lime accent. Cards use a bold outlined look with chunky shadows, the header is sticky with a blurred background, and the footer has a zigzag edge. The layout is fully responsive, with a menu button on mobile, and animations respect the reduced motion setting.

## Run it locally

1. Download or clone this repository.
2. Open `index.html` in any modern browser.

## Publish with GitHub Pages

1. Push the files to a new repository.
2. Open **Settings**, then **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select the `main` branch and the `/ (root)` folder, then save.
4. After a minute your page will be live at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Links used on the page

Courses:

- [Selenium Training in Hyderabad](https://www.justacademy.co/course-detail/hyderabad/selenium-training-in-hyderabad)
- [JavaScript Training in Hyderabad](https://www.justacademy.co/course-detail/hyderabad/javascript-training-in-hyderabad)
- [Python Training in Hyderabad](https://www.justacademy.co/course-detail/hyderabad/python-training-in-hyderabad)

Guides:

- [Selenium WebDriver Features That Make Automation Testing Easier](https://www.justacademy.co/blog-detail/selenium-webdriver-features-that-make-automation-testing-easier)
- [Selenium WebDriver Interview Questions for Automation Testers](https://www.justacademy.co/blog-detail/selenium-webdriver-interview-questions-for-automation-testers)
- [Selenium Automation Testing Framework: Complete Beginner Guide](https://www.justacademy.co/blog-detail/selenium-automation-testing-framework-complete-beginner-guide)
- [Selenium Automation Testing Roadmap 2026: Skills Required for QA Jobs](https://www.justacademy.co/blog-detail/selenium-automation-testing-roadmap-2026-skills-required-for-qa-jobs)
- [Developer vs Tester Career Comparison: Which IT Role Should You Choose?](https://www.justacademy.co/blog-detail/developer-vs-tester-career-comparison-which-it-role-should-you-choose)

## Customise

All colours live in the `:root` block at the top of the style section in `index.html`. Change the variables there to retheme the whole page. The feature cards, roadmap steps and locator data are plain arrays near the bottom of the script, so you can edit the text without touching the layout.

## Disclaimer

This is an independent learning page and is not affiliated with the Selenium project.
