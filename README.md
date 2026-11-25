# WindowShopper

Read BRIEF.html

## Setup

- Run Claude Code on your computer, in this folder. Chrome, `reports/` and the session all live there. Cloud sessions are not supported.
- Install the Claude in Chrome extension and sign it in to the same claude.ai account as Claude Code. Keep Chrome open while the session runs.
- In Claude Code run `/chrome` and turn on "Enabled by default" (or start with `claude --chrome`). Running `/chrome` once without that does not keep Chrome connected in later sessions.
- Without Chrome every price uses the fallback (WebFetch on the store page, then search results), so more prices come out labelled "from search, not verified on the store page".
- From your phone: reach the same session through Claude Code remote access, and read the published "WindowShopper reports" page on claude.ai while signed in.
- `.claude/settings.json` allows no Bash, git or gh, so during a build the builder's and Checker's Bash, git and gh calls come to you as permission prompts.
