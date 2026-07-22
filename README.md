<p align="center">
  <img src="apki/assets/apki_circle.png" alt="ApKI" width="140">
</p>

<h1 align="center">ApKI — Apple Knowledge Index</h1>

<p align="center">
  <img alt="AI Agents - Skill" src="https://img.shields.io/badge/AI--Agents-Skill-EF9035?style=flat">
  <a href="LICENSE"><img alt="MIT License" src="https://img.shields.io/badge/License-MIT-blue?style=flat"></a>
  <a href="https://www.linkedin.com/in/wolfgang-muhsal-12408194/"><img alt="LinkedIn" src="https://img.shields.io/badge/Contact-LinkedIn-95a5a6.svg?style=flat"></a>
</p>

ApKI is a compact routing skill for current, official Apple developer resources. It indexes Apple Developer videos, framework documentation, Swift, Human Interface Guidelines, sample code, technology overviews, Apple Open Source, and curated Apple/SwiftLang open-source repositories without copying the underlying documentation into the skill.

## Installing ApKI

Install the skill with `npx`:

```bash
npx skills add https://github.com/Gucky/ApKI --skill apki
```

To install it globally for Codex:

```bash
npx skills add https://github.com/Gucky/ApKI --skill apki --agent codex --global
```

For a specific agent:

```bash
npx skills add https://github.com/Gucky/ApKI --skill apki --agent claude-code
```

For all supported agents:

```bash
npx skills add https://github.com/Gucky/ApKI --skill apki --agent '*'
```

If `npx` is not available, install Node.js first. On macOS with Homebrew:

```bash
brew install node
```

## Using ApKI

Invoke the skill directly:

```text
$apki
```

Or ask naturally, for example: “Find the official Apple documentation and WWDC sessions for `AsyncImage`, StoreKit subscriptions, or App Intents.”

ApKI provides:

- a complete Apple Developer video catalogue;
- a directory of Apple frameworks and technologies;
- focused component indexes for common Apple-platform development tasks;
- curated Apple and SwiftLang libraries, developer tooling, toolchain references, and evolution resources;
- direct routes to HIG, sample code, technology overviews, and Apple Open Source.

## Requirements

- Node.js for `npx`
- An AI coding assistant that supports agent skills
- Internet access for following Apple source links

## License

ApKI was created by [Wolfgang Muhsal](https://github.com/Gucky). It is available under the [MIT License](LICENSE), which permits commercial use, modification, distribution, and private use.

The MIT License applies to ApKI’s original content and structure.

Apple and SwiftLang repository descriptions, documentation, videos, sample code, trademarks, and other linked materials remain subject to their applicable terms and licenses. Apple-provided video summaries in ApKI identify their linked Apple video pages and remain subject to those same terms. ApKI is an independent project and is not affiliated with or endorsed by Apple Inc.
