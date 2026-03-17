---
name: nutrient-management
description: "UK agricultural nutrient management based on the AHDB RB209 Nutrient Management Guide. Use this skill whenever the user asks about fertiliser recommendations, nutrient planning, soil nutrient indices, soil nitrogen supply (SNS), lime requirements, phosphate/potash/magnesium recommendations, or crop-specific nutrient needs for UK farming. Triggers include: any mention of RB209, AHDB nutrient guide, fertiliser recommendations for crops, soil P/K/Mg indices, SNS index calculation, nitrogen recommendations for wheat/barley/potatoes/vegetables/grass/fruit, sulphur recommendations, micronutrient deficiency, lime recommendations, NVZ rules, organic manure nutrient values, or soil sampling guidance. Also trigger when users ask about nutrient balance sheets, crop offtake values, or conversion between oxide and elemental forms of nutrients. This skill covers arable crops, grass/forage, potatoes, vegetables/bulbs, and fruit/vines/hops."
---

# RB209 Nutrient Management Guide

This skill provides nutrient management recommendations based on the AHDB RB209 guide — the UK's authoritative reference for agricultural nutrient planning. It covers all major crop sectors and helps users make evidence-based fertiliser decisions.

## How to use this skill

When answering nutrient management questions, follow this decision process:

1. **Identify the crop sector or topic** — which reference file to consult:
   - Arable crops (cereals, oilseeds, sugar beet, peas, beans) → read `references/arable.md`
   - Grass and forage → read `references/grass.md`
   - Potatoes → read `references/potatoes.md`
   - Vegetables and bulbs → read `references/vegetables.md`
   - Fruit, vines and hops → read `references/fruit.md`
   - Organic materials (manures, slurries, digestates, biosolids, compost, waste-derived materials) → read `references/organic-materials.md`

2. **For any question**, also consult `references/principles.md` which contains:
   - Soil Index classification tables (P, K, Mg — Index 0–9)
   - Soil category assessment (7 categories for SNS)
   - SNS calculation methods (Field Assessment and Measurement)
   - Lime recommendations
   - Conversion factors (element ↔ oxide)
   - Soil pH targets
   - General nutrient management principles

3. **For organic materials** (manures, slurries, digestates, biosolids, compost), consult `references/organic-materials.md` for nutrient content tables, crop-available nitrogen percentages by timing and soil type, and the 6-step process for calculating fertiliser requirements after deducting organic material contributions.

## Key concepts

### Soil Indices (P, K, Mg)
Soil analysis results (mg/L) are classified into Indices 0–9. Target Index is 2 for P and K (lower half 2- for K). Recommendations at Index 2 are maintenance levels; below Index 2, extra is applied to build reserves; above Index 2, applications can be reduced or omitted.

### Soil Nitrogen Supply (SNS)
SNS Index (0–6) estimates background nitrogen available to the crop. It depends on soil category, previous crop, and winter rainfall. Two methods exist:
- **Field Assessment Method**: uses lookup tables based on soil type, previous crop, and rainfall category (low/moderate/high)
- **Measurement Method**: uses Soil Mineral Nitrogen (SMN) sampling plus estimates of crop N and mineralisable N

### Nutrient units
- Recommendations are given as oxides: phosphate (P2O5), potash (K2O), magnesium oxide (MgO), sulphur trioxide (SO3)
- Soil analysis reports usually show elemental forms (mg/L of P, K, Mg)
- Key conversion factors: P × 2.291 = P2O5; K × 1.205 = K2O; Mg × 1.658 = MgO; S × 2.497 = SO3

### Rainfall categories
- Low: annual <600mm or excess winter rainfall <150mm
- Moderate: annual 600–700mm or excess winter rainfall 150–250mm
- High: annual >700mm or excess winter rainfall >250mm

## Important caveats

Always remind users that:
- Recommendations assume good soil structure, adequate water supply, and effective pest/disease control
- Organic material contributions must be deducted from fertiliser recommendations (Section 2: Organic Materials)
- NVZ and Farming Rules for Water regulations may impose additional constraints
- Soil sampling should be done every 3–5 years
- Professional agronomic advice should complement these guidelines
- These recommendations are for England and Wales; Scotland and Northern Ireland have separate but similar guidance
