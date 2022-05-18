# Introduction

Markdown note template for CTFs and OSCP.

It is generally the same template as the [note template generator I wrote](https://github.com/tera-si/CTF-Note-Template-Generator), but for folks that want to do it entirely manually.

Suggestions welcome!

# Usage

It's just a template, you can take note however you want. But here is how I usually do:

```
## 80 TCP Apache Tomcat 9

- [x] searchsploit    <------     I check out the things I've tried
- [ ] hacktricks
- [ ] google
- [x] robots.txt
  - /manager    <------   And use arrows and brief note to mark things that are worth noting/revisiting, like the next one
- [x] sitemap.xml
- [x] nikto
- [x] gobuster
  - dir mode
  - 2.3 medium + common combined list
  - html, txt extensions
  - interesting finds:
    - /console    <------   recursive gobuster here maybe?
    - /dev
- root page:    <------   other notes outside the checkboxes
  - login page for some service
    - simple SQLi bypass didn't work
  - nothing unusual in the web source code
```
