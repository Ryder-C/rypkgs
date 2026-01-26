# rypkgs

Personal [NUR](https://github.com/nix-community/NUR) repository.

![Build and populate cache](https://github.com/Ryder-C/rypkgs/workflows/Build%20and%20populate%20cache/badge.svg)

## Usage

Add to your flake inputs:

```nix
{
  inputs.rypkgs.url = "github:Ryder-C/rypkgs";
}
```

Then access packages via `inputs.rypkgs.packages.${system}.<package-name>`.

### With NUR

```nix
{
  inputs.nur.url = "github:nix-community/NUR";
}
```

Then use `nur.repos.rypkgs.<package-name>`.

## Packages

| Package | Description |
|---------|-------------|
| `blink` | A modern Jellyfin desktop client |

