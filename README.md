# VSCode

## Export extensions

__Unix:__

```bash
code --list-extensions | xargs -L 1 echo code --install-extension
```

__Windows (PowerShell, e. g. using Visual Studio Code's integrated Terminal):__

```powershell
code --list-extensions | % { "code --install-extension $_" }
```