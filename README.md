# scoop-bucket

[Scoop](https://scoop.sh) manifests for Windows builds of my projects.

```powershell
scoop bucket add huseynteymurzade28 https://github.com/Huseynteymurzade28/scoop-bucket
scoop install huseynteymurzade28/pomtex
```

| App | |
| --- | --- |
| [pomtex](https://github.com/Huseynteymurzade28/pomtex) | On-demand LaTeX: a portable TeX kernel that installs CTAN packages only when a document needs them |

Update with `scoop update pomtex`. A daily workflow picks up new releases, installs them on a fresh Windows runner and pushes the manifest only if that works.
