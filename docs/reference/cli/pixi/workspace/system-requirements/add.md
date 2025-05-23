<!--- This file is autogenerated. Do not edit manually! -->
# <code>[pixi](../../../pixi.md) [workspace](../../workspace.md) [system-requirements](../system-requirements.md) add</code>

## About
Adds an environment to the manifest file

--8<-- "docs/reference/cli/pixi/workspace/system-requirements/add_extender:description"

## Usage
```
pixi workspace system-requirements add [OPTIONS] <REQUIREMENT> <VERSION>
```

## Arguments
- <a id="arg-<REQUIREMENT>" href="#arg-<REQUIREMENT>">`<REQUIREMENT>`</a>
:  The name of the system requirement to add
<br>**required**: `true`
<br>**options**: `linux`, `cuda`, `macos`, `glibc`, `other-libc`
- <a id="arg-<VERSION>" href="#arg-<VERSION>">`<VERSION>`</a>
:  The version of the requirement
<br>**required**: `true`

## Options
- <a id="arg---family" href="#arg---family">`--family <FAMILY>`</a>
:  The Libc family, this can only be specified for requirement `other-libc`
- <a id="arg---feature" href="#arg---feature">`--feature (-f) <FEATURE>`</a>
:  The name of the feature to modify

--8<-- "docs/reference/cli/pixi/workspace/system-requirements/add_extender:example"
