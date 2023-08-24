# fossa-diff-demo

This repository demonstrates how to use FOSSA's `fossa test --diff` command

## How to do it

- [ ] Clone this repository
- [ ] Grab your FOSSA API token from your account settings in app.fossa.com
- [ ] Given that you have the CLI, you can run a diff in these ways:
  - [ ] If you're on the latest commit, run `fossa test --diff 899eac07b5c406b7a0c15014b58c9b06d54c8228`. `899eac07b5c406b7a0c15014b58c9b06d54c8228` is a previous commit.
  - [ ] Similarly, you can explicitly define two revisions (commits). In this case we specify the latest commit as the revision and we want to compare it to an older commit, so we diff it: `fossa test --diff 899eac07b5c406b7a0c15014b58c9b06d54c8228 --revision 8e8343997f0a5ddf738589a37a8e4cd9fc081959`
- [ ] If you don't have this repository cloned, but you know it's been scanned before, you can run `fossa test --project https://github.com/cmboling/fossa-diff-demo.git --diff 899eac07b5c406b7a0c15014b58c9b06d54c8228 --revision 8e8343997f0a5ddf738589a37a8e4cd9fc081959`
