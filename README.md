# Claude-GitHub

A sandbox repository for exploring the [Claude Code GitHub Action](https://github.com/anthropics/claude-code-action) integration.

## What this repo is for

This repository is set up with Claude Code's GitHub Actions workflows so that Claude can be triggered directly from issues, pull requests, and review comments:

- `.github/workflows/claude.yml` — runs Claude Code in response to `@claude` mentions in issue comments, PR review comments, PR reviews, and newly opened/assigned issues.
- `.github/workflows/claude-code-review.yml` — runs Claude Code to automatically review pull requests.

## Usage

Mention `@claude` in an issue or pull request comment with a request, and the Claude Code GitHub Action will pick it up, work on it, and respond or open a pull request as needed.
