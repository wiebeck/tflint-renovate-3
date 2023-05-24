# TFLint + Renovate Example 3

## Setup

- Each module lists only the providers which are being required for this module using **lower bound** version constraints

## Observation

- ✅ TFLint is happy
- ✅ Renovate updates providers from root module in lock file only
- ❌ Renovate **completely ignores** providers in child modules

## Workarounds

- manually keeping providers in child modules up to date
