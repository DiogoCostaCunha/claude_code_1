# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a small web project consisting of standalone HTML files with embedded CSS and JavaScript. No build tools, package managers, or frameworks are used — everything runs directly in the browser.

## Running the Project

Open any HTML file directly in a browser:
```
start tictactoe.html
```

There are no build, lint, or test commands.

## Architecture

Each game/app is a **single self-contained HTML file** with:
- Inline `<style>` for all CSS
- Inline `<script>` for all JavaScript
- No external dependencies

State is managed with plain JS variables. No frameworks, no modules, no bundler.

## Git — Required for All Changes

**Every code change must be committed.** After completing any modification (new feature, bug fix, new file, content update), stage and commit it before finishing.

- Commit after each meaningful change — do not leave uncommitted work
- Push to remote after committing: `git push`
- Use descriptive commit messages explaining *why*, not just *what*
- Always include the co-author trailer:
  `Co-Authored-By: Claude Sonnet 4.6 <noreply@anthropic.com>`
- Remote: `https://github.com/DiogoCostaCunha/claude_code_1`
