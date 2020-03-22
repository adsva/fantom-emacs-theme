# Fantom Theme for Emacs

Dark theme based of the VSCode theme
[Phantom Code](https://marketplace.visualstudio.com/items?itemName=tourervit.phantom).

## Installation

Fantom is available in MELPA

```
M-x package-install fantom-theme
```

To load on startup, add this to your init file:

```
(load-theme 'fantom-theme t)
```

Or via `use-package`:

```
(use-package fantom-theme
  :ensure t
  :config
  (load-theme 'fantom-theme t))
```
