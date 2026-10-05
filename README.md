# X-Camp Contest Guides

Contest guide pages for X-Camp students. Each page gives the contest rules, the contest
format and the difficulty level. Each page also maps the contest to the X-Camp course
roadmap.

Your site is live at
**https://x-camp-academy-ca.github.io/xcamp-contest-guides/**

## Pages

| Contest | Page | URL |
|---|---|---|
| CALICO Spring 2026 | CALICO 26 – Contest Guide + X-Camp Course Roadmap | [open](https://x-camp-academy-ca.github.io/xcamp-contest-guides/xcamp-calico-spring2026-contest-guide.html) |
| HPI 2026 | HPI 2026 – Contest Guide + X-Camp Course Roadmap | [open](https://x-camp-academy-ca.github.io/xcamp-contest-guides/xcamp-hpi-2026-contest-guide.html) |
| SACC 2026 | SACC 2026 – Contest Guide + X-Camp Course Roadmap | [open](https://x-camp-academy-ca.github.io/xcamp-contest-guides/xcamp-sacc-2026-contest-guide.html) |
| TeamsCode Spring 2026 | TeamsCode Spring 2026 – Contest Guide + X-Camp Course Reference | [open](https://x-camp-academy-ca.github.io/xcamp-contest-guides/xcamp-teamscode-spring2026-contest-guide.html) |
| TeamsCode Summer 2026 | TeamsCode Summer 2026 – Contest Guide + X-Camp Course Reference | [open](https://x-camp-academy-ca.github.io/xcamp-contest-guides/xcamp-teamscode-summer2026-contest-guide.html) |
| TJ IOI 2026 | TJ IOI 2026 – Contest Guide with X-Camp Courses | [open](https://x-camp-academy-ca.github.io/xcamp-contest-guides/xcamp-tjioi-2026-contest-guide.html) |
| WWPIT 2026 | WWPIT 2026 – Contest Guide with X-Camp Courses | [open](https://x-camp-academy-ca.github.io/xcamp-contest-guides/xcamp-wwpit-2026-contest-guide.html) |

## File names

Use this pattern for a new page:

```
xcamp-{partner}-{period}-contest-guide.html
```

- Write all characters in lower case. Use a hyphen between words.
- `{partner}` must be the same as the UTM source for that partner. Example: `calico`,
  `tjioi`, `wwpit`.
- `{period}` is the year. Add the season before the year if the partner holds more than one
  contest in a year. Example: `spring2026`, `summer2026`.
- Do not add a version number to the file name. Git keeps the history.
- Use the word `guide`. Do not use `guidebook` or `contest-info`.

## Google Analytics

Each page has the Google Analytics tag `G-L64HE50P6M` in the `<head>` block. Copy this
block into each new page:

```html
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-L64HE50P6M"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-L64HE50P6M');
</script>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
```

Google keeps this data for 30 days only. Download a report before the data expires.
