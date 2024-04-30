# zcmder-omp

A [Cmder](https://cmder.app/) inspired theme for [oh-my-posh](https://ohmyposh.dev).

This theme converges [zcmder](https://github.com/bwpge/zcmder) and [zcmder-pwsh](https://github.com/bwpge/zcmder-pwsh) and for a simpler, cross-platform solution.

## Installation

Clone this repository to a stable location, such as your home directory:

```sh
git clone https://github.com/bwpge/zcmder-omp.git
```

Then initialize your prompt with a remote config URL:

**zsh:**

```sh
eval "$(oh-my-posh init zsh --config 'https://raw.githubusercontent.com/bwpge/zcmder-omp/main/zcmder.omp.json')"
```

**PowerShell:**

```powershell
oh-my-posh init pwsh --config 'https://raw.githubusercontent.com/bwpge/zcmder-omp/main/zcmder.omp.json' | Invoke-Expression
```

Refer to the [oh-my-posh documentation](https://ohmyposh.dev/docs/installation/prompt) for shell-specific initialization.
