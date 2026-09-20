# SAMP-HDRL

**SAMP-HDRL: Segmented Allocation with Momentum-Adjusted Utility for Multi-agent Portfolio Management via Hierarchical Deep Reinforcement Learning**

This repository is the public project page for SAMP-HDRL, a hierarchical deep reinforcement learning framework for portfolio management under changing market regimes.

## Method overview

SAMP-HDRL is built around three core components:

- **Dynamic asset grouping**: periodically updates the asset structure using downside-risk-aware grouping signals.
- **Hierarchical upper-lower agent coordination**: combines market-wide guidance with specialized intra-group allocation.
- **Momentum-adjusted utility-based capital allocation**: coordinates capital across risky groups and the risk-free asset using utility-based allocation with momentum and rebound information.

## Repository structure

The implementation will follow the main methodological structure of the paper:

```text
dynamic_grouping/
hierarchical_agents/
utility_allocation/
```

## Code availability

Source code implementing the core methodological components of SAMP-HDRL will be released upon publication.

## Citation

Citation information is provided in `CITATION.cff` and will be updated with the final publication details when available.

## License

This project is distributed under the MIT License. See `LICENSE` for details.
