# n0mad-ai Homebrew tap

Homebrew formulas for [n0mad-ai](https://github.com/n0mad-ai) tools.

## Install

```bash
brew tap n0mad-ai/tap
brew install bastra-recall
```

## What's in here

| Formula | Source | Purpose |
|---|---|---|
| [`bastra-recall`](Formula/bastra-recall.rb) | [n0mad-ai/bastra-recall](https://github.com/n0mad-ai/bastra-recall) | Persistent teammate memory for AI assistants (Claude, ChatGPT, Cursor) — MCP server + REST gateway + `bastra` CLI |

## After install

Each formula's `caveats` block prints the post-install step. For `bastra-recall`:

```bash
bastra install all   # register with every supported AI client
bastra doctor        # verify the setup
```

## License

The formulas in this repo are MIT. Each linked source repo has its own license — check the upstream before redistributing.
