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

- [archives](https://github.com/git-pkgs/archives) - Reading and browsing archive files in memory
- [changelog](https://github.com/git-pkgs/changelog) - Parsing changelog files into structured entries
- [enrichment](https://github.com/git-pkgs/enrichment) - Fetching package metadata from multiple sources
- [forges](https://github.com/git-pkgs/forges) - Fetching repository metadata from git forges
- [gitignore](https://github.com/git-pkgs/gitignore) - Matching paths against gitignore rules
- [managers](https://github.com/git-pkgs/managers) - Wrapping package manager CLIs behind a common interface
- [manifests](https://github.com/git-pkgs/manifests) - Parsing package manager manifest and lockfiles
- [platforms](https://github.com/git-pkgs/platforms) - Translating platform identifiers across package ecosystems
- [purl](https://github.com/git-pkgs/purl) - Package URL construction, parsing, and registry URL mapping
- [registries](https://github.com/git-pkgs/registries) - Fetching package metadata from registry APIs
- [spdx](https://github.com/git-pkgs/spdx) - SPDX license expression parsing, normalization, and validation
- [vers](https://github.com/git-pkgs/vers) - Version range parsing and comparison per the VERS spec
- [vulns](https://github.com/git-pkgs/vulns) - Fetching vulnerability data from multiple sources
