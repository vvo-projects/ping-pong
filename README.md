# Ping Pong GitHub Actions Demo

This repository demonstrates two simple GitHub Action workflows:

## Workflows

### Ping Workflow
[![Ping Workflow](https://github.com/username/ping-pong/actions/workflows/ping.yml/badge.svg)](https://github.com/username/ping-pong/actions/workflows/ping.yml)

The Ping workflow simply prints "ping" and always succeeds. It runs on:
- Push to main branch
- Pull requests to main branch
- Manual workflow dispatch

### Pong Workflow
[![Pong Workflow](https://github.com/username/ping-pong/actions/workflows/pong.yml/badge.svg)](https://github.com/username/ping-pong/actions/workflows/pong.yml)

The Pong workflow prints "pong" and deliberately fails with exit code 1. It runs on:
- Push to main branch
- Pull requests to main branch
- Manual workflow dispatch

## Usage

These workflows can be used to test GitHub Actions notifications and integrations by providing predictable success and failure outcomes.

You may need to replace `username` in the badge URLs with your actual GitHub username/organization name.
