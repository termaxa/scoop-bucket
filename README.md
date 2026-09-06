# termaxa Scoop bucket

```
scoop bucket add termaxa https://github.com/termaxa/scoop-bucket
scoop install termaxa
```

Installs the prebuilt Windows binary from [GitHub Releases](https://github.com/termaxa/termaxa/releases), pinned by sha256. The hash in `bucket/termaxa.json` is computed from the downloaded release asset for every version, never copied; Scoop checks it again on your machine before installing.

Termaxa is a cooperative gate for the shell commands AI coding agents run — it previews the blast radius, backs up first, blocks the dangerous ones, and escalates repeat offenders. Docs and threat model: https://github.com/termaxa/termaxa

To update: `scoop update termaxa`.
