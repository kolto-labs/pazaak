# pazaak

The card game from KOTOR, playable in Discord and in the browser, with a fake-credit economy.

## Scope

- Rules packages (engine, policy, rating, tournament), published to npm so other projects can reuse the rules
- Discord bot
- Matchmaking and match authority on Cloudflare Workers Durable Objects
- Nakama module
- One web client

## Contracts

- Sign-in: client of the org-wide OpenID Connect service. No login code lives here.
- Discord plumbing: `kolto-bot-kit`.

## Status

Scaffold. Code is being migrated from `OpenKotOR/community-bots` with history, one draft pull request at a time.

Kolto Labs is an independent, non-commercial fan project, not affiliated with Lucasfilm, Disney, BioWare, Electronic Arts, Obsidian, Aspyr or Saber Interactive. This repository contains no game assets.
