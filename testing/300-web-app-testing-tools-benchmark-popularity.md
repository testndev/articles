
# Popularity of the 4 web-app. testing tools
 

 | indicator                           | Cypress | Selenium | Playwright | Nightwatch |
 | ----------------------------------- | ------- | -------- | ---------- | ---------- |
 | NPM weekly downloads [^1]           | 4908680 | 2088040  | 1304640    | 180000     |
 | Github stars                        | 43434   | 26651    | 51509      | 11370      |
 | Followers on Twitter                | 21000   | 23000    | 9000       | 3000       |
 | Interest over time on Google Trends | 84,71   | 2,65     | 26,29      | 1,71       |




![](../img/300/relative-popularity-of-tools.png)

> as per end of may 2023, this graph shows the relative popularity of each tool, according to the previous indicators (NPM downloads, Github stars, Twitter followers, Google Trends). 

## Trend on the NPM packages

The Node.js versions of those tools are available as NPM packages.

| Tool                        | npm Package name                                                         |
| --------------------------- | ------------------------------------------------------------------------ |
| **Cypress.io**              | [`cypress`](https://www.npmjs.com/package/cypress)                       |
| **Nightwatch.js**           | [`nightwatch`](https://www.npmjs.com/package/nightwatch)                 |
| **Playwright** (JS version) | [`playwright`](https://www.npmjs.com/package/playwright)                 |
| **Selenium** (JS version)   | [`selenium-webdriver`](https://www.npmjs.com/package/selenium-webdriver) |

On [npm](https://www.npmjs.com) Registry, and for each package, we can take the **number of weekly downloads** as an indicator of their popularity.

As for 17/05/2023, we have, for each package, on last 7 days:

| package name/url                                                         | number of weekly downloads |
| ------------------------------------------------------------------------ | -------------------------: |
| [`cypress`](https://www.npmjs.com/package/cypress)                       |                `5.177.231` |
| [`selenium-webdriver`](https://www.npmjs.com/package/selenium-webdriver) |                `2.125.727` |
| [`playwright`](https://www.npmjs.com/package/playwright)                 |                `1.329.253` |
| [`nightwatch`](https://www.npmjs.com/package/nightwatch)                 |                  `163.602` |


Thats good, but we can have a better view of the popularity of each tool, by comparing them on the same graph. And see progression over time.


From [npm trends](https://npmtrends.com/cypress-vs-nightwatch-vs-playwright-vs-selenium-webdriver), we can see the popularity of each tool, by number of weekly downloads from NPM, with different time ranges. 

### Last year

![](../img/300/npmtrends.cy-bw-pw-se.last-1y.png)
> NPM weekly downloads of each package (cypress / nightwatch / playwright / selenium-webdriver), over the past year [^1] 

### History, last 5 years

We can see in the graph below the rapid rise of the "Playwright" framework from 2020.

![](../img/300/npmtrends.cy-bw-pw-se.last-5y.png)
> same over the past 5 years 



## Trend on GitHub

Comparison of number of stars on Github:

- [nightwatchjs/nightwatch](https://github.com/nightwatchjs/nightwatch)
- [cypress-io/cypress](https://github.com/cypress-io/cypress)
- [microsoft/playwright](https://github.com/microsoft/playwright)
- [SeleniumHQ/selenium](https://github.com/SeleniumHQ/selenium)


| Tool          | Number of stars on GitHub |
| ------------- | ------------------------: |
| Playwright    |                     51509 |
| Cypress.io    |                     43434 |
| Selenium      |                     26651 |
| Nightwatch.js |                     11370 |

> 24/05/2023

![](../img/300/github-trends.png)

> source: https://www.github-trends.com/

Please note that:
- [SeleniumHQ/selenium](https://github.com/SeleniumHQ/selenium) is the repo for the Selenium "umbrella project", covering not only "test" automation. And this repository correspond not only JavaScript implementation. 


## Trend on Google Search

Interest[^2] over time, for each of this tools.

![](../img/300/google-trend-2018-now.png)

> source: https://trends.google.com/trends/explore?cat=32&date=2018-01-01%202023-05-17&q=playwright,cypress,selenium%20js,nightwatch,webdriverio&hl=en

> ⚠️ to be completed



----


_Notes :_

- [^1]:  30/04/13, cf. https://npmtrends.com/cypress-vs-nightwatch-vs-playwright-vs-selenium-webdriver
- [^2]: "_Interest over time_" number is defined by Google by: 
  > Numbers represent search interest relative to the highest point on the chart for the given region and time.
  > - a value of 100 is the peak popularity for the term. 
  > - a value of 50 means that the term is half as popular. 
  > - a score of 0 means there was not enough data for this term.