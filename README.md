# Project 7 - WordPress Pentesting

Time spent: **7** hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1. (Required) Vulnerability Name or ID
  - [ Checked user enumeration] Summary: 
    - Vulnerability types: User enumeration
    - Tested in version: 4.2
    - Fixed in version: 
  - [x] GIF Walkthrough: yes
  - [x] Steps to recreate: added a new user and looked while logging in
    <img src='WP 4.2 Username emumeration.gif' title='WordPress Username Enumeration' width='' alt='' />

1. (Required) Vulnerability Name or ID Cross site scripting
  - [ ] Summary: checked on the page of WordPress
    - Vulnerability types:Cross site scripting
    - Tested in version: 4.2
    - Fixed in version: 
  - [ ] GIF Walkthrough: yes
  - [ ] Steps to recreate: XSS on wordpress website
    <img src='WP 4.2 XSS on a WordPress site.gif' title='WordPress XSS' width='' alt='' />

1. (Required) Vulnerability Name or ID XSS to upload larger media than 2 mb
  - [ ] Summary: uploaded 56 MB media by XSS on it a file name
    - Vulnerability types: cross- site scripting
    - Tested in version:4.7.4
    - Fixed in version: 
  - [ ] GIF Walkthrough: yes
  - [ ] Steps to recreate: uploaded 56 MB media by XSS on it a file name
   <img src='WP 4.7.4 Large File Upload Error XSS.gif' title='WordPress XSS2' width='' alt='' />
