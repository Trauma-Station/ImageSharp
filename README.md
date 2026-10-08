<h1 align="center">

<img src="https://github.com/SixLabors/Branding/raw/main/icons/imagesharp/sixlabors.imagesharp.svg?sanitize=true" alt="SixLabors.ImageSharp" width="256"/>
<br/>
TraumaStation.ImageSharp
</h1>

<div align="center">

[![Build Status](https://img.shields.io/github/actions/workflow/status/Trauma-Station/ImageSharp/build-and-test.yml?branch=main)](https://github.com/Trauma-Station/ImageSharp/actions)
[![codecov](https://codecov.io/gh/SixLabors/ImageSharp/graph/badge.svg?token=g2WJwz770q)](https://codecov.io/gh/SixLabors/ImageSharp)
[![License: Six Labors Split](https://img.shields.io/badge/license-Six%20Labors%20Split-%23e30183)](https://github.com/SixLabors/ImageSharp/blob/main/LICENSE)

</div>

### *TraumaStation*'s **ImageSharp** fork is a high-performance, fully managed, cross-platform 2D graphics API.

ImageSharp is a mature, fully featured, high-performance image processing and graphics library for .NET, built for workloads across device, cloud, and embedded/IoT scenarios.

Designed from the ground up to balance performance, portability, and ease of use, ImageSharp provides a powerful yet approachable API for common image processing tasks, along with the low-level building blocks needed to extend the library for specialized workflows.

Built against **.NET 10**.

This **unofficial fork** has opinionated changes for Trauma Station, notably:
- Removed the stupid license begging for open source users.

The namespaces are still the same as upstream to keep code compatible and make it a drop-in replacement.

## License

ImageSharp is licensed under the [Six Labors Split License, Version 1.0](https://github.com/SixLabors/ImageSharp/blob/main/LICENSE)

## Support Six Labors Upstream

Support the efforts of the development of the upstream Six Labors projects.
 - [Purchase a Commercial License :heart:](https://sixlabors.com/pricing/)
 - [Become a sponsor via GitHub Sponsors :heart:]( https://github.com/sponsors/SixLabors)
 - [Become a sponsor via Open Collective :heart:](https://opencollective.com/sixlabors)

## Documentation

- [Detailed documentation](https://sixlabors.github.io/docs/) for the ImageSharp API is available. This includes additional conceptual documentation to help you get started.
- Their [Samples Repository](https://github.com/SixLabors/Samples/tree/main/SixLabors.Samples.ImageSharp) is also available containing buildable code samples demonstrating common activities.

## Questions

- Do you have questions? Please [join our their Discussions Forum](https://github.com/SixLabors/ImageSharp/discussions/categories/q-a). Do not open issues for questions.
- For feature ideas please [join their Discussions Forum](https://github.com/SixLabors/ImageSharp/discussions/categories/ideas) and we'll be happy to discuss.  
- Please read their [Contribution Guide](https://github.com/SixLabors/ImageSharp/blob/main/.github/CONTRIBUTING.md) before opening issues or pull requests!

## Installation 

Install stable releases via Nuget; development releases are available via MyGet.

| Package Name                   | Release (NuGet) | Nightly (Feedz.io) |
|--------------------------------|-----------------|-----------------|
| `TraumaStation.ImageSharp`         | [![NuGet](https://img.shields.io/nuget/v/TraumaStation.ImageSharp.svg)](https://www.nuget.org/packages/TraumaStation.ImageSharp/)

## Manual build

If you prefer, you can compile ImageSharp yourself (please do and help!)

- Using [Visual Studio 2022](https://visualstudio.microsoft.com/vs/)
  - Make sure you have the latest version installed
  - Make sure you have [the .NET 8 SDK](https://www.microsoft.com/net/core#windows) installed

Alternatively, you can work from command line and/or with a lightweight editor on **both Linux/Unix and Windows**:

- [Visual Studio Code](https://code.visualstudio.com/) with [C# Extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode.csharp)
- [.NET Core](https://www.microsoft.com/net/core#linuxubuntu)

To clone ImageSharp locally, click the "Clone in [YOUR_OS]" button above or run the following git commands:

```bash
git clone https://github.com/TraumaStation/ImageSharp
```

Then set the following config to ensure blame commands ignore mass reformatting commits.

```bash
git config blame.ignoreRevsFile .git-blame-ignore-revs
```

If working with Windows please ensure that you have enabled long file paths in git (run as Administrator).

```bash
git config --system core.longpaths true
```

This repository uses [Git Large File Storage](https://docs.github.com/en/github/managing-large-files/installing-git-large-file-storage). Please follow the linked instructions to ensure you have it set up in your environment.

This repository contains [Git Submodules](https://blog.github.com/2016-02-01-working-with-submodules/). To add the submodules to the project, navigate to the repository root and type:

``` bash
git submodule update --init --recursive
```

## How can you help?

Contribute any changes upstream would appreciate [to them](https://github.com/SixLabors/ImageSharp), otherwise just make a PR here.
