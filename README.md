chocolatey-recipe
=================

Chocolatey


## Usage

### Install

1. Install chocolatey by following https://chocolatey.org/
2. Install packages

  ```
  $ Invoke-WebRequest -Uri "https://raw.githubusercontent.com/takkyuuplayer/chocolatey-recipe/master/packages.config" -OutFile "packages.config"
  $ choco install .\packages.config -y
  ```

### Upgrade packages

```
$ choco upgrade all -y
```

### Export packages

Use ChocolateyGUI's export feature