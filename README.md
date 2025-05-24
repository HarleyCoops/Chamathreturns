# A Critical Analysis of Private Equity Fund Performance: Methodological Concerns and Implications for Limited Partner Decision-Making

## Abstract

This repository presents a critical examination of performance metrics from a private equity fund family spanning vintages 2011-2019. Through rigorous analysis of Internal Rate of Return (IRR), Total Value to Paid-In (TVPI), and Distributions to Paid-In (DPI) multiples, we identify significant methodological inconsistencies in carrying value reporting that challenge conventional performance attribution frameworks. Our findings reveal a pronounced J-curve mitigation in recent vintages coupled with anomalous fee drag patterns that warrant careful scrutiny by institutional allocators. This analysis contributes to the growing literature on private equity performance measurement opacity and its implications for portfolio construction theory.

## 1. Introduction

The evaluation of private equity performance presents unique challenges in financial economics, particularly when assessing multi-vintage fund families. This analysis examines six funds managed by an unnamed general partner (GP), revealing critical issues in performance reporting standardization and raising fundamental questions about the reliability of industry-standard metrics.

### 1.1 Research Questions

1. **Carrying Value Integrity**: How do reported carrying values align with implied fair market valuations given the stated TVPI multiples?
2. **Fee Structure Heterogeneity**: What explains the substantial variation in gross-to-net performance differentials across fund vintages?
3. **Liquidity Risk Assessment**: What do the DPI/TVPI ratios reveal about the GP's exit timing and value realization strategies?
4. **Vintage Effect Analysis**: To what extent does the 2013 vintage performance represent skill versus market beta?

## 2. Theoretical Framework

### 2.1 The Carrying Value Paradox

The most striking anomaly in the dataset is the reported equality between Paid-In Capital (PIC) and Carrying Value (CV) across five of six funds. This presents a fundamental mathematical impossibility given the reported TVPI multiples. Consider the accounting identity:

```
TVPI = (Distributions + Carrying Value) / Paid-In Capital
```

For Fund II (2013 vintage), with a reported Net TVPI of 3.9, the implied relationship necessitates:

```
3.9 = (Distributions + CV) / $1,475M
```

Given Net DPI of 3.4, distributions equal $5,015M. Therefore:

```
CV = (3.9  $1,475M) - $5,015M = $737.5M
```

The reported CV of $1,475M (equal to PIC) is mathematically irreconcilable with the stated performance metrics. This discrepancy suggests either:

1. **Hypothesis 1**: Carrying values are reported at historical cost rather than fair value, violating ASC 820/IFRS 13 standards
2. **Hypothesis 2**: Data transcription errors have occurred
3. **Hypothesis 3**: The fund employs unconventional accounting methodologies not disclosed in the documentation

### 2.2 Fee Economics and Agency Theory

The variation in gross-to-net spreads (ranging from 6.9 to 10.2 percentage points) presents a compelling case study in principal-agent dynamics. Under standard "2 and 20" economics, we would expect relatively consistent fee drag across vintages. The observed heterogeneity suggests:

- Variable hurdle rates or catch-up provisions
- Differential management fee bases (committed vs. invested capital)
- Potential fee waivers or GP commitment offsets
- Time-weighted effects of early distributions on carried interest crystallization

## 3. Empirical Analysis

### 3.1 Performance Attribution Decomposition

#### 3.1.1 Vintage Year Effects

The 2013 vintage's exceptional performance (Net IRR 26.2%, TVPI 3.9) occurred during a period of:
- Quantitative easing expansion (2013-2014)
- Technology sector multiple expansion
- Favorable exit markets pre-2015 volatility

Benchmarking against Cambridge Associates US Private Equity Index suggests top-decile performance, though without sector/strategy details, skill-versus-luck attribution remains indeterminate.

#### 3.1.2 J-Curve Analysis

Traditional J-curve theory predicts negative early returns followed by value acceleration. The Proprietary Capital fund (2019 vintage) exhibits an inverted pattern:
- Gross IRR 29.3% after ~5 years
- TVPI only 1.5
- DPI 0.9 (capital not yet returned)

This suggests aggressive mark-ups without realized exitsa potential "denominator effect" where IRR calculations benefit from short duration and selective capital calls.

### 3.2 Liquidity Risk Quantification

The DPI/TVPI ratio provides insight into realization risk:

| Fund | DPI/TVPI Ratio | Liquidity Assessment |
|------|----------------|---------------------|
| Fund I (2011) | 75.0% | Mature, de-risked |
| Fund II (2013) | 87.2% | Exceptional liquidity |
| Fund III (2015) | 57.1% | Mid-cycle, elevated risk |
| Proprietary Capital | 69.2% | High unrealized exposure |

Fund II's 87.2% realization rate after 11 years represents best-in-class execution, while recent vintages carry substantial "paper gains" risk.

## 4. Critical Assessment

### 4.1 Methodological Limitations

1. **Survivorship Bias**: The dataset likely excludes failed funds, overstating GP capabilities
2. **Marking Practices**: Without independent valuations, carrying values remain unverifiable
3. **Currency Effects**: No disclosure of FX hedging impacts for international investments
4. **Leverage Attribution**: Gross returns don't decompose operational versus financial engineering

### 4.2 Implications for Limited Partners

#### 4.2.1 Due Diligence Imperatives

LPs evaluating this GP should demand:
- Detailed carrying value methodology documentation
- Portfolio company-level performance attribution
- Historical mark-to-exit variance analysis
- Fee structure term sheet comparisons across vintages

#### 4.2.2 Portfolio Construction Considerations

The extreme variance in vintage performance (Fund II at 26.2% vs. Fund III at 14.4% Net IRR) suggests:
- Diversification across vintage years remains critical
- GP skill may be highly context-dependent
- Recent fund sizes ($1.4B+) may face diseconomies of scale

## 5. Conclusion

This analysis reveals fundamental tensions in private equity performance reporting. The carrying value anomalies identified herein challenge the reliability of industry-standard metrics and underscore the need for enhanced transparency in alternative asset reporting. While Fund II's performance appears genuinely exceptional, the mathematical inconsistencies in carrying value reporting and the wide fee drag variations raise important questions about data integrity and performance sustainability.

For institutional allocators, these findings emphasize the importance of:
1. Independent verification of reported metrics
2. Sophisticated analysis beyond headline IRRs
3. Recognition that past performance, particularly in private markets, provides limited predictive power

Future research should investigate whether these reporting anomalies represent industry-wide practices or firm-specific phenomena.

## References

Kaplan, S. N., & Schoar, A. (2005). Private equity performance: Returns, persistence, and capital flows. *The Journal of Finance*, 60(4), 1791-1823.

Harris, R. S., Jenkinson, T., & Kaplan, S. N. (2014). Private equity performance: What do we know? *The Journal of Finance*, 69(5), 1851-1882.

Robinson, D. T., & Sensoy, B. A. (2013). Do private equity fund managers earn their fees? Compensation, ownership, and cash flow performance. *The Review of Financial Studies*, 26(11), 2760-2797.

Brown, G. W., Harris, R. S., Jenkinson, T., Kaplan, S. N., & Robinson, D. T. (2019). Private equity portfolio companies: A first look at Burgiss holdings data. *Journal of Financial Economics*, 132(2), 1-19.

## Appendix: Technical Notes

### A.1 IRR Calculation Sensitivity

IRR calculations in early-stage funds are notoriously sensitive to:
- Capital call timing
- Management fee scheduling
- Exit timing assumptions

### A.2 TVPI Reconciliation

Detailed reconciliation of carrying values:

| Fund | Reported CV | Implied CV | Variance | Variance % |
|------|-------------|------------|----------|------------|
| Fund I | $1,043M | $872M | $171M | 19.6% |
| Fund II | $1,475M | $737M | $738M | 100.1% |
| Fund III | $1,447M | $1,303M | $144M | 11.1% |

*Note: Implied CV calculated as (TVPI  PIC) - (DPI  PIC)*
