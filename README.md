# iOS 26 release gate

This public repository is a workflow-only release-verification surface. It contains no application or dependency source.

The manual workflow checks out immutable revisions of three private repositories through separate read-only deploy keys, runs the current macOS 26 / iOS 26 build and test gate, and uploads no artifacts. The private key halves are stored only as encrypted GitHub Actions secrets.

Current pinned revisions:

- mobile app: `1fc431dce3659720958c39085de44b12d9d5eabc`
- token kit: `ad72cec20dc7aaebc8c370fdf4945fb4de04b266`
- Papercusp design tokens: `ffc6da5355a34d9652538fcbe1f64508e41191cf`
