# Project Roadmap

> **Last Updated**: 2026-01-30

This document tracks project status and planned work.

---

## Current Phase

**Phase: Foundation & Audit** - S-001 (Audit Codebase)

We are verifying the Ralph Svelte Chassis is properly set up and functional after extraction from Solar-Sim.

### Recent Progress

- ✅ **T-001-01**: Inventory & Cleanup Verification - Confirmed codebase is clean of Solar-Sim domain logic. Created audit report documenting findings and minor documentation cleanup recommendations.

### Next Up

- **T-001-02**: Toolchain Verification - Verify Bun and build toolchain functionality
- **T-001-03**: Agent Signature - Prove write access to core project files

---

## Quick Reference

**Check status**:
```bash
just dag-status
```

**Run sprint**:
```bash
RALPH_ALLOW_MAIN=1 WORKTREE_STORY=S-XXX just ralph
```

**Preview next task**:
```bash
just prompt
```

**Refresh DAG from tickets**:
```bash
just dag-refresh
```

See `docs/knowledge/playbook/ralph-loop.md` for detailed ralph loop instructions.
