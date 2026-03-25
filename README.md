# Homebrew Tap for ClaudeRelay

This is the official Homebrew tap for ClaudeRelay - a remote terminal relay server and CLI over WebSocket.

## Installation

```bash
brew install miguelriotinto/claude-relay/claude-relay
```

Or:

```bash
brew tap miguelriotinto/claude-relay
brew install claude-relay
```

## Usage

Start the relay server as a background service:

```bash
brew services start claude-relay
```

Create an auth token:

```bash
claude-relay token create --label "my-device"
```

## Default Ports

- WebSocket: 9200
- Admin API: 9100

## Configuration

Config is stored at `~/.claude-relay/config.json`

## Repository

Main project: [ClaudeRelay](https://github.com/miguelriotinto/ClaudeRelay)
