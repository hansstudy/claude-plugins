# Study Cisco Switch Config

A Claude Code plugin that audits Cisco IOS and IOS-XE switch running-configurations for security
and reliability defects, and generates hardened baseline configurations from a short spec. It can
also diff two configurations and explain which hardening controls a change affects.

## Install

```
/plugin marketplace add hansstudy/claude-plugins
/plugin install cisco-switch-config@hansstudy
```

Then ask, for example: "Audit this Cisco switch config for security issues," or paste a
`show running-config` and ask what is wrong with it.

## Privacy

The skill runs entirely offline using only the Python standard library. It makes no network
calls and sends nothing anywhere. Secret-bearing lines in a pasted configuration are masked in
its output.

## More

- Full source, documentation and releases: https://github.com/hansstudy/cisco-switch-config
- Product page: https://hans.study/tools/cisco-switch-config/
- Security contact: bugs@hans.study

Licensed under Apache-2.0 (see `LICENSE` and `NOTICE`). Trademark notes are in `TRADEMARKS.md`.
