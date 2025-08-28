# Airbnb_SEO_Scorecard_28 CaseCraft Analytics Project Sprint Project 28

## 🏡 Overview  
This project builds a modular Airbnb SEO scorecard using synthetic listing metadata, keyword presence, and visibility metrics. It blends keyword density logic, normalized scoring, and visual diagnostics to help hosts optimize discoverability and search ranking.

## 🎯 Objective  
To evaluate Airbnb listings based on SEO-relevant features and generate a composite score for ranking and optimization.

## 📦 Dataset & Features  
- **Listings**: 100 synthetic entries  
- Features:  
  - `title`: listing headline  
  - `description_length`: character count  
  - `num_photos`: photo count  
  - `review_count`: total reviews  
  - `avg_rating`: 3.5–5.0  
  - `response_rate`: 60–100%  
  - Derived: `keyword_score`, `visibility_score`, `seo_score`

## 🧠 Scoring Logic  
- **Keyword Score**: Count of SEO-relevant terms in title (`cozy`, `wifi`, `central`, etc.)  
- **Visibility Score**: Normalized average of review count, photo count, and response rate  
- **SEO Score**: Weighted sum → `0.4 × keyword_score + 0.6 × visibility_score`

## 📊 Visual Explorations  
- **Histogram**: SEO score distribution  
- **Scatterplot**: Keyword score vs visibility  
- **Regplot**: Avg rating vs SEO score  
- **Boxplot**: Photo count vs SEO score  
- **Histogram**: Response rate distribution  
- **Top Listings Table**: Ranked by SEO score

## 🧠 Key Insights  
1. **Keyword Optimization**: Listings with 2+ keywords consistently rank higher  
2. **Visibility Drivers**: Photo count and review volume strongly influence SEO score  
3. **Response Rate Impact**: Hosts with >90% response rate show higher visibility  
4. **Quality vs Discoverability**: High ratings don’t guarantee high SEO—optimization is distinct  
5. **Top Performers**: “Pet-friendly loft with balcony” and “Central location + free parking” dominate top 10  
6. **Modular Design**: Fully reproducible logic with markdown/code separation

## ✅ Final Conclusion  
The Airbnb SEO Scorecard offers a clarity-first framework for listing optimization. By combining keyword presence and visibility metrics, it enables hosts to audit and improve discoverability. Ready for integration into host dashboards or SEO audit tools.