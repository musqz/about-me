### Hi, I'm musqz 👋

Based in Midden-Holland (Middle Holland), NL. On Linux since Ubuntu Warty, moved through Debian-based distros, dropped Ubuntu entirely, and have been Arch-based for the last ~10 years. Daily driver is [Mabox Linux](https://maboxlinux.org/).

First code I ever wrote was on a Commodore 64 — moving fields around the screen, putting together simple animations. No formal background since — I learned by reading forum threads and wikis, copy-pasting snippets together, a lot of trial-and-error, then more reading until it actually made sense. Most of it came from studying and forking scripts across a lineage of distros: PsychOS, MX Linux, Puppy Linux, ArcoLinux, and for the last few years Mabox scripts (by Daniel). ArcoLinux and Mabox especially are where understanding a script's structure — what a function is actually doing, rather than just pattern-matching snippets — started to click. Claude Code builds on that now, on bigger or less familiar codebases.

- 🐚 Bash first, always — it's home turf. I only look into Python once something already works in Bash and needs more.
- 🧩 One file, or as few as possible — projects stay simple on purpose, easier to hold in your head that way
- 🔩 C isn't a strong area yet. My part in [skippy-xd](https://github.com/musqz/skippy-xd) stayed scoped to the man page and a bit of class code, not core logic
- 🛡️ Maintaining **archcanary**, a layered AUR supply-chain scanner (systemd + eBPF + kmod auditing) — the project that's picked up the most outside contribution so far
- 📦 Packaging things properly: AppImages with bundled deps + zsync delta updates, PKGBUILDs for AUR
- 🐧 X11, not Wayland — most of what I build assumes X11 first

---

### What I'm working on

| Project | What it does |
|---|---|
| [archcanary](https://github.com/musqz/archcanary) | AUR supply-chain security scanner — systemd, eBPF, kmod auditing |
| [forum-scout](https://github.com/musqz/forum-scout) / [forum-scout-qt](https://github.com/musqz/forum-scout-qt) | Multi-forum search tool for Arch-focused wikis/forums — GTK4 and Qt6 versions |
| [quickbox](https://github.com/musqz/quickbox) / [quickbox-qt](https://github.com/musqz/quickbox-qt) | GUI for [quickemu](https://github.com/quickemu-project/quickemu) — VM management, migration, snapshots |
| [fittsmon-gui](https://github.com/musqz/fittsmon-gui) | GUI for FittsMon — mouse hot-corner/edge actions on X11 |
| [volbar](https://github.com/musqz/volbar) | Minimal editable volume notifier for X11 (GTK) |

Most of these started as forks of tools I actually use daily, then got a GUI, a port to a different toolkit, or an AppImage build pipeline bolted on.

### Collaboration

Mostly solo maintainer, but open to it — archcanary has taken patches and input from outside contributors already, and I'll take issues/PRs seriously on anything actively maintained above. Best way in is a GitHub issue on the relevant repo.

### Tech

<img src="https://skillicons.dev/icons?i=bash,python,linux,git,github,c,cpp" alt="tech stack" />

---

<img src="https://github-readme-stats.vercel.app/api?username=musqz&show_icons=true&theme=default&hide_title=true" alt="musqz's github stats" height="165" />
<img src="https://streak-stats.demolab.com/?user=musqz" alt="musqz's github streak" height="165" />
