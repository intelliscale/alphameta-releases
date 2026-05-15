# AlphaMeta Releases

Public binary releases for AlphaMeta — an agentic trading tool for Interactive Brokers.

## Download

Each [release](https://github.com/intelliscale/alphameta-releases/releases) includes:

- \`alphameta-{version}-macos-arm64.tar.gz\` — compiled binary for macOS ARM64
- \`checksums.txt\` — SHA-256 checksums

## Installation

\`\`\`bash
curl -fsSL https://github.com/intelliscale/alphameta-releases/releases/latest/download/alphameta-{version}-macos-arm64.tar.gz | tar xz
sudo mv alphameta /usr/local/bin/
\`\`\`

## Verification

\`\`\`bash
shasum -a 256 -c checksums.txt
\`\`\`
