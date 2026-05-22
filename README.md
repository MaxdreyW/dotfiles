# dotfiles 🛠️

Personal dotfiles for Max — DevOps Engineer in training.

## What's inside

| File | Description |
|------|-------------|
| `.bashrc` | Bash configuration — history, prompt, PATH |
| `.gitconfig` | Git settings — user, aliases, editor |
| `aliases.sh` | Shell shortcuts for Git and navigation |

## How to use on a new machine

```bash
git clone git@github.com:MaxdreyW/dotfiles.git
cd dotfiles
cp .bashrc ~/
cp .gitconfig ~/
source aliases.sh
```

## Aliases

| Alias | Command |
|-------|---------|
| `gs` | `git status` |
| `ga` | `git add` |
| `gc` | `git commit -m` |
| `gp` | `git push` |
| `gl` | `git log --oneline` |
| `..` | `cd ..` |
