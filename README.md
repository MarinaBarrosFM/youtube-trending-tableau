# YouTube Trending Categories: Tableau Dashboard

**Live dashboard:** [Open on Tableau Public](https://public.tableau.com/app/profile/marina.moraes/viz/TendnciasdevdeosdoYouTubeporregio/TendnciasdevdeosdoYouTubeporregio)

## About the project
An interactive dashboard built in Tableau Public to analyze which video categories trend most often on YouTube across five regions: **France, India, Japan, Russia and the United States**. The period covered is **November 14, 2017 to June 14, 2018**.

## Questions answered
1. Which categories trend most frequently?
2. How are they distributed across regions?
3. What was especially popular in the US compared with the other regions?
4. How did each category's share evolve over time in the US?

## Data
`trending_by_time.csv`, with the following columns:

| Column | Description |
|---|---|
| `record_id` | Record identifier |
| `region` | Region |
| `trending_date` | Date the videos were trending |
| `category_title` | Video category |
| `videos_count` | Number of trending videos in the category |

## Tools and techniques
- **Tableau Public**: bar charts, discrete area chart (category share over time), **% of total** table calculation, date and country filters applied across all worksheets, and dashboard layout.
- A PDF presentation with the main charts and conclusions.

## Key findings
- **Entertainment** is the most frequent category (**27.9%**), followed by People & Blogs (13.1%), and Music and News & Politics (10.1% each).
- **India** is the region most concentrated in Entertainment (44.9%). **Russia** is the exception, led by People & Blogs (25.0%).
- **Japan** stands out in Pets & Animals (6.1%) and Gaming (5.0%).
- In the **United States**, Music (15.9%), Howto & Style (10.3%) and Science & Technology (5.8%) rank above the other regions, while News & Politics is low (6.0%).

## Files
- `Apresentacao_Tendencias_YouTube.pdf`: presentation (in Portuguese) with the charts and conclusions.
- `trending_by_time.csv`: data behind the dashboard.
