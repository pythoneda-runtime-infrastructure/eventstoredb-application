# runtime-infrastructure/eventstoredb-application

This package provides the application layer of <https://github.com/pythoneda-runtime-infrastructure/eventstoredb>.

## How to declare it in your flake

Check the latest tag of the definition repository: https://github.com/pythoneda-runtime-infrastructure-def/evenstoredb-application/tags, and use it instead of the `[version]` placeholder below.

```nix
{
  description = "[..]";
  inputs = rec {
    [..]
    pythoneda-runtime-infrastructure-eventstoredb-application = {
      [optional follows]
      url =
        "github:pythoneda-runtime-infrastructure-def/eventstoredb-application/[version]";
    };
  };
  outputs = [..]
};
```

If your project depends upon [https://github.com/nixos/nixpkgs](nixpkgs "nixpkgs") and/or [https://github.com/numtide/flake-utils](flake-utils "flake-utils"), you might want to pin them under the `[optional follows]` above.

The Nix flake is provided by the [https://github.com/pythoneda-runtime-infrastructure-def/eventstoredb-application](pythoneda-runtime-infrastructure-def/eventstoredb-application "pythoneda-runtime-infrastructure-def/eventstoredb-application") repository.
