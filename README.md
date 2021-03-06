# Cybersecurity
# Project 9 - Pentesting Live Targets

Time spent: **2** hours spent in total

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

Vulnerability #1: SQL Injection

Description:
Put the site to sleep through a SQL injection
<img src="blue-vuln1.gif">


## Green

Vulnerability #1: Cross Site Scripting

Description:
Cross site scripting on green using the script : <script>alert('Mallory found the XSS!');</script>
Had trouble cause there was a lots of feedback at the time.
<img src="green-vuln1.gif">


## Red

Vulnerability #1: Insecure Direct Object Reference

Description:
Users not in use/test users found through URL manipulation
<img src="red-vuln1.gif">


## Notes

Describe any challenges encountered while doing the work
