# Project 8 - Pentesting Live Targets
Time spent: 8.5 hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:

* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each color is vulnerable to only 2 of the 6 possible exploits. First discover which color has the specific vulnerability, then write a short description of how to exploit it, and finally demonstrate it using screenshots compiled into a GIF.

## Blue

Vulnerability #1: Session Hijacking

Description:I logged into the target using a chrome browser and grabbed the session ID and gave that one to the atacker, a firefox browser, then changed the url to the staff menu area and was able to access it without having to log in.

<img src="https://media.giphy.com/media/w8ABSaABPoFjGrJLXy/giphy.gif">

Vulnerability #2: __________________

Description:

<img src="blue-vuln2.gif">

## Green

Vulnerability #1: Cross-Site Scripting

Description:

<img src="https://media.giphy.com/media/0Xe5SZmtOR5DGYvTKS/giphy.gif">

Vulnerability #2: User Enumeration

Description:

<img src=>


## Red

Vulnerability #1: Insecure Direct Object Reference

Description:

<img src="red-vuln1.gif">

Vulnerability #2: __________________

Description:

<img src="red-vuln2.gif">


## Notes

Describe any challenges encountered while doing the work
