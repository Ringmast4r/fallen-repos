# Fallen Repos

**A preservation archive of GitHub repositories that have been removed, banned, DMCA'd, or otherwise lost to the void.**

Repos disappear from GitHub every day -- takedowns, DMCA claims, shadow bans, account suspensions, or authors simply deleting their work. Some of these projects were valuable tools, research, educational resources, or pieces of internet history that deserve to survive.

This repository preserves full source snapshots of fallen projects so they remain accessible to the community.

---

## Archive Index

| # | Repository | Original Author | Reason Lost | Category | Date Archived |
|---|-----------|----------------|-------------|----------|---------------|
| — | — | — | — | — | — |

*Archive is being seeded. Entries coming soon.*

---

## Removal Reasons

| Tag | Meaning |
|-----|---------|
| `DMCA` | Removed via DMCA takedown notice |
| `BANNED` | Author account banned or suspended |
| `SHADOW` | Repository shadow-banned (accessible but hidden from search/discovery) |
| `DELETED` | Voluntarily deleted by author or org |
| `NUKED` | Entire account nuked, taking all repos with it |
| `PRIVATE` | Made private after being public (effectively lost to the community) |
| `FORK-PURGE` | Upstream deleted, all forks cascade-removed |

## Structure

```
fallen-repos/
  README.md              <- this index
  repos/
    project-name/        <- full source snapshot
      _ARCHIVE.md        <- metadata: original URL, author, reason, date, description
      ...                <- original repo contents
```

Each archived repo includes an `_ARCHIVE.md` file at its root with preservation metadata:

```markdown
# Archive Record

- **Original URL:** https://github.com/author/repo
- **Author:** @author
- **Reason Lost:** DMCA / BANNED / DELETED / etc.
- **Date Lost:** YYYY-MM-DD (approximate)
- **Date Archived:** YYYY-MM-DD
- **Stars (last known):** N
- **Description:** What this project was and why it mattered
- **Context:** Why it was removed (if known)
```

## How to Contribute

If you have a local clone of a repo that has since been removed from GitHub:

1. Fork this repo
2. Add the project under `repos/project-name/`
3. Include an `_ARCHIVE.md` with the metadata above
4. Open a PR with context on why the project was notable

## Disclaimer

This archive exists for **educational and preservation purposes**. Archived code retains its original license. If you are the original author of an archived project and want it removed from this collection, open an issue and it will be taken down promptly.

---

*"The internet never forgets -- but sometimes it needs help remembering."*
