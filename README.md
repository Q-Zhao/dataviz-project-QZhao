# Internet User and Mobile Subscriptions 1990 - 2013

## Introduction

This project is intended to explore and visualize the Internet usage and mobile subscriptions in worldwide. A short video can be found [here].

## Project URL
https://q-zhao.github.io/dataviz-project-QZhao/

## Data Source

This project uses the combination of datasets include:
* [Internet users’ numbers and GDPs of different countries from 1981 – 2016](https://ourworldindata.org/grapher/correlation-between-internet-users-as-a-share-of-the-population-and-gdp-per-capita?overlay=data)
* [mobile phone subscriptions number of different countries from 1980 to 2013](https://ourworldindata.org/grapher/mobile-cellular-subscriptions-by-country?overlay=data)


## Descriptions of Visualization and Interactions

This visualization consists of 3 parts: (1) Country selector (left panel), (2) Relations between Internet Users and GDP per capita of a selected country (right top panel), and (3) Relations between Internet Users and mobile subscriptions of a selected country (right bottom panel)

In the Country selector panel, where there is a selector bar and a global map, users can select a specifc country by either drag and double-click the country in the earth, or select manually via the selection bar on the top. Once a country is selected, the rest two visualization parts are updated interactively. This visualization is a modification of [KoGor](https://bl.ocks.org/KoGor)'s block [global earth](http://bl.ocks.org/KoGor/5994804), by converting the d3.v3 to [d3.v4 global earth](http://bl.ocks.org/Q-Zhao/47c42d002a6d521457c1937caace12ea).

The second part of the visualization is a scatter plot of the relationship between Internet Users (x-axis) and GDP per capita (y-axis) of the country selected. The correlations between these two components are displayed. With mouse hover onto a specifc point, the correpsonding year is shown up.

The third part of the visualization contains a year selection bar, and a bar chart of the relations between Internet Users and mobile subscriptions. Once users change the year in selection bar, the below bar chart is updated.


## Discussions of visualization

This project is intended to address the following questions:

1. How are Internet usage and mobile subscriptionschanging over time in every country?
   * This question 
2. The relationship between GDP per capita and Internet User over time.
3. The relationship between Mobile subscriptions and Internet User over time. 


## Conclusion

In this data visualization project, the Internet usage and mobile subscriptions in worldwide is explored.

## References:


## Project Deployment

A template project that uses Webpack and D3. Designed as a starting point for interactive data visualization projects that require JavaScript code to be organized across many files (as ES6 modules).

The starter code here is from [Stylized Scatter Plot with Color Legend](https://bl.ocks.org/curran/ecb09f2605c7fbbadf0eeb75da5f0a6b).

This project uses NPM and Webpack. To get started, clone the repository and install dependencies like this:

```
cd dataviz-project-template
npm install
```

You'll need to build the JavaScript bundle using WebPack, using this command:

```
npm run build
```

To see the page run, you'll need to serve the site using a local HTTP server.

```
npm install -g http-server
http-server
```

Now the site should be available at localhost:8080.

For automatic refreshing during development, you can start the Webpack Dev Server like this:

```
npm run serve
```
