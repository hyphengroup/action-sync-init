# `sync-init` GitHub Action

Used in combination with `sync` action to track and commit generated changes.

## Usage

```
steps:
  - uses: actions/checkout@v2
  - uses: hyphengroup/action-sync-init@v0.1.0
  - run: cag generate
  - uses: hyphengroup/action-sync@v0.1.0
```
