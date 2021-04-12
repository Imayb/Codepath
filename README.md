# Project 8 - Pentesting Live Targets
Time spent: 11 hours spent in total

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

Description: Session Hijacking attack compromises the seassion token by stealing a valid session to gain unauthorized access to a web server. I logged into the target using a chrome browser and grabbed the session ID and gave that one to the atacker, a firefox browser, then changed the url to the staff menu area and was able to access it without having to log in.

<img src="https://media.giphy.com/media/w8ABSaABPoFjGrJLXy/giphy.gif">

Vulnerability #2: SQL Injection

Description: I checked to see if the salesperson ID would accept an SQL query a "database query failed" message popped up which informs me that this color and area is vulnerable to this type of attack. I injected a few others and one of them gave me access to "Daron Burke" salesperson ID. 

<img src="https://media.giphy.com/media/6ZBTR5w56HEW4hFrqQ/giphy.gif">

## Green

Vulnerability #1: Cross-Site Scripting

Description: I injected an alert script that gets triggered when accessing the staff feedback area.

<img src="https://media.giphy.com/media/0Xe5SZmtOR5DGYvTKS/giphy.gif">

Vulnerability #2: 

Description: User Enumeration

<img src=>


## Red

Vulnerability #1: Insecure Direct Object Reference

Description: Insecure direct object reference is a type of access control vulnerability that arises when a website or application implements user-supplied input to access objects directly. By modifying the ID value in the URL I was able to see salesperson that the other colors did not allow by bypassing access controls.

<img src="https://media.giphy.com/media/mzH8Cpup7lHYj292jj/giphy.gif">

Vulnerability #2:

Description:

<img src="red-vuln2.gif">


## Notes

Describe any challenges encountered while doing the work
