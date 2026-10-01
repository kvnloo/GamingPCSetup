# Reproducible gaming latency baseline

Use this before claiming any PC tweak improves gaming responsiveness.

Record:

- CPU / GPU / driver / OS
- display mode, refresh rate, VRR, VSync
- game cap and external limiter
- mouse polling rate
- power plan / governor
- overlays and capture tools
- workload version and scene

Protocol:

1. Stabilize temperature and clocks.
2. Warm up the workload.
3. Run at least five baseline repetitions.
4. Apply exactly one change.
5. Run at least five treatment repetitions.
6. Repeat baseline if the test is long enough for drift to matter.
7. Preserve raw captures.

Report p50, p95, p99, max and repeated-run variance for frametime/latency metrics. Average FPS alone is insufficient.

Every recommendation must include rollback instructions and the exact measurement that justified it.
