# AgentHound Homebrew tap

This repository is the release-managed Homebrew tap for
[AgentHound](https://github.com/adithyan-ak/AgentHound). GoReleaser writes the
collector and server formulas to `Formula/` for each tagged AgentHound release.

```bash
brew tap adithyan-ak/agenthound
brew install adithyan-ak/agenthound/agenthound
brew install adithyan-ak/agenthound/agenthound-server
```

The fully-qualified formula names are intentional: Homebrew requires them for
third-party taps that the user has not explicitly trusted.
