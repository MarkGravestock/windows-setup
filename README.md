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

``` Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression```

```scoop install nvm```

```nvm install 18```

##### Java

```scoop bucket add java```

See [JDK 21 Example](https://scoop.sh/#/apps?q=java+21)

#### Linux

```wsl --install``` - Currently installs Ubuntu 22.04

[Full WSL installation details](https://learn.microsoft.com/en-us/windows/wsl/install)

[Detailed Linux/Ubuntu Installation](https://github.com/MarkGravestock/linux-setup)
