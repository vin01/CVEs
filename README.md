# Vulnerabilities

This is a list of vulnerabilities I have discovered while using or reviewing various tools.

| CVE ID | Product / Tool | Description |
|--------|----------------|-------------|
| CVE-2018-5773 | [python-markdown2](https://github.com/trentm/python-markdown2) | [XSS](https://github.com/trentm/python-markdown2/issues/285) |
| CVE-2019-13422 | [Searchguard for elasticsearch](https://search-guard.com/) | [XSS](https://search-guard.com/cve-advisory/) |
| CVE-2020-28247 | [lettre](https://github.com/lettre/lettre) (a mailing library for Rust)| [Argument injection in sendmail transport](https://github.com/lettre/lettre/security/advisories/GHSA-vc2p-r46x-m3vx)|
| CVE-2020-7769 | [nodemailer](https://github.com/nodemailer/nodemailer) (a mailing library for Node) |  [Argument injection in sendmail transport](https://nvd.nist.gov/vuln/detail/CVE-2020-7769)|
| CVE-2020-27687 | [Thingsboard](https://github.com/thingsboard/thingsboard) (an open-source IoT platform) | [Host header injection in password-reset mails](https://nvd.nist.gov/vuln/detail/CVE-2020-27687)|
| TBD | [Gitlab](https://gitlab.com/gitlab-org/gitlab) | Unauthenticated SSRF |
