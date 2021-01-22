# RaidTheWeb's Personal Package Repository (raidtheweb.pkg.repo)

Add the source with: `sudo pkg addsource https://raw.githubusercontent.com/RaidTheWeb/raidtheweb.pkg.repo/main/packagelist.json` or you can `sudo su root` and do the same command without sudo.

CobraOS will automaticaly install your packages when requested, `sudo pkg install <packagename>` or if already in root, `pkg install <packagename>`

Feel free to clone this repo and create your own cobraos package repo. Tutorial will be posted in a seperate repo on the @cobrasys github org.

quick overview:

```
stdout = access to terminal.
args = access to args to program.
user = user id. (for special permissions)

all packages are run by default async (use await not .then())
```
