# Task_03_Descriptive_Stats

# 📈 Summary of Findings

## ✅ Results Consistency
All three approaches produced identical descriptive statistics (means, value counts, etc.) across datasets after ensuring consistent data cleaning and preprocessing.

## 🔧 Challenges
- Nested columns (`demographic_distribution`, `delivery_by_region`) required flattening and normalization.
- Stringified dictionaries needed conversion using `ast.literal_eval`.
- Consistent treatment of nulls and missing data was crucial.

## ⚙️ Performance and Usability Comparison

| Method      | Ease of Use          | Performance       | Suitability for New Analysts       |
|-------------|----------------------|-------------------|------------------------------------|
| Pure Python | ❌ Verbose and Manual| 🚫 Slowest         | ❌ Requires more effort             |
| Pandas      | ✅ Easy and Powerful | ⚠️ Slower than Polars | ✅ Recommended                   |
| Polars      | ⚠️ Slightly different syntax | ✅ Fastest    | ⚠️ Best for large datasets         |

✅ **Recommendation**: Start with **Pandas** for simplicity and community support.  
🚀 Use **Polars** for performance-intensive tasks or large datasets.

## 🧠 Role of AI (e.g., ChatGPT)
- Generated reusable template code for all approaches.
- Suggested strategies for nested dictionary columns and categorical handling.
- Defaults to recommending Pandas, which aligns with industry norms.
- Accelerated troubleshooting and ensured consistency across implementations.

💬 **Do I agree with AI's default suggestions (Pandas)?**  
**Yes** — it's intuitive, powerful, and has a large support ecosystem.
