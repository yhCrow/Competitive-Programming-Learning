# Contest Chapter Atlas

A study map for the 101 chapters of the 深入浅出程序设计竞赛 handouts (基础篇, 进阶篇, 拓展篇, NOI篇).

**Open the site:** https://yhcrow.github.io/Competitive-Programming-Learning/

## What's in it

- **Learning tree.** Every chapter placed by its prerequisites. Click a chapter to see what it needs, what it unlocks and the chapters still to learn first. The prerequisite links are an estimate from the chapter contents.
- **Chapter pages.** For each chapter: its IDEA / KEY POINT / TRAP boxes by section, every C++ program with its sample input and output, the handout PDF and its full text, and your own notes.
- **Problem lists.** The chapter's Luogu (8,895 in total) and Codeforces (7,557) problems, easiest first, with ★ on the ones that test exactly that chapter's technique.
- **Progress.** Mark chapters learned and tick solved problems. Progress is saved in your browser only.

## Files

| Path | Contents |
| --- | --- |
| `index.html` | The whole site (no build step) |
| `atlas.json` | Chapters, prerequisites, concept boxes and programs |
| `problems.json` | Luogu and Codeforces problems per chapter |
| `handouts/` | Each chapter's PDF and extracted text (`b` 基础篇, `j` 进阶篇, `t` 拓展篇, `n` NOI篇) |

To run it locally, serve the folder (for example `python -m http.server`) and open `http://localhost:8000`. Opening `index.html` straight from disk won't load the data.
