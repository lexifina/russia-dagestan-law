<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Republic of Dagestan only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-24 13:35 UTC, Republic of Dagestan: Official Internet Portal of Legal Information (region05): 11 addresses read; 5 added, 0 changed, 0 removed; changes found; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Republic of Dagestan: Official Internet Portal of Legal Information (region05)](http://publication.pravo.gov.ru/documents/block/region05) | `zakony-<year>/` | daily | 2026-11-24 13:35 UTC | changes found | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-24 13:28](checks/2026-11.md#ru-pravo-dagestan-20261124t132800z) | pravo-dagestan | 11 | 5 | 0 | 0 | 0 (0) | changes found | [3](https://github.com/lexifina/russia-dagestan-law/compare/77ee88c8fef1...95fe0d26a8a6) |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
