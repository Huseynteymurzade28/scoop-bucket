# scoop-bucket

[Scoop](https://scoop.sh) manifests for Windows builds of my projects.

```powershell
scoop bucket add huseynteymurzade28 https://github.com/Huseynteymurzade28/scoop-bucket
scoop install huseynteymurzade28/pomtex
```

| App | |
| --- | --- |
| [butaglyph](https://github.com/Huseynteymurzade28/butaglyph) | Fast prompt for PowerShell, bash, zsh and fish (the command is `buta`) |
| [pokeductor](https://github.com/Huseynteymurzade28/pokeductor) | Terminal Pokedex and evolution analyzer |
| [pomtex](https://github.com/Huseynteymurzade28/pomtex) | On-demand LaTeX: a portable TeX kernel that installs CTAN packages only when a document needs them |
| [tuiba](https://github.com/Huseynteymurzade28/tuiba) | Game Boy Advance emulator running in your terminal |

Update with `scoop update <app>`. A daily workflow picks up new releases, installs them on a fresh Windows runner and pushes the manifest only if that works.
