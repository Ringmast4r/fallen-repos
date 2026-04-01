<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,100:8B0000&height=200&section=header&text=FALLEN%20REPOS&fontSize=80&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Preservation%20Archive%20|%20DMCA%20|%20Banned%20|%20Deleted%20|%20Shadow%20Banned&descSize=18&descAlignY=55"/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&pause=1000&color=8B0000&center=true&vCenter=true&multiline=true&repeat=true&width=800&height=80&lines=%E2%96%88%E2%96%88%E2%96%88+THE+GRAVEYARD+%E2%96%88%E2%96%88%E2%96%88;Repos+disappear.+We+remember.)](https://git.io/typing-svg)

<br>

![Archived](https://img.shields.io/badge/Archived-0-8B0000?style=for-the-badge) ![DMCA](https://img.shields.io/badge/DMCA-0-da3633?style=for-the-badge) ![Banned](https://img.shields.io/badge/Banned-0-6e40c9?style=for-the-badge) ![Deleted](https://img.shields.io/badge/Deleted-0-555555?style=for-the-badge) ![Shadow%20Banned](https://img.shields.io/badge/Shadow%20Banned-0-FF8C00?style=for-the-badge) ![Nuked](https://img.shields.io/badge/Nuked-0-000000?style=for-the-badge)

*Last updated: 2026-04-01*

</div>

---

## `> cat /etc/motd`

```
+------------------------------------------------------------------------------+
|                                                                              |
|   Repos disappear from GitHub every day -- DMCA takedowns, account bans,     |
|   shadow bans, suspensions, or authors deleting their work. Some of these    |
|   projects were valuable tools, research, educational resources, or pieces   |
|   of internet history that deserve to survive.                               |
|                                                                              |
|   This repository preserves full source snapshots of fallen projects so      |
|   they remain accessible to the community.                                   |
|                                                                              |
|   "The internet never forgets -- but sometimes it needs help remembering."   |
|                                                                              |
+------------------------------------------------------------------------------+
```

---

## `> ls -la archive/`

<div align="center">

### Archived Repositories

| # | Repository | Original Author | Reason | Category | Stars | Date Archived |
|:-:|:-----------|:----------------|:------:|:--------:|:-----:|:-------------:|
| -- | *Archive empty* | -- | -- | -- | -- | -- |

*Monitoring 83 starred repos, 71 forks, and 17 subscriptions. When they fall, they land here.*

</div>

---

## `> cat removal_codes.conf`

<div align="center">

| | Tag | Meaning | Badge |
|:-:|:---:|:--------|:-----:|
| X | `DMCA` | Removed via DMCA takedown notice | ![DMCA](https://img.shields.io/badge/DMCA-da3633?style=flat-square) |
| X | `BANNED` | Author account banned or suspended | ![BANNED](https://img.shields.io/badge/BANNED-6e40c9?style=flat-square) |
| X | `SHADOW` | Shadow-banned -- accessible but hidden from search/discovery | ![SHADOW](https://img.shields.io/badge/SHADOW-FF8C00?style=flat-square) |
| X | `DELETED` | Voluntarily deleted by author or org | ![DELETED](https://img.shields.io/badge/DELETED-555555?style=flat-square) |
| X | `NUKED` | Entire account nuked, all repos gone | ![NUKED](https://img.shields.io/badge/NUKED-000000?style=flat-square) |
| X | `PRIVATE` | Made private after being public -- lost to community | ![PRIVATE](https://img.shields.io/badge/PRIVATE-0969da?style=flat-square) |
| X | `FORK-PURGE` | Upstream deleted, all forks cascade-removed | ![FORK-PURGE](https://img.shields.io/badge/FORK--PURGE-8B0000?style=flat-square) |

</div>

---

## `> cat stats.json`

<div align="center">

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': {'pie1': '#da3633', 'pie2': '#6e40c9', 'pie3': '#FF8C00', 'pie4': '#555555', 'pie5': '#000000', 'pie6': '#0969da', 'pie7': '#8B0000'}}}%%
pie showData
    title Removal Reasons (will populate as repos fall)
    "DMCA" : 0
    "Banned" : 0
    "Shadow Banned" : 0
    "Deleted" : 0
    "Nuked" : 0
    "Private" : 0
    "Fork Purge" : 0
```

</div>

---

## `> tree repos/`

```
fallen-repos/
  README.md                    <-- this index
  _ARCHIVE_TEMPLATE.md         <-- copy into each archived repo
  repos/
    project-name/              <-- full source snapshot
      _ARCHIVE.md              <-- metadata record
      ...                      <-- original repo contents
```

<details>
<summary><strong>> cat _ARCHIVE_TEMPLATE.md</strong></summary>

```markdown
# Archive Record

- **Original URL:** https://github.com/author/repo
- **Author:** @author
- **Reason Lost:** DMCA / BANNED / SHADOW / DELETED / NUKED / PRIVATE / FORK-PURGE
- **Date Lost:** YYYY-MM-DD
- **Date Archived:** YYYY-MM-DD
- **Stars (last known):** N
- **Language(s):**
- **License:**
- **Description:** What this project was and why it mattered
- **Context:** Why/how it was removed (if known)
- **Source:** Where the snapshot was obtained (local clone, archive.org, etc.)
```

</details>

---

## `> cat CONTRIBUTING.md`

If you have a local clone of a repo that has since been removed from GitHub:

```bash
# 1. Fork this repo
gh repo fork Ringmast4r/fallen-repos

# 2. Add the project
cp -r /path/to/dead-repo repos/project-name/

# 3. Copy the archive template
cp _ARCHIVE_TEMPLATE.md repos/project-name/_ARCHIVE.md

# 4. Fill in the metadata, commit, and open a PR
```

PRs should include:
- The full source snapshot under `repos/`
- A filled-out `_ARCHIVE.md` with as much metadata as possible
- Context in the PR description on why the project was notable

---

## `> cat DISCLAIMER`

```
This archive exists for EDUCATIONAL and PRESERVATION purposes only.

- Archived code retains its original license
- No ownership is claimed over any archived content
- Original authors may request removal via GitHub Issues
- Removal requests will be honored promptly

This project does not encourage or facilitate piracy, infringement,
or unauthorized distribution of proprietary software.
```

---

<div align="center">

```
+------------------------------------------------------------------------------+
|                                                                              |
|   "They can delete the repo, but they can't delete the clone."              |
|                                                                              |
|                                               - THE GRAVEYARD               |
|                                                                              |
+------------------------------------------------------------------------------+
```

![Views](https://komarev.com/ghpvc/?username=fallen-repos&label=VISITORS&color=8B0000&style=for-the-badge)

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:8B0000,100:000000&height=120&section=footer"/>
