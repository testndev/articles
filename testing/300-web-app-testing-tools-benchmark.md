# Benchmark of web-applications testing tools

![](https://github.com/testndev/web-app-testing-tools-benchmark/raw/main/doc/header-image.png)

|           | Benchmark of web-applications testing tools           |
| --------- | ----------------------------------------------------- |
| _Author_  | Alhusaine NEMER – [test'n'dev](https://testndev.com/) |
| _Date_    | 02/01/2024                                            |
| _Version_ | 0.91                                                  |
| _Licence_ | <a href="#licence">CC BY-NC-ND 4.0</a>                |

---

- [Benchmark of web-applications testing tools](#benchmark-of-web-applications-testing-tools)
  - [Introduction](#introduction)
  - [Quick presentation of the compared tools](#quick-presentation-of-the-compared-tools)
  - [Popularity of the 5 tools](#popularity-of-the-5-tools)
  - [Technical comparison](#technical-comparison)
  - [Installation 🚧](#installation-)
  - [Performance 🚧](#performance-)
  - [See also](#see-also)
  - [Conclusion](#conclusion)

---


## Introduction

In this article, I will compare some of **popular tools** used...
- *in* software development of web applications, 
- *for* testing purposes, 
- *in order* to automaticaly control your web application in a browser and check its behaviour.

I will try to be as objective as possible. It is not a "versus" article, not a "click bait" post, but a comparison of the characteristics, features and performance of each tool.

### selection of tools
We will focus on tools having those characteristics:
- **open-source** tools
- executable on [Node.js](https://nodejs.org) platform
- with possible implementation in TypeScript 
- and **mature** and quiet popular

We selected the following 5 tools: 

1. [Cypress.io](https://cypress.io/)                                       
2. [Nightwatch.js](https://nightwatchjs.org)                              
3. [Playwright](https://playwright.dev/)                                  
4. [Selenium WebDriver](https://www.selenium.dev/documentation/webdriver/) (+ a JavaScript testing framework)
5. [WebdriverIO](https://webdriver.io/)

In this article, and to be fair in the comparison, we will take JavaScript/TypeScript versions of Playwright and Selenium.

## Quick presentation of the compared tools

In the table below, the official quick presentations of the 5 tools, as given on their respective websites:

|                             | name                                                                    | presentation                                                                                                                                                                                                                                                                                                                                                                                     |
| --------------------------- | ----------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| ![](../img/icons/cy-48.png) | [Cypress.io](https://www.cypress.io/app)                                | Test modern apps directly in your browser<br/> Build, test, and debug directly in your browser with a seamless developer experience that is loved by developers all around the world. Test your code, not your patience.<br/> With Cypress, you can easily create tests for your modern web applications, debug them visually, and automatically run them in your continuous integration builds. |
| ![](../img/icons/nw-48.png) | [Nightwatch.js](https://nightwatchjs.org)                               | No-compromise test automation framework with a powerful set of tools to write, run and debug your tests across web and native mobile applications.                                                                                                                                                                                                                                               |
| ![](../img/icons/pw-48.png) | [Playwright](https://playwright.dev/)                                   | Playwright enables reliable end-to-end testing for modern web apps.                                                                                                                                                                                                                                                                                                                              |
| ![](../img/icons/se-48.png) | [Selenium WebDriver](https://www.selenium.dev/documentation/webdriver/) | Selenium automates browsers. That's it! <br/> What you do with that power is entirely up to you. Primarily it is for automating web applications for testing purposes, but is certainly not limited to just that.                                                                                                                                                                                |
| ![](../img/icons/wd-48.png) | [WebdriverIO](https://webdriver.io/)                                    | Next-gen browser and mobile automation test framework for Node.js                                                                                                                                                                                                                                                                                                                                |

## Popularity of the 5 tools

TL;DR:
- **Cypress** is today the **most popular tool**, among the 5
- **Playwright** is gradually **gaining popularity** (see [trends on NPM/GitHub/Google "fame" indicators](./300-web-app-testing-tools-benchmark-popularity.html))
- **Selenium** remains popular, but has **serious competitors**
- WebdriverIO is in the 4th position 
- Nightwatch seems to be less popular than the 4 others

To have an overview of "popularity" of each tool, we will use indicators retrieved on NPM, GitHub and Google.

See more details in ["popularity" sub-page](./300-web-app-testing-tools-benchmark-popularity.html).

The table below gives you an overview of the relative popularity of these 5 tools, with a few indicators and their evolution:

[![](../img/300/2023-relative-popularity-opensource-webapp-testing-tools-summary.png)](./300-web-app-testing-tools-benchmark-popularity.html)

## Technical comparison

| aspect                                   | Cypress        | Nighwatch      | Playwright             | Selenium  + | WebdriverIO    |
| ---------------------------------------- | -------------- | -------------- | ---------------------- | ----------- | -------------- |
| Other than JS/TS?                        | No, only JS/TS | No, only JS/TS | Yes (C#, Java, Python) | Yes, many   | No, only JS/TS |
| Protocol                                 | Inside Browser | WebDriver      | CDP (debug protocols)  | WebDriver   | WebDriver      |
| Open-source & supported/developped by... | Cypress        | BrowserStack   | Microsoft              | Community   | Community      |
 
> ⚠️ to be completed


## Installation 🚧

> ⚠️ to be completed


## Performance 🚧


We will use our code hosted on [`testndev/web-app-testing-tools-benchmark`](https://github.com/testndev/web-app-testing-tools-benchmark/) repository for our technical benchmark.


> ⚠️ to be completed

## See also

There is many articles that compare web-app test automation frameworks (especially Selenium vs Cypress vs Playwright since 2022), presenting their features, trade-offs, etc. 

You can read for example:
- ["Which web testing tool should i use?"](https://automationpanda.com/2023/04/24/which-web-testing-tool-should-i-use)   
  > (in english, 24/04/2023, by [*Andrew Knight*](https://twitter.com/automationpanda))
- ["Choix du logiciel et avis - Framework : Selenium vs Playwright vs Cypress"](https://blog.mrsuricate.com/choix-logiciel-avis-framework-selenium-playwright-cypress)
  > (in french, 13/03/2023, by [*Mr Suricate*](https://www.mrsuricate.com/))
- [Playwright vs. the world](https://medium.com/@jfgreffier/playwright-vs-the-world-c783e9bf4fc4)
  > (in french, 31/01/2023, by [*Jean-François Greffier*](https://linktr.ee/jfgreffier))
- [Cypress vs Selenium vs Playwright vs Puppeteer speed comparison](https://rag0g.medium.com/cypress-vs-selenium-vs-playwright-vs-puppeteer-speed-comparison-73fd057c2ae9)
  > (in english, 04/03/2021 by [*Giovanni Rago*](https://rag0g.medium.com/))
- [Comparison with leading frameworks (Nightwatch.js)](https://nightwatchjs.org/guide/comparison-with-leading-frameworks.html)
  > (in english, by [*Nightwatch.js*](https://nightwatchjs.org/))
-  State of JS: https://2022.stateofjs.com/en-US/libraries/testing/ ?
- "Selenium Vs … blog posts"
  > in english, 09/01/2024, by [David Burns @AutomatedTester](https://twitter.com/automatedtester)



## Conclusion

> ⚠️ to be completed






----


---

<a id="licence"></a>

_Licence_

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Licence Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a> 
 

This article is licensed under the terms of the 
<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">__Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)__</a> License

---

_Credits :_

...

---

_Photo Credits :_

- ...
  

