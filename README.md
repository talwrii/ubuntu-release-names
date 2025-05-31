# Ubuntu release names
**@readwithai** - [X](https://x.com/readwithai) - [blog](https://readwithai.substack.com/) - [machine-aided reading](https://www.reddit.com/r/machineAidedReading/) - [📖](https://readwithai.substack.com/p/what-is-reading-broadly-defined
)[⚡️](https://readwithai.substack.com/s/technical-miscellany)[🖋️](https://readwithai.substack.com/p/note-taking-with-obsidian-much-of)

Fetch the Ubuntu release names from Wikipedia and print to the command-line.

## Motivation
This is kind of a joke about all these names being annoying to look up and remember (always yet another Ubuntu release name). This was particularly annoying when looking for packages across multiple versions.

## Installation
```
pipx install ubuntu-release-names
```

## Usage
You can output all the release names with:
```
ubuntu-release-names
```

The finall column is whether the relase is a long term release.

You can output the versions in `--json`

```
ubuntu-release-names
```

## Caveats
This is machine parsing of human-readable data. An LLM would probably be more reliable, but then I would have to deal with API keys. Bet it doesn't break for a long time tho.

# About
I am @readwithai. I make tools for reading, research and agency. I am on [X](https://x.com/readwithai) and have a [blog](https://readwithai.substack.com/).
