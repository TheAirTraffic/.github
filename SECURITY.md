# Security Policy

Thanks for helping keep TheAirTraffic and its feeders safe.

## Reporting a vulnerability

Please report security issues **privately**. Do not open a public issue, pull request, or Discord post.

- **Email:** [security@grndcntrl.net](mailto:security@grndcntrl.net)
- **GitHub:** use **Report a vulnerability** on the repository's **Security** tab, where available.

Include as much of the following as you can:

- What is affected (site, API, repository, or feeder software and version)
- Steps to reproduce, or a proof of concept
- The impact you think it has
- How you would like to be credited, if at all

## Scope

- TheAirTraffic websites and APIs, including `theairtraffic.com` and its subdomains (such as `globe.theairtraffic.com`)
- Feeder and MLAT services that receivers connect to
- Repositories in the [TheAirTraffic](https://github.com/TheAirTraffic) GitHub organization, such as `tat-feeder` and `mlat-client`

Out of scope:

- Aircraft position data itself. ADS-B and MLAT data is broadcast publicly by aircraft and is shown by design.
- Denial of service, load testing, spam, or social engineering
- Reports from automated scanners with no demonstrated impact
- Missing best-practice headers or settings with no practical exploit

## Testing guidelines

- Only test against accounts and data you own.
- Do not access, change, or delete other users' or feeders' data.
- Do not degrade the service for others.
- Give us a reasonable amount of time to fix an issue before disclosing it publicly.

Good-faith research that follows these guidelines is welcome, and we will not pursue action against it.

A machine-readable contact is also published at [`/.well-known/security.txt`](https://theairtraffic.com/.well-known/security.txt).
