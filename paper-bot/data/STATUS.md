# SOL cloud paper test

Status: **active**. No real orders or wallet access.

| Metric | Value |
| --- | --- |
| Simulated equity | $196.72 |
| Net P/L | $-3.28 |
| Realized P/L | $-3.28 |
| Assumed fees paid | $0.47 |
| Cash | $196.72 |
| Last successful observation | 2026-11-19T23:35:49.729Z |
| Last attempt | 2026-11-19T23:35:49.729Z |
| Observations with a gap over 10 minutes | 71 |

Decision: Ten-minute cooldown after the last exit.

The scheduler can be late or skip runs. Stops are evaluated at the next observed price; no missed fills are invented. Indicative SOL/USD prices can differ from on-chain swaps. Profitability is unproven.
