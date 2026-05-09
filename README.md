# Hey, I'm Chris Scott 👋

Engineer at [Material Security](https://material.security) · building things at [iamzed.com](http://iamzed.com)

I like solving specific, annoying problems — the kind where the right tool doesn't exist yet, so you build it yourself. My projects tend to land in a few recurring obsessions: home automation, homebrewing, and developer tooling.

---

## 🛠️ Developer Tools & Integrations

**[bash-mcp](https://github.com/chrisscott/bash-mcp)** · TypeScript  
An MCP server that lets AI agents run shell commands — without handing them a loaded gun. Commands are allowlisted, args are validated per-command, execution never goes through a shell, the working directory is confined, and every call is audit-logged. Designed to fail closed: unknown commands are rejected outright.

**[untappd-graphql](https://github.com/chrisscott/untappd-graphql)** · JavaScript  
GraphQL wrapper around the Untappd API. Soon to be deprecated.

**[flippy](https://github.com/chrisscott/flippy)** · Go  
A Slack webhook responder that flips tables and text. `flip` → `(╯°□°）╯︵ ┻━┻`.

**[auth0/auth0-cli](https://github.com/auth0/auth0-cli)** · Go  
Early contributor to Auth0's official CLI when I worked there — build, manage, and test Auth0 integrations from the terminal.

## 🏠 Home Assistant

**[smooth-thermostat-card](https://github.com/chrisscott/smooth-thermostat-card)** · TypeScript  
A compact, HACS-installable thermostat card for Lovelace. Debounces rapid +/- taps into a single `climate.set_temperature` call, updates the UI optimistically, and fits two cards side-by-side on a phone. Supports range thermostats, preset modes, fan modes, and a wide-layout option. Full GUI editor — no YAML required.

## 🍺 Brewing & Hardware

**[iSpindel-multiservice](https://github.com/chrisscott/iSpindel-multiservice)** · TypeScript  
Proxy service for the [iSpindel](https://www.ispindel.de/docs/README_en.html) hydrometer that fans data out to multiple endpoints simultaneously — Brewfather, Grainfather, Ubidots, Home Assistant, and any custom HTTP target. Handles old iSpindel firmware that lacks HTTPS support. Used by brewers who don't want to pick just one platform.

---

## Languages & Tools

Primarily TypeScript and Go lately, with JavaScript, and a healthy appreciation for things that just work in production.

---

*Always open to issues, PRs, and interesting problems.*
