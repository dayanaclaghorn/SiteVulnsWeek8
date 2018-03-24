Project 8 - Pentesting Live Targets

Time spent: 17 hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: SQLI
- [Link 1](https://github.com/dayanaclaghorn/SiteVulnsWeek8/blob/master/week8SQLI.gif)

Vulnerability #2: Session Hacking
- [Link 1](https://github.com/dayanaclaghorn/SiteVulnsWeek8/blob/master/week8SessionH.gif)

## Green

Vulnerability #1: User Enumeration
- [Link 1](https://github.com/dayanaclaghorn/SiteVulnsWeek8/blob/master/week8UE.gif)

Vulnerability #2: XSS
- [Link 1](https://github.com/dayanaclaghorn/SiteVulnsWeek8/blob/master/week8XSS.gif)


## Red

Vulnerability #1: IDOR
- [Link 1](https://github.com/dayanaclaghorn/SiteVulnsWeek8/blob/master/week8IDOR.gif)

Vulnerability #2:CSRF 
- [Link 1](https://github.com/dayanaclaghorn/SiteVulnsWeek8/blob/master/week8CSRF.gif)


## Notes

I had a hard time getting started. It was really difficult for me to get to a place where I new where to look for the vulnerabilities; I just tried any place where a user could put in input. Eventually, I started to look at more pointed locations based on where I new where that vulnerability was most likely. Two examples: I was about 99% sure that the SQLI was in the URL, but I didn’t escape it properly at first and wasn’t sure where to try (I figured it was in the user pages, but had trouble with why that was.) The XSS took me several tries to get it right, but I was pretty sure that it was to be committed in the form page. 
