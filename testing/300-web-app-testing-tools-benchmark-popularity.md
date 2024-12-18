# Popularity of the 5 web-app. testing tools

- [Popularity of the 5 web-app. testing tools](#popularity-of-the-5-web-app-testing-tools)
  - [Introduction](#introduction)
  - [Methodology](#methodology)
  - [Summary](#summary)
  - [Trend on the NPM packages](#trend-on-the-npm-packages)
    - [Evolution compared to last year](#evolution-compared-to-last-year)
    - [NPM trend - graphs](#npm-trend---graphs)
  - [Trend on GitHub](#trend-on-github)
    - [👨‍💻 Number of contributors](#-number-of-contributors)
    - [⭐ Number of Stars on GitHub](#-number-of-stars-on-github)
      - ["Aligned timeline" view](#aligned-timeline-view)
      - ["by date" view](#by-date-view)
  - [Trend on Google Search](#trend-on-google-search)


## Introduction

In this section of "Benchmark of web-applications testing tools" article, we will compare **popularity** of the 5 tools chosen [above](../300-web-app-testing-tools-benchmark.html):

1. [Cypress.io](https://cypress.io/)
2. [Nightwatch.js](https://nightwatchjs.org)
3. [Playwright](https://playwright.dev/)
4. [Selenium WebDriver](https://www.selenium.dev/documentation/webdriver/)
5. [WebdriverIO](https://webdriver.io/)

## Methodology

We will use several indicators to compare the popularity of those tools:
- number of weekly downloads on NPM
- number of stars on GitHub
- interest over time on Google Search

## Summary

The table below gives you an overview of the relative popularity of these 5 tools, with a few indicators and their evolution:

[![](../img/300/2023-relative-popularity-opensource-webapp-testing-tools-summary.png)](../img/300/2023-relative-popularity-opensource-webapp-testing-tools-summary.png)

## Trend on the NPM packages

The Node.js versions of those tools are available as NPM packages. 

On [npm](https://www.npmjs.com) Registry, and for each package, we can take the **number of weekly downloads** as an indicator of their popularity.

As for 17/12/2023, we have, for each package, on last 7 days:

|                            |  **Cypress.io** <br/> ![](../img/icons/cy-48.png)  |   **Nightwatch.js** <br/> ![](../img/icons/nw-48.png)    |        **Playwright Test** <br/>  ![](../img/icons/pw-48.png)        |            **Selenium**  <br/>   ![](../img/icons/se-48.png)             |    **WebdriverIO**  <br/>   ![](../img/icons/wd-48.png)    |
| -------------------------- | :------------------------------------------------: | :------------------------------------------------------: | :------------------------------------------------------------------: | :----------------------------------------------------------------------: | :--------------------------------------------------------: |
| package name/url           | [`cypress`](https://www.npmjs.com/package/cypress) | [`nightwatch`](https://www.npmjs.com/package/nightwatch) | [`@playwright/test`](https://www.npmjs.com/package/@playwright/test) | [`selenium-webdriver`](https://www.npmjs.com/package/selenium-webdriver) | [`webdriverio`](https://www.npmjs.com/package/webdriverio) |
| number of weekly downloads |                     `5197350`                      |                         `142971`                         |                              `2779815`                               |                                `1726049`                                 |                         `1142691`                          |

- The most downloaded packages seems to be `cypress` framework, with more than 5 millions weekly downloads.
- It's followed by `@playwright/test` framework with more than 2 millions weekly downloads.
- The `selenium-webdriver` library is the third most downloaded package, with more than 1.7 millions weekly downloads.
- The `webdriverio` testing framework is the fourth most downloaded package, with more than 1.1 millions weekly downloads.
- While `nightwatch` framework is the less downloaded package, with less than 150k weekly downloads.

Thats good, but we can have a better view of the popularity of each tool, by comparing them on the same graph. And see progression over time.

This was made with data from [`npm trends` (www.npmtrends.com)](https://www.npmtrends.com/@playwright/test-vs-cypress-vs-nightwatch-vs-selenium-webdriver-vs-webdriverio).
On this site, we can see the popularity of each tool, by number of weekly downloads from NPM, with different time ranges. 

Before looking at graphs, let's see the evolution of each tool, compared to last year.

### Evolution compared to last year 


Comparing downloads on last 7 days, between july 2022 and july 2023:

|                             | package name         | 3 july 2022 |     | 1 july 2023 | evolution |
| --------------------------- | -------------------- | ----------: | --- | ----------: | --------: |
| ![](../img/icons/cy-48.png) | `cypress`            |   `3673636` | →   |   `4865643` |      +32% |
| ![](../img/icons/nw-48.png) | `nightwatch`         |    `171522` | →   |    `179653` |       +2% |
| ![](../img/icons/pw-48.png) | `@playwright/test`   |    `629646` | →   |   `2140160` | **+240%** |
| ![](../img/icons/se-48.png) | `selenium-webdriver` |   `2395860` | →   |   `2013031` |      -22% |
| ![](../img/icons/wd-48.png) | `webdriverio`        |    `924956` | →   |   `1141885` |      +23% |



 
We can see in the graphs below:
- **"`Cypress`" is still the most popular** framework, and keep growning.
- the **rapid rise of the "`Playwright`"** framework, since 2022.
- a slight decline in "`selenium-webdriver`" librairy weekly downloads, since beginning of 2023.
- `WebdriverIO` seems to be less popular than the 3 others, but its usage keeps growing.
- Usage of "`Nightwatch`" seems to be stable, but its the less popular of the 5.

### NPM trend - graphs

Graphs copied from [npm trends](https://www.npmtrends.com/@playwright/test-vs-cypress-vs-nightwatch-vs-selenium-webdriver-vs-webdriverio) the 11/11/2024:

| period | npm trend graph  |
| - | - |
| over the past year | ![1 Year](../img/300/npm-trends-playwrighttest.cypress.nightwatch.selenium-webdriver.webdriverio-1_year.png) | 
| over the past 2 years | ![2 Years](../img/300/npm-trends-playwrighttest.cypress.nightwatch.selenium-webdriver.webdriverio-2_years.png) | 
| over the past 5 years | ![5 Years](../img/300/npm-trends-playwrighttest.cypress.nightwatch.selenium-webdriver.webdriverio-5_years.png) | 
| since beginning | ![All time](../img/300/npm-trends-playwrighttest.cypress.nightwatch.selenium-webdriver.webdriverio-all_time.png) | 

## Trend on GitHub

Each of those "open-source" tools is hosted on a GitHub repository.

Like for all GitHub repositories, we can take several indicators as an indicator of their popularity: 
- how people are interested in the project,
- how many people contribute to the project,
- how many people use the project, etc.

List of repositories:

 | Tool          | GitHub repository name                                                                         |
 | ------------- | ---------------------------------------------------------------------------------------------- |
 | Cypress.io    | https://github.com/**[`cypress-io/cypress`](https://github.com/cypress-io/cypress)**           |
 | Nightwatch.js | https://github.com/**[`nightwatchjs/nightwatch`](https://github.com/nightwatchjs/nightwatch)** |
 | Playwright    | https://github.com/**[`microsoft/playwright`](https://github.com/microsoft/playwright)**       |
 | Selenium      | https://github.com/**[`SeleniumHQ/selenium`](https://github.com/SeleniumHQ/selenium)**         |
 | WebdriverIO   | https://github.com/**[`webdriverio/webdriverio`](https://github.com/webdriverio/webdriverio)** |

There are several ways to compare the popularity of those tools on GitHub :

| indicator                               | meaning                                                                           |
| --------------------------------------- | --------------------------------------------------------------------------------- |
| number of **stars**                     | how many people "starred/bookmarked" the repository                               |
| number of forks                         | how many people "forked" the repository as a starting point for their own project |
| number of watchers                      | how many people "watch" the repository, to be notified of new commits             |
| number of **contributors**              | how many people contributed to the project                                        |
| number of commits and/or  pull requests | the activity made on the project                                                  |
| number of issues                        | how many issues were opened on the project                                        |
| number of dependents projects           | how many projects depends on this project                                         |


### 👨‍💻 Number of contributors

We can take the **number of contributors** as an indicator of their popularity.

Please note that contributors can be:
- either **human** or **robots** (like [Dependabot](https://github.com/dependabot), [GitHub Actions](https://github.com/features/actions) or other specific bots),
- for humans: **paid** by the company that maintains or sponsors the tool, or **volunteer** members of the opensource community
- that contribute to the code and/or to the documentation

Comparison of number of contributors on GitHub (december 2023):

|                        |       **Cypress.io** <br/> ![](../img/icons/cy-48.png)        |           **Nightwatch.js** <br/> ![](../img/icons/nw-48.png)           |      **Playwright Test** <br/>  ![](../img/icons/pw-48.png)       |        **Selenium**  <br/>   ![](../img/icons/se-48.png)        |          **WebdriverIO**  <br/>   ![](../img/icons/wd-48.png)           |
| ---------------------- | :-----------------------------------------------------------: | :---------------------------------------------------------------------: | :---------------------------------------------------------------: | :-------------------------------------------------------------: | :---------------------------------------------------------------------: |
| GitHub repository      | [`cypress-io/cypress`](https://github.com/cypress-io/cypress) | [`nightwatchjs/nightwatch`](https://github.com/nightwatchjs/nightwatch) | [`microsoft/playwright`](https://github.com/microsoft/playwright) | [`SeleniumHQ/selenium`](https://github.com/SeleniumHQ/selenium) | [`webdriverio/webdriverio`](https://github.com/webdriverio/webdriverio) |
| Number of contributors |                              464                              |                                   122                                   |                                488                                |                               726                               |                                   522                                   |


Note on top contributors, for each tool, in last 12 months (Jan 1, 2022 – Dec 25, 2023):

- Cypress.io : Naturaly, the [top contributors](https://github.com/cypress-io/cypress/graphs/contributors?from=2022-01-01&to=2023-12-25&type=c) are from Cypress.io (the company behind Cypress)
- For  Nightwatch.js : [main contributors](https://github.com/nightwatchjs/nightwatch/graphs/contributors?from=2022-01-01&to=2023-12-25&type=c) works at [BrowserStack](https://www.browserstack.com/), the company that supports Nightwatch.
- WebdriverIO : [Christian Bromann](https://github.com/christian-bromann/christian-bromann), previously at Sauce Labs, now at Ionic is the [main contributor](https://github.com/webdriverio/webdriverio/graphs/contributors?from=2022-01-01&to=2023-12-25&type=c).
- Playwright : The [5 top contributors](https://github.com/microsoft/playwright/graphs/contributors?from=2022-01-01&to=2023-12-25&type=c) are from **Microsoft**, and between them 4 worked at Google (on Chrome/DevTools) until 2019 and then at full-time on the Playwright project since its beginning (2019).
- For Selenium, its more difficult to say who are the [top contributors](https://github.com/SeleniumHQ/selenium/graphs/contributors?from=2022-01-01&to=2023-12-25&type=c) for the Node.js version, as Selenium project is a "umbrella project" that cover several languages and tools.


### ⭐ Number of Stars on GitHub

We can take the **number of stars** as an indicator of their popularity.

Allmost all those tools has more than 10k stars on GitHub. Some more quickly than others...

Comparison of number of stars on GitHub (december 2023):

| Tool          | Number of stars on GitHub | + 5k stars in... | + 10k stars in... |
| ------------- | ------------------------: | ---------------- | ----------------- |
| Cypress.io    |                     45401 | 3 years          | 4 years           |
| Nightwatch.js |                     11507 | 3 years          | 8 years           |
| Playwright    |                     57606 | 1 month          | 4 months          |
| Selenium      |                     28459 | 4 years          | 6 years           |
| WebdriverIO   |                      8433 | 8 years          | not yet...        |

#### "Aligned timeline" view

The "aligned timeline" view indicates how many "stars" each tool has, after N years of existence.
>
> [![Star History Chart - aligned timeline view](https://api.star-history.com/svg?repos=microsoft/playwright,SeleniumHQ/selenium,cypress-io/cypress,nightwatchjs/nightwatch,webdriverio/webdriverio&type=Timeline)](https://star-history.com/#microsoft/playwright&SeleniumHQ/selenium&cypress-io/cypress&nightwatchjs/nightwatch&webdriverio/webdriverio&Timeline)

#### "by date" view

The "by date" view gives how many "stars" each tool has, at a given date.

> [![Star History Chart - by dates view](https://api.star-history.com/svg?repos=microsoft/playwright,SeleniumHQ/selenium,cypress-io/cypress,nightwatchjs/nightwatch,webdriverio/webdriverio&type=Date)](https://star-history.com/#microsoft/playwright&SeleniumHQ/selenium&cypress-io/cypress&nightwatchjs/nightwatch&webdriverio/webdriverio&Date) 

## Trend on Google Search

Google offers "Google Trends" as a data exploration tool that shows what terms people are searching for on Google (search engine) in real time.

It can be used to measure the search interest in a particular topic, location, or language at a particular time.

We can use it to compare the popularity of each tool. 

For this, Google Trends offers a "interest over time" metric, that shows the popularity of a search term over time.  "_Interest over time_" number is defined by Google by: 
  > Numbers represent search interest relative to the highest point on the chart for the given region and time.
  > - a value of 100 is the peak popularity for the term. 
  > - a value of 50 means that the term is half as popular. 
  > - a score of 0 means there was not enough data for this term.


We gave to "Google Trends" the following search terms to Google Trends: `Cypress`, `Nightwatch`, `Playwright`, `Selenium JS` and `WebdriverIO`.
> note: the "`Selenium JS`" search term is used to filter results on Selenium JavaScript version, and not on other languages.

And we filtered results with the parameters:
- location: **worldwide**
- time: from 01/01/2022 to 31/12/2023
- category: "Computers & Electronics > Software"
- web search



The 2 below graphs represent "interest over time", for each of those tools, over the years 2022 and 2023 (excluding last 2 weeks of december).

We can see in the graphs above:
- Of these 5 frameworks, **`Cypress`** is the **most searched for** on Google, in 2022 and 2023. 
  - Average value for "_Interest over time_" is more than 70.
- the second one is **"`Playwright`"**  comes in second place. We can observe that its interest is growing over time ("_Interest over time_" was in [10 ; 30] range in 2022, and in [20 ; 50] range in 2023).
- The 3 other (`Nightwatch`, `Selenium JS` and `WebdriverIO`) seem to be much less "searched" on Google ("_Interest over time_" maximal value is 20).

| 2022                                                      | 2023                                                      |
| --------------------------------------------------------- | --------------------------------------------------------- |
| ![](../img/300/interest_over_time-google_trends-2022.png) | ![](../img/300/interest_over_time-google_trends-2023.png) |

> source: https://trends.google.com/trends/explore?cat=32&date=2022-10-10%202024-10-10&q=Cypress,Nightwatch,Playwright,Selenium%20JS,WebdriverIO&hl=en
>
> captured on 31/12/2023

 ----


_Notes :_
 



- [n-1]: [SeleniumHQ/selenium](https://github.com/SeleniumHQ/selenium) is the repo for the Selenium "umbrella project", covering not only "test" automation. And this repository correspond not only JavaScript implementation. 
