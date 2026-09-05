# Crosstalk status

`https://status.crosstalkhq.dev` redirects to the Crosstalk status page at
[crosstalk.betteruptime.com](https://crosstalk.betteruptime.com/), which is
run by Better Stack: uptime checks from several regions, incidents with
written updates, and maintenance notices.

This repository is the redirect: a GitHub Pages site of one page
(`index.html`, also served as `404.html` so old deep links land too) and the
`CNAME` that keeps the domain. Nothing runs here.

It was an [Upptime](https://upptime.js.org) site until 2026-09-05, with its
own checks and incident issues. That was retired so there is one status page
and one set of checks; see crosstalkhq/crosstalk#308.

If Crosstalk moves to a Better Stack plan with a custom domain, the DNS
`CNAME status` moves from `crosstalkhq.github.io` to `status.betteruptime.com`
and this repository can be archived.
