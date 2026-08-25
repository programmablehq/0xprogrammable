<p align="center">
  <a href="https://programmable.market" aria-label="Open Programmable">
    <picture>
      <source
        media="(prefers-reduced-motion: reduce)"
        srcset="./assets/profile/programmable-github-profile-night-garden-v3.png"
      />
      <img
        src="./assets/profile/programmable-github-profile-night-garden-v4.gif"
        alt="Programmable's white loop mark above a colorful night garden while small round stars twinkle in a black sky"
        width="100%"
      />
    </picture>
  </a>
</p>

<h1 align="center">Programmable</h1>

<h3 align="center">Shape what assets can do</h3>

<p align="center">
  Programmable is an open launch system for Uniswap v4 on Ethereum. Explore public launches, create with an available
  launch model, or use the Custom Launch API to prepare an exact Router action for a wallet.
</p>

<p align="center">
  <a href="https://programmable.market"><strong>Open Programmable</strong></a>
  &nbsp;·&nbsp;
  <a href="https://programmable.market/explore">Explore</a>
  &nbsp;·&nbsp;
  <a href="https://programmable.market/markets">Prediction markets</a>
  &nbsp;·&nbsp;
  <a href="https://programmable.market/launch">Create</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/0xprogrammable/Hookbuilder-Skill">Builder</a>
  &nbsp;·&nbsp;
  <a href="https://programmable.market/developers/custom-launch-api-v1.md">Custom Launch API</a>
  &nbsp;·&nbsp;
  <a href="https://programmable.market/docs">Docs</a>
</p>

<br />

## Start with what you want to do

| Goal | Start here |
| --- | --- |
| Explore launches and their public records | [Explore](https://programmable.market/explore) |
| Create or trade a prediction market | [Prediction Markets](https://programmable.market/markets) |
| Create with an available launch model | [Create](https://programmable.market/launch) |
| Build and check a Uniswap v4 project | [Programmable v4 Builder](https://github.com/0xprogrammable/Hookbuilder-Skill) |
| Create or revoke a wallet-bound API key | [API key management](https://programmable.market/developers/api-keys) |
| Prepare a Custom launch | [Custom Launch API guide](https://programmable.market/developers/custom-launch-api-v1.md) |
| Read the versioned launch requirements | [Programmable Launch Policy](https://github.com/0xprogrammable/Launch-Policy) |
| Integrate verified launch data | [Developer documentation](https://programmable.market/docs/developers) |

## Prediction Markets

Open the product to create or trade a market. The dedicated open-source repository is the source of truth for current
supported markets, networks, contracts, release evidence and technical boundaries.

[Open Prediction Markets](https://programmable.market/markets)<br />
[Read the current source and release record](https://github.com/0xprogrammable/Prediction-Markets)

## Build from plain language

<p align="center">
  <a href="https://github.com/0xprogrammable/Hookbuilder-Skill">
    <img
      src="./assets/profile/programmable-builder-skill-v4.jpg"
      alt="A path branches into several mechanisms inside the Programmable night garden"
      width="100%"
    />
  </a>
</p>

[Programmable v4 Builder](https://github.com/0xprogrammable/Hookbuilder-Skill) is a portable Agent Skill for turning an idea
or an existing repository into a complete project with explicit evidence. It can model hooks, tokens, apps, games,
services, settlement systems and mixed projects without forcing the idea into a fixed catalog.

The Builder repository owns installation, release verification, and the build-and-check workflow. It does not create or
submit a Custom Launch API request. A short starting request is enough:

```text
Use Programmable v4 Builder. Build and check this project against the current Programmable Launch Policy. Stop before
any API submission, external write, wallet signature, or broadcast: <idea or public GitHub URL>
```

[Install the current Builder release](https://github.com/0xprogrammable/Hookbuilder-Skill#install-the-builder)<br />
[Read the Agent Skill guide](https://github.com/0xprogrammable/Hookbuilder-Skill/blob/main/docs/AGENT_SKILL.md)

## One responsibility per repository

| Repository | What it owns |
| --- | --- |
| [PROGRAMMABLE](https://github.com/0xprogrammable/PROGRAMMABLE) | Application, contracts, public read model and release evidence |
| [Prediction-Markets](https://github.com/0xprogrammable/Prediction-Markets) | Prediction market contracts, tests and current release evidence |
| [Hookbuilder-Skill](https://github.com/0xprogrammable/Hookbuilder-Skill) | Agent Skill and local tools for building reproducible Uniswap v4 projects |
| [Launch-Policy](https://github.com/0xprogrammable/Launch-Policy) | Versioned launch requirements, policies and machine-readable evidence contracts |
| [Developers](https://github.com/0xprogrammable/Developers) | Discovery manifest, API contracts and direct verification rules for integrations |

## Launch Custom projects through the API

New Custom launches use a wallet-bound API key instead of a GitHub application pull request. The Builder can build and
check a project against the [Programmable Launch Policy](https://github.com/0xprogrammable/Launch-Policy). An agent or
developer then constructs the request from the project artifacts and the live
[Custom Launch API](https://programmable.market/developers/custom-launch-api-v1.md) schema.

The API validates the submitted commitments and prepares the exact Router action for the API key's bound wallet. An API
key cannot sign or broadcast a transaction. The wallet controller must review, sign and broadcast the prepared action.
Preparation is not an audit, safety claim, listing guarantee or Uniswap endorsement.

## Integrate without guessing

<p align="center">
  <a href="https://programmable.market/docs/developers">
    <img
      src="./assets/profile/programmable-profile-ecosystem-v4.jpg"
      alt="Distinct flowering islands connected through one coherent Programmable night garden"
      width="100%"
    />
  </a>
</p>

[Programmable Developers](https://github.com/0xprogrammable/Developers) defines the Router-first verification path,
versioned manifest, read-only API contracts and failure rules used by external apps. Integrations preserve canonical
launch identity and treat market data as optional enrichment rather than inventing support from names or metadata.
This unauthenticated discovery surface is separate from the authenticated Custom Launch API.

[Open the developer documentation](https://programmable.market/docs/developers)<br />
[Read the public specification](https://github.com/0xprogrammable/Developers)

<br />

<p align="center">
  <a href="https://programmable.market">Website</a>
  &nbsp;·&nbsp;
  <a href="https://programmable.market/explore">Explore</a>
  &nbsp;·&nbsp;
  <a href="https://programmable.market/launch">Create</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/0xprogrammable/Hookbuilder-Skill">Builder</a>
  &nbsp;·&nbsp;
  <a href="https://programmable.market/developers/custom-launch-api-v1.md">Custom Launch API</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/0xprogrammable/Launch-Policy">Launch policy</a>
  &nbsp;·&nbsp;
  <a href="https://programmable.market/docs">Docs</a>
  &nbsp;·&nbsp;
  <a href="https://x.com/0xprogrammable">X</a>
</p>
