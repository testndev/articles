# Benchmark of web-applications testing tools

![](https://github.com/testndev/web-app-testing-tools-benchmark/raw/main/doc/header-image.png)

|           | le « test » logiciel : 4 définitions                                                                       |
| --------- | ---------------------------------------------------------------------------------------------------------- |
| _Author_  | Alhusaine NEMER – [test'n'dev](https://testndev.com/)                                                      |
| _Date_    | 13/05/2023                                                                                                 |
| _Version_ | 0.1                                                                                                        |
| _Licence_ | <a href="#licence"><img alt="by-nc-nd" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a> |

---

- [Benchmark of web-applications testing tools](#benchmark-of-web-applications-testing-tools)
  - [Introduction](#introduction)

---



> ⚠️ to be completed


## Introduction

In this article, we will compare [Cypress.io](https://cypress.io/) *vs* [Nightwatch.js](https://nightwatchjs.org) *vs* [Playwright](https://playwright.dev/) *vs* [Selenium WebDriver](https://www.selenium.dev/documentation/webdriver/), all in their [Node.js](https://nodejs.org) versions.

Indeed, in this article, and to be fair in the comparison, we will take Javacript/TypeScript version of Playwright and Selenium.

This comparison is based on code hosted on this repository: [testndev/web-app-testing-tools-benchmark](https://github.com/testndev/web-app-testing-tools-benchmark/).

## Quick comparison of the 4 compared tools

There is many articles that compare web-app test automation frameworks (especially Selenium vs Cypress vs Playwright since 2022), presenting their features, trade-offs, etc. You can read for example ["Which web testing tool should i use?"](https://automationpanda.com/2023/04/24/which-web-testing-tool-should-i-use) article, written 24/04/2023 by [Andrew Knight](https://twitter.com/automationpanda).

### Quick table

| aspect                                   | Cypress        | Nighwatch    | Playwright              | Selenium  |
| ---------------------------------------- | -------------- | ------------ | ----------------------- | --------- |
| Other than JS/TS?                        | No             | No           | Yes (C#, Java, Python)  | Yes, many |
| NPM weekly downloads  [^1]               | > 4.600k       | > 180k       | > 1.300k                | > 1.900k  |
| Github stars                             | > 43k          | > 11k        | > 50k                   | > 26k     |
| Protocol                                 | Inside Browser | WebDriver    | > CDP (debug protocols) | WebDriver |
| Open-source & supported/developped by... | Cypress        | BrowserStack | Microsoft               | Community |
 

### Trend on the NPM packages

From [npm trends](https://npmtrends.com/cypress-vs-nightwatch-vs-playwright-vs-selenium-webdriver), we can see the popularity of each tool, by number of weekly downloads from NPM. 

#### last week
As for 13/05/2013, we have:

| 🔵 Cypress | 🔴 Selenium | 🟢 Playwright | 🟠 Nightwatch |
| --------- | ---------- | ------------ | ------------ |
| > 4.600k  | > 1.900k   | > 1.300k     | > 180k       |


#### Last year

![](../img/300/npmtrends.cy-bw-pw-se.last-1y.png)
> NPM weekly downloads of each package (cypress / nightwatch / playwright / selenium-webdriver), over the past year [^1] 

#### History, last 5 years

We can see in the graph below the rapid rise of the "Playwright" framework from 2020.

![](../img/300/npmtrends.cy-bw-pw-se.last-5y.png)
> same over the past 5 years 



## Conclusion

> ⚠️ to be completed






----


---

<a id="licence"></a>

_Licence_

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Licence Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a> 

Cet article est mise à disposition selon les termes de la <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Licence Creative Commons Attribution - Pas d&#39;Utilisation Commerciale - Pas de Modification 4.0 International</a>


---

_Credits :_

...

---

_Photo Credits :_

- ...
  

_Illustrations Credits :_
- [^1]:  30/04/13, cf. https://npmtrends.com/cypress-vs-nightwatch-vs-playwright-vs-selenium-webdriver
    