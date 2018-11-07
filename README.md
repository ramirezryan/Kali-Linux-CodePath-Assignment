# Kali-Linux-CodePath-Assignment
Scanning earlier versions of WordPress for security flaws and demonstrating exploitative capabilities.

# Project 7 - WordPress Pentesting

Time spent: **6** hours spent in total

> Objective: Find, analyze, recreate, and document **three vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1. Vulnerability Name or ID: Authenticated Stored XSS
  - [ ] Summary: XSS vulnerability in the comments section of a wordpress site.
    - Vulnerability types: XSS
    - Tested in version: 4.2
    - Fixed in version: 4.2.6
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: Post a comment on the wordpress site containing a malicious XSS script (such as a link).
  - [ ] Affected source code:
    - [Link 1](https://wpvulndb.com/vulnerabilities/8358)
2. Vulnerability Name or ID: User Enumeration
  - [ ] Summary: Discover users using wpscan's --enumerate u. Reduces the time needed to falsely login as another user.
    - Vulnerability types: User Enumeration
    - Tested in version: 4.2
    - Fixed in version: 4.7.1
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: wpscan --url http://<wordpress site address> --enumerate u
  - [ ] Affected source code:
    - [Link 1](https://www.exploit-db.com/exploits/41497/)

## Assets

List any additional assets, such as scripts or files

## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while doing the work

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
