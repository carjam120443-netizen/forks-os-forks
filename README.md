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

## More OSes

This repo is meant to grow beyond ObsidianOS. Future workflows can cover different distributions, bases, installers, ISO builders, VM experiments, and OS forks.

> **One repo. Many OSes. Lots of experiments.** 🚀
