---
name: Release
about: Track a planned hello_world release
title: 'Release vX.X — Hello, [Scope]!'
labels: release
---

**Version:** vX.X  
**Greeting:** `print("Hello, [Scope]!")`

## Checklist
- [ ] Dev: create file, test, tag dev-vX.X, test executables, PR dev→test
- [ ] Test: tag test-vX.X, acceptance test, PR test→prod
- [ ] Prod: tag prod-vX.X, publish release, sync branches, close issue
