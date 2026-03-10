# Security & Safety

## Sensitive Actions
The following actions require explicit confirmation:
- Delete item
- Large price change
- Batch operations

## Two-step Confirmation (required)
1. First confirmation: explain impact and irreversibility
2. Second confirmation: require exact confirmation phrase

## Safe Defaults
- Safe Mode is default (`MODE: safe`)
- Circuit breaker after 2 consecutive failures of same action
- Stop automation when captcha/login exception/risk signal appears
