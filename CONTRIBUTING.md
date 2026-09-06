# Contributing

Thanks for helping keep this list accurate. Corrections matter as much as additions here, and that includes corrections to servers that compete with RankSpot.

## What gets listed

An MCP server qualifies if all three are true:

1. **It exists and runs.** A public repo, a published package, or a live hosted endpoint. Not a roadmap item, not a waitlist, not a blog post announcing plans.
2. **It speaks MCP.** A REST API is not an MCP server. If there is no MCP interface, it does not belong here.
3. **It is useful for SEO.** Search data, crawl data, ranking data, backlink data, analytics, indexing, or AI search visibility.

## What does not get listed

- Agent skills and slash commands. Those belong in a skills list, not here.
- Standalone SEO tools with no MCP interface.
- Dead links, archived repos with no successor, and servers that have not worked for a year. If a listed server dies, we move it to [Archived or superseded](README.md#archived-or-superseded) rather than deleting it, so people stop rediscovering it.

## Adding an entry

Open a PR that adds one row to the right table. Keep the row in descending star order within its section, or alphabetical for vendor servers with no repo.

```
| [owner/repo](https://github.com/owner/repo) | What it does in one line | Local | API key | 0 | 2026-09-06 |
```

Fill the columns like this:

- **What it does**: one line, plain language, no marketing. Say what data it exposes.
- **Type**: `Remote` for a hosted URL, `Local` for something that runs on the user's machine.
- **Auth**: `OAuth`, `API key`, `Google OAuth`, `Paid licence`, or `None`.
- **Stars** and **Updated**: put anything in, a workflow refreshes both weekly.

If it is a remote server, also add the endpoint to the endpoints table so people do not have to hunt for it.

## Self-submissions

Submitting your own server is fine and encouraged. Say so in the PR description, describe it factually, and put it in star order like everything else. Entries that oversell get edited down, not rejected.

## Corrections

Open an issue or a PR for anything wrong: a dead link, a rename, a server that moved to a new maintainer, a wrong auth method, an official server we listed as community. This list only earns its keep by being right.
