# Movie Studio Phase 2 Project

## Project Overview
This project explores movie data to provide actionable insights for a new movie studio. Using **IMDb (`im.db`)**, **movie info**, and **review datasets**, the goal is to identify trends in genres, studios, directors, and audience ratings to guide strategic decisions.

---

## Business Questions

### From the IMDb Database (`im.db`)
1. **Which genres perform best based on IMDb ratings?**  
   Comparing genre-level averages to determine which movie types are most consistently well-received by viewers.

2. **Which directors have the highest average-rated movies?**  
   Identifying top-performing directors helps studios recognize and collaborate with talent that consistently delivers high-quality films.

3. **Does movie runtime affect audience ratings?**  
   Investigating whether longer or shorter movies perform better to help production teams balance storytelling depth with audience engagement.

### From the Merged Movie Datasets (Movie Info + Review)
4. **Which studios consistently produce the highest-rated movies?**  
   Understanding which studios achieve the best audience ratings provides insights into which production houses maintain strong reputations and audience trust. This helps identify potential partnerships or benchmark studios for performance comparisons.

5. **Which movie genres receive the highest audience ratings?**  
   Exploring which genres resonate most with audiences to guide production and acquisition strategies toward high-performing genres.

---

## Datasets Used
- **IMDb Database (`im.db`)**
  - Key tables: `movie_basics`, `movie_ratings`  
  - Contains movie titles, original titles, release years, runtime, genres, and IMDb ratings.

- **Movie Info Dataset**
  - Includes studios, directors, release dates, and other production details.

- **Movie Review Dataset**
  - Contains audience reviews, ratings, and box office performance.

> These datasets were merged and cleaned for analysis to answer the business questions above.
