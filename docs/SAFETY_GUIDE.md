# Trading Safety & Risk Management

## Pre-Trade Checklist
- [ ] Verify RPC endpoint is responsive
- [ ] Check SOL balance covers fees + slippage
- [ ] Confirm safety filters are enabled
- [ ] Review max trade size limits
- [ ] Verify stop-loss is configured
- [ ] Test with small amount first

## Risk Parameters
| Parameter | Recommended | Aggressive |
|-----------|------------|------------|
| Max trade size | 0.1 SOL | 1 SOL |
| Stop-loss | -10% | -20% |
| Take-profit | +50% | +100% |
| Max open positions | 3 | 5 |
| Slippage tolerance | 5% | 15% |

## Red Flags to Avoid
- Token with no liquidity lock
- Deployer holds >50% supply
- Mint authority not revoked
- No social media or website
- Honeypot contract patterns
- Sudden massive liquidity removal

## Recovery Procedures
1. If bot hangs: Check RPC connection, restart
2. If stuck transaction: Increase priority fee
3. If unexpected loss: Pause bot, review logs
4. If RPC rate limited: Switch to backup endpoint

## Disclaimer
This is for educational purposes. Cryptocurrency trading carries significant risk. Never trade more than you can afford to lose.
