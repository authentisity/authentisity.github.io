+++
# Never rendered as its own page; the index lists these entries in order.
title = "Projects"
render = false

[[extra.entries]]
title = "Aeroacoustic Wind Tunnel Instrument"
meta = "Feb 2026 – present · controls, CFD"
description = "A magnetic suspension and balance system that levitates a ferromagnetic-core model under closed-loop electromagnet current control, eliminating strut noise from aeroacoustic measurements while keeping coil EMI out of the condenser microphones. OpenLB CFD sweeps over angle of attack and flow speed locate each airfoil's frequency peaks."

[[extra.entries]]
title = "FFmpeg"
meta = "Feb 2026 – present · C"
description = "Open-source contributions: a checkasm test for VVC (H.266) intra-prediction decoding that measures cross-platform assembly correctness and speedup, and a signed-integer-overflow fix in libswscale, both merged upstream. Also researching a least-squares quadratic guided filter for edge-preserving smoothing, integrated into a custom fork."
links = [
  { label = "checkasm test", url = "https://github.com/FFmpeg/FFmpeg/commit/724c1e00616db125ce7cd78c5eb874a75919215a" },
  { label = "swscale fix", url = "https://github.com/FFmpeg/FFmpeg/commit/e33b3962e5b12cbf3e2d2c6387331c10c6d46bb5" },
  { label = "guided filter", url = "https://github.com/authentisity/nonlinear-guided-filter" },
]

[[extra.entries]]
title = "High-Frequency Trading System"
meta = "Oct 2025 – Feb 2026 · FPGA, RL"
description = "A low-latency order-matching engine with a price-time-priority order book (a red-black tree of price levels, FIFO queues within each), a BRAM controller for a bank of parallel min-queues based on the MultiQueue architecture with deterministic 2-cycle reads and writes, and a PPO reinforcement-learning agent on a second FPGA that predictively caches hot orders."
+++
