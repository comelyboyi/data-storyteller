# 📊 Data Storyteller

> Turn raw data into insightful narratives that drive decisions

## The Problem

Most data analysis tools output charts and statistics. Decision-makers see a wall of numbers but have no idea what to do. Data Storyteller solves this: it transforms data into a complete story — with a beginning, a conflict, a conclusion, and actionable recommendations.

## ✨ Core Capabilities

| Capability | Description |
|------------|-------------|
| 📋 Data Profiling | Auto-detect data structure, types, and quality |
| 🔍 Pattern Discovery | Identify trends, anomalies, correlations, distributions, and comparisons |
| 📖 Story Crafting | Weave patterns into a coherent narrative with tension and insight |
| 🎯 Actionable Insights | Extract key findings and specific action items linked to data |

## 🔄 Workflow

```
Raw Data → Data Profiling → Pattern Discovery → Story Crafting → Actionable Insights
   │            │                │                  │                │
   │        Structure         Trends              Opening          Key Findings
   │        Types             Anomalies           Body             Action Items
   │        Quality           Correlations        Twist            Risk Alerts
   │                           Distributions       Conclusion
```

## 📖 Output Format

Each analysis produces four sections:

| Section | Content | Purpose |
|---------|---------|---------|
| Data Profile | Dataset description & quality assessment | Understand the full picture |
| Data Story | 500-800 word narrative | Grasp what the data means |
| Key Findings | 3-5 findings with specific numbers | Quick takeaway |
| Action Items | 2-4 concrete, executable recommendations | Guide decision-making |

## 💡 Usage Example

### Input: Quarterly Sales Data
| Quarter | Orders(K) | Avg Price(¥) | Return Rate(%) | New Customer(%) | Repeat Rate(%) |
|---------|-----------|---------------|-----------------|------------------|-----------------|
| Q1 | 120 | 258 | 8.2 | 65 | 28 |
| Q2 | 95 | 235 | 12.5 | 72 | 22 |
| Q3 | 145 | 280 | 6.8 | 55 | 38 |
| Q4 | 180 | 310 | 5.1 | 48 | 45 |

### Output: Data Story (excerpt)

> In 2024, a home goods e-commerce store underwent a quiet transformation — shifting from "traffic-driven" growth reliant on new customers to "repeat-driven" growth powered by loyal buyers...
>
> The starting point wasn't promising. Q2 was the darkest hour: orders dropped to 95K, return rate surged to 12.5% — roughly 1 in 8 orders came back...
>
> The most counter-intuitive finding: new customer share dropped from 72% to 48%, yet orders grew 89%. This completely contradicts the "acquisition drives growth" instinct...

### Output: Action Items

| Priority | Action | Data Evidence | Expected Impact |
|----------|--------|---------------|-----------------|
| P0 | Build tiered loyalty program for repeat customers | Q4 repeat rate 45%, repeat buyers have higher AOV and lower returns | Push repeat rate to 50%+ in Q1 |
| P1 | Optimize new customer first-order experience | Q2's 72% new customer share drove 12.5% return rate | Reduce new customer returns to 6% |
| P2 | Create repeat purchase triggers (seasonal reminders, bundles) | Home goods are naturally low-frequency | Shorten repurchase cycle from 6 to 4 months |

## 📦 Project Structure

```
data-storyteller/
├── SKILL.md                          # Core skill file
├── README.md                         # Project documentation (Chinese)
├── README.en.md                      # Project documentation (English)
├── references/
│   ├── data-patterns.md              # Pattern discovery guide
│   └── story-templates.md            # Narrative template library
└── examples/
    └── data-story-before-after.md    # Before/after examples
```

## Applicable Scenarios

- **Sales Analysis**: Quarterly reviews, regional comparisons, product performance
- **User Behavior**: Retention, conversion funnels, behavior paths
- **Financial Reports**: Revenue breakdown, cost structure, profit trends
- **Survey Analysis**: Customer satisfaction, market research, user feedback

## 📋 Technical Specs

- **Input**: Tabular data (CSV/Excel content, data tables, metrics)
- **Output**: Data story + key findings + action recommendations
- **Robustness**: Handles small (4+ rows) to large datasets, gracefully handles edge cases
- **Security**: No data storage, no sensitive content generation, objective output

## 📄 License

MIT License
