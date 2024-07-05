# Windows Setup

Development Orientated Setup

#### Winget Installs

Install in bulk

```winget import -i .\WinGet\winget.json```

Install individually e.g.

```winget install Docker.DockerDesktop```

```winget install JetBrains.Toolbox```

```winget install JAMSoftware.TreeSize.Free```

#### Scoop Installs

```iwr -useb get.scoop.sh | iex```

```scoop install nodejs```

#### Linux

```wsl --install``` - Currently installs Ubuntu 22.04

[Full WSL installation details](https://learn.microsoft.com/en-us/windows/wsl/install)

[Detailed Linux/Ubuntu Installation](https://github.com/MarkGravestock/linux-setup)
