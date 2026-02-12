# Liquid Network Directory Research Findings
**Date:** February 12, 2026  
**Repository:** awesome-liquid-network  
**Branch:** feature/add-boltz-anya-feb-2026

## Summary

Conducted research for new Liquid Network projects with significant constraints (no web search API, intermittent GitHub API access). Discovered **2 high-quality resources** focusing on swap infrastructure and multi-layer wallet support.

## Resources Added: 2

### Development Tools

1. **Boltz Exchange** (https://boltz.exchange/)
   - Non-custodial swap service supporting Bitcoin, Lightning, and Liquid
   - Submarine swaps and chain swaps for instant, trustless exchanges
   - Active development: Updated Feb 12, 2026
   - Professional API and documentation: https://docs.boltz.exchange/
   - GitHub repos: boltz-backend, boltz-web-app
   - **Why it matters:** Major non-custodial bridge missing from directory, fills gap in Liquid swap infrastructure

### Wallets

2. **Anya Mobile Wallet** (https://github.com/Conxian/anya-mobile)
   - Multi-layer Bitcoin wallet with native Liquid Network support
   - Supports L1, Lightning, Liquid, and Stacks in one unified interface
   - Hexagonal architecture with TypeScript/liquidjs-lib
   - Features: Unified balance view, Silent Payments, advanced privacy
   - Active development: Updated Feb 12, 2026
   - **Why it matters:** Comprehensive multi-layer wallet showcasing Liquid integration alongside other Bitcoin layers

## Quality Assessment

**Overall Quality: HIGH**

### Strengths
- Both projects updated within last 24 hours (Feb 11-12, 2026)
- Professional documentation and architecture
- Fill identified gaps: swap infrastructure (Boltz) and multi-layer wallet (Anya)
- Real-world production services (Boltz) and open-source development (Anya)
- Native Liquid support, not just added as afterthought

### Verification
✅ Both actively maintained (Feb 2026 updates)  
✅ No duplicates in current directory  
✅ Professional quality and documentation  
✅ Clear Liquid Network integration  
✅ Relevant to directory's audience

## Research Constraints

### Significant Limitations
- ❌ **Web Search API unavailable** (no Brave API key configured)
- ❌ **GitHub API largely non-functional** (rate limits or connectivity issues)
- ❌ **Web fetch limited** (Cloudflare protection on most sites)

### Methodology
Despite constraints, successfully used:
1. GitHub Topics page scraping (https://github.com/topics/liquid-network)
2. Direct README fetching via raw.githubusercontent.com
3. Manual web_fetch on key project sites
4. Cross-referencing with previous research (Feb 5 findings)

## Rejected/Not Considered

### Excluded:
- **bitcoin-liquidity-network** - Not related to Liquid Network sidechain (different "liquidity")
- **BlitzWallet/blitz-wallet-pos** - POS system, not wallet/tool focused
- **Various "liquid" named projects** - False positives from search (liquid neural networks, etc.)

## Changes Made

### Files Modified
- `README.md` - 2 additions (1 to Development Tools, 1 to Wallets)

### Placement Decisions
- **Boltz:** Added to Development Tools after TDEX (similar swap/trading category)
- **Anya:** Added to Wallets section alphabetically (after Aqua)

## Branch Information

**Branch Name:** `feature/add-boltz-anya-feb-2026`  
**Status:** Ready for PR  
**Base Branch:** main  
**Files Changed:** 1 (README.md)  
**Lines Added:** ~2

## Recommendations

1. **Immediate:** Review and merge this PR
2. **Future:** Configure Brave API key for more comprehensive research
3. **Future:** Monitor Boltz ecosystem for additional tools/integrations
4. **Future:** Track multi-layer wallet development (Anya, others) as they mature
5. **Consider:** Creating dedicated "Bridges & Swaps" section if more services emerge

## Notes

- Research severely limited by API availability
- Quality over quantity approach: 2 solid additions vs. forcing 3 mediocre ones
- Both additions are timely (updated this week) and fill real gaps
- Boltz is particularly significant - major production service not in directory
- Anya represents emerging trend of unified multi-layer wallets

## Search Methodology

Given constraints, used:
1. GitHub Topics exploration (liquid-network tag)
2. Recent repository activity filtering (pushed:>2026-02-05)
3. Manual README inspection
4. Cross-reference with Feb 5 research to avoid duplicates
5. Conservative vetting: only added well-documented, actively maintained projects
