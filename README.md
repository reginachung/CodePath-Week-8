# CodePath-Week-8
# Project 8 - Pentesting Live Targets

Time spent: **8** hours spent in total

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

Vulnerability #1: SQL Injection (SQLi)
![sql injection](https://user-images.githubusercontent.com/35437875/38462716-d957623e-3ab9-11e8-8e4c-5f92b617df30.gif)

Vulnerability #2: Session Hijacking/Fixation
![session hjacking](https://user-images.githubusercontent.com/35437875/38462719-e88752a0-3ab9-11e8-8387-d63a28f6e0a5.gif)

## Green

Vulnerability #1: Username Enumeration

-When typing in an existing username, the "Log in was unsuccessful" returns as a bolded text. As a result, the usernames, pperson and jmonroe99, returned the bolded text.
![username enumeration](https://user-images.githubusercontent.com/35437875/38462721-f338b784-3ab9-11e8-932e-81809f80b067.gif)

Vulnerability #2: Cross-Site Scripting (XSS)
![cross-site scripting](https://user-images.githubusercontent.com/35437875/38462723-fad21580-3ab9-11e8-8161-3f0249c5795d.gif)

## Red

Vulnerability #1: Insecure Direct Object Reference (IDOR)
![insecure direct object reference](https://user-images.githubusercontent.com/35437875/38462725-03423704-3aba-11e8-9352-d0b4941b094d.gif)

Vulnerability #2: Cross-Site Request Forgery (CSRF)
![cross site request forgery](https://user-images.githubusercontent.com/35437875/38462726-09f25318-3aba-11e8-9a24-b68140dd3b8a.gif)

## Notes

The main difficulty for this lab was testing the vulnerability for each website. When attempting to find the exploits, there was a lot of doubt whether the website's response was correct or not.
