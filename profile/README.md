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

### Tools

- [brief](https://github.com/git-pkgs/brief) - Detect a project's toolchain, configuration, and conventions
- [capcheck](https://github.com/git-pkgs/capcheck) - Fail CI when Go code or dependencies gain new privileged operations
- [licenses](https://github.com/git-pkgs/licenses) - Scan repositories for license text using ScanCode's rule corpus
- [outline](https://github.com/git-pkgs/outline) - Reduce a source tree to a structural skeleton for LLM context
- [pin](https://github.com/git-pkgs/pin) - Vendor browser assets without npm
- [proxy](https://github.com/git-pkgs/proxy) - Lightweight caching proxy for package registries

### Libraries

- [archives](https://github.com/git-pkgs/archives) - Reading and browsing archive files in memory
- [attestation](https://github.com/git-pkgs/attestation) - Parsing SLSA provenance v1 attestation bundles
- [changelog](https://github.com/git-pkgs/changelog) - Parsing changelog files into structured entries
- [cooldown](https://github.com/git-pkgs/cooldown) - Filtering package versions by minimum age across ecosystems
- [enrichment](https://github.com/git-pkgs/enrichment) - Fetching package metadata from multiple sources
- [forge](https://github.com/git-pkgs/forge) - Fetching repository metadata from git forges
- [gitignore](https://github.com/git-pkgs/gitignore) - Matching paths against gitignore rules
- [managers](https://github.com/git-pkgs/managers) - Wrapping package manager CLIs behind a common interface
- [manifests](https://github.com/git-pkgs/manifests) - Parsing package manager manifest and lockfiles
- [markup](https://github.com/git-pkgs/markup) - Rendering markup files to HTML
- [platforms](https://github.com/git-pkgs/platforms) - Translating platform identifiers across package ecosystems
- [pom](https://github.com/git-pkgs/pom) - Resolving effective POMs for Maven artifacts
- [purl](https://github.com/git-pkgs/purl) - Package URL construction, parsing, and registry URL mapping
- [registries](https://github.com/git-pkgs/registries) - Fetching package metadata from registry APIs
- [resolve](https://github.com/git-pkgs/resolve) - Parsing package manager resolve output into dependency trees
- [reuse](https://github.com/git-pkgs/reuse) - Extracting SPDX license and copyright data from REUSE-compliant projects
- [sbom](https://github.com/git-pkgs/sbom) - Reading and writing Software Bill of Materials documents
- [sigstore](https://github.com/git-pkgs/sigstore) - Verifying attestation bundles against the Sigstore TUF trust root
- [spdx](https://github.com/git-pkgs/spdx) - SPDX license expression parsing, normalization, and validation
- [vers](https://github.com/git-pkgs/vers) - Version range parsing and comparison per the VERS spec
- [vulns](https://github.com/git-pkgs/vulns) - Fetching vulnerability data from multiple sources

### Integrations

- [actions](https://github.com/git-pkgs/actions) - Reusable GitHub Actions for git-pkgs dependency analysis
- [skills](https://github.com/git-pkgs/skills) - Claude Code skills plugin for git-pkgs and brief
