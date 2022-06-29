# WTax Build Support

Various bits and bobs used in building projects that don't warrant having their 
own project. This repository is public so that the files in it can be linked to
easily using public URLs, e.g. this file's URL is https://raw.githubusercontent.com/wtaxco/wtax-build-support/main/README.md.

## OWASP Dependency Check

**Directory:** `owasp-dependency-check`

Various reusable suppression files for the OWASP Dependency Check, to
work around commonly encountered false positives, are available here:

| File                               | Description                                                                                                                                     |
|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| `suppression.xml`                  | Contains suppression rules commonly needed in our Spring Boot-based projects. Useful as a base suppression file for most Spring Boot projects.  |
| `suppression-CVE-2016-1000027.xml` | Contains a suppression rule for [CVE-2016-1000027](https://www.cvedetails.com/cve/CVE-2016-1000027)                                             |
| `suppression-CVE-2020-5408.xml`    | Contains a suppression rule for [CVE-2020-5408](https://www.cvedetails.com/cve/CVE-2020-5408)                                                   |

