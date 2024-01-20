# TeqBench Sandbox Library Solution/Project Template

![Build Status Badge](.badges/build-status.svg) ![Build Number Badge](.badges/build-number.svg) ![Coverage](.badges/code-coverage.svg)

## Overview

Template repository for a .NET library sandbox including unit tests.

> [!NOTE]
> After cloning, remember to init/update the submodules. See [https://github.com/teqbench/teqbench.dev](https://github.com/teqbench/teqbench.dev) for more information.

### Update Template Names

Update all following instances of `TeqBench.Dev.Templates.Sandbox.DotNet.Library`:

- Solution name
    - TeqBench.Dev.Templates.Sandbox.DotNet.Library.sln
- Project names
    - TeqBench.Dev.Templates.Sandbox.DotNet.Library.csproj
    - TeqBench.Dev.Templates.Sandbox.DotNet.Library.Tests.csproj
- RootNamespace in TeqBench.Dev.Templates.Sandbox.DotNet.Library.csproj
- AssemblyName in TeqBench.Dev.Templates.Sandbox.DotNet.Library.csproj

### Update Repository Settings

Also have to update repository's settings.

- Add branch protect for the `main` branch.
    - Navigate to `Settings > Branches`.
    - Select `Add rule`.
    - Select `Require a pull request before merging`.
    - Leave all other settings as default values.
    - Select `Save`.
- Update Actions configuration.
    - Navigate to `Settings > Actions > General`.
    - Select `Allow teqbench, and select non-teqbench, actions and reusable workflows`
        - Select `Allow actions created by GitHub`.
    - Select `Save`.
    - Leave all other settings as default values.


## Contents
- [Developer Environment Setup](#Developer+Environment+Setup)
- [Usage](#Usage)
- [License](#License)

## Developer Environment Setup

### General
- [Branching Strategy & Practices](https://github.com/teqbench/teqbench.docs/wiki/Branching-Strategy)

### .NET
- [General Tooling](https://github.com/teqbench/teqbench.docs/wiki/.NET-General-Tooling)
- [Configurations](https://github.com/teqbench/teqbench.docs/wiki/.NET-Configuration-Standards)
- [Coding Standards](https://github.com/teqbench/teqbench.docs/wiki/.NET-Coding-Standards)
- [Solutions](https://github.com/teqbench/teqbench.docs/wiki/.NET-Solutions)
- [Projects](https://github.com/teqbench/teqbench.docs/wiki/.NET-Projects)
- [Building](https://github.com/teqbench/teqbench.docs/wiki/.NET-Build-Process)
- [Versioning](https://github.com/teqbench/teqbench.docs/wiki/.NET-Versioning-Standards)

## Licensing

[License](https://github.com/teqbench/teqbench.docs/wiki/License)
