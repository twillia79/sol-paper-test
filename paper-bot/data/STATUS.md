# SOL cloud paper test

Status: **active**. No real orders or wallet access.

| Metric | Value |
| --- | --- |
| Simulated equity | $197.51 |
| Net P/L | $-2.49 |
| Realized P/L | $-2.49 |
| Assumed fees paid | $0.31 |
| Cash | $197.51 |
| Last successful observation | 2026-11-13T09:58:07.249Z |
| Last attempt | 2026-11-13T09:58:07.249Z |
| Observations with a gap over 10 minutes | 47 |

Decision: Ten-minute cooldown after the last exit.

The scheduler can be late or skip runs. Stops are evaluated at the next observed price; no missed fills are invented. Indicative SOL/USD prices can differ from on-chain swaps. Profitability is unproven.
