# forks-os-forks 🐧

**Your hub for experimenting with other operating systems.**

This repository is for collecting tools, workflows, build helpers, and experiments for trying different Linux and Unix-like operating systems in VMs and other test environments.

## Featured: ObsidianOS

The repository includes a GitHub Actions workflow that fetches the **official ObsidianOS Arch-based installer** from `arbs.obsidianos.xyz` and stores it as a workflow artifact.

The workflow is intentionally limited to downloading and checking the official installer. It does **not** run the installer on the GitHub runner or modify a real disk.

### Run it

1. Open **Actions**.
2. Select **ObsidianOS Installer**.
3. Choose **Run workflow**.
4. Download the `obsidianos-official-installer` artifact.

## 🧪 Cool & Unique OS Projects

A growing collection of interesting operating systems and OS projects worth experimenting with in VMs:

| OS / Project | What makes it interesting | Repository |
|---|---|---|
| **SerenityOS** | A full desktop OS built from scratch with its own UI, apps, libraries, and kernel | https://github.com/SerenityOS/serenity |
| **Redox OS** | Unix-like operating system written largely in Rust | https://github.com/redox-os/redox |
| **ToaruOS** | Hobby OS with a graphical desktop, applications, and its own userspace | https://github.com/klange/toaruos |
| **Haiku** | Open-source continuation inspired by BeOS, with a distinctive desktop environment | https://github.com/haiku/haiku |
| **Collapse OS** | Tiny Z80-based OS designed around extreme hardware/resource constraints | https://github.com/emptymalei/collapseos |
| **Twilight OS** | Experimental OS project with a very different approach from mainstream Linux distributions | https://github.com/akashKarmakar02/twilight_os |
| **Nost_Gia_OS** | Experimental/educational OS project to explore another custom OS design | https://github.com/seanpm2001/Nost_Gia_OS |
| **XOS** | Experimental operating-system project for low-level OS experimentation | https://github.com/Anand-M-P/eXperimental_Operating_System_XOS |

### ⭐ Good VM experiments

- **SerenityOS** — great for exploring a completely independent desktop OS.
- **Redox OS** — especially interesting if you want to mess with Rust-based OS internals.
- **ToaruOS** — fun for seeing how a hobby OS can grow into a usable graphical system.
- **Haiku** — excellent for a BeOS-style desktop experience.
- **Collapse OS** — the weirdest one here; very different from a normal PC Linux distro.

## More OSes

This repo is meant to grow beyond ObsidianOS. Future workflows can cover different distributions, bases, installers, ISO builders, VM experiments, and OS forks.

> **One repo. Many OSes. Lots of experiments.** 🚀
