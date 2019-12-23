# react-from-svg

[![Repo on GitHub](https://img.shields.io/badge/repo-GitHub-3D76C2.svg)](https://github.com/MoOx/react-from-svg)
[![Repo on GitLab](https://img.shields.io/badge/repo-GitLab-6C488A.svg)](https://gitlab.com/MoOx/react-from-svg)

> Turns SVG files into React Native (Web) (+ optional ReasonML) components

## Usage

```console
react-from-svg [sourcePath] [outputPath] [--with-reason] [--remove-fill]
```

### Examples

Just React Native / React Native Web SVGs, with fill svg props removed, nice for icons

```console
react-from-svg assets/svgs src/Svgs --remove-fill
```

React Native (Web) + ReasonML bindings SVGs

```console
react-from-svg assets/svgs src/Svgs --with-reason
```

