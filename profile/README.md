[git-pkgs](https://github.com/git-pkgs/git-pkgs) tracks package dependencies across your repository's git history. It answers questions like "who added this dependency?", "when was it introduced?", and "how long were we exposed to this vulnerability?" Works with 35+ package managers.

Install it with:

```bash
brew tap git-pkgs/git-pkgs
brew install git-pkgs
```

Or download a binary from the [releases page](https://github.com/git-pkgs/git-pkgs/releases).

Or build from source:

```bash
go install github.com/git-pkgs/git-pkgs@latest
```

### Libraries

- [managers](https://github.com/git-pkgs/managers) - Go library wrapping package manager CLIs behind a common interface
- [manifests](https://github.com/git-pkgs/manifests) - Go library for parsing package manager manifest and lockfiles
- [purl](https://github.com/git-pkgs/purl) - Go library for Package URL construction, parsing, and registry URL mapping
- [registries](https://github.com/git-pkgs/registries) - Go library for fetching package metadata from registry APIs
- [spdx](https://github.com/git-pkgs/spdx) - Go library for SPDX license expression parsing and normalization
- [vers](https://github.com/git-pkgs/vers) - Version range parsing and comparison per the VERS spec
