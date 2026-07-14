# anvil.urda.com/forged-statusline

This repository receives and deploys the Forged Statusline website from build artifacts produced by an internal builder. Content arrives as workflow artifacts from the private builder via `repository_dispatch` events, downloaded by `deploy.yaml`, and deployed to GitHub Pages.

Live site: [https://anvil.urda.com/forged-statusline/](https://anvil.urda.com/forged-statusline/)

The Forged Statusline renderer itself (the bash script) is at [github.com/urda/forged-statusline](https://github.com/urda/forged-statusline).
