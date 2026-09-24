# ViOptimizer-Updates

Public update feed for **Vi Optimizer / Vi Drivers**.

## Stable channel

Vi Optimizer checks:

`https://raw.githubusercontent.com/Zelv-rus/ViOptimizer-Updates/main/latest.json`

Vi Optimizer 0.11.0 contains the in-app updater bootstrap.

Normal update behavior:
- automatic feed checks are throttled to once per 6 hours;
- packages are accepted only from this repository's GitHub Releases path;
- SHA-256 is verified before installation;
- the current runtime is backed up before replacement;
- the updated app must confirm a healthy start;
- failed startup triggers automatic rollback.

The feed stays disabled until a newer release package is actually available.
