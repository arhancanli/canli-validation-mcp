# Where this code lives

This repository is the standalone home of the `canli-validation-mcp` package, published so the
server can be installed, scanned and reviewed on its own. It is imported from the `mcp/`
directory of [arhancanli/canlicapital](https://github.com/arhancanli/canlicapital/tree/main/mcp),
which is where changes are made and tested; this repository is updated from it.

Imported from canlicapital commit `d4d0014797c59bc910ff57d1396e14ebecab2762` (tag `mcp-v0.8.1`).

- npm: https://www.npmjs.com/package/canli-validation-mcp
- MCP Registry: `io.github.arhancanli/canli-validation-mcp`
- Hosted endpoint (no install): https://canlicapital.com/mcp

The Claude Desktop bundle attached to each release is built by `mcp/mcpb/build.sh` in the
canlicapital repository, from its committed files.

Files owned by this repository and kept across syncs: `.github/` (CI, CodeQL, OpenSSF Scorecard,
Dependabot, and the release workflow that builds, signs and attaches the Claude Desktop bundle),
`MIRROR.md`, `glama.json`, and the digest-pinned base image in `Dockerfile`.
