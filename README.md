# metalhud

[![MIT License](https://badgen.net/github/license/timkurvers/metalhud)](LICENSE.md)

<img align="right" width="200" src="https://user-images.githubusercontent.com/378235/202293687-e3bb9558-439c-4bae-b52c-78ca2b33606f.png" />

Quickly enable/disable the Metal 3 Performance HUD as outlined in [MrMacRight's excellent video].

Requires **macOS Ventura 13**.

As opposed to enabling the HUD for each individual game or application, this binary sets the env
variable `MTL_HUD_ENABLED` globally to apply to any Metal 3 context.

## Installation

Add as a bundle through [Antigen]:

```shell
antigen bundle timkurvers/metalhud
```

## Usage

```shell
metalhud on
metalhud off
```

[Antigen]: https://github.com/zsh-users/antigen
[MrMacRight's excellent video]: https://www.youtube.com/watch?v=OtOjIrBpvrI
