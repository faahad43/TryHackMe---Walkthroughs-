# Report: Walkthrough the Website 

**Room Link:** [https://tryhackme.com/room/walkinganapplication](https://tryhackme.com/room/walkinganapplication
**Pathway:** Jr Penetration Tester
**Room:** Walking an Application
**Author:** Syed Fahad Shah
**Date:** 16 Aug 2025

## Objectives: 
This room tells about the first step a pentester should taken when working with a website. It also cover the manual techinques for website inspection as automation tools and script sometimes miss some useful information

## Tools Covered:
The room cover the developer tools and four main thing in the browser developer tools:
1- View page source
2- Inspector
3- Debugger
4- Network Tab

## Walkthrough:

### Task 1 - Walking an Application
- Deployed the virtual machine and navigated to the provided url
- Observed the landing page of the ACME website for the context

### Task 2 - Exploring the Website
- Visit the multiple pages present on the website
- Document the important things on each page for example /news/article?id={no} shows different articles and some are premieum.

### Task 3 - Viewing the Page source
- Right click on the page and click view source page.
- Source page tells all the information available for the page in the html form.
- Comments on the source page are the inforation developer leaves for themselve so if someone review the code they understand what code is doing.
- Sometimes developers forget to remove the comment they add during development that might contain some useful information
- While viewing page source, the 1st line comments says there is a page at /new-home-beta
![source code image](./images/q1.png)
- insert in url /newhomebeta and there is flag.


